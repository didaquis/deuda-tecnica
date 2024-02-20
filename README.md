# Deuda técnica

Este repositorio contiene algunas reflexiones alrededor del concepto "deuda técnica". Estas reflexiones son fruto de mi experiencia profesional.

-------- 

### ¿Qué es?
La deuda técnica es el coste y los intereses a pagar por hacer mal las cosas. Es el sobresfuerzo a pagar cuando trabajamos con un producto de software de baja calidad.

Una deuda técnica elevada, es un claro riesgo de negocio.


### ¿Por qué la terminología no es adecuada?
Debemos de tener en cuenta que la deuda técnica, no es precisamente "técnica". En realidad una terminología más adecuada sería "deuda de producto".

Es importante que el equipo de desarrollo sepa trasladar a la gente de producto y negocio el concepto de deuda técnica de manera adecuada.


### ¿Cómo se origina?
Algunos de los principales motivos por los cuales se origina la deuda técnica:
* Excesiva presión con las fechas de entrega
* Falta de cuidado/educación/implicación (malas prácticas durante el desarrollo del software, baja calidad del software)
* Inexistencia de la verificación de la calidad del software desarrollado
* Developers con conocimientos técnicos y/o de producto insuficientes
* Errores de diseño (funcionales o no funcionales)
* Roadmap indeciso (cambios de opinión o idas y venidas en la concepción de producto que no van acompañadas del tiempo necesario para refactorizar el código existente)
* Software que no ha tenido un mantenimiento periódico y ha envejecido de manera desatendida
* Falta de documentación o silos de conocimiento


### ¿Qué va a pasar con la deuda técnica?
La deuda técnica se comporta exactamente como una deuda financiera. No desaparece, tiende a incrementarse con el paso del tiempo, y sus consecuencias pueden ser insostenibles a largo plazo.

Como cualquier otra deuda, alguien va a pagar por ella de manera consciente o inconsciente.


Las diferentes maneras de pagar una deuda técnica y/o como esta se manifiesta son:
* Conscientemente se decide invertir tiempo para reducir la deuda técnica. Usualmente: refactorizando el código, revisando la infraestructura, definiendo el producto, desechando código, etc.
* Aparecen evidentes dificultades para modificar ese código por falta de conocimientos. Ejemplo: nadie sabe como funciona el software, que hace, o como se pone en marcha. O incluso, no encontramos programadores de << INSERTE AQUÍ UNA TECNOLOGÍA O LENGUAJE OBSOLETO >> para contratar.
* Pérdida de talento en el equipo. A nadie le gusta trabajar con una base de código horrible. Puede suceder que el equipo decida abandonar el proyecto y/o la empresa por desmotivación y/o estrés.
* Timmings excesivamente largos al modificar o añadir código (y por tanto sobrecoste de desarrollo). La deuda técnica suele incrementar la complejidad del desarrollo de nuevas funcionalidades, provocando que la entrega de esas funcionalidad se retrase en exceso.
* Deuda funcional. Puede suceder que no seamos capaces de implementar alguna funcionalidad que venga definida desde el equipo de producto.
* Gran cantidad de bugs. Al ponerlo en producción aparecen de manera masiva multitud de bugs que no se conocían. Por ejemplo, teníamos un cliente que sólo utilizaba una sección del software, pero ahora tenemos mil clientes y estos utilizan todos los rincones del software. De repente descubrimos que el software no funciona bien y hay múltiples errores. Peligro: pérdida de clientes y una imagen de marca difícil de reparar.
* Imposibilidad de escalar. Rendimiento y problemas de infraestructura. Por ejemplo, nuestra aplicación funciona correctamente, pero cuando tiene muchos clientes conectados el servidor se satura. O bien, el sistema funciona correctamente, pero cuando la base de datos crece las consultas comienzan a ralentizarse hasta un punto insostenible.


### ¿Cómo lo arreglamos?
Debemos aumentar la calidad del software. Serán de utilidad los siguientes conceptos: arquitectura de software, principios SOLID, YAGNI, clean code, testing, retirar funcionalidades que no aporten valor al producto, etc.

A menudo ocurre que durante el desarrollo de un proyecto nos enfrentamos al mítico triángulo: coste-tiempo-alcance. Las empresas tienen tendencia a reducir el tiempo, sin embargo debemos tener en cuenta que la consecuencia directa de reducir el tiempo de entrega es una baja calidad del trabajo, por tanto estamos generando deuda técnica. Es más inteligente reducir el alcance y no sacrificar la calidad del trabajo entregado.

Lo más sensato es tratar de reducirla escalonadamente. Por ejemplo, tratar de dedicar un 20% del tiempo de cada sprint a reducir la deuda técnica.

Suele ser recomendable pagarla cuanto antes, ya que tiende a aumentar de manera incremental con el tiempo si no se hace nada por reducirla.

Es más costo-eficiente pagar la deuda técnica de aquellas partes del código que mutan frecuentemente.

Debemos valorar el impacto que tiene a nivel de negocio esa deuda técnica, para tomar las decisiones correctas al enfrentarse a ella. Por ejemplo: ¿los costes de desarrollo se han disparado? ¿Puedo sufrir una pérdida de clientes? ¿Un competidor pueden lanzar más funcionalidades en menos tiempo? ¿tengo dificultades para contratar desarrolladores?

La deuda técnica se puede medir mediante algunas técnicas/herramientas (por ejemplo: SonarQube). Lo ideal es hacer un seguimiento empírico de su evolución. Es decir, tratar de cuantificar la deuda técnica e ir haciendo un seguimiento de su evolución.

> 🔔 **Un apunte**: No todo es blanco y negro! Hay que tener en cuenta, que casi todos los proyectos tienen algo de deuda técnica. Y no hay ningún problema con ello mientras la deuda técnica sea relativamente baja o esté focalizada en aquellas áreas menos trascendentales o susceptibles a cambio.
La deuda técnica se convierte en un problema cuando su volumen es considerable.



### La deuda técnica como herramienta a nuestro favor ⚠️
La deuda técnica puede ser intencionada en algunos casos. Por ejemplo, una startup podría estar interesada en salir a mercado lo antes posible y/o evaluar la viabilidad económica de un proyecto. Para lograrlo, conscientemente puede "comprar" deuda y dejarla a deber para cuando el modelo de negocio esté validado.   
Una empresa convencional puede estar en el mismo supuesto cuando trata de crear un nuevo producto. Es posible que para conseguir las primeras ventas y ganar los primeros clientes, recurran a "comprar" deuda técnica dejándola a deber.

En estos casos, la deuda técnica es una herramienta que las empresas utilizan a su favor. Sin embargo, la deuda va a estar ahí y la empresa tarde o temprano va a tener que lidiar con ella. Por tanto, será crucial que la empresa no haga oídos sordos al pago de la deuda técnica en el futuro o se convertirá en un problema.  

