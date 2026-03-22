
# Computing Resources Security / Seguridad en Recursos de Cómputo

La Seguridad en Recursos de Cómputo constituye la capa de defensa técnica aplicada directamente sobre los sistemas, dispositivos y aplicaciones de una organización para reducir drásticamente su superficie de ataque y mitigar riesgos operativos. 

---

## Applying Secure Baselines / Aplicación de Líneas Base Seguras

Es la implementación de configuraciones mínimas seguras previamente definidas para sistemas operativos, servidores, dispositivos de red y endpoints.

Incluye:

- Deshabilitar servicios innecesarios
- Configurar políticas de contraseña
- Establecer reglas de firewall locales
- Configurar auditoría y logging
- Aplicar políticas de cifrado

El objetivo es garantizar consistencia, cumplimiento y reducción de superficie de ataque.

---

## Mobile Solutions / Soluciones Móviles

Se refiere a la gestión segura de dispositivos móviles dentro de la organización.

Controles clave:

- MDM (Mobile Device Management)
- MAM (Mobile Application Management)
- Cifrado de dispositivo
- Autenticación multifactor
- Remote wipe
- Control de aplicaciones instaladas

Permite proteger datos corporativos en dispositivos BYOD o corporativos.

---

## Hardening / Endurecimiento

Proceso de fortalecer sistemas eliminando configuraciones débiles o innecesarias.

Acciones comunes:

- Eliminar cuentas por defecto
- Aplicar parches y actualizaciones
- Configurar políticas de bloqueo
- Restringir privilegios administrativos
- Deshabilitar protocolos inseguros (ej. Telnet, SMBv1)

Reduce el riesgo de explotación de vulnerabilidades conocidas.

---

## Wireless Security / Seguridad Inalámbrica

Protección de redes Wi-Fi corporativas.

Medidas esenciales:

- Uso de WPA3 o mínimo WPA2-Enterprise
- Autenticación basada en 802.1X
- Segmentación de red (VLANs)
- Deshabilitar SSID broadcasting cuando aplique
- Detección de rogue access points

Previene accesos no autorizados y ataques como Evil Twin o Rogue AP.

---

## Application Security / Seguridad de Aplicaciones

Protección del software durante su desarrollo y ejecución.

Controles clave:

- Validación de entrada de datos
- Principio de mínimo privilegio
- Gestión segura de sesiones
- Uso de HTTPS/TLS
- Revisión de código y análisis estático

Reduce vulnerabilidades como inyección, XSS o escalación de privilegios.

---

## Sandboxing / Aislamiento Controlado

Ejecución de aplicaciones o código en entornos aislados para prevenir impacto al sistema principal.

Se utiliza en:

- Navegadores
- Análisis de malware
- Entornos de prueba
- Contenedores

Limita el acceso a recursos críticos del sistema.

---

## Monitoring / Monitoreo

Supervisión continua de recursos de cómputo para detectar actividad anómala.

Incluye:

- Recolección de logs
- Detección de cambios de configuración
- Alertas por comportamiento sospechoso
- Integración con SIEM

Permite detección temprana de incidentes y desviaciones del baseline.


## Reflexión Técnica

El desarrollo de esta sección me ha permitido comprender que la seguridad de los recursos de cómputo no depende únicamente de herramientas avanzadas, sino también de configuraciones básicas correctamente aplicadas y mantenidas.

Al analizar las líneas base de seguridad (secure baselines), el hardening de sistemas, la seguridad de redes inalámbricas, la protección de aplicaciones y el monitoreo, he reforzado la importancia de la estandarización como mecanismo para reducir errores humanos y desviaciones de configuración.

También he podido identificar que muchos incidentes de seguridad tienen su origen en configuraciones débiles o por defecto, lo que confirma que el endurecimiento de sistemas y la aplicación consistente de controles preventivos son fundamentales dentro de las operaciones de seguridad.


