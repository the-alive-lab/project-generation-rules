# Reglas de fundamentación de proyectos — v0.1

**Estado:** recomendaciones candidatas; aplicación proporcional.

## Antes de crear una estructura

1. **Identificar la unidad:** ¿proyecto, producto, biblioteca, investigación, experimento, repositorio operativo o documentación? No tratarlos como sinónimos.
2. **Buscar continuidad:** ¿ya existe repositorio, concepto, definición o autoridad equivalente? Preferir extender antes que duplicar.
3. **Explicitar razón de existir:** problema/necesidad, destinatarios, resultados pretendidos y exclusiones.
4. **Establecer estado epistemológico:** hechos comprobables, observaciones, hipótesis, propuestas, decisiones adoptadas y resultados deben distinguirse.
5. **Señalar autoridad:** quién puede adoptar cambios de identidad, método, arquitectura, alcance o publicación.
6. **Definir un camino de continuación:** dónde está el trabajo vigente, qué sigue y qué permanece pendiente.

## Reglas de estructura

- Empezar con el mínimo que soporte la comprensión y el trabajo real.
- Crear carpetas por **responsabilidad diferenciada**, no solo por parecerse a otros repositorios.
- Cada carpeta significativa debería tener orientación local si la ruta no es autoexplicativa.
- Mantener el README raíz como mapa y entrada, no como duplicación de todas las especificaciones.
- Separar documentación de producto, propuestas, investigación/evidencia, decisiones y artefactos operativos cuando su autoridad o ciclo de vida difieran.
- No forzar categorías como `method/`, `design/`, `framework/`, `governance/` o `docs/` sin una necesidad verificable.
- Conservar vínculos de procedencia e historia sin reescribir retrospectivamente artefactos congelados.
- Usar nombres estables, comprensibles y enlaces relativos dentro del repositorio.

## Mínimo documental

La orientación inicial debe permitir responder: qué es; qué no es; por qué existe; estado actual; navegación; cómo contribuir o continuar; fuentes de verdad y límites de autoridad. No se exige un archivo diferente por respuesta.

## Estados y autoridad

Una nota «candidate» o una propuesta de agente **no es una norma**. Diferenciar explícitamente: *referencia*, *propuesta*, *aprobación*, *adopción* y *evidencia validada*. No usar un README para convertir decisiones pendientes en conclusiones.

## Variantes

- **Conceptual:** definiciones, relaciones, límites, historia y decisiones; sin prometer implementación.
- **Software:** instrucciones de ejecución, pruebas, arquitectura efectiva y seguridad; evitar instrucciones de código inventadas.
- **Investigación:** preguntas, protocolos, evidencia, trazabilidad y estado de revisión.
- **Experimento/prototipo:** alcance acotado, reproducibilidad, limitaciones y carácter no productivo.

La estructura debe seguir a las responsabilidades reales; un proyecto puede combinar variantes.
