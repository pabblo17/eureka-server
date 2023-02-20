# eureka-server

# Docker


```bash
  mvn clean install
```

Crear imagen 

```bash
  docker build -t unir-eureka:latest .
```

Ejecutar imagen

```bash
  docker run -p 8761:8761 unir-eureka:latest
```