# README – Informe Técnico Módulo 3  
**Autor:** Pedro Pérez Fernández  
**Asignatura:** Seguridad Informática  
**Centro:** MEDAC  
**Archivo:** `InformeTécninoModulo3.pdf`  

---

## Descripción general  
Este documento corresponde a la **tarea de evaluación del Módulo 3**, centrada en los principales mecanismos de seguridad informática aplicados en entornos de trabajo. El informe está estructurado en cuatro partes prácticas y una reflexión final.  

Cada apartado incluye capturas de pantalla, pasos detallados y conclusiones sobre las herramientas utilizadas.  

---

## Contenido del informe  

### **Parte 1 – Cifrado simétrico con AES Crypt**  
Se describe el proceso de descarga, instalación y uso de **AES Crypt** para proteger archivos mediante cifrado simétrico.  
Incluye una reflexión sobre las ventajas y riesgos de utilizar una misma clave para varios archivos.  

### **Parte 2 – Cifrado asimétrico con Gpg4win / Kleopatra**  
Se detalla la creación de un par de claves con **Kleopatra**, la exportación de la clave pública y el cifrado de mensajes de prueba.  
Se analiza qué ocurriría en caso de filtración de la clave privada.  

### **Parte 3 – Verificación de integridad con MD5**  
Se utiliza **PowerShell** para calcular el hash MD5 de un archivo y comprobar el **efecto avalancha** al modificar su contenido.  

### **Parte 4 – Control de acceso con ACL en Windows**  
Se crean tres usuarios locales (Técnico, Gerente y Externo) y se definen sus permisos específicos mediante listas de control de acceso (**ACL**).  

### **Reflexión final**  
Se expone la importancia de los mecanismos de seguridad para proteger la información sensible y prevenir accesos no autorizados en entornos empresariales.  

---

## Objetivo de la tarea  
Demostrar la comprensión y aplicación práctica de los conceptos fundamentales de **cifrado, integridad de datos y control de acceso** en sistemas informáticos.  

---

## Formato y herramientas utilizadas  
- **Formato del documento:** PDF  
- **Herramientas utilizadas:**  
  - AES Crypt  
  - Gpg4win / Kleopatra  
  - PowerShell (comando `Get-FileHash`)  
  - Configuración de permisos ACL en Windows  

---

## Conclusión  
El informe presenta una ejecución completa de las prácticas del Módulo 3, con evidencias gráficas y explicaciones claras. Facilita la revisión del aprendizaje práctico en materia de seguridad informática.  
