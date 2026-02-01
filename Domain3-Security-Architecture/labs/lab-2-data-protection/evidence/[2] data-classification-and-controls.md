
# Data Classification and Security Controls / Clasificación de datos y controles de seguridad

## 1. Data Classification / Clasificación de datos

### Public Data 
Información destinada al público general.
- Ejemplos: sitio web corporativo, comunicados públicos
- Impacto ante exposición: bajo

### Internal Data
Información de uso interno de la organización.
- Ejemplos: documentación interna, diagramas no sensibles
- Impacto ante exposición: medio

### Confidential Data
Información crítica para la operación del negocio.
- Ejemplos: datos financieros, bases de datos de clientes
- Impacto ante exposición: alto

### Sensitive / Restricted Data
Información altamente sensible o regulada.
- Ejemplos: credenciales, información personal (PII), datos legales
- Impacto ante exposición: crítico

---

## 2. Security Controls by Data Type / Controles de seguridad por tipo de datos

### Encryption at Rest / Cifrado en reposo
- Aplicado a bases de datos y sistemas de almacenamiento
- Protege datos en caso de acceso no autorizado al sistema

### Encryption in Transit / Cifrado en tránsito
- Uso de TLS/VPN para comunicaciones internas y externas
- Evita intercepción y manipulación de datos

### Access Control / Control de acceso
- Control de acceso basado en roles (RBAC)
- Principio de mínimo privilegio

### Network Segmentation / Segmentación de red
- Separación de zonas (usuarios, servidores, gestión)
- Reduce la superficie de ataque y el movimiento lateral

### Monitoring and Auditing / Supervisión y auditoría
- Registro y monitoreo de accesos a datos críticos
- Detección temprana de accesos no autorizados

