# 🧩 Módulo 5 – Microservicios y DevOps

Este repositorio contiene configuraciones, scripts, ejemplos y documentación del **Módulo 5** del bootcamp **Desarrollo Web Fullstack con Java** (CodiGo). En este módulo se aprende a desarrollar y desplegar aplicaciones basadas en **microservicios**, además de integrar herramientas de **DevOps**.

---

## 📚 Contenido del módulo

### 🔸 Arquitectura de Microservicios

- Diferencias entre monolito y microservicios
- Comunicación entre servicios
- Principios de diseño desacoplado
- Patrón API Gateway
- Registro y descubrimiento de servicios con **Eureka**
- Configuración centralizada con **Spring Cloud Config**
- Balanceo de carga con **Ribbon**
- Fallos controlados con **Resilience4j**
- Comunicación declarativa con **Feign**

### 🔸 Trazabilidad y monitoreo

- Uso de **Spring Sleuth** y **Zipkin** para trazabilidad distribuida
- Centralización de logs

### 🔸 DevOps y despliegue

- Introducción a **Docker**
  - Crear imágenes y contenedores
  - Dockerfile y docker-compose
- Despliegue de microservicios en contenedores
- Introducción a **Jenkins**
  - CI/CD básico con Jenkinsfile
- Conceptos iniciales de **Kubernetes**

---

## 📁 Estructura del repositorio

```bash
bootcamp-modulo5-microservicios-devops/
├── README.md
├── /config-server
├── /eureka-server
├── /gateway
├── /servicio-usuarios
├── /servicio-productos
├── /docker
│   └── docker-compose.yml
├── /jenkins
│   └── Jenkinsfile
├── /docs
│   └── arquitectura_microservicios.png
├── /notas
│   └── comandos_docker_k8s.md
└── /recursos
    └── enlaces.txt
```

---

## ✅ Progreso

- [ ] Configuración de Eureka y Spring Config Server
- [ ] Servicios con Feign y Ribbon
- [ ] Gateway API funcional
- [ ] Trazabilidad con Sleuth y Zipkin
- [ ] Contenedores Docker para cada microservicio
- [ ] docker-compose funcionando
- [ ] Jenkinsfile y pruebas CI/CD
- [ ] Exploración inicial de Kubernetes

---

## 🔗 Recursos útiles

- [Spring Cloud Reference](https://spring.io/projects/spring-cloud)
- [Docker Docs](https://docs.docker.com/)
- [Docker Compose Docs](https://docs.docker.com/compose/)
- [Jenkins Docs](https://www.jenkins.io/doc/)
- [Kubernetes Docs](https://kubernetes.io/docs/)
- [12-Factor App](https://12factor.net/)

---

## ✍️ Autor

**Marcelo Amaya**  
Bootcamp Fullstack Java – CodiGo  
[GitHub](https://github.com/MarceloAM94)  
[LinkedIn](https://www.linkedin.com/in/marcelo-amaya-medina-614518268/)
