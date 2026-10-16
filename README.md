# Project Generation Rules

Guía compartida de **The Alive Lab** para iniciar y mantener proyectos comprensibles, navegables y recuperables por personas y agentes de IA.

**Estado:** propuesta editorial v0.1. **Alcance:** orientación reutilizable, no plantilla obligatoria ni política automáticamente adoptada por todos los proyectos.

## Qué problema resuelve

Un proyecto recién creado debería permitir responder, sin conocer los chats que lo originaron: **qué es, para quién existe, qué problema intenta resolver, qué se sabe, qué está propuesto, qué está adoptado, dónde trabajar y cómo continuar**. La estructura debe crecer con el proyecto, no anticipar una arquitectura completa.

## Puntos de entrada

| Recurso | Propósito |
| --- | --- |
| [Reglas de generación](rules/project-foundation.md) | Decisiones mínimas, estructura proporcional, autoridad y continuidad |
| [Reglas de descubrimiento](rules/human-and-agent-discovery.md) | README, AGENTS.md, llms.txt y navegación |
| [Guía de creación](guides/bootstrap.md) | Procedimiento desde un repositorio vacío |
| [Guía de evolución](guides/evolution.md) | Cómo cambiar la estructura sin romper continuidad |
| [Checklist](checklists/new-project.md) | Comprobaciones para una primera versión |
| [AGENTS.md](AGENTS.md) | Orientación de agentes que contribuyen a este repositorio |
| [llms.txt](llms.txt) | Índice de descubrimiento de documentos |

## Mapa de responsabilidades

| Superficie | Principal destinatario | Qué contiene |
| --- | --- | --- |
| `README.md` | Humanos y agentes | Resumen, alcance, estado y navegación |
| `AGENTS.md` | Agentes colaboradores | Cómo trabajar, qué leer, límites y pruebas |
| `llms.txt` | Consumidores LLM | Índice corto de fuentes con enlaces |
| `docs/` u otras carpetas | Según contexto | Información que merece crecer fuera del README |
| Historial/decisiones | Quienes mantienen | Cambios relevantes, motivos y alternativas |

Los archivos de orientación **enlazan fuentes**, no deben duplicar o contradecir el canon.

## Estructura mínima sugerida

```text
project/
├── README.md
├── AGENTS.md                # cuando existan colaboradores automáticos
├── llms.txt                 # cuando sea útil el descubrimiento para LLM
└── docs/                    # solo si el contenido lo requiere
```

No copiar automáticamente las carpetas de TDidacta u otro proyecto. Un repositorio de código, una línea de investigación y un producto conceptual tienen necesidades diferentes.

## Referencias relacionadas

- [Visualization Rules](https://github.com/the-alive-lab/visualization-rules): convenciones visuales complementarias, no sustituye estas reglas.
- [TDidacta](https://github.com/the-alive-lab/tdidacta): ejemplo de repositorio conceptual con navegación por responsabilidades; **no** es una plantilla universal.

## Adopción y límites

Cada proyecto puede citar una versión o subconjunto de estas recomendaciones. En caso de conflicto prevalecen sus decisiones canónicas específicas y las instrucciones explícitas de quienes tienen autoridad. **Crear una propuesta no la convierte en decisión adoptada.**

La publicación y las acciones con efectos externos siguen requiriendo la autorización correspondiente. No se incluyen herramientas de scaffolding ni validación automatizada en v0.1.
