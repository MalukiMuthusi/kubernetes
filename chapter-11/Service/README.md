# Service

Create a kubernetes service. Expose an application to the external network. The application can now be accessed through a static IP address or a domain name. Any changes to the pods does not affect how you access the application. Pods are not destroyed and recreated and each time they are assigned a new IP address. Using services provides an abstraction.

Using the NodePort, the application is mapped to aport number. Kubernetes performs load balancing, any request received by the service is routed to one of the pods.
