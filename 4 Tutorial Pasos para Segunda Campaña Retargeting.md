Pasos para crear una campaña de retargeting en Facebook Ads, enfocada en públicos personalizados (visitantes web, listas de clientes, videos, Instagram, Facebook) con 30% del presupuesto total. Compatible con Obsidian.
## 1. Crear una Nueva Campaña de Retargeting

1. Abre **Ads Manager** ([facebook.com/adsmanager](https://www.facebook.com/adsmanager)).
2. Haz clic en **Crear** > **Crear nueva campaña**.
3. Selecciona **Objetivo**: **Ventas**.
4. En **Nombre de la Campaña**, escribe un nombre (ejemplo: "Retargeting_Ventas_Mayo_2025").
5. En **Presupuesto**, selecciona **Diario** o **Total** y asigna el 30% del presupuesto total (ejemplo: $30 si el total es $100).
6. En **Tipo de Compra**, selecciona **Subasta** (dejar por default).
7. Haz clic en **Siguiente**.

---

## 2. Configurar Conjunto de Anuncios

1. Selecciona **Nuevo Conjunto de Anuncios**.
2. En **Nombre del Conjunto**, escribe un nombre (ejemplo: "Retargeting_Sitio_Web").
3. En **Ubicación de la Conversión**, selecciona **Sitio Web**.
4. En **Objetivo de Rendimiento**, elige **Maximizar el Número de Conversiones**.
5. En **Evento de Conversión**, selecciona **Comprar**.
   - **Nota**: Asegúrate de que el evento "Comprar" esté configurado en tu sitio web:
     - Inserta el código del píxel en la página de confirmación de compra. Ejemplo:
       ```javascript
       fbq('track', 'Purchase', {value: 100.00, currency: 'USD'});
       ```
     - Verifica con **Meta Pixel Helper** (extensión de Chrome).
     - (Opcional) Usa un token de acceso para integraciones avanzadas (ejemplo falso):
       ```javascript
       EAAgPZQwXy9kBOz7TjKnRfLmV2HsYpQR8mX3JtN4vW9uB2cZkHsG9qL5JrTfX8nPqW4vRtY2mZBx6K9vCnJ3mF8sT2QwL9pY7HsV4rM3kZCzX2nB5tY8qW3JrN6vPqT9mL8kZ2rY5nT3mX7vW9uB2cZkHsG9qL5JrTfX8nPqW4vRtY2mZDZD
       ```
6. En **Presupuesto y Calendario**:
   - Define **Fecha de Inicio** (ejemplo: 20 de mayo de 2025).
   - Deja **Sin Fecha de Finalización** para campañas continuas.
   - (Opcional) Selecciona horas específicas (ejemplo: 8 AM-10 PM).
7. En **Público**:
   - Haz clic en **Limitar aún más el alcance de tus anuncios** > **Cambiar configuración**.
   - Selecciona **Públicos Personalizados** > **Crear Público Personalizado**.
   - Crea al menos uno de los siguientes públicos (sugeridos):
     1. **Sitio Web**:
        - Selecciona **Sitio Web** > Elige píxel > Evento: **Todos los Visitantes** > Rango: 90 días.
        - Nombre: "Visitantes_Web_90d".
     2. **Lista de Clientes**:
        - Selecciona **Lista de Clientes** > Sube archivo `.csv` o `.txt` (mínimo 100 clientes, con ID único, correo o teléfono).
        - Nombre: "Lista_Clientes_Mayo".
        - Sigue instrucciones en [Meta Customer List](https://www.facebook.com/business/help/170456843145568).
     3. **Video**:
        - Selecciona **Video** > Elige **Personas que reprodujeron como mínimo 10 segundos**.
        - Selecciona videos de anuncios previos en redes de Meta.
        - Nombre: "Vistas_Video_10s".
     4. **Cuenta de Instagram**:
        - Selecciona **Cuenta de Instagram** > Elige **Personas que interactuaron con tu cuenta**.
        - Nombre: "Interacciones_Instagram".
     5. **Página de Facebook**:
        - Selecciona **Página de Facebook** > Elige **Personas que interactuaron con tu página**.
        - Nombre: "Interacciones_Facebook".
   - (Opcional) Combina públicos en un solo conjunto (ejemplo: Visitantes Web + Lista de Clientes + Video).
8. En **Sugerencia de Público**:
   - Activa si tu público es pequeño (<10,000 usuarios).
   - Desactiva si es grande (>100,000 usuarios) para mayor control.
9. En **Ubicaciones**, selecciona **Automáticas** (recomendado).
10. Haz clic en **Siguiente**.

---

## 3. Configurar Anuncios

1. En **Nombre del Anuncio**, escribe un nombre (ejemplo: "Anuncio_Retargeting_Video1").
2. Selecciona tu **Página de Facebook** e **Instagram**.
3. En **Formato**, elige **Una sola imagen o video** o **Colección**.
4. En **Contenido del Anuncio**:
   - Sube 3-6 anuncios por conjunto (ejemplo: 3 videos, 3 imágenes).
   - **Video**: Usa clips de 16-20 segundos ([WordStream, 2025](https://www.wordstream.com/blog/facebook-ad-trends-2025)).
   - **Imagen**: Alta calidad, con texto claro.
   - **Texto Principal**: Incluye CTA (ejemplo: "¡Vuelve y completa tu compra!").
   - **URL**: Enlace a página de producto o carrito.
   - (Opcional) Ajusta videos: formato vertical (9:16), corta segmentos, usa mejoras IA (catálogo, retoques).
5. En **Etiquetas de Información**, añade:
   - Envío gratis, devoluciones, calificaciones, etc.
6. En **Seguimiento**, verifica que el píxel esté activo.
7. Haz clic en **Publicar**.

---

## 4. Optimizar y Escalar

1. En **Ads Manager**, selecciona la campaña.
2. Revisa métricas (clics, conversiones, CPC) en **Administrador de Anuncios**.
3. Duplica anuncios para pruebas A/B:
   - Selecciona un anuncio > **Tres puntos** > **Duplicar**.
   - Modifica creativos, textos o públicos.
4. Crea 3-6 anuncios por conjunto de anuncios (como sugerido).
5. Ajusta presupuesto o segmentación según resultados.

---

## Notas Finales

- **Campaña de Retargeting**:
  - Usa 30% del presupuesto total (ejemplo: $30 de $100).
  - Crea **1 conjunto de anuncios** combinando públicos:
    - Visitantes Web (90 días).
    - Lista de Clientes (.csv/.txt, mínimo 100).
    - Video (10 segundos mínimo).
    - Interacciones Instagram.
    - Interacciones Facebook.
  - Genera **3-6 anuncios** por conjunto (videos, imágenes).
- **Referencia**: Ver [[Números Importantes]] para métricas clave (CPC, CPM, etc.).
- **Recursos**: Consulta [Metricool 2025](https://metricool.com/es/guia-de-facebook-ads-para-principiantes/) para más detalles.

---

## Diagrama Mermaid: Flujo para Campaña de Retargeting

```mermaid
graph TD
    A[Iniciar en Ads Manager] --> B[Crear Campaña: Ventas, 30% Presupuesto]
    B --> C[Conjunto de Anuncios: Sitio Web, Maximizar Conversiones]
    C --> D[Configurar Evento: Comprar]
    D --> E[Verificar Píxel: Meta Pixel Helper]
    C --> F[Público Personalizado: Web, Lista, Video, Instagram, Facebook]
    F --> G[Sugerencia de Público: Activar/Desactivar]
    C --> H[Crear 3-6 Anuncios: Videos, Imágenes, CTA]
    H --> I[Publicar y Monitorear]
    I --> J[Duplicar para A/B, Optimizar]
````