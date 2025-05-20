# Notas Importantes: Optimización de Campañas en Facebook Ads

Pasos para personalizar columnas en el Ads Manager, analizar métricas clave y optimizar campañas de retargeting.

---

## 1. Personalizar Columnas en Ads Manager

1. Abre **Ads Manager** ([facebook.com/adsmanager](https://www.facebook.com/adsmanager)).
2. Ve a la pestaña **Campañas**.
3. Busca el botón **Columnas** (arriba, junto a la barra de búsqueda) y haz clic.
4. Selecciona **Personalizar columnas**.
5. Elimina todas las columnas actuales:
	1. Haz clic en la **X** junto a cada columna.
	2. Deja solo **Entrega** (activada por default).
6. Busca y selecciona manualmente las siguientes columnas:
	1. **Entrega** (ya incluido).
	2. **Presupuesto**.
	3. **Importe Gastado**.
	4. **Resultados**.
	5. **Costo por Resultado**.
	6. **Compras por Valor** (desactiva columnas internas: haz clic en la flecha junto a la columna y desmarca subcolumnas).
	7. **ROAS Total** (desactiva columnas internas).
	8. Personalizadas:
		1. **Tasa de conversión:** Tu defines la tasa de conversión; recomendable: Compras / Visitas a la página
		2. **Ticket promedio:** El valor de ventas sobre cuantos productos se vendieron: Valor de conversión de compras / Compras
7. Haz clic en **Aplicar**.
8. (Opcional) Guarda la configuración:
   - Haz clic en **Guardar como predefinido** > Nombra el conjunto (ejemplo: "Métricas_Retargeting") > **Guardar**.

---

## 2. Analizar y Optimizar Campañas

1. **Espera 5-7 días** para recopilar datos suficientes (clics, conversiones, etc.).
2. Analiza las métricas clave:
   - **Resultados**: Número de acciones logradas (ejemplo: compras).
   - **Costo por Resultado**: Costo promedio por acción (ejemplo: $2 por compra).
   - **ROAS Total** (Retorno de la Inversión Publicitaria): Relación Ventas/Costo. Mayor ROAS = mejor rendimiento.
     - Ejemplo: ROAS de 5 = $5 en ventas por cada $1 gastado.
3. Filtra anuncios según rendimiento:
   - Identifica anuncios con **alto ROAS** y **bajo Costo por Resultado** (generan ingresos).
   - Mantén anuncios con ROAS moderado para dar flexibilidad al algoritmo.
   - **No elimines todos los anuncios** con bajo rendimiento; pausa los peores (ejemplo: Costo por Resultado > $10 sin conversiones).
4. Monitorea la **vida útil de las campañas**:
   - Si el **Costo por Resultado** sube significativamente (ejemplo: de $2 a $5), los anuncios pueden estar fatigando a la audiencia.
   - Cambia creativos (imágenes, videos, textos) o ajusta públicos cada 2-4 semanas.
5. (Opcional) Usa dashboards para análisis:
   - Configura un dashboard en [Facebook Ads Dashboard](https://l.rw.rw/dashboards/facebook-ads-dashboard-coupler).
   - Revisa métricas como frecuencia (ideal: 1.5-2) y clics por demografía.

---

## Notas Finales

- **Columnas Clave**:
  - Entrega, Presupuesto, Importe Gastado, Resultados, Costo por Resultado, Compras por Valor, ROAS Total.
- **Optimización**:
  - Evalúa tras 5-7 días.
  - Mantén anuncios rentables, pausa los peores, no elimines todos.
  - Cambia anuncios si el Costo por Resultado sube (fatiga de audiencia).
- **Vida Útil**: Actualiza creativos cada 2-4 semanas.
- **Referencia**: Integra con [[4 Tutorial Pasos para Segunda Campaña Retargeting]] para configuración inicial.
- **Recursos**: Consulta [Metricool 2025](https://metricool.com/es/guia-de-facebook-ads-para-principiantes/) y [Coupler.io 2025](https://blog.coupler.io/facebook-ads-strategy/).
- [[Errores Comunes]]
---

## Diagrama Mermaid: Flujo de Optimización

```mermaid
graph TD
    A[Personalizar Columnas: Ads Manager] --> B[Seleccionar: Entrega, Presupuesto, ROAS]
    B --> C[Esperar 5-7 días]
    C --> D[Analizar: Resultados, Costo por Resultado, ROAS]
    D --> E[Filtrar Anuncios: Alto ROAS, Bajo Costo]
    E --> F[Pausar Anuncios Peores]
    E --> G[Mantener Anuncios Moderados]
    F --> H[Monitorear Costo por Resultado]
    H -->|Sube| I[Cambiar Creativos: Videos, Imágenes]
    I --> J[Publicar y Reevaluar]
````