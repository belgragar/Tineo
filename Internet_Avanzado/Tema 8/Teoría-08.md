# 🛠️ Instalación de WordPress y Joomla!

> **Curso de Iniciación a la Informática**
> *Da el salto a la profesionalidad: Gestores de Contenido (CMS) y sus instalaciones.*

---

## 🧠 1. ¿Qué es un Gestor de Contenidos (CMS)?

Un **CMS** (*Content Management System* o Sistema de Gestión de Contenidos) es un programa que te permite crear y gestionar una página web **sin necesidad de saber programar**.

Imagina que quieres construir una casa:
- **Programar desde cero:** Tienes que fabricar los ladrillos, el cemento y diseñar cada viga tú mismo. (Difícil y lento).
- **Usar un CMS:** Llegas a un sitio donde ya tienes los ladrillos hechos, las paredes prefabricadas y solo tienes que "ensamblar" la casa arrastrando piezas. (Rápido y fácil).

> 💡 **La gran ventaja:** Te centras en el **contenido** (noticias, fotos, textos) y el CMS se encarga del **código técnico**.

---

## 📊 2. Conceptos Básicos sobre CMS

### ✅ Ventajas de usar un CMS
- 🚀 **Fácil de usar:** Interfaz visual similar a un procesador de textos (Word).
- 🎨 **Diseños listos:** Miles de plantillas (temas) para que tu web se vea profesional.
- 🔌 **Extensible:** Puedes añadir funciones nuevas (tienda, galerías, foros) instalando **plugins** o **módulos**.
- 👥 **Multiusuario:** Puedes tener varios administradores con diferentes permisos.
- 📱 **Responsive:** Las plantillas modernas se adaptan automáticamente a móviles.

### ❌ Inconvenientes
- 🛡️ **Seguridad:** Al ser tan populares, son objetivos frecuentes de ataques (requiere actualizaciones constantes).
- 🐌 **Velocidad:** A veces son más lentos que una web hecha a código puro si se instalan muchos plugins.
- 💰 **Costes:** Aunque el software es gratis, a veces hay que pagar por plantillas, plugins premium o un hosting mejor.

### 🎯 Usos según el tipo de web
| Tipo de Web | CMS Recomendado | ¿Por qué? |
|---|---|---|
| 📰 **Blog / Noticias** | **WordPress** | Es el rey de los blogs, muy flexible. |
| 🛒 **Tienda Online** | **WordPress (WooCommerce)** o **Joomla!** | Tienen módulos de comercio electrónico muy potentes. |
| 🏢 **Web Corporativa** | **WordPress** o **Joomla!** | Permiten estructuras complejas y formularios. |
| 🎓 **Portal de Comunidad** | **Joomla!** | Gestionar usuarios y niveles de acceso es muy fuerte en Joomla. |

### 🏆 Principales Gestores de Contenido
1.  **WordPress:** El más usado del mundo (más del 40% de la web). Muy fácil y con miles de plugins.
2.  **Joomla!:** Un punto medio entre facilidad y potencia. Ideal para webs que necesitan estructuras complejas de usuarios.
3.  **Drupal:** Muy potente pero difícil de aprender. Para expertos.
4.  **Magento:** Específico para tiendas online grandes.

---

## 🌍 3. WordPress: El Rey de la Web

WordPress es el CMS más popular. Es ligero, fácil de instalar y tiene una comunidad enorme.

### 📥 Instalación de WordPress

Tienes dos formas de hacerlo:

#### A. Instalador Automático (La forma recomendada)
La mayoría de empresas de **Hosting** (donde guardas tu web) tienen un "Panel de Control" (como cPanel o Softaculous).
1.  Entras al panel de tu hosting.
2.  Buscas la opción **"Instalar WordPress"** (o Softaculous).
3.  Rellenas un formulario sencillo (Nombre de la web, usuario, contraseña).
4.  Click en **"Instalar"**.
5.  *¡Listo!* En 2 minutos tu web está online.

