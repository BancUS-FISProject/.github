# BancUS - FIS Project

## Acceso al Servicio Web

El servicio se encuentra desplegado en Azure y expuesto mediante un túnel **Ngrok** (para optimización de costes).

### Requisito Previo: Certificados SSL
Nuestra API Gateway utiliza **HTTPS con certificados autofirmados**. Para que el navegador permita la conexión, debes realizar este paso **una única vez** antes de acceder a la web:

1. Accede al **Health Check de Autorización**: [🔗 Enlace a Health Auth](https://68.221.252.242:10000/v1/user-auth/health)
2. El navegador mostrará una advertencia de seguridad ("La conexión no es privada").
3. Haz clic en **Configuración avanzada** y selecciona **Continuar a... (inseguro)** para confiar en el certificado.

> **ℹNota sobre seguridad:**
> Usamos certificados autofirmados para cifrar la conexión (HTTPS). Esto significa que la transmisión de datos es segura, pero al no usar una entidad certificadora de pago, el navegador no reconocerá nuestra "firma" automáticamente. Por eso es necesario aceptar la excepción de seguridad manualmente accediendo a una ruta a través de la API Gateway

### Acceso a la Aplicación
Una vez aceptado el certificado en el paso anterior, puedes acceder a la plataforma:

[**Ir a la Página Web**](https://uncloseted-florine-brokenhearted.ngrok-free.dev/)

## 🛠️ Stack Tecnológico

### Infraestructura, Despliegue & Cloud
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![HTTPS](https://img.shields.io/badge/HTTPS-Secure-success?style=for-the-badge&logo=letsencrypt&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)

### Backend & Lenguajes
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Frontend & Bases de Datos
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)

### DevOps & Herramientas
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---
<div align="center">
  <sub>Desarrollado con ❤️ por el equipo de BancUS-FISProject | 2025/2026</sub>
</div>
