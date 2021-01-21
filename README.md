# Upgrade as of 21/01/2021

As previous [article](https://github.com/ponddmj28/dwi-kubernate-gcp) we builded serveral projects for tracking and managements jobs so now we upgraded technologies and applied Circuit Breaker Pattern ,Ribbon Client LoadBalancing,Zuul Gateway and deploy it go AWS Kubernates

### what we gained from this pactices
- Spring Config Server 
  - how to setting up project and config either server and client for local till go up cloud
  - how it's helping us in Cloud
- Hystrix Circuit Breaker
  - how its working either Thread or Semaphore and setting up configurations
  - how to write circuit break at client and server side
- Ribbon Client Loadbalancing
  - how it works with discovery and feign client
  - how to config manually route and automated discovery routing to our endpoints
- Eureka Discovery
  - how this program made us helpful and applied easier with us
  - how to config either client and server side local till up to cloud
  - how it works with feign and ribbon
- Zuul Gateway
  - how to config for mapped routing each endpoints
  - how to implements Pre,Route,Post,Error filters
each environment configuration is differences so we were spending times to search root causes why not working each at that environments. but in the end we got it!


