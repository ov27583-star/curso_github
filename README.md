# Reporte de Prácticas y Aprendizaje de Git

## 1. Qué aprendiste del video
A través de la práctica realizada en este repositorio, aprendí los conceptos fundamentales y el flujo de trabajo esencial de control de versiones con Git y GitHub:

* **Inicialización y estados de Git:** Comprobar el estado del directorio de trabajo (`git status`) para diferenciar entre archivos no rastreados (*untracked*), preparados (*staged*) y confirmados (*committed*).
* **Confirmación de cambios (*commits*):** Agrupar archivos y registrar puntos de control en la historia del proyecto con mensajes explicativos utilizando `git commit -m`.
* **Vinculación con repositorios remotos:** Conectar un repositorio local con GitHub (`git remote add origin`) y subir los cambios a la nube (`git push`).
* **Mantenimiento y corrección:** Realizar ajustes continuos al contenido, como actualizar el archivo `README.md` y corregir formatos o imágenes asociadas antes de sincronizarlos nuevamente.

---

## 2. Paso a paso de los comandos utilizados

A continuación se detalla el flujo de trabajo ejecutado en la terminal para la creación y gestión del repositorio:

### Paso 1: Inicialización del repositorio y verificación
Navegación al directorio local e inicialización de Git:
```bash
cd C:\Users\Oscar\OneDrive\Desktop\git
ls
git init
git status