# este es una clase de intro a github

# Mi primer repositorio con Git

## 📌 Descripción
Este proyecto es una práctica para aprender a usar Git y GitHub.

## 👩‍💻 Autor
Rocío de Ochoa

## 📅 Fecha
Abril 2026

# 🧭 Guía Práctica de Git (Paso a Paso)

## 📌 Descripción

Esta guía muestra el uso básico de Git mediante un ejercicio práctico, donde se aplican los comandos fundamentales para el control de versiones.

---

## 🔁 Flujo de trabajo en Git

El ciclo básico que se repite es:

```bash
git status
git add .
git commit -m "mensaje del cambio"
git push
```

---

## 🔹 Paso 1: Verificar estado

```bash
git status
```

**Explicación:**
Permite ver los cambios realizados en los archivos.

---

## 🔹 Paso 2: Ver cambios realizados (opcional)

```bash
git diff
```

**Explicación:**
Muestra exactamente qué se ha modificado en el archivo.

---

## 🔹 Paso 3: Agregar cambios

```bash
git add intro.md
```

**O agregar todo:**

```bash
git add .
```

**Explicación:**
Prepara los archivos para ser guardados.

---

## 🔹 Paso 4: Guardar cambios (commit)

```bash
git commit -m "Agrego nueva sección"
```

**Explicación:**
Guarda los cambios en el historial del proyecto.

---

## 🔹 Paso 5: Subir cambios a GitHub

```bash
git push
```

**Explicación:**
Envía los cambios al repositorio en línea.

---


### ✔ Actividad 3

Corrige o modifica un texto existente

---

## 🔍 Ver historial de cambios

```bash
git log
```

**Versión resumida:**

```bash
git log --oneline
```

---

## ⚠️ Errores comunes

* No ejecutar `git add`
* Olvidar `git push`
* Escribir mensajes de commit poco claros

---

## 🎯 Buenas prácticas

* Hacer commits frecuentes
* Escribir mensajes claros
* Revisar cambios antes de subirlos

---

## 🚀 Conclusión

Git permite llevar un control ordenado de los cambios en un proyecto, facilitando el trabajo individual y colaborativo.
