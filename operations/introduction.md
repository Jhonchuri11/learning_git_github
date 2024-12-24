# Guía para Retroceso en Git

Cuando trabajamos en un proyecto de Git, a veces hacemos cambios que queremos eliminar. Git ofrece funciones similares a las de un borrador que nos permiten deshacer errores durante la creación del proyecto.

---

git show HEAD

## 2. chekout: Descartar Cambios en el Directorio de Trabajo

Si decides cambiar algo en tu directorio de trabajo pero luego quieres descartar ese cambio, puedes usar:

**Descripción:**
Descarta los cambios y vuelve al estado original de un archivo específico en el directorio de trabajo.

**Comando:**

```bash
git checkout HEAD <filename>

```bash
git checkout -- . 

```
## 3. more : Agregar Múltiples Archivos al Área de Preparación

Si decides agregar multiples archivos, puedes usar:

**Descripción:**
El comando git add se utiliza para agregar múltiples archivos al área de preparación.

Comando:

**Comando:**
```bash
git add <filename_1> <filename_2>
git add .
```

## 4. reset : Restablecer Archivos en el Área de Preparación (Parte I)

Podemos usar lo siguiente:

**Descripción:**
Este comando restablece un archivo en el área de preparación para que coincida con el HEAD actual. Nota: No afecta el directorio de trabajo

Comando:

**Comando:**
```bash
git reset HEAD <filename>

```

## 5. reset : Restablecer a un Commit Anterior (Parte II)

Podemos usar lo siguiente parte II:

**Descripción:**
Permite volver a un commit específico en el historial utilizando los primeros 7 caracteres del SHA de dicho commit.

Comando:

**Comando:**
```bash
git reset <commit_SHA>

**Example:**
Si el SHA de tu commit anterior es 5d692065cf51a2f50ea8e7b19b5a7ae512f633ba, usa:
```bash
git reset 5d69206