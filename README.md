# 📊 Análisis de Servicio al Cliente – Power BI

## Objetivo / Pregunta de negocio
¿Cómo está funcionando el centro de atención al cliente? Se buscó identificar patrones en la atención, medir la satisfacción de los usuarios y evaluar el desempeño de los asistentes por área.

Proyecto desarrollado como parte del evento "Acelerador de Carrera con Power BI + IA" (Daxus Latam), simulando el rol de Analista de Datos en un centro de atención al cliente.

## Datos
Tabla principal **atenciones**:

| Columna | Tipo | Descripción |
|---|---|---|
| Id Llamada | TEXT | Identificador único de la llamada |
| Fecha | DATE | Fecha de la atención |
| Asistente | TEXT | Nombre del asistente |
| Área | TEXT | Área de atención (Ventas, Reclamos, etc.) |
| Respondido - Resuelto | TEXT | Si fue respondida y resuelta (S/N) |
| Velocidad de respuesta | INT | Segundos hasta responder |
| Duración de la llamada | TIME | Duración total de la llamada |
| Índice de satisfacción | FLOAT | Puntuación de satisfacción del cliente |

## Proceso
1. **Limpieza de datos:** depuración y estandarización en Excel.
2. **Carga en Power BI:** importación y transformación con Power Query.
3. **Modelado:** definición de medidas (DAX) y relaciones entre tablas.
4. **Visualización:** construcción del dashboard interactivo (gráfico de dona, barras, mapa de árbol, KPIs).

## Entregable
Dashboard interactivo en Power BI (ver capturas abajo).

## Insights
- Se gestionaron **1,009 llamadas** en el periodo analizado.
- El índice de satisfacción promedio fue de **3.40** (sobre escala del dataset).
- La velocidad de respuesta promedio fue de **67 segundos**.
- La tasa de resolución alcanzó **92.67%** — la mayoría de las llamadas se resuelven en el primer contacto.

## Recomendación / Siguiente paso
Si este fuera un caso real, priorizaría investigar qué separa al asistente/área con mejor índice de satisfacción del resto, para replicar esas prácticas en el equipo completo. También propondría una meta de reducir la velocidad de respuesta por debajo de 60 segundos, ya que suele correlacionar con mayor satisfacción del cliente.

## Panel de Control
![Dashboard](panel%20de%20control.png.jpeg)
![Datos](datos.png.jpeg)
![Modelo de Datos](modelo.png.jpeg)

## Cómo ejecutar
Requisitos: Microsoft Power BI Desktop. Abrir el archivo `.pbix` del proyecto.

## Herramientas utilizadas
Microsoft Excel, Microsoft Power BI Desktop (Power Query, DAX)

## Autor
**Stiven Lizarazo** — Junior Data Analyst
Proyecto desarrollado como parte del evento "Acelerador de Carrera con Power BI + IA", organizado por Daxus Latam · 19 de marzo de 2026 · 8 horas
Certificado emitido por: Zaira Hurtado
[LinkedIn](https://www.linkedin.com/in/stiven-lizarazo-4b5177258/) · lizarazostiven36@gmail.com
