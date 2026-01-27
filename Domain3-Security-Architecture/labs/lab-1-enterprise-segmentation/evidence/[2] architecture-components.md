
# Architecture Components Overview / Descripción general de los componentes de la arquitectura

Este documento describe los componentes principales del diagrama de arquitectura de seguridad utilizado en este laboratorio así como su propósito dentro de una infraestructura empresarial.


## Cloud Provider (IaaS / PaaS / SaaS)
Representa servicios en la nube que requieren controles adicionales de seguridad.
Se observan mecanismos como:
- Cloud Firewall
- CASB (Cloud Access Security Broker)
para control de acceso, visibilidad y protección de datos.


## Edge Firewall (NGFW)
Firewall perimetral encargado de:
- Filtrar tráfico entrante y saliente
- Proteger contra ataques externos (ej. DDoS)
- Controlar el acceso hacia la DMZ y la red interna


## DMZ (Screened Subnet)
Zona intermedia que aloja servicios expuestos:
- Web servers (protegidos con WAF)
- Mail gateways
- DNS servers

Reduce el riesgo de acceso directo a la red interna.


## Internal Firewall (Segmentation)
Firewall interno utilizado para:
- Segmentación de red
- Control de tráfico entre zonas
- Aplicación del principio de mínimo privilegio


## Internal Network (Trusted Zone)
Red interna protegida donde se encuentran sistemas críticos, dividida en zonas:

### User Access Zone
- Estaciones de trabajo
- VDI
- NAC para control de acceso a la red

### Server Zone
- Servidores de aplicaciones
- Bases de datos (cifradas en reposo)
- Hosts de virtualización

### IoT / ICS Zone
- Dispositivos IoT
- Controladores industriales (ICS)
- Firewall industrial para entornos OT

### Management Zone
- SIEM para monitoreo
- IAM / PAM para gestión de identidades
- Orquestación de seguridad


## Secure Switches (VLANs)
Uso de switches seguros y VLANs para:
- Separar tráfico
- Reducir superficie de ataque
- Mejorar el control de red


## Resilience & Recovery Components
Elementos enfocados en disponibilidad y continuidad:
- Firewalls y balanceadores en alta disponibilidad
- Sistemas de backup cifrados (on-site y cloud)
- Sitio de recuperación ante desastres
- UPS y generadores eléctricos


