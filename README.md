# Abrir un Proyecto de Unity desde un Archivo .zip

Este documento describe los pasos necesarios para extraer y ejecutar un proyecto de Unity desde un archivo `.zip` usando Unity Hub.

## 📌 Requisitos Previos
- **Unity Hub** instalado ([Descargar aquí](https://unity.com/download))
- Una versión de **Unity** compatible con el proyecto
- Un programa para extraer archivos `.zip` (WinRAR, 7-Zip o equivalente)

---

## 📂 Paso 1: Extraer el Archivo .zip
1. Ubica el archivo `.zip` en tu computadora.
2. Haz clic derecho sobre el archivo y selecciona:
   - **Windows**: "Extraer aquí" o "Extraer en [nombre de la carpeta]".
   - **Mac**: Doble clic sobre el archivo para descomprimirlo automáticamente.
3. Espera a que se extraigan los archivos en una nueva carpeta.

---

## 📁 Paso 2: Verificar la Estructura del Proyecto
Dentro de la carpeta extraída, asegúrate de que contiene los siguientes directorios y archivos:
- `Assets/` → Contiene todos los archivos del juego.
- `ProjectSettings/` → Configuraciones del proyecto.
- `Packages/` → Dependencias del proyecto.
- `Library/` (puede no estar incluida en el `.zip`, Unity la generará automáticamente).
- Archivos `.unity` (escenas del juego).

Si solo encuentras un archivo `.exe`, significa que el `.zip` contiene un juego compilado y no un proyecto editable.

---

## 🖥️ Paso 3: Abrir el Proyecto en Unity Hub
1. Abre **Unity Hub**.
2. Haz clic en **‘Open’ (Abrir proyecto)**.
3. Navega hasta la carpeta extraída y selecciona la **carpeta raíz** del proyecto.
4. Haz clic en **‘Select Folder’ (Seleccionar carpeta)**.
5. Si el proyecto fue creado en una versión diferente de Unity, elige una versión compatible.
   - Si no tienes la versión correcta, descárgala desde la pestaña **‘Installs’** en Unity Hub.

---

## ⏳ Paso 4: Esperar a que Unity Cargue el Proyecto
- Unity puede tardar en reconstruir la carpeta `Library/` y compilar los assets.
- Si aparecen errores, revisa la **Consola** (`Ctrl + Shift + C`) y corrige cualquier problema.
- Si Unity pide actualizar el proyecto a una versión más nueva, es recomendable hacer un respaldo antes de aceptar.

---

## ▶️ Paso 5: Ejecutar el Proyecto en Unity
1. Abre una escena desde `Assets/Scenes` haciendo doble clic sobre ella.
2. Asegúrate de que la ventana **Game View** esté visible.
3. Presiona el botón **Play** en la parte superior para ejecutar el juego dentro del editor.

---

## ❓ Solución de Problemas Comunes
| Problema | Solución |
|----------|----------|
| **No se encuentra el proyecto** | Asegúrate de seleccionar la carpeta raíz al abrirlo en Unity Hub. |
| **El juego no corre bien** | Revisa los errores en la consola (`Ctrl + Shift + C`). |
| **Faltan paquetes** | Abre "Package Manager" (`Window > Package Manager`) y reinstala los paquetes necesarios. |

---

🚀 ¡Listo! Ahora puedes trabajar en tu proyecto de Unity sin problemas. 🎮
