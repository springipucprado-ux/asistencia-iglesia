# 📊 Control de Asistencia - Iglesia

App web para registrar y guardar la asistencia de hombres, mujeres y niños en los servicios de la iglesia.

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-activo-brightgreen)

---

## ✨ Características

✅ **Conteo rápido:** Botones para +1, +5, +10 (y -1, -5, -10 para corregir)  
✅ **Almacenamiento local:** Los datos se guardan en el navegador  
✅ **Integración Google Drive:** Guarda automáticamente en Google Sheets  
✅ **Sin necesidad de login:** Abre y usa directamente  
✅ **Responsive:** Funciona en computadora y teléfono  
✅ **Offline:** Funciona sin internet (sincroniza después)  

---

## 🚀 Cómo Usar

### **Opción 1: Usar Online (Recomendado)**

Simplemente abre esta URL en tu navegador:
```
https://tu-usuario.github.io/asistencia-iglesia/
```

### **Opción 2: Usar Local**

1. Descarga `control_asistencia_iglesia_v2.html`
2. Abre el archivo en tu navegador (doble clic)
3. ¡Listo! Funciona sin necesidad de servidor

---

## 📋 Configuración Inicial

### **Paso 1: Crear Google Sheets**
1. Ve a [sheets.google.com](https://sheets.google.com)
2. Crea una nueva hoja llamada "Asistencia Iglesia"
3. Comparte con los miembros de tu iglesia

### **Paso 2: Crear Google Apps Script**
1. En Google Sheets → Extensiones → Apps Script
2. Borra el código existente
3. Copia el código del archivo `google_apps_script.js`
4. Guarda (Ctrl+S)

### **Paso 3: Publicar Script**
1. Haz clic en "Deploy" → "New deployment"
2. Selecciona "Web app"
3. Ejecutar como: Tu cuenta
4. Quién tiene acceso: Cualquiera con el enlace
5. Copia la URL que genera

### **Paso 4: Configurar App**
1. Abre la app
2. Ve a "Configuración de Google Drive"
3. Pega la URL del Apps Script
4. Haz clic en "Guardar Configuración"

**Ver instrucciones completas:** [INSTRUCCIONES.md](./INSTRUCCIONES.md)

---

## 💻 Uso Diario

```
1. Abre la URL de la app
2. Selecciona la fecha del servicio
3. Presiona los botones para contar:
   ➕ +1, +5, +10 para sumar
   ➖ -1, -5, -10 para restar (si te equivocas)
4. Presiona "💾 Guardar en Drive" para guardar
5. Los datos aparecen automáticamente en Google Sheets
```

---

## 📊 Datos Guardados

Cada registro incluye:
- **Fecha:** Del servicio
- **Hombres:** Cantidad
- **Mujeres:** Cantidad
- **Niños:** Cantidad
- **Total:** Suma automática
- **Hora de Registro:** Cuándo se guardó

---

## 🔧 Tecnología

- **Frontend:** HTML5 + CSS3 + JavaScript
- **Almacenamiento:** localStorage (navegador)
- **Backend:** Google Apps Script
- **Base de datos:** Google Sheets
- **Hosting:** GitHub Pages

---

## 📁 Archivos

```
asistencia-iglesia/
├── control_asistencia_iglesia_v2.html    # App principal
├── google_apps_script.js                 # Script para Google
├── INSTRUCCIONES.md                      # Guía de instalación
├── PUBLICAR_EN_GITHUB_PAGES.md           # Cómo publicar
└── README.md                             # Este archivo
```

---

## 🌐 URLs Importantes

| Recurso | URL |
|---------|-----|
| **App Web** | `https://tu-usuario.github.io/asistencia-iglesia/` |
| **Repositorio** | `https://github.com/tu-usuario/asistencia-iglesia` |
| **Google Sheets** | Crea el tuyo en `sheets.google.com` |

---

## ❓ FAQ

**P: ¿Es gratis?**  
R: Sí, 100% gratuito. Usa servicios gratuitos de GitHub y Google.

**P: ¿Todos pueden usar a la vez?**  
R: Sí, varios usuarios pueden registrar datos simultáneamente.

**P: ¿Se pierden los datos si cierro la app?**  
R: No, quedan guardados localmente. Se sincronizan con Google cuando presionas "Guardar".

**P: ¿Necesito internet?**  
R: No necesitas internet para contar, pero sí para guardar en Google Drive.

**P: ¿Puedo corregir errores?**  
R: Sí, usa los botones ➖ para restar sin perder el contador.

**P: ¿Cómo comparto la app con otros?**  
R: Solo comparte la URL de GitHub Pages (no es contraseña).

---

## 🛠️ Modificar la App

Si necesitas cambios (colores, textos, funcionalidades):

1. Edita `control_asistencia_iglesia_v2.html`
2. Busca el código que quieres cambiar
3. Haz clic en ✏️ en GitHub
4. Realiza los cambios
5. Haz commit
6. Los cambios aparecen en 1-2 minutos

---

## 📱 Crear Atajo en Teléfono

### iPhone (Safari):
1. Abre la URL
2. Compartir → Añadir a pantalla de inicio
3. ¡Listo! Funciona como app

### Android (Chrome):
1. Abre la URL
2. ⋮ → Instalar aplicación
3. ¡Listo! Funciona como app

---

## 📧 Soporte

Si tienes problemas:
1. Lee las instrucciones nuevamente
2. Verifica que la URL del Google Apps Script sea correcta
3. Limpia el caché del navegador (Ctrl+F5)
4. Prueba en otro navegador

---

## 📜 Licencia

Este proyecto está bajo licencia MIT. Eres libre de usarlo, modificarlo y compartirlo.

---

## 🙏 Créditos

Creado para ayudar a las iglesias a registrar su asistencia de forma simple y gratuita.

---

**¡Gracias por usar esta app! 🎉**

Si te fue útil, comparte con otras iglesias. 📱

---

*Última actualización: 2026*
