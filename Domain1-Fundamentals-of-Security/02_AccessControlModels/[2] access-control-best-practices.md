# Access Control Best Practices

Un control de acceso efectivo reduce la superficie de ataque y garantiza que los usuarios solo accedan a los recursos que necesitan. Las mejores prácticas clave incluyen:

---

## 1. Aplicar Principio de Mínimo Privilegio (PoLP)

Los usuarios deben tener únicamente los permisos necesarios para realizar sus tareas.

Esto reduce el impacto en caso de compromiso de cuentas o abuso de privilegios.

---

## 2. Implementar Segregación de Funciones (SoD)

Divide tareas críticas entre múltiples usuarios para evitar fraude o uso indebido.

**Ejemplo:**  
quien crea pagos no debe aprobarlos.

---

## 3. Realizar Revisiones de Acceso Periódicas

Auditar permisos regularmente permite:

- eliminar accesos innecesarios  
- detectar cuentas antiguas  
- reducir privilegios excesivos

---

## 4. Implementar Control de Acceso Basado en Roles (RBAC)

Estandarizar permisos por rol ayuda a:

- reducir errores humanos  
- simplificar la administración de accesos  
- mantener consistencia en la asignación de privilegios

---

## 5. Aplicar MFA Siempre que Sea Posible

La autenticación multifactor añade una capa adicional de seguridad más allá de usuario y contraseña.

Esto reduce significativamente el riesgo de accesos no autorizados.

---

## 6. Desactivar Cuentas Inactivas

Las cuentas no utilizadas representan posibles puntos de entrada para atacantes.

Se recomienda deshabilitar o eliminar cuentas que no se utilicen.

---

## 7. Aplicar Control de Acceso Basado en Atributos (ABAC)

Permite aplicar restricciones dinámicas basadas en atributos como:

- **ubicación**
- **horario**
- **tipo de dispositivo**
- **nivel de riesgo detectado**

Este enfoque se alinea con modelos modernos de seguridad, como **Zero Trust**.
