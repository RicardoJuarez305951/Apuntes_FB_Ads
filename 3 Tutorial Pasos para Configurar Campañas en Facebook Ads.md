# Tutorial: Pasos para Configurar Campañas en Facebook Ads (Basado en Apuntes Originales)

Este documento describe los pasos exactos para configurar campañas en el Administrador de Anuncios de Facebook, crear públicos personalizados con píxel y lanzar anuncios, según los apuntes originales. Está diseñado para guiarte directamente a las funcionalidades clave, sin explicaciones adicionales, y es compatible con Obsidian.

---

## 1. Acceder al Administrador de Anuncios

1. Abre [facebook.com/adsmanager](https://www.facebook.com/adsmanager).
2. Inicia sesión con tu cuenta de Facebook.
3. (Opcional) Si gestionas múltiples cuentas, ve a [business.facebook.com](https://business.facebook.com) y selecciona tu cuenta publicitaria.

---

## 2. Crear una Campaña

1. En **Ads Manager**, haz clic en **Crear** (botón verde).
2. Selecciona un objetivo:
   - Ventas
   - Interacción
   - Clientes Potenciales
   - Reconocimiento
3. En **Nombre de la Campaña**, escribe un nombre (ejemplo: "Ventas_Mayo_2025").
4. En **Tipo de Compra**, selecciona **Subasta**.
5. En **Presupuesto**, elige **Diario** o **Total**. Ejemplo: $10/día.
   - (Recomendación) Divide en dos campañas: 70% presupuesto en la primera ($7), 30% en la segunda ($3).
6. En **Estrategia de Puja**, selecciona **Volumen más Alto**.
7. Haz clic en **Siguiente**.

---

## 3. Configurar Conjunto de Anuncios

1. En **Nombre del Conjunto de Anuncios**, escribe un nombre (ejemplo: "Ventas_Sitio_Web").
2. En **Ubicación de la Conversión**, selecciona **Sitio Web**.
3. En **Objetivo de Rendimiento**, elige **Maximizar el Número de Conversiones**.
4. En **Conjunto de Datos**, selecciona tu píxel (configurado en la sección 4).
5. En **Evento de Conversión**, elige una acción (ejemplo: Compra, Registro, Agregar al Carrito).
6. En **Presupuesto y Calendario**:
   - Establece fechas (ejemplo: 20-30 mayo).
   - Selecciona horas (ejemplo: 8 AM-10 PM).
7. En **Público**:
   - **Lugares**: Selecciona países/ciudades (ejemplo: México, Ciudad de México).
   - **Edad y Sexo**: Define rango (ejemplo: 25-34, mujeres).
   - **Segmentación Detallada**: Añade intereses (ejemplo: moda, fitness).
   - (Opcional) Selecciona público personalizado o similar (creado en la sección 4).
8. En **Ubicaciones**, selecciona **Automáticas** (recomendado).
9. Haz clic en **Siguiente**.

---

## 4. Crear Público Personalizado con Píxel

### 4.1. Instalar Píxel
1. Ve a **Business Manager** ([business.facebook.com](https://business.facebook.com)).
2. Navega a **Configuración de Negocio** > **Orígenes de Datos** > **Píxeles**.
3. Haz clic en **Crear Píxel**.
4. Nombra el píxel (ejemplo: "TiendaX_Pixel").
5. Copia el código del píxel y pégalo en el `<head>` de tu sitio web.
6. (Opcional) Genera un **Token de Acceso**:
   - Ve a **Administrador de Eventos** > selecciona tu píxel > **Configuración** > **Generar Token de Acceso**.
   - Ejemplo:
     ```javascript
     EAAfLXAyD0JsBO0CQmxCqYiihSJBmeLWVL6ZAlmXQR0uM9vSzvbMhZArSFQnoZBWo5Bunuoe1grrJtUxSsGNEXFe01ZCbw2T1iZBQ9gKVFMi5cJZB3rJhrIR2F1Vi3B22kWNh2Ij5NxKUuzlvs3s3n5LrQenBZB9R4BODkCPHw6VArYsnWGo6xjOulzrRnjvzowpcQZDZD
     ```
7. Verifica el píxel con **Meta Pixel Helper** (extensión de Chrome).

### 4.2. Crear Público Personalizado
1. En **Ads Manager**, ve a **Públicos** (menú lateral).
2. Haz clic en **Crear Público** > **Público Personalizado** > **Sitio Web**.
3. Selecciona tu píxel.
4. Elige un evento (ejemplo: Visitas a la Página, Compras).
5. Define rango de tiempo (ejemplo: últimos 30 días).
6. Nombra el público (ejemplo: "Visitantes_Sitio_30d").
7. Haz clic en **Crear**.

### 4.3. Crear Público Similar
1. En **Públicos**, haz clic en **Crear Público** > **Público Similar**.
2. Selecciona el público personalizado (ejemplo: "Visitantes_Sitio_30d").
3. Elige país/región (ejemplo: México).
4. Ajusta tamaño (1% para mayor similitud, hasta 10% para alcance).
5. Nombra el público (ejemplo: "Lookalike_Visitantes_1%").
6. Haz clic en **Crear**.

---

## 5. Configurar Anuncio

1. En **Nombre del Anuncio**, escribe un nombre (ejemplo: "Anuncio_Video_Mayo").
2. En **Página**, selecciona tu página de Facebook e Instagram.
3. En **Formato**, elige **Una sola imagen o video**.
4. En **Contenido del Anuncio**:
   - Sube imagen o video (recomendado: 16-20 segundos).
   - Añade **Texto Principal** (ejemplo: "¡Nueva colección, 20% off!").
   - Incluye **URL** del sitio/producto.
   - (Opcional) Ajusta video: corta segmentos, usa formato vertical (9:16).
   - Activa **Mejoras IA** (retoques visuales, catálogo si aplica).
5. En **Etiquetas de Información**, añade:
   - Envío gratuito, opciones de pago, devoluciones, etc.
   - Información de cuenta (ubicación, horarios, calificaciones).
6. En **Destino**, verifica la URL del anuncio.
7. En **Seguimiento**, asegura que el píxel esté activado.
8. Haz clic en **Publicar**.

---

## 6. Crear Campaña para Público Frío

1. En **Ads Manager**, selecciona tu campaña > **Editar**.
2. En el conjunto de anuncios, haz clic en los **tres puntos** > **Duplicar**.
3. En el nuevo conjunto, ve a **Segmentación Detallada** y elimina intereses previos.
4. En **Públicos Personalizados**, selecciona **Crear Público Similar**.
5. Elige origen (ejemplo: público personalizado o Instagram).
6. Configura país y tamaño (ejemplo: México, 1%).
7. Nombra el público (ejemplo: "Lookalike_Instagram_1%").
8. Haz clic en **Crear** y **Publicar**.

---

## 7. Optimizar y Duplicar Anuncios

1. En **Ads Manager**, selecciona tu campaña.
2. Navega al conjunto de anuncios > selecciona el anuncio.
3. Haz clic en los **tres puntos** > **Duplicar**.
4. Modifica elementos (imagen, texto, público) para pruebas A/B.
5. Repite pasos de la sección 5 para cada nuevo anuncio.
6. Publica y monitorea en **Ads Manager** (clics, conversiones).

---

## Diagrama Mermaid: Flujo de Configuración

```mermaid
graph TD
    A[Acceder Ads Manager] --> B[Crear Campaña: Objetivo, Subasta]
    B --> C[Configurar Conjunto: Público, Píxel, Conversión]
    C --> D[Instalar Píxel: Sitio Web]
    D --> E[Crear Público Personalizado: Visitas, Compras]
    E --> F[Crear Público Similar: Lookalike]
    C --> G[Configurar Anuncio: Video, Texto, URL]
    G --> H[Publicar y Duplicar: Pruebas A/B]
    H --> I[Monitorear Resultados]
````