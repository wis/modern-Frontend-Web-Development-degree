# Serverless
## What does it mean?
- No need to manage servers
- No need to even **think** about servers
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
- set the port of the Server application (standard 80 for the web), expose the same port on that compute instance.
- get the IP Address of the machine (or the load balancing solution IP Address) and manually set records for your Domain.

