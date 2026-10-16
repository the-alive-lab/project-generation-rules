# Descubrimiento para humanos y agentes — v0.1

## README.md

Puerta de entrada primaria. Recomendar: resumen en lenguaje claro, motivación, alcance, estado, mapa de navegación, primer paso para uso/contribución y vínculos a gobernanza o decisiones pertinentes. Mostrar «qué es ahora» antes de narrar toda su historia.

## AGENTS.md

Punto de entrada operativo para agentes compatibles. Recomendar: orden de lectura, localización de fuentes canónicas, límites de edición, acciones permitidas/prohibidas, pruebas antes de contribuir, convenciones locales y procedimientos de entrega. **No** ocultar instrucciones esenciales solo allí si las personas también las necesitan. Si existen AGENTS.md anidados, especificar alcance y precedencia sin asumir que todas las herramientas los interpretan igual.

## llms.txt

Índice Markdown/Texto conciso de documentos relevantes, con una línea que explique cada enlace. Es un mecanismo de *descubrimiento*, no fuente de autoridad ni garantía de lectura automática. Evitar duplicar contenido extenso, reglas operativas completas o secretos. Preferir enlaces estables y accesibles. `llms-full.txt` solo cuando haya una razón práctica para servir una consolidación; no requerido.

## Consistencia entre entradas

Los tres recursos deben coincidir en identidad, estado, canon y alcance. README orienta; AGENTS instruye al colaborador; llms.txt descubre las fuentes. Ninguno sustituye a los documentos especializados.

## Accesibilidad y comprensión

- Títulos informativos; glosario cuando se usan términos especializados.
- Enlaces descriptivos, rutas reales y estructura compatible con Markdown convencional.
- Explicar diagramas en texto; no depender únicamente de imágenes, color o Mermaid.
- Usar [Visualization Rules](https://github.com/the-alive-lab/visualization-rules) como **referencia opcional**, si el proyecto lo adopta.
- Separar «lectura obligatoria para esta tarea» de «material de contexto opcional» para evitar cargas innecesarias en agentes.
- Verificar visibilidad/permisos: un enlace público hacia documentación privada no da acceso.

## Descubrimiento no es autoridad

La exposición de una página en `llms.txt` o un enlace en `README.md` no promueve su contenido a política adoptada ni invalida la documentación canónica del proyecto.
