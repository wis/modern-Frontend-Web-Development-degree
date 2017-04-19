# Serverless
## What does it mean?
- No need to manage servers
- No need to even *think* about servers
- No need to provision infrastructure
- Pay only for what you use
- It's not about *billing* it's about *developer experience* 
- Function as a server (**FAAS**): Deploy *functions* not *apps*
- **Event-based/oriented**
- Applies to compute & non-compute services

# So.. What are the advantages?
The traditional way websites was deployed to the cloud is very **complex**.
and is more **wasteful** of compute resources & thus money (because of **overprovisioning** for a *load balancing solution*).
### most simple way:
- you deploy the website's server code to a Compute instance 
- set the port of the Server application (standard 80 for the web), expose the same port on that compute instance to the public network.
- get the IP Address of the machine (or the load balancing solution IP Address) and manually set records for your Domain to point to it.

# Why the hype?, Is it the new thing?, Why FAAS?
- you can't get rid of the overprovisioning problem completely. but it's inappreciable with the FAAS model.
- deploying functions is the easiest and the most flexable.
    - continuous deployment is easy with:
        - a function versioning *(application specific)* solution.
        - paying only for what you use *(function invokations)* not what you deploy.
    - no microservices headache, spinning up new instances *(machine / docker container)* for a specific microservice as you scale up. 
# More advantages to the FAAS model
- Functions Scale Independently (down to 0 if needed)
- Functions are Isolated from one another
- Stateless/ephemeral
- More closely matches your traffic pattern and User behavior (some functions executed a lot, some a little)
