# Planilla del módulo

- **Enlace a Google Sheets (cualquier persona con el enlace puede ver):** [[planilla_marketing](https://docs.google.com/spreadsheets/d/1p4LTVQ4Kv7STDGOIgiYZKx3pc8bmfAud/edit?usp=sharing&ouid=106354847187346939808&rtpof=true&sd=true)]
- **Archivo subido:** `02-datos/planilla.xlsx`

## Hojas incluidas
1. **Público objetivo:** segmentos (tereré cotidiano, interesado en lo orgánico, explorador) con edad, motivación, canal principal y porcentaje estimado.
2. **Calendario 12 semanas:** plan semana por semana con canal, formato de contenido y objetivo (6 canales distintos).
3. **Presupuesto:** distribución de USD 3.000 entre Facebook, Instagram, YouTube, TikTok y WhatsApp/apps, con control de total.
4. **KPIs:** alcance, clics y conversiones objetivo por canal, con CTR y tasa de conversión.

## Fórmulas principales utilizadas
- `=SUM(E2:E4)`: total de porcentajes del público objetivo (debe dar 100%).
- `=B2/B$7` y `=SUM(B2:B6)`: porcentaje de cada canal sobre el total del presupuesto.
- `=IF(B7=3000,"OK","REVISAR")`: control que verifica que el presupuesto sume exactamente USD 3.000.
- `=C2/B2` (CTR) y `=D2/C2` (tasa de conversión) en la hoja KPIs.

## Gráfico
Qué muestra: gráfico de columnas con la distribución del presupuesto por canal (hoja Presupuesto), tomado de los montos asignados en USD.

## Supuestos
- Los porcentajes del público objetivo y las metas de KPI son hipótesis a validar, no datos medidos. Se explican en el informe.
- Los montos del presupuesto son una propuesta inicial que suma USD 3.000.
