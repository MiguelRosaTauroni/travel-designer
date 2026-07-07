# Travel Designer

Proyecto para configurar un asistente de diseño de viajes a medida como **Claude Project**, con una base de conocimiento propia que complementa el prompt de sistema.

## Estructura

```
travel_designer/
├── README.md                      Este archivo
├── system_prompt.md                Instrucciones de sistema del proyecto (pegar en "Custom instructions" de Claude Projects)
└── knowledge_base/                 Documentos a subir como archivos de proyecto en Claude Projects
    ├── 01_climatologia_mundial.md
    ├── 02_viajes_por_continentes.md
    ├── 03_safaris.md
    ├── 04_hoteles_especiales.md
    ├── 05_experiencias_unicas.md
    ├── 06_presupuestos.md
    ├── 07_checklist_de_viaje.md
    └── 08_prompt_de_calidad.md
```

## Cómo montarlo en Claude Projects

1. Crea un nuevo Project en claude.ai llamado, por ejemplo, "Travel Designer".
2. Copia el contenido de `system_prompt.md` en las **Custom instructions** del Project.
3. Sube los 8 archivos de `knowledge_base/` como **Project knowledge** (archivos adjuntos del proyecto).
4. Abre una conversación nueva dentro del Project cada vez que quieras diseñar un viaje.

## Por qué esta estructura

- El **prompt de sistema** define el rol, la filosofía de diseño y el formato de respuesta: es el "cómo piensa" el consultor.
- La **base de conocimiento** aporta datos de referencia (climatología, presupuestos, experiencias, alojamientos) que el prompt por sí solo no puede garantizar que sean correctos o estén actualizados: es el "qué sabe" el consultor.
- Separar ambos permite actualizar los datos (por ejemplo, precios o temporadas) sin tocar la lógica de razonamiento, y viceversa.

## Mantenimiento

Estos documentos son un punto de partida razonado, no una fuente de datos en tiempo real. Antes de un viaje real:

- Verifica fechas de festivales, temporadas y precios en fuentes oficiales actualizadas.
- Revisa requisitos de visado/vacunas en la web consular o de Sanidad Exterior correspondiente a la fecha del viaje.
- Actualiza `06_presupuestos.md` periódicamente, ya que es el documento que más rápido queda desactualizado.

## Próximos pasos sugeridos

- Añadir un `09_casos_resueltos.md` con itinerarios reales ya diseñados y validados, como ejemplos de referencia de calidad.
- Si el volumen de destinos cubiertos crece mucho, dividir `02_viajes_por_continentes.md` en un archivo por continente.
