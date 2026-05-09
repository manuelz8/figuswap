# FiguSwap Landing Page - Sitio Completo y Listo

## 📁 ESTRUCTURA COMPLETA:

```
figuswap-site-v2/
├── index.html                          ← Landing principal (ABRIR ESTE)
├── README.md                           ← Este archivo
├── .htaccess                           ← Configuración del servidor
│
├── assets/
│   ├── videos/
│   │   └── hero-video.mp4             ← Video TikTok (✅ incluido)
│   │
│   ├── images/
│   │   ├── IMG_1459_2.jpg             ← Screenshots app (✅ incluidos)
│   │   ├── IMG_1463.jpg
│   │   ├── IMG_1465.jpg
│   │   ├── IMG_1466.jpg
│   │   ├── IMG_1453.jpg
│   │   ├── IMG_1436.jpg
│   │   ├── Album_actualizado.jpg
│   │   ├── cap-scan.png
│   │   ├── cambio-cap-5.png
│   │   ├── propuesta-cap.jpg
│   │   ├── tutorial-step-1.jpg        ← ⚠️ PLACEHOLDERS (reemplazar)
│   │   ├── tutorial-step-2.jpg        ← ⚠️ PLACEHOLDERS (reemplazar)
│   │   ├── tutorial-step-3.jpg        ← ⚠️ PLACEHOLDERS (reemplazar)
│   │   └── tutorial-step-4.jpg        ← ⚠️ PLACEHOLDERS (reemplazar)
│   │
│   └── apk/
│       └── (vacía - PONER FiguSwap.apk aquí) ← ⚠️ SUBIR TU APK
```

---

## ✅ YA CONFIGURADO:

- ✅ Número WhatsApp: **541122502455**
- ✅ Hero con 3 slides (video en slide 2)
- ✅ Botón verde "Descargar para Android"
- ✅ Badges negros "Próximamente" (Apple/Google Play)
- ✅ Sección WhatsApp de asistencia
- ✅ Tutorial con 4 pasos + botón descarga
- ✅ Features estilo cards (6 secciones)
- ✅ Footer con botones iguales al hero
- ✅ Responsive mobile y desktop

---

## ⚠️ SOLO FALTA REEMPLAZAR (3 cosas):

### **1. SCREENSHOTS DEL TUTORIAL** 🟡 IMPORTANTE
Reemplazar los 4 archivos en `assets/images/`:
- `tutorial-step-1.jpg` → Screenshot: Descarga del APK
- `tutorial-step-2.jpg` → Screenshot: Configuración de seguridad
- `tutorial-step-3.jpg` → Screenshot: Abrir archivo APK
- `tutorial-step-4.jpg` → Screenshot: Instalación completa

**Cómo obtenerlos:**
1. Descargá tu APK en un Android
2. Tomá capturas de pantalla en cada paso
3. Guardá con los nombres exactos de arriba
4. Reemplazá los archivos grises

### **2. ARCHIVO APK** 🔴 OBLIGATORIO
Colocar tu APK en: `assets/apk/FiguSwap.apk`

### **3. LINKS REDES SOCIALES** 🟢 OPCIONAL
**Archivo:** `index.html`
**Buscar:** Links en footer (Instagram y TikTok con `href="#"`)
**Reemplazar con:** Tus URLs reales

---

## 🚀 CÓMO SUBIR AL SERVIDOR:

### **Paso 1: Reemplazar Placeholders**
Antes de subir, completá los 3 puntos de arriba

### **Paso 2: Subir vía FTP/cPanel**
1. Conectá a tu servidor
2. Subí la carpeta completa `figuswap-site-v2/`
3. Asegurate que `index.html` esté en la raíz
4. Mantené la estructura de carpetas `assets/`

### **Paso 3: Verificar**
- Abrí: `https://tudominio.com/`
- Probá el slider (debe cambiar automáticamente)
- Probá el video (debe reproducirse en slide 2)
- Probá el botón de descarga
- Probá el botón de WhatsApp

---

## 🧪 PROBAR LOCALMENTE (ANTES DE SUBIR):

1. Descargá la carpeta `figuswap-site-v2/`
2. Abrí `index.html` con tu navegador (doble click)
3. Verificá:
   - ✅ Slider funciona
   - ✅ Video se reproduce
   - ✅ Imágenes cargan
   - ✅ Botones tienen los links correctos

---

## 🎨 CARACTERÍSTICAS FINALES:

### **Hero:**
- 3 slides con auto-rotate (5 segundos)
- Video en slide 2 (loop automático)
- Botón verde "Descargar para Android"
- 2 badges negros "Próximamente" (Apple/Google)

### **Sección WhatsApp:**
- Botón verde contacto directo
- Número: 541122502455

### **Tutorial:**
- Título + subtítulo
- Botón descarga verde
- 4 tarjetas con pasos visuales

### **Features:**
- Título "Mira FiguSwap en acción"
- 6 cards alternadas (imagen + texto)
- Tags de características
- Diseño moderno tipo portfolio

### **Footer:**
- CTA "Descargá FiguSwap antes que todos"
- Botón verde descarga
- 2 badges negros "Próximamente"
- Links Instagram + TikTok
- Copyright

---

## 📱 DESPUÉS DE SUBIR:

Tu sitio estará en:
- **Home:** `https://tudominio.com/`
- **Descarga APK:** `https://tudominio.com/assets/apk/FiguSwap.apk`

---

## 🔧 PROBLEMAS COMUNES:

### **Las imágenes no cargan:**
→ Verificá estructura `assets/images/` correcta

### **El video no se reproduce:**
→ Verificá que `assets/videos/hero-video.mp4` existe
→ Algunos servidores requieren config MIME types

### **El APK no descarga:**
→ Verificá que `FiguSwap.apk` está en `assets/apk/`
→ El `.htaccess` ya está configurado para APKs

### **WhatsApp no abre:**
→ Verificá el número: `541122502455`
→ Formato correcto: `https://wa.me/541122502455`

---

## ✅ CHECKLIST FINAL:

- [ ] ⚠️ Reemplazar 4 screenshots del tutorial
- [ ] ⚠️ Subir FiguSwap.apk a assets/apk/
- [ ] 🟢 (Opcional) Actualizar links Instagram/TikTok
- [ ] ✅ Probar localmente
- [ ] ✅ Subir al servidor manteniendo estructura
- [ ] ✅ Verificar que todo funcione online

---

## 💡 NOTAS IMPORTANTES:

- El video pesa ~6MB (optimizado para web)
- Todas las imágenes están optimizadas
- El `.htaccess` configura cache y compresión
- Responsive funciona en todos los dispositivos
- Número WhatsApp ya configurado: **541122502455**

---

¡El sitio está 95% listo! Solo reemplazá los placeholders y subilo 🚀
