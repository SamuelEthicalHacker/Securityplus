# Encryption Basics

**Propósito:** proteger la confidencialidad (y, en algunos casos, integridad) de datos.

- **Cifrado simétrico:** misma clave para cifrar y descifrar. Ej.: AES. Eficiente para grandes volúmenes.  
- **Cifrado asimétrico (pública/privada):** par de claves (RSA, ECC). Útil para intercambio de claves, firma digital y TLS handshake.  
- **Modos y prácticas:** usar AES-GCM para confidencialidad + integridad; evitar modos inseguros (ECB).  
- **Key management:** la seguridad depende de la gestión de claves (rotación, almacenamiento seguro, acceso restringido).

**Relevancia Security+:**
- Saber diferencias, cuándo usar cada uno, y conceptos de PKI (certificados, CA, CSR).
