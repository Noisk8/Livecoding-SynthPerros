# Livecoding-SynthPerros
Taller y herramientas de livecoding para  la comunidad SynthS Perros 


## Que es Livecoding 

El livecoding es una práctica artística y musical en la que se crea y se reproduce música de manera interactiva y en tiempo real utilizando un lenguaje de programación. El livecoding se caracteriza por su enfoque en la improvisación, la experimentación y la colaboración, y se diferencia del método tradicional de composición musical, en el que se crea música de manera secuencial y se reproduce después de que esté completamente terminada.

El livecoding se utiliza principalmente por músicos y artistas que quieren explorar nuevas formas de creación y reproducción de música, y que buscan una mayor interacción y comunicación con su público. En una sesión de livecoding, el músico o el artista utiliza un lenguaje de programación para crear patrones de sonido y ritmo, y luego los reproduce en tiempo real mientras el público observa y escucha el proceso de creación.

El livecoding se ha vuelto popular en la comunidad de música electrónica y experimental, y se ha utilizado en diferentes contextos, como conciertos, festivales, conferencias y talleres. El livecoding también se ha relacionado con el movimiento de código abierto y la cultura hackers, y ha sido objeto de estudio en campos como la música, la informática y las artes.

## [Toplap](https://toplap.org/)

Toplap es una comunidad de músicos y artistas que utilizan el livecoding como forma de creación y reproducción musical. Toplap es un acrónimo que significa "Topología de las prácticas de programación en vivo", y se refiere a la idea de que el livecoding es una forma de arte que se basa en la interacción y la colaboración entre diferentes personas y tecnologías.

Toplap es una red global de músicos y artistas que utilizan lenguajes de programación como FoxDot, TidalCycles, SuperCollider y otros para crear y reproducir música de manera interactiva y en tiempo real. Toplap organiza eventos, conciertos y talleres en diferentes ciudades del mundo, y ofrece recursos y tutoriales para quienes quieren aprender y practicar el livecoding.

En resumen, Toplap es una comunidad que promueve y fomenta el livecoding como forma de arte y de comunicación, y que ofrece un espacio de colaboración y de intercambio para músicos y artistas que utilizan la tecnología para crear y reproducir música.


## [Livecoding tools](https://github.com/toplap/awesome-livecoding)

### + razones 

El livecoding puede ser una forma muy útil para las personas que quieren hacer música sin tener que gastar mucho dinero en equipo costoso. El livecoding implica escribir y modificar el código de un programa de síntesis en tiempo real, lo que permite a los usuarios crear y modificar sonidos utilizando solo una computadora y un software de síntesis. 

Esto significa que las personas que quieren hacer música con livecoding solo necesitan una computadora y un software de síntesis, lo que puede ser más accesible y asequible que comprar un sintetizador costoso. Además, el livecoding también permite a los usuarios experimentar y explorar de forma más libre y creativa con sus sonidos, lo que puede ser muy divertido y enriquecedor para aquellos que deseen hacer música de una manera no convencional.

## [FoxDot](https://foxdot.org/)

FoxDot es un lenguaje de programación y un entorno de desarrollo para crear y reproducir música de manera interactiva. FoxDot se basa en el lenguaje de programación Python, y se utiliza para crear patrones de sonido y ritmo que se pueden reproducir en tiempo real. FoxDot se caracteriza por su facilidad de uso y por su enfoque en la experimentación y la improvisación musical.

FoxDot se utiliza principalmente por músicos y artistas que quieren crear música de manera rápida y sencilla, sin necesidad de conocimientos profundos de programación o de música. FoxDot permite a los usuarios crear patrones de sonido y ritmo utilizando sintaxis y comandos simples, y también ofrece una amplia variedad de herramientas y efectos para personalizar y mejorar la música que se crea.

FoxDot es un proyecto de código abierto, lo que significa que está disponible gratuitamente y que cualquier persona puede contribuir a su desarrollo y mejora. FoxDot se puede utilizar en diferentes plataformas, como Windows, macOS y Linux, y se puede integrar con otros lenguajes y herramientas para crear música de manera más compleja y sofisticada.


Ejemplo de código en FoxDot


        Clock.bpm = 120

        d1 >> play("x-o-")

        d2 >> play("--(--[--])--")

        d3 >> play("  o ")

        d4 >> play("[--]")

        d5 >> play("  * ")

        d6 >> play("  o ")

        d7 >> play("  * ")


En este código se establece una velocidad de 120 pulsos por minuto (bpm) con la instrucción Clock.bpm = 120. Luego, se utilizan las instrucciones d1 >> play("x-o-"), d2 >> play("--(--[--])--"), etc. para crear diferentes patrones de sonido y ritmo con los símbolos x, o, -, (, [, ], *, etc. Cada una de estas instrucciones se asigna a un canal de sonido diferente (d1, d2, d3, etc.), y se pueden reproducir y modificar de manera independiente.

Al ejecutar este código en FoxDot, se creará una pieza musical que combina diferentes patrones de sonido y ritmo, y que se podrá escuchar y modificar en tiempo real. Es un ejemplo sencillo, pero te puede servir para empezar a explorar las posibilidades de FoxDot y de la música generativa.



