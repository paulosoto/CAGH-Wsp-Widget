# GH WhatsApp Widget

Modern floating WhatsApp widget with QR popup, auto mode and customizable UI.

Floating quietly in the corner like a digital concierge ready to help. ✨

---

# Features

- Floating WhatsApp button
- QR popup mode
- Direct WhatsApp mode
- Auto mode:
  - Mobile → opens WhatsApp directly
  - Desktop → shows QR popup
- Custom phone number
- Custom position
- Custom color
- Custom message
- Lightweight Vanilla JavaScript
- No dependencies
- Responsive
- Modern glassmorphism UI

---

# Instalacion

Add the script before the closing </body> tag.

html <script   src="src/gh-whatsapp-widget.js"   data-phone="51944648831"   data-mode="auto"   data-position="right"   data-color="#25D366"   data-message="Habla con nosotros 💬" ></script> 

---

# Configuración

| Attribute | Description | Values | Default |
|---|---|---|---|
| data-phone | WhatsApp number with country code | 51999999999 | ERROR |
| data-mode | Widget behavior | direct, qr, auto | direct |
| data-position | Screen position | right, left | right |
| data-color | Main button color | Any HEX color | #25D366 |
| data-message | QR popup title | Text | Habla con nosotros 💬 |

---

# Modos

## Direct Mode

Click opens WhatsApp directly.

html <script   src="src/gh-whatsapp-widget.js"   data-phone="51944648831"   data-mode="direct" ></script> 

---

## QR Mode

Click displays the QR popup.

html <script   src="src/gh-whatsapp-widget.js"   data-phone="51944648831"   data-mode="qr" ></script> 

---

## Auto Mode

- Mobile devices → opens WhatsApp
- Desktop devices → shows QR popup

html <script   src="src/gh-whatsapp-widget.js"   data-phone="51944648831"   data-mode="auto" ></script> 

---

# Custom Color Example

html <script   src="src/gh-whatsapp-widget.js"   data-phone="51944648831"   data-color="#0066ff" ></script> 

---

# Left Position Example

html <script   src="src/gh-whatsapp-widget.js"   data-phone="51944648831"   data-position="left" ></script> 

---

# Ejemplo

html <script   src="src/gh-whatsapp-widget.js"   data-phone="51944648831"   data-mode="auto"   data-position="right"   data-color="#25D366"   data-message="Atención médica 💬" ></script> 

---

# Estructura

plaintext gh-whatsapp-widget/ ├── README.md ├── LICENSE ├── demo.html ├── .gitignore └── src/     └── gh-whatsapp-widget.js 

---

# Compatibilidad

Compatible with:

- HTML
- WordPress
- JSP / Tomcat
- Vue.js
- PHP
- Laravel
- React
- Static websites

---

# Autor

Paulo Soto  
🌐 https://www.goodhope.org.pe/  
🐙 https://github.com/paulosoto

---

# Licencia

All rights reserved.

This software and its source code are the property of Paulo Soto and Clínica Adventista Good Hope.

Unauthorized copying, modification, distribution, or commercial use is prohibited without prior written permission.

---

# Ideas futuras

- Dark mode
- Notification badge
- Sound effects
- Analytics integration
- Multiple agents
- Online/offline status
- Chat preload message
- Theme presets
- SDK API

---

# ⭐ GH WhatsApp Widget

Minimalist. Modern. Floating quietly in the corner like a digital concierge waiting to help.
