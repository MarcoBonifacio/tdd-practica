# Práctica TDD - Construcción de Software

## ¿Qué es TDD?
Test-Driven Development (TDD) es una técnica de desarrollo de software donde se escriben las pruebas automatizadas **antes** del código de producción.

Sigue un ciclo iterativo:
1. **RED**: Escribir una prueba que falle.
2. **GREEN**: Escribir la menor cantidad de código posible para hacer pasar la prueba.
3. **REFACTOR**: Mejorar y limpiar el código manteniendo las pruebas pasando.

## Módulos Desarrollados
- **FizzBuzz**: Módulo que convierte números enteros a cadenas según reglas de divisibilidad.
- **Validador**: Módulo para validar que una contraseña cumpla con ciertos criterios de seguridad.

## Ejecución de Pruebas
Para ejecutar la suite completa de pruebas:
```bash
python -m unittest discover
