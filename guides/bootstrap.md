# Guía: iniciar un proyecto desde cero

## Paso 0 — Comprobar continuidad

Buscar proyectos y abstracciones equivalentes. Si ya existe un repositorio pertinente, documentar por qué no puede extenderse antes de crear otro.

## Paso 1 — Definir intención

Registrar en el README, de forma concisa: nombre; tipo de proyecto; necesidad que aborda; público; estado; objetivos y no-objetivos; autoridad de decisiones.

## Paso 2 — Crear navegación

Añadir únicamente las carpetas necesarias para material existente o trabajo inmediato. Nombrar las rutas por responsabilidades estables. No trasladar automáticamente estructuras de otros proyectos.

## Paso 3 — Habilitar entrada para agentes

Si se espera colaboración de agentes, añadir `AGENTS.md` con cómo interpretar y trabajar sobre el repositorio. Si se quiere descubrimiento documental por LLM, añadir `llms.txt` apuntando a documentos reales. Ambos deben enlazar el canon, no copiarlo.

## Paso 4 — Declarar estado y procedencia

Señalar explícitamente qué está definido, explorándose o pendiente de aprobación. Enlazar antecedentes verificables sin tratarlos como resultados científicos.

## Paso 5 — Hacer una prueba de llegada

Intentar responder sin memoria conversacional:
- ¿En menos de un minuto sé qué es y dónde empezar?
- ¿Sé qué fuente es canónica y cuáles son candidatas?
- ¿Puedo encontrar cómo contribuir o ejecutar el proyecto?
- ¿Un agente podría editar la superficie correcta sin inventar reglas?
- ¿Hay algún enlace roto, secreto expuesto o promesa no sustentada?

## Ejemplo mínimo

```text
nombre-proyecto/
├── README.md       # qué es, estado, navegación
├── AGENTS.md       # cómo colaborar, si corresponde
└── llms.txt        # qué consultar, si corresponde
```

Agregar `docs/`, `src/`, `tests/`, `research/` u otras carpetas **solo** si corresponden al tipo y al estado real del proyecto.