#### B. Instalación Manual (Para aprender)
1.  Descargas los archivos de WordPress desde `es.wordpress.org`.
2.  Subes los archivos a tu hosting usando **FileZilla**.
3.  Creas una base de datos en el panel de tu hosting.
4.  Entras a la dirección de tu web y sigues el asistente de instalación (te pedirá los datos de la base de datos).

### 🚀 Primeros pasos en WordPress
Una vez instalado, entras al **Panel de Administración** (ej: `tuweb.com/wp-admin`).
1.  **Entrada:** Escribe tu título y contenido.
2.  **Apariencia > Temas:** Elige el diseño de tu web (ej: Astra, OceanWP).
3.  **Plugins > Añadir nuevo:** Instala extensiones (ej: *Yoast SEO* para aparecer en Google, *Contact Form 7* para formularios).
4.  **Páginas:** Crea tus secciones fijas (Inicio, Contacto, Sobre mí).

> 💡 **Consejo:** WordPress usa "Entradas" para noticias (que van a la portada) y "Páginas" para información estática (como "Quiénes somos").

---

## 🕸️ 4. Joomla!: La Alternative Potente

Joomla! es el segundo CMS más popular. Es un poco más técnico que WordPress, pero ofrece una gestión de usuarios y menús más avanzada "de fábrica".

### 📥 Instalación de Joomla!

Al igual que WordPress, lo ideal es usar el **Instalador Automático** del hosting.
1.  En el panel de control (cPanel), busca "Joomla" en Softaculous.
2.  Rellena los datos (Título, Usuario, Contraseña).
3.  Instala.

**Instalación Manual:**
1.  Descarga Joomla! desde `downloads.joomla.org`.
2.  Sube los archivos con **FileZilla**.
3.  Crea la base de datos.
4.  Sigue el asistente en tu navegador.

### 🚀 Primeros pasos en Joomla!
El panel de administración es diferente (`tuweb.com/administrator`).
1.  **Extensiones > Plantillas:** Cambia el diseño. Joomla! separa muy bien el diseño de la estructura.
2.  **Menús:** Joomla! es muy fuerte creando menús complejos (submenús, menús específicos por usuario).
3.  **Contenido > Artículos:** Similar a las entradas de WordPress.
4.  **Componer > Componentes:** Aquí instalas las funcionalidades extra (como una tienda o galería).
    *   *Nota:* A diferencia de WordPress, en Joomla! los componentes a veces se instalan como "módulos" que se colocan en zonas específicas de la plantilla (izquierda, derecha, arriba).

> 💡 **Diferencia clave:** En WordPress, todo parece un "plugin". En Joomla!, hay una distinción clara entre **Componentes** (la funcionalidad principal, ej: un formulario de contacto) y **Módulos** (pequeños bloques que se colocan en la barra lateral, ej: el reloj o el menú).

---

## 🧩 Resumen Rápido

| Concepto | WordPress | Joomla! |
|---|---|---|
| **Facilidad** | ⭐⭐⭐⭐⭐ (Muy fácil) | ⭐⭐⭐ (Media) |
| **Flexibilidad** | ⭐⭐⭐⭐⭐ (Miles de plugins) | ⭐⭐⭐⭐ (Muy flexible) |
| **Gestión de Usuarios** | Básica (se mejora con plugins) | Avanzada (de fábrica) |
| **Instalación** | Muy rápida (automática) | Rápida (automática) |
| **Ideal para** | Blogs, webs pequeñas, tiendas | Webs corporativas, portales complejos |
| **Sistema** | Entradas y Páginas | Artículos y Categorías |

---

> ✏️ **Actividad Práctica:**
> 1.  Si tienes un hosting, entra en tu panel de control y busca la opción de **Instalar WordPress**. Haz una instalación de prueba.
> 2.  Entra al panel de administración (`wp-admin`).
> 3.  Crea una **Entrada** (ej: "Mi primera noticia") y una **Página** (ej: "Contacto").
> 4.  Instala un **Tema** gratuito (ve a Apariencia > Temas > Añadir nuevo, busca "Astra" e instálalo).
> 5.  (Opcional) Si tienes espacio, prueba a instalar **Joomla!** en un subdominio (ej: `joomla.tuweb.com`) para comparar ambas interfaces.

---
