Cambios pendientes en el prompt:
[Hecho 2026-08-17] Asegurar respuestas estandarizadas — regla añadida en FORMA DE RESPONDER
[Hecho 2026-08-17] No emitir emoticonos en la respuesta — regla añadida en FORMA DE RESPONDER
[Hecho 2026-08-17] asegurar siempre el mismo orden de emision de las respuestas, sobre todo en tablas y listados — regla añadida en FORMA DE RESPONDER
[Hecho 2026-08-17] Asegurar que se entrega nombre comida y descripcion, con un delimitador especifico que permita identificar titulo y descripcion — formato `**Nombre** — descripción` añadido en GASTRONOMÍA
[Hecho 2026-08-17] Alinear alojamientos al mismo formato — tabla fija con niveles Económico/Medio/Premium/Lujo añadida en ALOJAMIENTOS (alineada con normalizeTiers en travel_selector/src/lib/markdownBlocks.ts, no se usó el ejemplo de Brasil como referencia; validar que el resultado visual convence)
[Hecho 2026-08-17] Experiencias unicas debe de incluir siempre las columnas experiencia, donde, porque es unica y exigencia — tabla de 4 columnas añadida en EXPERIENCIAS
[Hecho 2026-08-17] En resumen de viaje, indicar explicitamente cuando se requiera un viaje interno — regla añadida en ITINERARIOS

Pendiente de verificar con una prueba real end-to-end (varios destinos) que Claude respeta los formatos nuevos de forma consistente antes de dar esto por cerrado.




