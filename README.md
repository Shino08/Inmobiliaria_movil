# 📱 Vistas - Aplicación Inmobiliaria Móvil

Colección completa de **35 vistas HTML** organizadas en **9 categorías** funcionales. Todas las vistas utilizan **Tailwind CSS**, **Material Symbols** y están optimizadas para dispositivos móviles con soporte de modo oscuro.

---

## 📁 Estructura del Proyecto

```
vistas/
├── autenticacion/          (2 vistas)
├── inicio/                 (3 vistas)
├── propiedades/            (9 vistas)
├── visitas-ofertas/        (5 vistas)
├── inversiones/            (4 vistas)
├── perfil/                 (4 vistas)
├── configuracion/          (4 vistas)
├── soporte/                (3 vistas)
└── onboarding/             (1 vista)
```

---

## 🎯 Índice de Vistas

### 🔐 Autenticación (2)

| Vista            | Archivo         | Descripción                               |
| ---------------- | --------------- | ----------------------------------------- |
| Inicio de Sesión | `login.html`    | Formulario de login con validación        |
| Registro         | `registro.html` | Formulario de registro de nuevos usuarios |

---

### 🏠 Inicio (3)

| Vista             | Archivo             | Descripción                           |
| ----------------- | ------------------- | ------------------------------------- |
| Página de Entrada | `index.html`        | Vista inicial de la aplicación        |
| Home Principal    | `home.html`         | Página principal con mapa interactivo |
| Inmobiliaria      | `inmobiliaria.html` | Vista alternativa de inmobiliaria     |

---

### 🏘️ Propiedades (9)

| Vista        | Archivo             | Descripción                           |
| ------------ | ------------------- | ------------------------------------- |
| Búsqueda     | `busqueda.html`     | Barra de búsqueda de propiedades      |
| Filtros      | `filtros.html`      | Filtros avanzados de búsqueda         |
| Resultados   | `resultados.html`   | Lista de resultados de búsqueda       |
| Detalles     | `detalles.html`     | Información completa de propiedad     |
| Favoritos    | `favoritos.html`    | Propiedades guardadas como favoritas  |
| Comparar     | `comparar.html`     | Comparación de múltiples propiedades  |
| Tour Virtual | `tour-virtual.html` | Recorrido virtual 360°                |
| Galería      | `galeria.html`      | Galería de fotos en pantalla completa |
| Calculadora  | `calculadora.html`  | Calculadora hipotecaria               |

---

### 📅 Visitas y Ofertas (5)

| Vista                | Archivo                  | Descripción                       |
| -------------------- | ------------------------ | --------------------------------- |
| Agendar Visita       | `agendar-visita.html`    | Calendario para programar visitas |
| Mis Visitas          | `mis-visitas.html`       | Gestión de visitas agendadas      |
| Historial de Visitas | `historial-visitas.html` | Registro de visitas realizadas    |
| Hacer Oferta         | `hacer-oferta.html`      | Formulario para realizar ofertas  |
| Mis Ofertas          | `mis-ofertas.html`       | Seguimiento de ofertas realizadas |

---

### 💰 Inversiones (4)

| Vista                 | Archivo                     | Descripción                         |
| --------------------- | --------------------------- | ----------------------------------- |
| Oportunidades         | `oportunidades.html`        | Lista de oportunidades de inversión |
| Detalles de Inversión | `detalles-inversion.html`   | Información de inversión            |
| Detalles Adicionales  | `detalles-adicionales.html` | Información complementaria          |
| Confirmación          | `confirmacion.html`         | Confirmación de inversión exitosa   |

---

### 👤 Perfil (4)

| Vista         | Archivo              | Descripción                     |
| ------------- | -------------------- | ------------------------------- |
| Mi Perfil     | `mi-perfil.html`     | Perfil del usuario              |
| Editar Perfil | `editar-perfil.html` | Formulario de edición de perfil |
| Chat          | `chat.html`          | Chat en tiempo real con agentes |
| Mensajes      | `mensajes.html`      | Historial de conversaciones     |

---

### ⚙️ Configuración (4)

| Vista          | Archivo               | Descripción                     |
| -------------- | --------------------- | ------------------------------- |
| Ajustes        | `ajustes.html`        | Configuración general de la app |
| Idioma         | `idioma.html`         | Selección de idioma             |
| Seguridad      | `seguridad.html`      | Configuración de seguridad      |
| Notificaciones | `notificaciones.html` | Preferencias de notificaciones  |

