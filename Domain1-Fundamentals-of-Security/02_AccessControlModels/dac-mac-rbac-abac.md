
# Access Control Models (DAC, MAC, RBAC, ABAC)

Los modelos de control de acceso definen cómo se gestionan los permisos dentro de un sistema. Security+ requiere conocer sus características, ventajas y limitaciones.

---

## 1. DAC – Discretionary Access Control
En DAC, el **propietario del recurso** decide quién puede acceder.  
- **Ventajas:** flexible, fácil de administrar.  
- **Desventajas:** menos seguro; usuarios pueden dar acceso accidentalmente.  
- **Ejemplo:** permisos de archivos en Windows (propietario decide Allow/Deny).

---

## 2. MAC – Mandatory Access Control
El sistema aplica permisos basados en **clasificaciones y etiquetas**.  
- **Ventajas:** muy seguro, ideal para ambientes gubernamentales.  
- **Desventajas:** estrictamente controlado; poca flexibilidad.  
- **Ejemplo:** sistemas con niveles como Confidential, Secret, Top Secret.

---

## 3. RBAC – Role-Based Access Control
Los permisos se asignan por **roles**, no por usuarios individuales.  
- **Ventajas:** escalable, estándar empresarial.  
- **Desventajas:** requiere diseño claro de roles.  
- **Ejemplo:** rol “HR_Manager” accede a datos de empleados; rol “Admin” accede a sistemas críticos.

---

## 4. ABAC – Attribute-Based Access Control
El acceso depende de **atributos**: usuario, recurso, contexto, hora, ubicación.  
- **Ventajas:** muy granular y dinámico.  
- **Desventajas:** complejidad en políticas y reglas.  
- **Ejemplo:** “Permitir acceso si empleado es del departamento Finanzas **y** está dentro del país **y** es horario laboral”.
