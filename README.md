# README – Informe Técnico Módulo 3  
**Autor:** Pedro Pérez Fernández  
**Asignatura:** Seguridad Informática  
**Centro:** MEDAC  
**Archivo principal:** `InformeTécninoModulo3.pdf`  

---

## Descripción general  
Este repositorio contiene la **tarea de evaluación del Módulo 3**, centrada en los principales mecanismos de seguridad informática aplicados en sistemas operativos y gestión de datos.  

El trabajo se divide en cuatro partes prácticas (cifrado simétrico, cifrado asimétrico, verificación de integridad y control de acceso) y una reflexión final. Además, se incluyen los archivos generados durante la realización de las prácticas.  

---

## Contenido del repositorio  

### **1. Documento principal**
- `InformeTécninoModulo3.pdf`  
  Informe técnico completo que documenta paso a paso el desarrollo de todas las prácticas del módulo.

---

### **2. Archivos de la práctica de cifrado simétrico (AES Crypt)**  
Estos archivos fueron cifrados mediante **AES Crypt** utilizando una clave común para demostrar el funcionamiento del cifrado simétrico:

- `clientes.txt` → Archivo original.  
- `clientes.txt.aes` → Archivo cifrado con AES.  
- `contratos.txt.aes` → Archivo cifrado adicional.  
- `manual.pdf.aes` → Archivo PDF cifrado con AES.

**Objetivo:** Proteger la información confidencial en archivos locales mediante una contraseña compartida.  
**Conclusión:** Usar una sola contraseña facilita el acceso, pero representa un riesgo si se compromete.  

---

### **3. Archivos de la práctica de cifrado asimétrico (Gpg4win / Kleopatra)**  
Estos archivos corresponden al uso de cifrado con claves pública y privada mediante **Kleopatra**:

- `mensaje.txt` → Mensaje original sin cifrar.  
- `mensaje.txt.gpg` → Mensaje cifrado con la clave pública.  
- `pedro perez fernandez_0xA5DF2CB2_public.asc` → Clave pública exportada desde Kleopatra.  

**Objetivo:** Demostrar el cifrado de datos mediante par de claves asimétricas (pública y privada).  
**Conclusión:** Si la clave privada se filtra, un tercero puede descifrar los mensajes o suplantar la identidad del propietario.  

---

### **4. Archivos de la práctica de verificación de integridad (MD5)**  
Se muestran los resultados de los comandos utilizados para generar y comparar los hashes de un archivo:

- `hash_original.txt` → Hash original generado con MD5.  
- `hash_copia.txt` → Hash posterior a la modificación del archivo.  

**Objetivo:** Comprobar cómo un cambio mínimo en el archivo genera un hash completamente distinto (efecto avalancha).  

---

### **5. Control de acceso con ACL en Windows**  
La práctica consistió en crear tres usuarios locales con diferentes niveles de permisos sobre una carpeta compartida:

- **Técnico** – Acceso total.  
- **Gerente** – Lectura y modificación.  
- **Externo** – Solo lectura.  

**Objetivo:** Aplicar listas de control de acceso (ACL) para gestionar los permisos en entornos Windows.  
**Conclusión:** La correcta configuración de permisos minimiza riesgos de acceso no autorizado.  

---

## Objetivo de la tarea  
Demostrar la comprensión y aplicación práctica de los conceptos de **cifrado, integridad y control de acceso**, fundamentales para la protección de la información en sistemas informáticos.  

---

## Herramientas utilizadas  
- **AES Crypt** – Cifrado simétrico.  
- **Gpg4win / Kleopatra** – Cifrado asimétrico.  
- **PowerShell** – Comandos `Get-FileHash` y `certutil` para verificación de integridad.  
- **Windows** – Configuración de permisos mediante ACL.  

---

## Conclusión  
El conjunto de archivos y el informe demuestran la aplicación práctica de distintos métodos de seguridad informática:  
- El **cifrado** protege la confidencialidad.  
- La **verificación de integridad** garantiza que los datos no se han modificado.  
- El **control de acceso** limita la exposición a usuarios no autorizados.  

Este proyecto evidencia el dominio de las herramientas básicas para la protección de la información en entornos empresariales.  
