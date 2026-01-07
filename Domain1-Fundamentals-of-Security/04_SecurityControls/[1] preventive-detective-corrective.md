# Preventive / Detective / Corrective Controls

**Resumen rápido:**
- **Preventive controls:** evitan que un incidente ocurra.
  - Ejemplos: firewalls, MFA, hardening, políticas de acceso.
- **Detective controls:** identifican actividades sospechosas o incidentes.
  - Ejemplos: IDS/IPS, SIEM, FIM (File Integrity Monitoring), logs y auditorías.
- **Corrective controls:** mitigan o corrigen el daño tras un incidente.
  - Ejemplos: restauración desde backups, reconfiguración, parches de emergencia, playbooks de IR.

**Cómo se emplean en conjunto:**
- Un IDS detecta un intento (detective) → alerta SIEM → playbook IR activa contención (corrective) → aplicar parche y endurecimiento para prevenir recurrencias (preventive).

**Buenas prácticas alineadas a Security+:**
- Diseñar controles en capas (defense in depth): preventivos al frente, detectivos en el centro, correctivos planificados.
- Priorizar controles según riesgo y costo.
