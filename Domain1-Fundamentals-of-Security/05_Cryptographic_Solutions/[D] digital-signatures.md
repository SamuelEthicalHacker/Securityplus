# Digital Signatures

**¿Qué son?:** mecanismo que usa criptografía asimétrica para garantizar **autenticidad** e **integridad** del mensaje/documento.

Proceso:
1. Se calcula un hash del mensaje (ej. SHA-256).
2. El hash se cifra con la **clave privada** del firmante → firma.
3. El receptor descifra la firma con la **clave pública** del firmante y compara el hash.
 
**Usos prácticos:**
- Firma de emails (S/MIME), firmas de código, documentos legales digitales.
- Verificación de integridad en transferencias sensibles.

**Nota práctica:** las firmas no garantizan confidencialidad; para eso se cifra el contenido además de firmarlo.
