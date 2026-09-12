# 📊 Extractor de Texto PowerPoint

Aplicación web 100% cliente que extrae texto de archivos PowerPoint (.pptx) de forma instantánea, privada y sin necesidad de servidor.

## ✨ Características

- ✅ **100% Client-side**: Todo se procesa en el navegador del usuario
- ✅ **Privado**: Los archivos nunca se suben a ningún servidor
- ✅ **Rápido**: Extracción instantánea sin latencia de red
- ✅ **Sin dependencias de backend**: Gratis de alojar
- ✅ **Drag & Drop**: Interfaz intuitiva y moderna
- ✅ **Copiar al portapapeles**: Un clic para copiar todo el texto
- ✅ **Descargar como .txt**: Exporta el resultado
- ✅ **Notas del orador**: Opción para incluir anotaciones

## 📁 Estructura del Proyecto

```
.
└── index.html          (Todo el código en un archivo)
```

Solo necesitas **UN archivo**: `index.html`

---

# 🚀 CÓMO DESPLEGAR EN 3 PASOS

Elige la opción que más te convenga:

## OPCIÓN 1: Vercel (⭐ RECOMENDADO - Lo más rápido)

### Paso 1: Crea un repositorio en GitHub (1 minuto)
1. Ve a https://github.com/new
2. Nombre: `pptx-extractor`
3. Descripción: "Extractor de texto PowerPoint"
4. Elige **Public** (para que Vercel lo pueda desplegar gratis)
5. Marca "Add a README file"
6. **Create repository**

### Paso 2: Sube el archivo `index.html` (1 minuto)
1. En tu repositorio, haz clic en "Add file" → "Create new file"
2. Nombre: `index.html`
3. Copia TODO el contenido del archivo `index.html`
4. Pegalo en el editor
5. **Commit changes**

### Paso 3: Despliega en Vercel (2 minutos)
1. Ve a https://vercel.com/
2. Haz clic en **"Sign up"** (o inicia sesión si ya tienes cuenta)
3. Elige "Continue with GitHub"
4. Autoriza Vercel
5. Haz clic en "Import Project"
6. Busca tu repositorio `pptx-extractor`
7. Haz clic en "Import"
8. ✅ **¡LISTO!** Vercel te dará una URL como `https://pptx-extractor.vercel.app`

**Tu enlace público:** Copia la URL y envíasela a tu novia 📧

---

## OPCIÓN 2: GitHub Pages (Gratis, dentro de GitHub)

### Paso 1: Crea un repositorio en GitHub
1. Ve a https://github.com/new
2. Nombre: `pptx-extractor`
3. Elige **Public**
4. Marca "Add a README file"
5. **Create repository**

### Paso 2: Sube el archivo
1. En tu repositorio, haz clic en "Add file" → "Create new file"
2. Nombre: `index.html`
3. Pegalo el contenido del archivo
4. **Commit changes**

### Paso 3: Activa GitHub Pages
1. Ve a **Settings** (arriba a la derecha)
2. En el menú lateral, haz clic en **"Pages"**
3. En "Source", elige rama **main**
4. Elige carpeta **root** (/)
5. Haz clic en **Save**
6. Espera 1-2 minutos

**Tu URL pública:** `https://tu-usuario.github.io/pptx-extractor`

---

## OPCIÓN 3: Netlify (Alternativa a Vercel)

### Paso 1: Crea repositorio GitHub
(Mismo proceso que arriba)

### Paso 2: Despliega en Netlify
1. Ve a https://netlify.com
2. Haz clic en **"Sign up"** → "Continue with GitHub"
3. Autoriza Netlify
4. Haz clic en **"New site from Git"**
5. Selecciona tu repositorio `pptx-extractor`
6. Deja todo por defecto
7. Haz clic en **"Deploy site"**

**Tu URL:** Netlify te dará una URL automática en el panel

---

## 🔄 ¿Cómo actualizar después?

Si necesitas hacer cambios:

### En Vercel/Netlify:
- Solo edita el `index.html` en GitHub
- Vercel/Netlify se actualiza automáticamente (en segundos)

### En GitHub Pages:
- Edita el `index.html` en GitHub
- Espera 1-2 minutos para que se actualice

---

## 📊 Información Técnica

**Librerías usadas (vía CDN):**
- **JSZip** (3.10.1): Lee archivos .pptx (que son ZIPs)
- **Tailwind CSS**: Estilos modernos

**Cómo funciona:**
1. El usuario arrastra o selecciona un `.pptx`
2. El navegador lee el archivo como ZIP
3. Extrae los XML de las diapositivas (`ppt/slides/`)
4. Parsea el XML y obtiene todo el texto
5. Muestra el resultado formateado
6. El usuario puede copiar o descargar

**Límites:**
- Archivos hasta ~50MB (depende del navegador)
- Compatible con Chrome, Firefox, Safari, Edge
- Funciona offline (después de cargar la página)

---

## 🎯 Resumen Rápido

| Opción | Velocidad | Coste | Facilidad |
|--------|-----------|-------|-----------|
| **Vercel** ⭐ | 2 min | Gratis | Muy fácil |
| GitHub Pages | 5 min | Gratis | Fácil |
| Netlify | 3 min | Gratis | Muy fácil |

**Recomendación:** Usa **Vercel** para tu novia, es lo más rápido y simple 🚀

---

## ❓ Preguntas Frecuentes

**P: ¿Se suben los archivos a algún servidor?**
R: No. Todo se procesa en el navegador del usuario. Completamente privado.

**P: ¿Funciona sin internet?**
R: Después de cargar la página por primera vez, sí (menos las librerías de CDN).

**P: ¿Soporta otros formatos?**
R: Actualmente solo .pptx. Pptx es el estándar actual de PowerPoint.

**P: ¿Puedo desplegar en mi propio servidor?**
R: Sí, solo descarga el `index.html` y súbelo donde quieras (Apache, Nginx, etc).

**P: ¿Por qué no puedo ejecutarlo localmente?**
R: Puedes: abre el archivo `index.html` directamente en tu navegador.

---

## 📝 Licencia

Libre para usar y modificar. Disfruta 😊
