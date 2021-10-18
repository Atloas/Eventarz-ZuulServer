# Eventarz-ZuulServer

A part of my Master's dissertation - a simple web application for organizing events, consisting of 7 microservices:

- [Eventarz-Gateway](https://github.com/Atloas/Eventarz-Gateway) - contains full project description.
- [Eventarz-Application](https://github.com/Atloas/Eventarz-Application)
- [Eventarz-Users](https://github.com/Atloas/Eventarz-Users)
- [Eventarz-Groups](https://github.com/Atloas/Eventarz-Groups)
- [Eventarz-Events](https://github.com/Atloas/Eventarz-Events)
- [Eventarz-EurekaServer](https://github.com/Atloas/Eventarz-EurekaServer)
- [Eventarz-ZuulServer](https://github.com/Atloas/Eventarz-ZuulServer)

---

This microservice acts as a single access point to the entire application, functioning both as a reverse proxy that splits incoming requests between Application and Gateway depending on their addresses, and as a load balancer of requests addressed to Gateway.