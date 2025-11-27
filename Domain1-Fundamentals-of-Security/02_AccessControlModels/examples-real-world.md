# Real-World Examples of Access Control Models

En este apartado listaré ejemplos concretos para relacionar los modelos con implementaciones reales:


1. DAC (Discretionary Access Control):

Sistemas Windows
Los archivos y carpetas permiten que el propietario decida quién puede leer, escribir o ejecutar. El dueño tiene control discrecional sobre permisos.


2. MAC (Mandatory Access Control):

Entornos del gobierno / militares
Documentos clasificados (Confidential, Secret, Top Secret) se asignan según etiquetas y niveles de seguridad.
Los usuarios no pueden modificar sus propios permisos.


3. RBAC (Role-Based Access Control):

Aplicaciones corporativas como Active Directory
Roles definidos:

"HR"

"Finance"

"IT Admin"

"Support"

Los usuarios heredan permisos según el rol asignado.


4. ABAC (Attribute-Based Access Control)

Servicios en la nube como AWS IAM o Azure AD
Las políticas toman decisiones basadas en atributos:

Usuario → “Department=Finance”

Recurso → “Data=Payroll”

Contexto → “Location=Office”, “Time=Business Hours”

Política típica:

“Permitir acceso si el usuario es del departamento de Finanzas, está en horario laboral y se conecta desde una IP corporativa.”


5. Mixto/Contextual (Zero Trust)

Google BeyondCorp
Acceso basado en:

Estado de dispositivo

Identidad

Riesgo en tiempo real

Reglas dinámicas

No se confía en nada por defecto, incluso dentro de la red interna.
