# Aplicación Web de Ventas de Celulares - Refactorización con Factory Method

## Patrón Aplicado: Factory Method

### ¿Por qué se eligió este patrón?
El código original contenía múltiples condicionales para la creación de diferentes tipos de celulares, lo que lo hacía difícil de mantener y escalar. Con el patrón Factory Method, delegamos la responsabilidad de la creación a las fábricas específicas para cada tipo de celular.

### Mejoras introducidas:
- **Legibilidad:** Las clases responsables de la creación de objetos están organizadas y encapsuladas.
- **Escalabilidad:** Ahora es mucho más fácil agregar nuevos tipos de celulares sin modificar el código existente.
- **Flexibilidad:** El método de creación es dinámico y puede cambiar sin impactar otras partes del código.
