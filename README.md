# Proyecto de Despliegue - UD4
**Autor:** [Nombre del Alumno]
**Fecha:** Febrero 2026

## 1. Entorno de Servidor
* **Servidor Web:** Apache (XAMPP) / Nginx (Linux)
* **Versión PHP:** 8.x
* **Acceso SFTP:** Configurado para usuario `deployer`

## 2. Configuración de Red
* **Dominio Local:** `www.proyecto-daw.test` -> Resolviendo a 127.0.0.1

## 3. Instrucciones de Despliegue
1. Clonar el repositorio.
2. Mover archivos mediante SFTP a la carpeta `htdocs`.
3. Verificar permisos de escritura en la subcarpeta `/uploads`.