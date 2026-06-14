##**Trabajo Práctico:** Servidor Linux (Debian)
**Asignatura:** Computación Aplicada  
**Fecha de Entrega:** 15 de junio de 2026  

##INTEGRANTES:
* Agustina Giorgi
* Pablo Alexander Valenciano
* Mariangeles Sol Gomez Dalla Fontana

---

##CONTENIDO: 
El repositorio cuenta con los siguientes entregables, comprimidos individualmente en formato .tar.gz:
* **root.tar.gz**: Directorio home del usuario administrador, incluyendo las claves SSH (.ssh/);
* **etc.tar.gz**: Archivos de configuración global del sistema;
* **opt.tar.gz**: Scripts de automatización personalizados (en /opt/scripts/); 
* **www_dir.tar.gz**: Directorio de la aplicación web;
* **backup_dir.tar.gz**: Dedicado al almacenamiento de backups.

---

##**Notas:
Debido a las restricciones de tamaño de archivo de GitHub, el directorio /var ha sido comprimido y dividido en partes de máximo 20MB cada una:
* **var.tar.gz.part_aa**
* **var.tar.gz.part_ab**
* ...

Para descomprimir y reconstruir la carpeta /var original en un entorno Linux, utilizar los siguientes comandos:
1. cat var.tar.gz.part_* > var.tar.gz (para unir las partes en un único archivo comprimido);
2. tar -xzf var.tar.gz (para descomprimir el archivo que contiene todas las partes).
