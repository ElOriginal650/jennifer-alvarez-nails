# 💅 Jennifer Álvarez — Nails & Spa Boutique

Sitio web moderno, responsive y de alta conversión para manicurista y pedicurista profesional con sistema de agendamiento inteligente conectado directamente a WhatsApp.

---

## ✨ Características Principales

- **Diseño Estético & Prémium**: Tipografía editorial (*Cormorant Garamond* y *Plus Jakarta Sans*), paleta de colores Blush Rose & Gold y efectos de cristal (*glassmorphism*).
- **Catálogo de Servicios Interactivo**: Manicura rusa, uñas esculpidas (acrílico y polygel), pedicura Jelly Spa, nail art de autor y combos dúo.
- **Selector Inteligente de Citas**:
  - Selector dinámico de días (próximos 7 días actualizados en tiempo real).
  - Verificación de turnos y disponibilidad horaria (mañana y tarde) con indicación de cupos libres y ocupados.
- **Conexión Directa con WhatsApp**: Genera automáticamente un mensaje estructurado y formal con el nombre de la clienta, servicio, fecha, hora solicitada y notas para confirmar con Jennifer con un solo toque.
- **Protocolo de Higiene & Garantía**: Sección de bioseguridad, esterilización hospitalaria y garantía de 7 días.
- **Galería de Trabajos**: Muestra visual de acabados de alta costura.

---

## 🚀 Cómo Publicar la Página Gratis en Internet (GitHub Pages)

1. En este repositorio, dirígete a la pestaña **Settings** (Ajustes).
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En la sección **Build and deployment > Branch**:
   - Selecciona la rama **`main`**.
   - Carpeta: **`/ (root)`**.
4. Haz clic en **Save** (Guardar).
5. En 1 minuto tu página estará publicada en vivo en:
   👉 **`https://eloriginal650.github.io/jennifer-alvarez-nails/`**

---

## 📱 Personalización del Teléfono de WhatsApp

Para cambiar el número de teléfono donde Jennifer recibe los mensajes de las citas:
1. Abre el archivo `index.html`.
2. Busca la línea:
   ```javascript
   const WHATSAPP_NUMERO = "584120000000";
   ```
3. Reemplaza el número por el teléfono de Jennifer en formato internacional (sin el signo `+`).