---

### 🆘 Soporte (3)

| Vista                    | Archivo                      | Descripción               |
| ------------------------ | ---------------------------- | ------------------------- |
| Centro de Notificaciones | `centro-notificaciones.html` | Bandeja de notificaciones |
| Centro de Ayuda          | `centro-ayuda.html`          | FAQ y ayuda               |
| Atención al Cliente      | `atencion-cliente.html`      | Contacto con soporte      |

---

### 🎓 Onboarding (1)

| Vista    | Archivo         | Descripción                        |
| -------- | --------------- | ---------------------------------- |
| Tutorial | `tutorial.html` | Tutorial introductorio de 4 slides |

---

## 🎨 Características Generales

- ✅ **Diseño Responsive** - Mobile-first, adaptable a tablets y desktop
- ✅ **Modo Oscuro** - Soporte completo con clase `dark:`
- ✅ **Animaciones Suaves** - Transiciones y micro-interacciones
- ✅ **Iconos Material** - Material Symbols Outlined
- ✅ **Paleta Consistente** - Primary: `#EA5B2B`, Primary Dark: `#C74A21`
- ✅ **Tipografía Inter** - Google Fonts
- ✅ **Sin Dependencias** - Solo Tailwind CDN

---

## 🔗 Rutas de Navegación

### Autenticación

```html
<a href="vistas/autenticacion/login.html">Iniciar Sesión</a>
<a href="vistas/autenticacion/registro.html">Registrarse</a>
```

### Inicio

```html
<a href="vistas/inicio/index.html">Inicio</a>
<a href="vistas/inicio/home.html">Home</a>
```

### Propiedades

```html
<a href="vistas/propiedades/busqueda.html">Buscar</a>
<a href="vistas/propiedades/resultados.html">Resultados</a>
<a href="vistas/propiedades/detalles.html">Ver Detalles</a>
<a href="vistas/propiedades/favoritos.html">Favoritos</a>
<a href="vistas/propiedades/comparar.html">Comparar</a>
<a href="vistas/propiedades/tour-virtual.html">Tour Virtual</a>
<a href="vistas/propiedades/galeria.html">Galería</a>
<a href="vistas/propiedades/calculadora.html">Calculadora</a>
```

### Visitas y Ofertas

```html
<a href="vistas/visitas-ofertas/agendar-visita.html">Agendar Visita</a>
<a href="vistas/visitas-ofertas/mis-visitas.html">Mis Visitas</a>
<a href="vistas/visitas-ofertas/hacer-oferta.html">Hacer Oferta</a>
<a href="vistas/visitas-ofertas/mis-ofertas.html">Mis Ofertas</a>
```

### Inversiones

```html
<a href="vistas/inversiones/oportunidades.html">Inversiones</a>
<a href="vistas/inversiones/detalles-inversion.html">Detalles</a>
```

### Perfil

```html
<a href="vistas/perfil/mi-perfil.html">Mi Perfil</a>
<a href="vistas/perfil/editar-perfil.html">Editar Perfil</a>
<a href="vistas/perfil/chat.html">Chat</a>
<a href="vistas/perfil/mensajes.html">Mensajes</a>
```

### Configuración

```html
<a href="vistas/configuracion/ajustes.html">Configuración</a>
<a href="vistas/configuracion/idioma.html">Idioma</a>
<a href="vistas/configuracion/seguridad.html">Seguridad</a>
<a href="vistas/configuracion/notificaciones.html">Notificaciones</a>
```

### Soporte

```html
<a href="vistas/soporte/centro-notificaciones.html">Notificaciones</a>
<a href="vistas/soporte/centro-ayuda.html">Ayuda</a>
<a href="vistas/soporte/atencion-cliente.html">Soporte</a>
```

### Onboarding

```html
<a href="vistas/onboarding/tutorial.html">Tutorial</a>
```

---

## 🛠️ Integración

### Configurar Rutas en Router

