# CAGS – Project ARES  
### (Autonomous Repair Exploration System)

🚀 **Proyecto desarrollado para el NASA Space Apps Challenge**

---

## 🧠 Descripción del Proyecto

**CAGS – Project ARES (Autonomous Repair Exploration System)** es una plataforma integral orientada a la **inspección, diagnóstico y reparación autónoma** mediante drones inteligentes en entornos críticos como:

- Estaciones espaciales  
- Zonas remotas  
- Ambientes industriales peligrosos  

El sistema integra **Inteligencia Artificial**, **backend administrativo**, **frontend de control tipo centro NASA** y **comunicación en tiempo real con drones**, permitiendo operaciones autónomas con supervisión humana.

---

## 👤 Liderazgo y Autoría

Este proyecto fue **concebido, propuesto y liderado por Juan Camilo Gómez Duarte**, quien dirigió al equipo durante el desarrollo dentro del **NASA Space Apps Challenge**, además de encargarse del diseño, entrenamiento e integración del backend de IA.

### Equipo del Proyecto

- **Juan Camilo Gómez Duarte**  
  *Líder del Proyecto & IA Backend*  
  Arquitectura del sistema, dirección del equipo, desarrollo y entrenamiento de la IA.

- **Gustavo Adolfo Castillo Páez**  
  *Ingeniero de Drones*  
  Diseño, ensamblaje y documentación técnica del dron CAGS_F413.

- **Ángel Daniel Scarpetta Ruiz**  
  *Backend Developer*  
  Desarrollo del backend administrativo, seguridad, roles y gestión de datos.

- **Sara Sofía Alzate Charry**  
  *Frontend Developer*  
  Interfaz gráfica de control y visualización estilo “Centro de Control NASA”.

---

## 🎯 Objetivo General

Desarrollar una plataforma completa que integre **IA, backend, frontend y drones**, capaz de ejecutar misiones de **diagnóstico y reparación remota de forma autónoma**, con monitoreo humano en tiempo real.

---

## 🏗️ Arquitectura del Sistema

El sistema está compuesto por cuatro capas principales:

1. **Capa Física / Dron**
   - Sensores, telemetría y navegación
   - Comunicación en tiempo real (MQTT / WebSockets)

2. **Capa Lógica / Backend**
   - Django REST Framework
   - Autenticación JWT y control por roles
   - Gestión de drones, eventos, reparaciones y auditoría

3. **Capa de Interfaz / Frontend**
   - React + Vite
   - Panel de control tipo NASA
   - Comunicación en tiempo real vía WebSockets

4. **Capa de Inteligencia Artificial**
   - Modelos de diagnóstico y predicción de fallas
   - Priorización de reparaciones
   - Aprendizaje continuo con datasets enviados desde el frontend

---

## 📦 Contenido del Repositorio

Este repositorio contiene:

/ai-models → Código de la Inteligencia Artificial
/frontend → Interfaz web de control y visualización
/videos → Video explicativo del proyecto
/reports → Informes técnicos y documentación


---

## 🧪 Estado del Proyecto

⚠️ **Este proyecto se encuentra en versión BETA**

- Backend funcional y seguro  
- Frontend conectado y en fase final  
- IA entrenada en entorno local  
- Comunicación con drones validada  

Aún pueden existir cambios estructurales, optimizaciones y mejoras antes de una versión estable.

---

## 🔐 Seguridad y Estándares

- HTTPS / TLS
- JWT con expiración y refresh tokens
- Roles y permisos diferenciados
- Logs inmutables y auditoría
- Preparado para evaluación OWASP Top 10

---

## 🌌 Contexto NASA Space Apps Challenge

Este proyecto fue desarrollado como parte del **NASA Space Apps Challenge**, tomando inspiración en:

- Operaciones autónomas espaciales  
- Telemetría de misiones NASA  
- Sistemas de mantenimiento orbital  

---

## 📌 Nota Final

CAGS – Project ARES representa una solución escalable y modular que demuestra la **integración real entre IA, software y hardware**, con potencial de aplicación en escenarios espaciales, industriales y de rescate.

---

### 📫 Contacto
**Juan Camilo Gómez Duarte**  
Proyecto líder y autor principal  
