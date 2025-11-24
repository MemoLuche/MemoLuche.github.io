# Mi Portafolio - GitHub Pages

Este es mi portafolio personal alojado en GitHub Pages.

## 🚀 Cómo subir a GitHub Pages

### Paso 1: Crear repositorio en GitHub
1. Ve a [github.com](https://github.com) e inicia sesión
2. Clic en el botón **"+"** (arriba derecha) → **"New repository"**
3. Nombre del repositorio: **`tuusuario.github.io`** (reemplaza "tuusuario" con tu nombre de usuario de GitHub)
   - **IMPORTANTE**: El nombre DEBE ser exactamente tu usuario seguido de `.github.io`
   - Ejemplo: si tu usuario es `juan123`, el repo debe llamarse `juan123.github.io`
4. Marca como **"Public"** (GitHub Pages gratis solo funciona con repos públicos)
5. NO marques "Add a README file"
6. Clic en **"Create repository"**

### Paso 2: Subir archivos desde tu computadora
Abre PowerShell en esta carpeta y ejecuta estos comandos:

```powershell
# Inicializar git en esta carpeta
git init

# Agregar todos los archivos
git add .

# Hacer commit
git commit -m "Mi portafolio inicial"

# Conectar con tu repositorio (reemplaza TUUSUARIO con tu usuario de GitHub)
git remote add origin https://github.com/TUUSUARIO/TUUSUARIO.github.io.git

# Cambiar a la rama main
git branch -M main

# Subir archivos
git push -u origin main
```

### Paso 3: Activar GitHub Pages (si no se activa automáticamente)
1. Ve a tu repositorio en GitHub
2. Clic en **"Settings"** (Configuración)
3. En el menú lateral, clic en **"Pages"**
4. En **"Source"**, selecciona:
   - Branch: **main**
   - Folder: **/ (root)**
5. Clic en **"Save"**

### Paso 4: ¡Ver tu página!
- En 1-2 minutos, tu página estará en: **`https://tuusuario.github.io`**
- GitHub te mostrará la URL en la sección Pages

## 📝 Personalizar tu portafolio

Antes de subir, personaliza estos datos en `index.html`:

- [ ] Tu nombre (línea 17, 38)
- [ ] Tus enlaces de GitHub, LinkedIn, Email (líneas 50-58)
- [ ] Descripción sobre ti (línea 40-43)
- [ ] Tu educación y ubicación (líneas 76-85)
- [ ] Nombres y URLs de tus 3 proyectos (líneas 97-190)
- [ ] Descripciones de proyectos
- [ ] Tecnologías que usaste en cada proyecto
- [ ] Tus habilidades técnicas (líneas 199-240)
- [ ] Tu información de contacto (líneas 256-280)

## 🔄 Actualizar tu portafolio

Cuando hagas cambios a los archivos:

```powershell
git add .
git commit -m "Descripción de los cambios"
git push
```

Los cambios se verán en tu página en 1-2 minutos.

## 🎨 Características

✅ Diseño responsive (móvil y escritorio)
✅ Tema oscuro profesional
✅ Animaciones suaves
✅ Menú hamburguesa en móvil
✅ Navegación smooth scroll
✅ Iconos de Font Awesome
✅ Tarjetas de proyectos interactivas

## 📱 Vista previa local

Para ver tu página antes de subirla:
1. Abre `index.html` directamente en tu navegador
2. O usa Live Server en VS Code

## 🆘 Problemas comunes

**No se ve mi página:**
- Verifica que el nombre del repo sea exactamente `tuusuario.github.io`
- Espera 2-5 minutos después de hacer push
- Verifica en Settings → Pages que esté activado

**Error 404:**
- Asegúrate de que el archivo se llame `index.html` (minúsculas)
- Verifica que esté en la raíz del repositorio, no en una subcarpeta

**Los cambios no se reflejan:**
- Limpia el caché del navegador (Ctrl + Shift + R)
- Espera unos minutos

---

¡Listo! Ahora tienes tu portafolio profesional en línea 🎉
