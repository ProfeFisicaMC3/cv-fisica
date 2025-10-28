# 📚 CV Yoel Leonardo Alvez - Profesor de Física 🔬

Curriculum Vitae interactivo con animaciones de física y códigos QR.

## 🚀 Características

- ✅ **Login de acceso** con credenciales
- ✅ **Animaciones únicas** para cada fórmula física
- ✅ **Códigos QR** para contacto rápido
- ✅ **Diseño responsive** (móvil, tablet, desktop)
- ✅ **Descarga PDF** con el botón de impresión
- ✅ **Átomos animados** con electrones en órbita
- ✅ **Efectos visuales** específicos por fórmula

## 📁 Estructura del proyecto

```
cv-yoel-alvez/
├── index.html       # Página de login
├── cv.html          # Curriculum vitae
├── styles.css       # Estilos CSS
├── script.js        # JavaScript
└── README.md        # Este archivo
```

## 🔐 Credenciales de acceso

**Usuario:** `admin`  
**Contraseña:** `fisica2025`

También puedes acceder como invitado con el botón "Ver como invitado".

## 🌐 Cómo subir a GitHub Pages

### Opción 1: Interfaz web de GitHub

1. **Crear un repositorio en GitHub:**
   - Ve a https://github.com/new
   - Nombre: `cv-yoel-alvez` (o el que prefieras)
   - Público o Privado (tu elección)
   - Click en "Create repository"

2. **Subir los archivos:**
   - Click en "uploading an existing file"
   - Arrastra los 4 archivos: `index.html`, `cv.html`, `styles.css`, `script.js`
   - Click en "Commit changes"

3. **Activar GitHub Pages:**
   - Ve a Settings (⚙️) del repositorio
   - Menú lateral → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` y carpeta `/ (root)`
   - Click en "Save"
   - Espera 1-2 minutos

4. **¡Listo! Tu sitio estará en:**
   ```
   https://tu-usuario.github.io/cv-yoel-alvez/
   ```

### Opción 2: Línea de comandos (Git)

```bash
# 1. Crear carpeta del proyecto
mkdir cv-yoel-alvez
cd cv-yoel-alvez

# 2. Copiar los archivos al directorio
# (copia index.html, cv.html, styles.css, script.js)

# 3. Inicializar Git
git init
git add .
git commit -m "Initial commit - CV Yoel Alvez"

# 4. Crear repositorio en GitHub y conectar
git remote add origin https://github.com/TU-USUARIO/cv-yoel-alvez.git
git branch -M main
git push -u origin main

# 5. Activar GitHub Pages desde Settings → Pages
```

## 📥 Descargar como PDF

1. Accede al CV
2. Click en el botón **"Descargar PDF"**
3. Se abrirá el diálogo de impresión del navegador
4. Selecciona "Guardar como PDF" como destino
5. Click en "Guardar"

**Tip:** En el diálogo de impresión, selecciona "Fondo de gráficos" para mantener los colores y degradados.

## 🎨 Personalización

### Cambiar credenciales de login

Edita `index.html`, línea ~200:

```javascript
if (username === 'admin' && password === 'fisica2025') {
```

Cambia `'admin'` y `'fisica2025'` por tus credenciales.

### Cambiar información de contacto

Edita `cv.html` en la sección de contacto y actualiza:
- Números de teléfono
- Emails
- Códigos QR (se generan automáticamente)

### Cambiar colores

Edita `styles.css`, líneas 1-7:

```css
:root {
    --primary: #1a237e;      /* Color principal */
    --secondary: #0091ea;    /* Color secundario */
    --accent: #00e676;       /* Color de acento */
    --light: #e8eaf6;        /* Color claro */
    --dark: #0d47a1;         /* Color oscuro */
    --gray: #546e7a;         /* Color gris */
}
```

## 🔧 Tecnologías utilizadas

- **HTML5** - Estructura
- **CSS3** - Estilos y animaciones
- **JavaScript** - Interactividad
- **MathJax** - Renderizado de fórmulas matemáticas
- **QRCode.js** - Generación de códigos QR
- **Font Awesome** - Iconos

## 📱 Compatibilidad

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Móviles (iOS y Android)

## 🐛 Solución de problemas

### Los códigos QR no aparecen

1. Verifica que la librería QRCode.js esté cargando
2. Abre la consola del navegador (F12) y busca errores
3. Intenta recargar la página (Ctrl + F5)

### Las fórmulas no se ven

1. Verifica tu conexión a internet (MathJax se carga desde CDN)
2. Espera unos segundos para que MathJax cargue completamente

### No puedo acceder

1. Verifica las credenciales: `admin` / `fisica2025`
2. Borra el caché del navegador
3. Abre en modo incógnito

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de usar, modificar y distribuir.

## 👨‍🏫 Contacto

**Yoel Leonardo Alvez**  
📧 yoelalvez@abc.gob.ar  
📧 yoelleo102015@gmail.com  
📱 +54 9 221 3103127  
📱 +54 9 11 33402821

---

⚛️ **"La física es el lenguaje con el que está escrito el universo"** - Galileo Galilei

Desarrollado con 💙 y ⚡ por Yoel Alvez
