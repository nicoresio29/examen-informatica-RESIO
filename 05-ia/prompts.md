# Registro de uso de IA

## Prompt 1
- **Herramienta:** Perplexity
- **Etapa:** 1. Investigación
- **Prompt:** "Perfil del consumidor de yerba mate en Asunción: hábitos y tendencias de consumo" (con el contexto del caso)
- **Qué respondió (resumen):** estudios sobre consumo en Paraguay y Departamento Central, con cifras de tereré, mate, criterios de compra y una tabla de fuentes con sus limitaciones.
- **Qué acepté / qué corregí y por qué:** acepté los datos de hábitos de consumo, pero separé Central de Asunción porque son jurisdicciones distintas. Marqué como [REVISAR] los datos de precio y la fecha del material del MIC. Descarté la afirmación de que el precio es un criterio de compra, porque el estudio no midió disposición a pagar.

## Prompt 2
- **Herramienta:** Perplexity
- **Etapa:** 1. Investigación
- **Prompt:** "Canales digitales de mayor uso en Paraguay para marcas de consumo"
- **Qué respondió (resumen):** audiencias publicitarias de DataReportal, datos del INE sobre acceso a internet, datos de CAPACE sobre compradores online y una recomendación de canales por objetivo.
- **Qué acepté / qué corregí y por qué:** acepté las audiencias de DataReportal, pero aclaré que no son comparables ni se suman. Usé el 44% de WhatsApp y el 65% de apps como datos de compradores online, no de toda la población. Descarté los 67% (Facebook) y 58% (Instagram) porque son de 2023 y de una fuente secundaria.

## Prompt 3
- **Herramienta:** Perplexity
- **Etapa:** 1. Investigación
- **Prompt:** "Competidores y precios de yerba premium en el mercado paraguayo"
- **Qué respondió (resumen):** precios de Pajarito, La Rubia, Pajarito Orgánica y Selecta en supermercados y comparadores, con referencias de precio por 500 g.
- **Qué acepté / qué corregí y por qué:** acepté La Rubia (₲ 22.050) y Pajarito Orgánica (₲ 24.300–24.350). Marqué como [REVISAR] Pajarito Premium (₲ 18.600), porque es un listado promocional con stock agotado. Descarté el precio de Selecta, porque no había precio verificable.

## Prompt 4
- **Herramienta:** NotebookLM
- **Etapa:** 2. Síntesis
- **Prompt:** "Con base solo en estas fuentes, resumí los hábitos de consumo de yerba en Asunción, los criterios de compra y los canales digitales más usados por marcas de consumo en Paraguay. Para cada dato indicá de qué fuente sale. Si algo no está en las fuentes, decí 'no hay información'."
- **Qué respondió (resumen):** una síntesis en tres bloques (hábitos, criterios de compra y canales), con los datos citados por número de fuente.
- **Qué acepté / qué corregí y por qué:** quité las marcas de cita y reemplacé cada una por el nombre de la fuente. Marqué [VERIFICADO] los datos que coincidían con mis fuentes y [REVISAR] los que no encontré. Detecté una contradicción: la síntesis daba 83,1% de penetración nacional, pero ese número correspondía a Itapúa. Lo dejé como [REVISAR] y no lo usé en el informe. También marqué como no verificados el 100% de sitios web y el 66% de redes sociales.

## Prompt 5
- **Herramienta:** Claude
- **Etapa:** 3. Planilla
- **Prompt:** "Haceme la estructura de la planilla de Marketing Digital en 4 hojas, con las columnas, las fórmulas y el gráfico de distribución del presupuesto de USD 3.000."
- **Qué respondió (resumen):** la estructura de las hojas Público objetivo, Calendario 12 semanas, Presupuesto y KPIs, con fórmulas para porcentajes, totales y control del presupuesto.
- **Qué acepté / qué corregí y por qué:** acepté la estructura y las fórmulas. Cambié los montos de ejemplo del presupuesto y las metas de KPI por supuestos que yo misma tengo que justificar en el informe. Verifiqué que el total diera USD 3.000.

## Prompt 6
- **Herramienta:** Claude
- **Etapa:** 4. Informe
- **Prompt:** "Haceme un borrador del informe del módulo con la estructura de enlace-informe.md, usando los datos de la investigación y la planilla. Marcá los datos no verificados."
- **Qué respondió (resumen):** un borrador con portada, resumen ejecutivo, contexto, desarrollo del módulo, recomendación, uso de IA y fuentes.
- **Qué acepté / qué corregí y por qué:** reescribí con mis palabras el contexto y la propuesta de valor. Reduje el texto para cumplir el límite de 1 a 2 páginas de contenido. Revisé que la tabla del presupuesto coincidiera con la planilla.

## Prompt 7
- **Herramienta:** Gamma
- **Etapa:** 5. Presentación
- **Prompt:** descripción de la presentación de 6 láminas para la gerencia, con el público objetivo, el calendario y presupuesto con gráfico, KPIs, recomendación y fuentes, en tono profesional.
- **Qué respondió (resumen):** una presentación generada a partir de esa descripción.
- **Qué acepté / qué corregí y por qué:** revisé que tuviera 6 láminas, que el gráfico de presupuesto estuviera en la lámina 4 y que no hubiera textos en inglés. [Completá acá qué cambiaste después de revisar la presentación.]

## Reflexión final
Un dato que tuve que verificar o corregir: la síntesis de NotebookLM daba 83,1% de penetración de internet a nivel nacional, pero ese número correspondía a Itapúa según las fuentes. Lo verifiqué contra los datos del INE, lo marqué como [REVISAR] y no lo usé en el informe hasta resolverlo.
