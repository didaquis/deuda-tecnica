# Deuda técnica

Este repositorio contiene algunas reflexiones alrededor de la deuda técnica.  


-------- 

### ¿Qué es?
La deuda técnica es el coste y los intereses a pagar por hacer mal las cosas. Es el sobre esfuerzo a pagar para mantener un producto de software de baja calidad. 

Una deuda técnica elevada es un riesgo de negocio.  


### ¿Cómo se origina?
Algunos de los principales motivos por los cuales se origina la deuda técnica:  
* Excesiva presión con las fechas de entrega
* Falta de cuidado/educación/implicación (malas prácticas durante el desarrollo del software, baja calidad del software)
* Inexistencia de la verificación de la calidad del software desarrollado
* Developers con conocimientos técnicos o de producto insuficientes
* Errores de diseño (funcionales o no funcionales)
* Roadmap indeciso (cambios de opinión, idas y venidas de concepción de producto)
* Software que no ha recibido mantenimiento periódico y ha envejecido de manera desatendida


### ¿Qué va a pasar con la deuda técnica?
La deuda técnica se comporta exactamente como una deuda financiera. No desaparece, tiende a incrementarse con el paso del tiempo, y sus consecuencias pueden ser insostenibles a largo plazo.  
Es importante que el equipo de desarrollo sepa trasladar este concepto a la gente de producto/negocio.  

Como cualquier otra deuda, alguien va a pagar por ella de manera consciente o inconsciente.  


Las diferentes maneras de pagar una deuda técnica (el pago puede ser consciente o inconsciente) y/o como se manifiesta:
* Conscientemente se decide invertir tiempo para reducir la deuda técnica. Usualmente: refactorizando el código, revisando la infraestructura, definiendo el producto, desechando código, etc.
* Aparecen evidentes dificultades para modificar ese código por falta de conocimientos. Ejemplo: nadie sabe como funciona el software, que hace o como se pone en marcha. O incluso, no encontramos programadores de << INSERTE AQUÍ UN LENGUAJE OBSOLETO >>
* Perdida de talento en el equipo. A nadie le gusta trabajar con una base de código terrible. Puede pasar que el equipo decida abandonar el proyecto y/o la compañía por desmotivación y/o estrés.
* Timmings excesivamente largos al modificar o añadir código (y por tanto sobre coste de desarrollo). La deuda técnica suele complicar el desarrollo de nuevas funcionalidades provocando que la entrega se retrase.
* Deuda funcional. Puede suceder que no seamos capaces de implementar algunas funcionalidades que vienen definidas desde el equipo de producto.
* Gran cantidad de bugs. Al ponerlo en producción aparecen de manera masiva  multitud de bugs que no se conocían. Por ejemplo, teníamos un cliente que sólo utilizaba una sección del software, pero ahora tenemos mil clientes y estos utilizan todos los rincones del software. De repente descubirmos, que no funciona bien y hay múltiples errores. Peligro: pérdida de clientes y una imagen de marca difícil de reparar.
* Imposibilidad de escalar. Rendimiento y problemas de infraestructura. Por ejemplo, nuestra aplicación funciona correctamente, pero cuando tiene muchos clientes conectados el servidor se satura. O bien, el sistema funciona correctamente, pero cuando la base de datos crece las consultas comienzan a ralentizarse hasta un punto sostenible.


### ¿Cómo lo arreglamos?
Debemos aumentar la calidad del software. Serán de utilidad: arquitectura de software, principios SOLID, YAGNI, clean code, testing, etc.  

Lo más sensato es tratar de reducirla escalonadamente. Por ejemplo, tratar de dedicar un 20% de cada sprint a reducirla.  

Suele ser recomendable pagarla cuanto antes, ya que tiende a incrementarse con el tiempo.  

Es más costo-eficiente pagar la deuda técnica de aquellas partes del código que mutan frecuentemente.  

La deuda técnica se puede medir mediante algunas técnicas/herramientas. Por tanto, lo ideal es hacer un seguimiento empírico de su evolución.  

> Un apunte: No todo es blanco y negro! Hay que tener en cuenta, que casi todos los proyectos tienen algo de deuda técnica. Y no hay ningún problema con ello mientras la deuda técnica sea relativamente baja. 
La deuda técnica se convierte en un problema cuando su volumen es considerable.  



### La deuda técnica como herramienta a nuestro favor ⚠️
La deuda técnica puede ser intencionada en algunos casos. Por ejemplo, una startup podría estar interesada en salir a mercado lo antes posible y/o evaluar la viavilidad económica de un proyecto. Para lograrlo, conscientemente puede "comprar" deuda y dejarla a deber para cuando el modelo de negocio esté validado.   
Una empresa convencional puede estar en el mismo supuesto cuando trata de crear un nuevo producto. Es posible que para conseguir las primeras ventas y ganar los primeros clientes recurran a la deuda técnica dejando a deber la deuda.  

En estos casos, la deuda técnica es una herramienta que las empresas utilizar a su favor. Sin embargo, la deuda va a estar ahí y la empresa tarde o temprano va a tener que lidiar con ella. Será crucial que la empresa no haga oídos sordos al pago de la deuda técnica en el futuro.  

