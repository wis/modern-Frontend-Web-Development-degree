# Google Cloud Functions
- HTTP Functions
    - *(currently)* free a TLS certificate
    - for synchronous use cases
        - synchronous invocations over HTTPS.
    - you get a URL.
    - will work out-of-the-box with  *Webhook* callback
- Background Functions
    - asynchronously invoked by cloud events.
    - for use cases where you don't need to know the output of the function in real-time.
        - happy for it to be processed in the background.
    - typical use and typically will be invoked when an Event is emitted from a cloud service. such as:
        - Google Cloud Storage
        - Firebase Realtime Database

## HTTP Functions

### code example:
``` js
    // Function triggerd via HTTPS
    // Express.js request and response
    exports.helloWorld = function helloWorld (request, response) {
        // just a response without a HTTP status code 
        response.send("Hello World");
        // OR send a HTTP status code before the response in the HTTP Header:
        response.status(200).send("Hello World");
    }
```
### Google Cloud Platform Command Line Interface (GCP CLI)


#### Synopsis

``` bash
gcloud beta functions deploy "<NAME>" (--trigger-bucket=TRIGGER_BUCKET     | --trigger-http     | --trigger-topic=TRIGGER_TOPIC) [--entry-point=ENTRY_POINT] [--include-ignored-files] [--memory=MEMORY] [--region=REGION] [--timeout=TIMEOUT] [--local-path=LOCAL_PATH     | --source-path=SOURCE_PATH] [--source-branch=SOURCE_BRANCH     | --source-revision=SOURCE_REVISION     | --source-tag=SOURCE_TAG] [--source-url=SOURCE_URL     | --stage-bucket=STAGE_BUCKET] [GLOBAL-FLAG …]
```

#### deploy Example code command
``` bash
gcloud beta functions deply "helloWorld" --stage-bucket "functions-src" --trigger-http
```


