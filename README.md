# Seminario de animación programática

Este repositorio contiene material educativo relacionado con Manim, creado por un grupo de integrantes de Animathica con el objetivo de
* entender algunos conceptos básicos de la programación orientada a objetos (clases, atributos, métodos, herencia, etc.) y los fundamentos de Manim en este contexto;
* conocer algunas herramientas de ManimCommunity útiles para nuestro trabajo;
* aprender a modificar clases y métodos existentes de ManimCommunity para adecuarlos a nuestros fines;
* crear nuestras propias clases y métodos para generar animaciones reutilizables;
* generar recursos educativos para quienes quieran aprender a aprender con ManimCommunity, tanto dentro del grupo de Animathica como fuera de él;
* contribuir al desarrollo de ManimCommunity, tanto de la documentación como del software en sí.

## Temario

### Introducción a Manim y programación orientada a objetos (OOP)

1. Paradigma de OOP. (Objetos, clases, atributos y métodos, sintáxis de Python para OOP)
2. Subclases y herencia.
3. Animaciones en Manim.

### Herramientas de Manim

#### _Scenes, Mobjects y Cameras_

4. Escenas de texto. (Clases `Scene`, `Text`, `Tex` y `Brace`)
5. Escenas 2D. (Clases `VectorScene`, `Arrow`, `Polygon` y `LinearTransformationScene`)
6. Escenas 3D. (Clases `ThreeDScene`, `Surface`, `Arrow3D` y `SpecialThreeDScene`)
7. Ejes y campos vectoriales. (Clases `Axes` y `VectorField`)
8. Cámaras móviles. (Clases `MovingCamera`, `MovingCameraScene`, `ThreeDCamera` y `ZoomedScene`)

#### _Animation_

9. Animaciones básicas.
10. Transformaciones.
11. Actualización de Mobjects. (Atributo `animate`, método `add_updater()` y clase `ValueTracker`)
12. Animación de grupos. (Clase `AnimationGroup`)

### Uso de Manim

13. ¿Cómo planeo una animación antes de implementarla en Manim?
14. ¿Cómo creo mis propias clases y métodos en Manim?
15. ¿Cómo puedo contribuir al proyecto de Manim?

## Acuerdos sobre los _notebooks_ del seminario

* Hacer un repositorio **constructivo**; es decir, para cada _notebook_, asumir que quien lo leerá no sabrá más de Manim de lo que viene en los _notebooks_ anteriores a él en el repositorio.
* Al preparar un tema, partir de los ejemplos sencillos disponibles en internet (como en la [galería de ejemplos](https://docs.manim.community/en/stable/examples.html) o en videos de YouTube que compartan su código), experimentar con ellos y simplificarlos o separarlos, de ser necesario, para hacerlo más didáctico.
* Poner comentarios cortos en el código **hablando de los porqués del código** -más allá de sólo describirlo-, asumiendo que quienes lo leerán serán aprendices principiantes de Manim y que el texto en Markdown previo a la celda de código complementará los comentarios.
* Al explicar un método de una clase, procurar exponer de forma clara cuáles son los parámetros de entrada y cuál es la salida del método.
* Constantemente preguntarnos "¿Cómo es que esto es útil para nuestro trabajo?" y mostrarlo con ejemplos siempre que sea posible, los cuales podemos aprovechar para integrar varios conceptos expuestos.
* Si experimentamos o sabemos de la existencia de errores recurrentes, **exponerlos**, explicar por qué (creemos que) suceden y, de ser posible, mostrar cómo corregirlos.
* Colocar hipervínculos en todas partes (siempre y cuando sean útiles).
* Siempre que se utilicen _flags_ distintas de `-qm -v WARNING`, llamar la atención a esto y explicar el porqué, para así aprender las diferentes opciones disponibles de _rendering_.
* Incluir al final de cada _notebook_ una sección con recursos adicionales para complementar la presentcaión; el último recurso adicional en todos los _notebooks_ debe ser el [Manual de referencia](https://docs.manim.community/en/stable/reference.html) de Manim.

**Nota** En las presentaciones se podrán mostrar ejemplos más complejos de lo que permite la "estructura constructiva" de los _notebooks_ del repositorio, pero estos no deben quedar en los _notebooks_.
