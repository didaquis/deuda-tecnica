# Deuda técnica

Este repositorio contiene algunas reflexiones alrededor de la deuda técnica.  


-------- 

### ¿Qué es?
La deuda técnica es el coste y los intereses a pagar por hacer mal las cosas. Es el sobre esfuerzo a pagar para mantener un producto software mal hecho.  

### ¿Cómo se origina?
Algunos de los principales motivos por los cuales se origina la deuda técnica:  
* Excesiva presión con las fechas
* Falta de cuidado/educación/implicación (malas prácticas durante el desarrollo del software)
* Inexistencia de la verificación de la calidad del software desarrollado
* Developers con conocimientos técnicos insuficientes
* Errores de diseño
* Roadmap indeciso (cambios de opinión, idas y venidas de concepción de producto)
* Software que no ha recibido mantenimiento periódico y ha envejecido de manera desatendida

### La deuda técnica como herramienta a nuestro favor
La deuda técnica puede ser intencionada en algunos casos. Por ejemplo, una startup podría estar interesada en salir a mercado lo antes posible y/o evaluar la viavilidad económica de un proyecto. Para lograrlo, conscientemente puede "comprar" deuda y dejarla a deber para cuando el modelo de negocio esté validado.  
Una empresa convencional puede estar en el mismo supuesto cuando trata de crear un nuevo producto. Es posible que para conseguir las primeras ventas recurran a la deuda técnica y cuando llegue el momento de escalar, el software no pueda hacerlo.  
En estos casos, la deuda técnica es una herramienta que las empresas utilizar a su favor. Sin embargo, la deuda va a estar ahí y la empresa tarde o temprano va a tener que lidiar con ella.  

### ¿Qué va a pasar con la deuda técnica?
La deuda técnica se comporta exactamente como una deuda financiera. No desaparece, tiende a incrementarse con el paso del tiempo, y sus consecuencias pueden ser insostenibles.    

Como cualquier otra deuda, alguien va a pagar por ella de manera consciente o inconsciente. 


Las diferentes maneras de pagar una deuda técnica (el pago puede ser consciente o inconsciente):
* Conscientemente se decide invertir tiempo para reducir la deuda técnica. Usualmente: refactorizando el código, revisando la infraestructura, definiendo el producto, desechando código, etc.
* Aparecen evidentes dificultades para modificar ese código por falta de conocimientos (Ejemplo: nadie sabe como funciona o como se pone en marcha. O incluso, no encontramos programadores de << INSERTE AQUÍ UN LENGUAJE OBSOLETO >>)
* Perdida de talento en el equipo. A nadie le gusta trabajar con una base de código terrible. Puede pasar que el equipo decida abandonar el proyecto y/o la compañía.
* Timmings excesivos (y por tanto sobre coste de desarrollo). La deuda técnica suele complicar el desarrollo de nuevas funcionalidad provocando que la entrega se retrase. Si por ejemplo, una funcionalidad debería haberse entregado en 20 días, pero debido a la baja calidad del código se ha tardado 33 días, esos 13 días extras son consecuéncia de la deuda técnica.
* Deuda funcional
* Gran cantidad de bugs. Al ponerlo en producción de manera masiva aparecen multitud de bugs.
* Imposibilidad de escalar. Rendimiento y problemas de infraestructura. Por ejemplo, base de datos que se ralentizan. Servidores caídos.




### ¿Cómo lo arreglamos?
Lo más sensato es tratar de reducirla escalonadamente.  
Suele ser mucho más recomendable pagarla cuanto antes, ya que tiene a incrementarse con el tiempo.  
Es más costo eficiente pagar la deuda técnica de aquellas partes del código que mutan frecuentemente.  
La deuda técnica see puede medir. Por tanto, lo ideal es hacerle un seguimiento de su evolución.  

