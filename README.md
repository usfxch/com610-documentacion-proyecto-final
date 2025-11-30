# 🧩 Proyecto Final – Trabajando en la Nube  
**Carrera:** Ciencias de la Computación  
**Asignatura:** Trabajando en la Nube (COM610)
**Docente:** Ing. Marcelo Quispe Ortega
**Grupo:**  
- Integrante 1 – (correo)  
- Integrante 2 – (correo)  
- Integrante 3 – (opcional)  
- Integrante 4 – (opcional)

## 📌 1. Título del Proyecto
> Nombre representativo del sistema o solución creada.

## 🎯 2. Objetivo General
Describir claramente el propósito del proyecto y el problema que resuelve.

## 🎯 3. Objetivos Específicos
- Objetivo 1  
- Objetivo 2  
- Objetivo 3  

## 📝 4. Descripción General del Proyecto
Breve explicación de qué hace el sistema, quiénes serían los usuarios finales y en qué escenario real sería útil.

## 🛠️ 5. Tecnologías Utilizadas
Listar y describir las tecnologías empleadas y su propósito de uso.
- Docker  
- Docker Compose  
- AWS EC2  
- AWS RDS  
- AWS S3  
- Auto Scaling Group (ASG)  
- Elastic Load Balancer (ELB)  
- Lenguajes, frameworks adicionales (Node.js, Python, React, etc.)  

## 📚 6. Temas de la Asignatura Implementados
Explicar cómo se aplicó cada tema avanzado:

### 6.1 Contenerización con Docker
- Breve descripción  
- Dockerfile utilizado  

### 6.2 Orquestación con Docker Compose
- Servicios definidos  
- Variables de entorno  
- Dependencias  

### 6.3 Instancias Computacionales, Acceso Seguro y Bases de Datos (EC2, RDS)
- Configuración de la instancia EC2  
- Acceso SSH / llaves  
- Configuración de seguridad (Security Groups)  
- Motor de base de datos en RDS  
- Conexiones seguras a la BD  

### 6.4 Almacenamiento, Elasticidad y Escalado Automático (S3, ASG, ELB)
- Uso del bucket S3 (estático, almacenamiento, uploads, etc.)  
- Configuración del Auto Scaling Group (métricas, políticas)  
- Configuración del Balanceador de Carga (tipo, listeners, rutas)  

## 🏗️ 7. Arquitectura del Sistema
### 7.1 Diagrama General de la Infraestructura (requerido)
_Incluir imagen del diseño arquitectónico._  
Sugerencia: subir el diagrama en `/assets/diagram.png`

### 7.2 Explicación del Flujo de la Solución
Describir cómo interactúan los componentes:
- Usuario → ELB → ASG/EC2  
- Contenedores Docker → Aplicación  
- EC2 → RDS  
- EC2/Aplicación → S3  

## 🚀 8. Pasos para Desplegar la Solución
### 8.1 Requisitos Previos
- AWS CLI configurado  
- Docker y Docker Compose instalados  
- Parámetros necesarios (.env, secrets)  

### 8.2 Instrucciones
```bash
# Ejemplo
docker-compose up -d
```

(Actualizar con pasos reales del proyecto).

## 📚 9. Conclusiones y Lecciones Aprendidas

Resumen de los principales logros y desafíos técnicos superados. ¿Qué harían diferente?