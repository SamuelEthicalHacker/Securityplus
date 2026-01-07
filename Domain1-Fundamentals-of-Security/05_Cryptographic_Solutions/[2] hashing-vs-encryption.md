# Hashing vs Encryption

**Hashing (no reversible):**
- Función unidireccional que mapea datos a un valor fijo (hash).
- Usos: integridad (verificar que un archivo no cambió), almacenamiento de contraseñas (con salt y algoritmos adecuados).
- Ejemplo: SHA-256. No usar MD5/SHA1 para seguridad.

**Encryption (reversible):**
- Transforma datos para ocultarlos; reversible con la clave correcta.
- Usos: confidencialidad en tránsito (TLS) y en reposo (full-disk encryption).

**Comparación rápida:**
- Hashing garantiza integridad; cifrado garantiza confidencialidad.  
- Para autenticar origen + integridad se usan **firmas digitales** (hash + cifrado asimétrico).

**Mejores prácticas:**
- Hashear contraseñas con algoritmos lentos (bcrypt, Argon2) y salt.  
- Usar TLS para datos en tránsito y AES para reposo; gestionar claves en HSM/KMS cuando sea posible.
