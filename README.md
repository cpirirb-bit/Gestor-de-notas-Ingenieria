# Gestor de Notas Académicas

## Redacción del problema
El **Gestor de Notas Académicas** es un sistema diseñado para facilitar la administración de calificaciones y cursos para estudiantes, profesores o instituciones educativas. Su objetivo principal es permitir el registro, consulta y manejo de información académica de forma rápida y sencilla, directamente desde la consola.

Este sistema está dirigido a personas que necesitan llevar un control básico de sus notas sin recurrir a aplicaciones complejas o bases de datos externas. Su enfoque es totalmente práctico y busca cubrir la necesidad de tener una herramienta ligera que permita visualizar el progreso académico, almacenar datos temporalmente y generar reportes simples en un entorno fácil de usar.

## Requisitos del sistema

### Funcionales
1. Registrar un nuevo curso y su respectiva nota.
2. Mostrar todas las notas registradas.
3. Calcular el promedio de las notas ingresadas.
4. Buscar una nota específica por nombre del curso.
5. Eliminar un curso y su nota del registro.

### No funcionales
- El sistema se ejecutará en consola usando Python.
- No utilizará librerías externas.
- Implementará estructuras de control como bucles y condicionales.
- El menú principal estará diseñado en pseudocódigo antes de su implementación en Python.

## Explicación de listas, funciones y modularización
En esta etapa se añadió:
- **Uso de listas**: Todas las notas se almacenan en una lista para facilitar su recorrido, búsqueda y eliminación.
- **Funciones**: Se implementaron funciones como `registrarNotas()`, `mostrarNotas()` y `eliminarCurso()` para organizar el código y evitar repeticiones.
- **Modularización**: El menú principal llama a estas funciones, lo que hace que el programa sea más legible, mantenible y fácil de ampliar en el futuro.

