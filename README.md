# spring-cloud-zuul-server

# Spring
- 1.5 release used across with Edgware.SR2 cloud version

# Zuul
- HTTP Basic authentication enabled
- Load balancer
- Is also EurekaClient (use @EnableDiscoveryClient annotation) it will discover all the services and automatically will create routes
- Automatic refresh as services changes at eureka discovery server -> This can be controlled by settings -> To find out
- Use for private api authentication -> TODO
- Use for public api authentication via Spring OAuth2 -> TODO
- Replace web server (nginx) -> serve static data