```javascript
const routes = {
  // Autenticación
  "/login": "vistas/autenticacion/login.html",
  "/registro": "vistas/autenticacion/registro.html",

  // Inicio
  "/": "vistas/inicio/index.html",
  "/home": "vistas/inicio/home.html",

  // Propiedades
  "/buscar": "vistas/propiedades/busqueda.html",
  "/propiedades": "vistas/propiedades/resultados.html",
  "/propiedad/:id": "vistas/propiedades/detalles.html",
  "/favoritos": "vistas/propiedades/favoritos.html",
  "/comparar": "vistas/propiedades/comparar.html",
  "/tour/:id": "vistas/propiedades/tour-virtual.html",
  "/galeria/:id": "vistas/propiedades/galeria.html",
  "/calculadora": "vistas/propiedades/calculadora.html",

  // Visitas y Ofertas
  "/agendar-visita/:id": "vistas/visitas-ofertas/agendar-visita.html",
  "/mis-visitas": "vistas/visitas-ofertas/mis-visitas.html",
  "/hacer-oferta/:id": "vistas/visitas-ofertas/hacer-oferta.html",
  "/mis-ofertas": "vistas/visitas-ofertas/mis-ofertas.html",

  // Inversiones
  "/inversiones": "vistas/inversiones/oportunidades.html",
  "/inversion/:id": "vistas/inversiones/detalles-inversion.html",

  // Perfil
  "/perfil": "vistas/perfil/mi-perfil.html",
  "/editar-perfil": "vistas/perfil/editar-perfil.html",
  "/chat/:agentId": "vistas/perfil/chat.html",
  "/mensajes": "vistas/perfil/mensajes.html",

  // Configuración
  "/configuracion": "vistas/configuracion/ajustes.html",

  // Soporte
  "/notificaciones": "vistas/soporte/centro-notificaciones.html",
  "/ayuda": "vistas/soporte/centro-ayuda.html",

  // Onboarding
  "/tutorial": "vistas/onboarding/tutorial.html",
};
```

### Personalizar Colores

```javascript
// En cada archivo HTML, busca:
tailwind.config = {
  theme: {
    extend: {
      colors: {
        primary: "#EA5B2B", // Cambia aquí
        "primary-dark": "#C74A21", // Y aquí
      },
    },
  },
};
```

### Conectar con Backend

```javascript
// Ejemplo: Cargar detalles de propiedad
async function loadPropertyDetails(propertyId) {
  const response = await fetch(`/api/properties/${propertyId}`);
  const data = await response.json();

  // Actualizar DOM con datos reales
  document.getElementById("price").textContent = data.price;
  document.getElementById("address").textContent = data.address;
  // ...
}
```

---

## 📊 Resumen por Categoría

| Categoría            | Vistas | % del Total |
| -------------------- | ------ | ----------- |
| 🏘️ Propiedades       | 9      | 25.7%       |
| 📅 Visitas y Ofertas | 5      | 14.3%       |
| 💰 Inversiones       | 4      | 11.4%       |
| 👤 Perfil            | 4      | 11.4%       |
| ⚙️ Configuración     | 4      | 11.4%       |
| 🏠 Inicio            | 3      | 8.6%        |
| 🆘 Soporte           | 3      | 8.6%        |
| 🔐 Autenticación     | 2      | 5.7%        |
| 🎓 Onboarding        | 1      | 2.9%        |
| **TOTAL**            | **35** | **100%**    |

---

## 🚀 Checklist de Implementación

- [ ] Configurar rutas en el router
- [ ] Actualizar enlaces de navegación
- [ ] Integrar con API/Backend
- [ ] Agregar validación de formularios
- [ ] Implementar autenticación
- [ ] Configurar persistencia de datos
- [ ] Optimizar imágenes
- [ ] Pruebas en dispositivos reales
- [ ] Configurar analytics
- [ ] Deploy a producción

---

## 📝 Notas Técnicas

- **Framework:** HTML5 + Tailwind CSS + JavaScript Vanilla
- **Dependencias:** Tailwind CDN, Google Fonts, Material Symbols
- **Compatibilidad:** Chrome, Firefox, Safari, Edge (últimas versiones)
- **Optimización:** Mobile-first, touch events, viewport optimizado
- **Accesibilidad:** HTML5 semántico, ARIA labels
- **Nomenclatura:** kebab-case en español para consistencia

---

## 📞 Soporte

Para preguntas o mejoras, contacta al equipo de desarrollo.

**Versión:** 2.0  
**Fecha:** Noviembre 2025  
**Vistas Totales:** 35  
**Stack:** HTML5, Tailwind CSS, JavaScript, Material Symbols
