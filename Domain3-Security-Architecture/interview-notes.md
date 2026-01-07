
## Interview Notes – Domain 2: Security Architecture  

Notas técnicas basadas en escenarios reales del Dominio 2 y orientadas a entrevistas.

---

## Modelos de Arquitectura
La arquitectura se elige según control, escalabilidad y superficie de ataque.

- **On-Premises:** mayor control físico y lógico.
- **Cloud:** modelo de responsabilidad compartida, enfoque en IAM y cifrado.
- **IoT / ICS:** aislamiento, monitoreo y control de acceso estricto.

---

## Infraestructura Empresarial
Aplicación de defensa en profundidad y mínimo privilegio.

- Segmentación de red
- Accesos seguros (VPN, MFA)
- Comunicación cifrada (TLS, IPSec)

---

## Protección de Datos
La protección depende del tipo y criticidad del dato.

- Datos en reposo: cifrado
- Datos en tránsito: TLS
- Datos sensibles: control de acceso y auditoría

---

## Resiliencia y Recuperación
Disponibilidad garantizada mediante diseño resiliente.

- Redundancia y alta disponibilidad
- Backups probados
- BCP / DRP


