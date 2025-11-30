# Authorization Challenges

**Definición:** autorización es la decisión que determina qué recursos puede usar un usuario autenticado.

Desafíos comunes:

- **Privilege Creep:** acumulación de permisos innecesarios con el tiempo.
- **Segregation of Duties faltante:** un usuario tiene permisos que deberían estar separados.
- **Excessive privileges:** roles mal diseñados o permisos demasiado amplios.
- **Stale accounts:** cuentas de ex-empleados no revocadas.
- **Context-aware access**: necesidad de políticas dinámicas (ej. hora, ubicación).

Modelos que reducen desafíos:

- **RBAC:** roles con permisos predefinidos — simplifica la gestión.
- **ABAC:** decisiones por atributos (usuario, recurso, ambiente) — más granular.
- **Least privilege:** conceder sólo lo estrictamente necesario.

Controles operativos:

- Revisiones periódicas de acceso (access reviews).
- Provisioning/Deprovisioning automatizado con IAM.
- Uso de just-in-time (JIT) access para permisos temporales.

**Ejemplo:** una empresa debe auditar trimestralmente roles administrativos y revocar permisos no usados en 90 días.
