# GH WhatsApp Widget

Widget flotante moderno de WhatsApp con popup QR, modo automático y UI personalizable.

Flotando silenciosamente en la esquina como un concierge digital listo para ayudar. ✨

---

# Características

- Botón flotante de WhatsApp
- Modo QR
- Modo directo
- Modo automático:
  - Móvil → abre WhatsApp directamente
  - Desktop → muestra QR
- Número personalizable
- Posición personalizable
- Color personalizable
- Mensaje personalizable
- Vanilla JavaScript puro
- Sin dependencias
- Responsive
- UI moderna glassmorphism

---

# Instalación

Agrega el script antes de cerrar el `</body>`.

```html
<script
  src="src/gh-whatsapp-widget.js"
  data-phone="51944648831"
  data-mode="auto"
  data-position="right"
  data-color="#25D366"
  data-message="Habla con nosotros 💬"
></script>
```

---

# Configuración

| Atributo | Descripción | Valores | Default |
|---|---|---|---|
| `data-phone` | Número WhatsApp con código país | `51999999999` | `ERROR` |
| `data-mode` | Comportamiento | `direct`, `qr`, `auto` | `direct` |
| `data-position` | Posición | `right`, `left` | `right` |
| `data-color` | Color principal | HEX | `#25D366` |
| `data-message` | Título popup QR | Texto | `Habla con nosotros 💬` |

---

# Modos

## Direct

Abre WhatsApp directamente.

```html
<script
  src="src/gh-whatsapp-widget.js"
  data-phone="51944648831"
  data-mode="direct"
></script>
```

---

## QR

Muestra popup QR.

```html
<script
  src="src/gh-whatsapp-widget.js"
  data-phone="51944648831"
  data-mode="qr"
></script>
```

---

## Auto

- Mobile → abre WhatsApp
- Desktop → muestra QR

```html
<script
  src="src/gh-whatsapp-widget.js"
  data-phone="51944648831"
  data-mode="auto"
></script>
```

---

# Personalización de color

```html
<script
  src="src/gh-whatsapp-widget.js"
  data-phone="51944648831"
  data-color="#0066ff"
></script>
```

---

# Posición izquierda

```html
<script
  src="src/gh-whatsapp-widget.js"
  data-phone="51944648831"
  data-position="left"
></script>
```

---

# Ejemplo completo

```html
<script
  src="src/gh-whatsapp-widget.js"
  data-phone="51944648831"
  data-mode="auto"
  data-position="right"
  data-color="#25D366"
  data-message="Atención médica 💬"
></script>
```

---

# Estructura del proyecto

```text
gh-whatsapp-widget/
├── README.md
├── LICENSE
├── demo.html
├── .gitignore
└── src/
    └── gh-whatsapp-widget.js
```

---

# Compatibilidad

Compatible con:

- HTML
- WordPress
- JSP / Tomcat
- Vue.js
- PHP
- Laravel
- React
- Sitios estáticos

---

# Autor

**Paulo Soto**  
https://www.goodhope.org.pe/  
https://github.com/paulosoto

---

# Licencia

Reservada. Todos los derechos reservados.

---

# ⭐ GH WhatsApp Widget

Minimalista. Moderno. Flotando silenciosamente en la esquina como un concierge digital listo para ayudar. 🟢
