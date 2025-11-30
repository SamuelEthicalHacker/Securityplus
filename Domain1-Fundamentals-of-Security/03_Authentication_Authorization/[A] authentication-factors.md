
# Authentication Factors

**Definición:** factores que prueban la identidad de un usuario antes de otorgar acceso.

Tipos principales:

- **Something you know**: contraseña, PIN.
- **Something you have**: token hardware, smartphone (OTP), smartcard.
- **Something you are**: biometría (huella, cara, iris).
- **Somewhere you are**: geolocalización, dirección IP.
- **Something you do**: patrones de comportamiento (keystroke dynamics).

**MFA (Multi-Factor Authentication):**

- Uso recomendado: combinar al menos dos factores (ej. contraseña + OTP).
- Ventaja: reduce riesgo por contraseña comprometida.

**SSO (Single Sign-On):**

- Permite autenticarse una vez y acceder a múltiples servicios.
- Riesgo: si falla la protección central, el impacto es mayor — debe ir acompañado de MFA.

**Good practices (Security+):**

- Forzar MFA en accesos remotos y administradores.
- Políticas de complejidad y expiración razonables.
- Bloqueo de cuenta tras múltiples intentos fallidos y alertas.

**Breve ejemplo práctico:** habilitar MFA en un servicio (Google/Office 365) como control preventivo para accesos administrativos.
