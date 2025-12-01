# PKI Overview (Public Key Infrastructure)

**Componentes clave:**
- **CA (Certificate Authority):** emite certificados X.509.
- **Certificates:** vinculan identidad con clave pública.
- **CSR (Certificate Signing Request):** petición de certificado.
- **CRL / OCSP:** mecanismos para revocar certificados.
- **Key pair:** private key (secreta) + public key (distribuible).

**Flujo básico:**
1. Generar keypair.  
2. Crear CSR y enviarlo a la CA.  
3. CA emite certificado firmado.  
4. Servidor usa certificado para TLS; cliente verifica firma de la CA.

**Buenas prácticas:**
- Proteger la clave privada (HSM / envío seguro).
- Rotación periódica de certificados.
- Automatizar con ACME (Let's Encrypt) si aplica.

**Security+:** Incluye protección de sesiones TLS, validación de identidades en entornos corporativos y verificación de integridad mediante firmas digitales.
