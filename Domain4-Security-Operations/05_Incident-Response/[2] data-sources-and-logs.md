# Data Sources and Logs / Fuentes de Datos y Registros

Las investigaciones de seguridad dependen del uso adecuado de múltiples fuentes de datos. 
Los registros (logs) permiten reconstruir eventos, identificar responsables y determinar el impacto de un incidente.

---

## Log Data / Datos de Registro

Los logs registran eventos generados por sistemas y aplicaciones.

Principales tipos:

### System Logs / Registros del Sistema
- Eventos del sistema operativo.
- Intentos de autenticación.
- Fallos de servicios.
- Escalamientos de privilegios.

### Application Logs / Registros de Aplicaciones
- Errores de aplicación.
- Accesos a funcionalidades.
- Cambios de configuración.
- Transacciones críticas.

### Security Device Logs / Registros de Dispositivos de Seguridad
- Firewalls.
- IDS/IPS.
- Proxies web.
- VPN.

Estos registros son esenciales para detectar actividad sospechosa y accesos no autorizados.

## Network Data / Datos de Red

Proporcionan visibilidad sobre el tráfico que circula dentro y fuera de la organización.

Ejemplos:

- NetFlow.
- Capturas de paquetes (PCAP).
- Consultas DNS.
- Registros DHCP.
- Alertas de sistemas de detección de intrusiones.

Son clave para identificar movimientos laterales y comunicación con servidores externos maliciosos.

## Endpoint Telemetry / Telemetría de Endpoint

Las soluciones de monitoreo en equipos finales permiten observar actividad a nivel host:

- Creación de procesos.
- Modificaciones del registro.
- Cambios en archivos.
- Eventos de memoria.
- Alertas EDR.

Permiten detectar comportamientos asociados a malware y técnicas de evasión.

## Identity and Authentication Logs / Registros de Identidad y Autenticación

Muchos incidentes están relacionados con el abuso de credenciales.

Fuentes relevantes:

- Registros de Active Directory.
- Logs de plataformas IAM en la nube.
- Eventos de autenticación multifactor.
- Uso de cuentas privilegiadas.

Ayudan a detectar accesos indebidos y escalamiento de privilegios.

## Cloud Data Sources / Fuentes de Datos en la Nube

Los entornos cloud generan registros específicos como:

- Actividad de API.
- Accesos a almacenamiento.
- Cambios de configuración.
- Alertas de postura de seguridad.

La centralización de estos registros es crítica en arquitecturas híbridas.

---

## Log Management and SIEM / Gestión de Logs y SIEM

La agregación centralizada mejora la capacidad de análisis y correlación.

Aspectos clave:

- Normalización de datos.
- Sincronización de tiempo (NTP).
- Políticas de retención.
- Reglas de correlación.
- Generación de alertas.

Las plataformas SIEM permiten identificar patrones complejos y acelerar investigaciones.

## Supporting Investigations / Soporte a Investigaciones

Las fuentes de datos permiten:

- Reconstrucción cronológica de eventos.
- Identificación de usuarios o sistemas comprometidos.
- Evaluación del impacto.
- Preservación de evidencia.
- Cumplimiento regulatorio.

La efectividad de una investigación depende de la integridad, disponibilidad y retención adecuada de los registros.

## Reflexión Técnica

Con el estudio de las fuentes de datos y registros he reforzado un aspecto clave: la calidad de la detección y la investigación depende directamente de la integridad y cobertura de los logs disponibles.

Identifiqué la necesidad de centralizar y normalizar los eventos para facilitar la correlación y el análisis eficiente.

Asimismo, comprendí la importancia de contar con políticas de retención adecuadas para soportar investigaciones forenses y cumplir con requisitos normativos.

Este análisis fortaleció mi entendimiento sobre los registros como uno de los activos más críticos dentro de las operaciones de seguridad.
