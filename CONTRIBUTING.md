# Guía para colaborar en el proyecto "Eventos Chiapas"

Este documento tiene como objetivo establecer una guía clara y ordenada para todos los colaboradores que participen en el desarrollo del proyecto. El uso adecuado de Git y GitHub asegura un trabajo organizado, eficiente y sin conflictos innecesarios.

## ¿Cómo colaborar correctamente?

1. **Clona el repositorio** desde GitHub:
   git clone https://github.com/cristiantru/ProfeDonas.git

2. **Crea una nueva rama** para trabajar tu parte:
   git checkout -b rama-nombre

3. Realiza tus cambios y **haz commits significativos**.

4. **Sube tu rama al repositorio remoto**:

   git push origin rama-nombre

5. **Crea un Pull Request** para integrar tus cambios a `main`.

6. Espera la **revisión y aprobación** de al menos un compañero antes de hacer merge.

## Reglas para nombrar ramas

Para mantener un flujo de trabajo claro y ordenado:

* Usa prefijos descriptivos según el contenido de tu trabajo:

  * `rama-header`
  * `rama-footer`
  * `rama-contacto`
  * `rama-cristian`
  * `rama-estilos`
  * `rama-js-eventos`

* Evita nombres como `rama1`, `nueva-rama`, `test`, etc.

## Reglas para escribir mensajes de commit

Los mensajes de commit deben ser **claros, concisos y en infinitivo**. Esto permite entender rápidamente qué cambio se hizo.

### Ejemplos correctos:

* `Agregado formulario de contacto`
* `Diseñado el header del sitio`
* `Corregido error en la sección de eventos`
* `Estilizado botones de navegación`

### Ejemplos incorrectos:

* `Cambios`
* `Listo`
* `Trabajo final`
* `asd`

## Uso de Pull Requests (PR)

* **Siempre crea un PR desde tu rama hacia `main`.**
* Antes de hacer merge:

  * Al menos un integrante debe **revisar y aprobar** tu PR.
  * Si hay comentarios o sugerencias, **haz los cambios antes del merge.**
  * Si existe un **conflicto**, resuélvelo de manera manual y documenta el proceso en `CONFLICT-LOG.md`.


## Checklist antes de hacer merge

* [ ] Probé que los cambios funcionan.
* [ ] Mi código no genera errores.
* [ ] Mi rama está actualizada con `main`.
* [ ] Recibí al menos una revisión/aprobación del equipo.
* [ ] Resolví cualquier conflicto si fue necesario.


