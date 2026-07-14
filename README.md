spring.application.name=branch-master-service
server.port=8104

# CONFIG SERVER
spring.config.import=configserver:http://localhost:8128


management.endpoints.web.exposure.include=*
management.endpoint.health.show-details=always

spring.boot.admin.client.url=http://localhost:9090

management.metrics.enable.all=true

management.info.env.enabled=true
management.info.java.enabled=true
management.info.os.enabled=true
