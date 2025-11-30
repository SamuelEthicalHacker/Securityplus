# Case Study: Privilege Creep

**Escenario resumido:**
- Empleado "Leonardo" entra en soporte (Role: Helpdesk).
- Con el tiempo le asignan tareas de inventario, luego proyecto de seguridad (Role: Analyst).
- No se retiraron permisos originales (reset de contraseñas, acceso a cuentas de usuarios).
- Resultado: Leonardo acumula permisos innecesarios y ahora puede cambiar políticas o ver datos sensibles.

**Riesgos:**
- Mayor superficie de ataque si la cuenta se compromete.
- Potencial abuso interno (intencional o accidental).
- Dificulta auditoría y cumplimiento.

**Medidas de remediación (prácticas, Security+):**
1. Implementar **RBAC** y mapear roles a responsabilidades claras.  
2. Revisiones periódicas de acceso (access recertification) cada 90 días.  
3. Automatizar **provisioning/deprovisioning** con un sistema IAM (con integración HR).  
4. Registrar cambios y exigir justificación para permisos elevados (approval workflow).  
5. Aplicar **just-in-time (JIT)** y sesiones elevadas temporales para tareas administrativas.

**Resultado esperado:** reducción de privilegios activos, mejora en trazabilidad y cumplimiento.
