# learning_git_github
Complementando conocimiento en el control de versiones con Git y el almacenamiento de proyectos con GitHub.
# Git & GitHub Learning Notes

## 📚 Education Resources
[Git Cheat Sheet - Education PDF](https://education.github.com/git-cheat-sheet-education.pdf)

---

## 📝 Definition of Git
**Git** es un software de control de versiones que permite realizar un seguimiento de los cambios realizados en un proyecto a lo largo del tiempo.  
Funciona registrando cambios, almacenándolos y permitiéndote consultarlos cuando sea necesario.

---

## 🔄 Git Workflow
Un proyecto Git se compone de tres partes principales:

<div align="center">
  <img src="https://github.com/Jhonchuri11/learning_git_github/blob/main/basic%20-%20workflow/workflow.png" alt="Git Workflow" width="600">
</div>

1. **Directorio de trabajo**: Donde crearás, editarás, eliminarás y organizarás archivos.
2. **Área de preparación (staging area)**: Donde se enumeran los cambios realizados en el directorio de trabajo.
3. **Repositorio**: Almacén permanente de los cambios en diferentes versiones del proyecto.

**Flujo de trabajo en Git:**
1. Edita archivos en el directorio de trabajo.
2. Agrega los cambios al área de preparación.
3. Guarda los cambios en el repositorio.

---

## 🛠️ Git Commands and Usage

### 1️⃣ `git init`
- **Descripción**: Inicializa un nuevo repositorio Git, configurando las herramientas necesarias para comenzar a rastrear los cambios.  
- **Uso**:  
  ```bash
  git init
### 2️⃣ git status
- **Descripción**: Muestra el estado del directorio de trabajo, el área de preparación y qué archivos están rastreados o no.  
- **Uso**:  
  ```bash
  git status
### 3️⃣ git add
- **Descripción**: Agrega archivos al área de preparación para que Git los rastree.
- **Uso**:  
  ```bash
  git add <filename>
  git add scene-1.txt
### 4️⃣ git diff
- **Descripción**: Compara diferencias entre el directorio de trabajo y el área de preparación.
- **Uso**:  
  ```bash
  git diff <filename>
- **Ejemplo**:  
  ```bash
  git diff scene-1.txt
### 5️⃣ git commit
- **Descripción**: Guarda permanentemente los cambios del área de preparación dentro del repositorio.
- **Convenciones para mensajes de confirmación:**
   - Escribe el mensaje entre comillas.
   - Usa tiempo presente.
   - Sé breve (50 caracteres o menos).
- **Uso**:  
  ```bash
  git commit -m "Mensaje de confirmación"
- **Ejemplo**:  
  ```bash
  git commit -m "Complete first line of dialogue"
### 6️⃣ git log
- **Descripción**: Muestra un historial cronológico de las confirmaciones realizadas en el repositorio.
- **Información proporcionada:**
   - Código SHA (40 caracteres, identifica la confirmación).
   - Autor de la confirmación.
   - Fecha y hora de la confirmación.
   - Mensaje de confirmación.
- **Uso**:  
  ```bash
  git log
! Sigamos aprendiendo 😊 !

