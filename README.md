🌍 Delta Hotels by Marriott City Center Doha — Multilingual Info Page

Este proyecto es una página web informativa e interactiva para los huéspedes del **Delta Hotels by Marriott City Center Doha**, diseñada para mostrar los servicios e instalaciones del hotel en **tres idiomas**: **inglés**, **ruso** y **árabe**.

---

🏨 Descripción General

La web permite a los huéspedes seleccionar su idioma preferido y explorar las facilidades del hotel según el piso en el que se encuentren. Cada sección muestra información detallada, como horarios, servicios y accesos especiales.

El diseño es **minimalista, funcional y completamente adaptable** a distintos dispositivos (desktop, tablet, móvil).

---

✨ Características Principales

* 🌐 **Multilingüe:** Inglés, Ruso y Árabe.
* 🧭 **Navegación sencilla:** Selección de idioma → Menú por pisos → Detalle del servicio.
* 💻 **Interfaz limpia y moderna:** Basada en HTML, CSS y JavaScript puro (sin dependencias pesadas).
* 🏢 **Información estructurada por pisos:**

  * 32°: *Irish Cuisine – Shamrock Tavern & Pub*
  * 30°: *Satsuma Pan Asian Restaurant*
  * 29°: *Goose Lounge*
  * 17°: *Lotus Spa, Gym, Pool*
  * Planta Baja: *Lewiston Café, Mini Mart*
* 📶 **Datos útiles:** Red WiFi, teléfono de asistencia.
* 🎨 **Diseño adaptado al branding del hotel:**

  * Fondo: `#D0C7B8`
  * Botones y encabezado: `#141C4C`
  * Tipografía: *Segoe UI / Verdana*.

---

🧱 Estructura del Proyecto

```
.
├── index.html          # Página principal con estructura completa
├── README.md           # Este archivo
└── assets/             # (Opcional) Carpeta para imágenes o recursos
```

---

⚙️ Tecnologías Utilizadas

* **HTML5** – estructura semántica del sitio
* **CSS3** – estilos personalizados (colores, botones, tipografía)
* **JavaScript (ES6)** – manejo dinámico del contenido multilingüe
* **Font Awesome 6.5.0** – íconos para pisos y secciones

---

🚀 Cómo Usar

1. **Descarga o clona** el proyecto:

   ```bash
   git clone https://github.com/tuusuario/delta-hotels-info.git
   ```

2. Abre el archivo `index.html` directamente en tu navegador.
   No requiere servidor o instalación adicional.

3. Selecciona el idioma (English / Русский / العربية).
   Luego elige un piso para ver la información del hotel.

---

## 🌐 Idiomas Soportados

| Código | Idioma  | Dirección del texto |
| :----: | :------ | :-----------------: |
|  `en`  | English |    Left-to-right    |
|  `ru`  | Русский |    Left-to-right    |
|  `ar`  | العربية |    Right-to-left    |

---

## 🧩 Funciones JavaScript Principales

| Función           | Descripción                                        |
| ----------------- | -------------------------------------------------- |
| `showMenu(lang)`  | Muestra el menú de pisos en el idioma seleccionado |
| `showInfo(floor)` | Muestra la información detallada del piso elegido  |
| `goBack()`        | Regresa a la pantalla de selección de idioma       |
| `backToMenu()`    | Regresa del detalle al menú de pisos               |

---

## 🖼️ Personalización

Puedes actualizar:

* 🏷️ **Textos y traducciones:** en el objeto `translations` dentro del `<script>`.
* 🎨 **Colores:** en la sección `<style>` (variables como `background`, `color`, etc.).
* 🖼️ **Imagen de bienvenida:** línea con `background: url(...)` en la clase `.welcome`.

---

## 📱 Compatibilidad

La página está optimizada para:

* Desktop (Windows, macOS)
* Tablets
* Smartphones (Android, iOS)

No requiere conexión a internet después de cargarse, salvo para los íconos de Font Awesome.

---

## 👨‍💻 Autor

**Desarrollado por:** Claudia Mancera
**Proyecto:** Interfaz informativa para huéspedes de Delta Hotels by Marriott City Center Doha
**Versión:** 1.0
**Fecha:** Octubre 2025
