# Real-World Examples of Access Control Models

En este apartado se presentan ejemplos concretos que relacionan los modelos de control de acceso con implementaciones reales.

---

## 1. DAC (Discretionary Access Control)

**Ejemplo: Sistemas Windows**

Los archivos y carpetas permiten que el **propietario del recurso** decida quién puede:

- Leer
- Escribir
- Ejecutar

El propietario tiene control discrecional sobre los permisos, pudiendo otorgar o revocar acceso a otros usuarios.

---

## 2. MAC (Mandatory Access Control)

**Ejemplo: Entornos gubernamentales o militares**

Los documentos clasificados se asignan según **niveles de seguridad y etiquetas**, tales como:

- Confidential
- Secret
- Top Secret

Características clave:

- Los permisos son definidos por el sistema o la política de seguridad.
- Los usuarios no pueden modificar sus propios permisos.

---

## 3. RBAC (Role-Based Access Control)

**Ejemplo: Aplicaciones corporativas con Active Directory**

Los permisos se asignan a **roles**, y los usuarios heredan los accesos según el rol asignado.

Roles típicos dentro de una organización:

- **HR**
- **Finance**
- **IT Admin**
- **Support**

Esto permite administrar permisos de forma centralizada y escalable.

---

## 4. ABAC (Attribute-Based Access Control)

**Ejemplo: Servicios en la nube (AWS IAM o Azure AD)**

Las políticas toman decisiones de acceso basadas en **atributos**.

### Tipos de atributos

**Usuario**

- `Department = Finance`

**Recurso**

- `Data = Payroll`

**Contexto**

- `Location = Office`
- `Time = Business Hours`

### Política típica

> Permitir acceso si el usuario pertenece al departamento de Finanzas, se encuentra dentro del horario laboral y se conecta desde una IP corporativa.

---

## 5. Modelo Mixto / Contextual (Zero Trust)

**Ejemplo: Google BeyondCorp**

El acceso se basa en múltiples factores dinámicos:

- Estado del dispositivo
- Identidad del usuario
- Riesgo en tiempo real
- Reglas dinámicas de seguridad

Principio clave:

> No se confía en ningún usuario o dispositivo por defecto, incluso si se encuentra dentro de la red interna.
