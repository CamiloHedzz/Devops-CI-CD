# Prácticas de CI/CD — IBM

Repositorio de aprendizaje del curso **Continuous Integration and
Continuous Delivery (CI/CD)** de IBM.

Aquí documento mis apuntes, ejercicios y prácticas para conectar
los conceptos del curso con procesos de desarrollo y despliegue.

## Objetivos

- Comprender los principios de integración y entrega continuas.
- Practicar el trabajo con ramas, commits y pull requests.
- Automatizar tareas de compilación y construcción.
- Incorporar pruebas y controles ante errores.
- Construir progresivamente un laboratorio reproducible de CI/CD.

## Progreso

Último avance confirmado: **15 de noviembre de 2026**.

- [x] Módulo 1: Introduction to CI/CD.
- [ ] Módulo 2: Continuous Integration — en curso.
- [ ] Completar los módulos restantes.
- [ ] Implementar y documentar un laboratorio de CI/CD.

Siguiente contenido: **Tools of Continuous Integration (CI)**.

## Prácticas realizadas

### Análisis de un flujo de construcción y despliegue

Ejercicio escrito sobre un proceso conocido:

1. Preparar una rama de trabajo.
2. Modificar y compilar código.
3. Construir una imagen de contenedor.
4. Desplegar en un entorno de desarrollo.
5. Comprobar el comportamiento mediante pruebas y logs.
6. Solicitar revisión e integración mediante un pull request.
7. Recuperar la versión anterior si el cambio falla.

Se identificó una automatización Bash existente para compilar y
construir imágenes, y se propuso mejorar la trazabilidad entre
el commit, la compilación y la imagen generada.

Esta práctica fue de análisis y documentación; no incluyó
la implementación de un pipeline nuevo.

## Próximos pasos

- Continuar el curso desde el último contenido completado.
- Preparar un laboratorio personal pequeño.
- Registrar el código de origen y la imagen generada.
- Verificar que un fallo de compilación detenga la construcción.
- Incorporar progresivamente estos pasos a un flujo de CI.

## Criterio de documentación

Cada práctica distinguirá:

- Qué se implementó o ejecutó.
- Cómo se comprobó el resultado.
- Qué falló y cómo se resolvió.
- Qué permanece como propuesta o trabajo pendiente.

Los ejemplos utilizarán código y datos de laboratorio.

## Curso

[Continuous Integration and Continuous Delivery (CI/CD) — IBM](https://www.coursera.org/learn/continuous-integration-and-continuous-delivery-ci-cd)
