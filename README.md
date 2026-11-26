# QA Store | Reto 5 de DevOps y calidad de software

## Objetivo

Construir un flujo de integración continua que permita al equipo de QA decidir,
con base en pruebas y evidencias de ejecución, si un cambio en QA Store cumple
los criterios de calidad para integrarse en la rama `main`.

## Alcance previsto

- Validar los flujos de consulta de productos, inicio de sesión y compra simulada.
- Ejecutar pruebas automatizadas en cada pull request mediante GitHub Actions
  y conservar los reportes como artefactos de ejecución.
- Evaluar el rendimiento con k6 y Apache JMeter, y documentar los resultados
  frente a los umbrales de aceptación.
- Revisar la accesibilidad de la interfaz y documentar los hallazgos.
- Evaluar la relevancia, la coherencia y la exactitud de las respuestas de un
  asistente de tienda, y registrar la revisión humana del contenido generado con IA.
