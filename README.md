# Proyecto 1 - Pasarelas de Pago.

## Producto seleccionado.

Pasarelas de Pago.

## ¿En qué consiste y qué servicio ofrece? ¿Qué hace? ¿Cómo funciona actualmente?

Las pasarelas de pago prestan un servicio que provee diferentes métodos de pago a una plataforma de E-Commerce. Estos mecanismos permiten realizar ventas en linea y transaciones nacionales e internacionales con una mayor rapidez y facilidad que métodos tradicionales como una consignación bancaría o pago en efectivo

Este tipo de servicios funcionan actualmente de la siguiente forma:

1. Un cliente realiza un pedido en un sitio web presionando el botón de "emitir orden" (o similar) o ingresa los detalles de su tarjeta de crédito a un servicio IVR.
2. Si la orden es a través de un sitio web, el navegador web del cliente cifra la información que viaja hasta el servidor web del vendedor. Esto se hace normalmente mediante cifrado Secure Socket Layer (SSL) o Transport Layer Security.
3. El vendedor reenvía los detalles de la transacción a su pasarela de pago, el cual contiene los detalles de las cuentas de sus vendedores. Normalmente, ésta es otra conexión cifrada mediante SSL al servidor de pago, almacenada en la pasarela de pago.
La pasarela de pago que recibe la información de la transacción del vendedor reenvía la información al banco adquirente del vendedor.
4. El banco adquirente reenvía la información de la transacción al banco emisor (el banco que le emitió la tarjeta de crédito al cliente) para autorización.
5. El banco emisor de la tarjeta recibe el pedido de autorización y envía una respuesta a la pasarela de pago (a través del banco adquirente) con un código de respuesta. Además de determinar el destino del pago (es decir, "aprobado" o "rechazado"), el código de respuesta se usa para definir la razón por la cual la transacción falló (como por ejemplo, por fondos insuficientes o enlace al banco no disponible) [1].


## Enlistar las propuestas de la estrategia y por cada una explicar el motivo por el cual sería efectiva.



### Recursos utilizados para llegar a la propuesta de mejora 
Ejercicio de las [11 estrellas](11stars.md)

El anterior ejercicio tiene como finalidad poder tener una visión del producto desde su estado actual y a dónde podría llegar. Con esto en cuenta la estrategia consiste en:

- Upgrade del producto a un sistema de puntos con beneficios:
Aunque muchas entidades bancarias ya brindan puntos por usar los servicios, el esquema de la pasarela de pagos incluiría un esquema diferente, otorgando puntos por estar inscrito y sumas adicionales por realizar transacciones. Los puntos no se redimen de forma tracicional. No se pierden puntos por redimir algun artículo o beneficio. Al alcanzar algún umbral de puntos recibe automáticamente el beneficio y sigue sumando para el siguiente. Todo esto con el fin de fomentar la consistencia en el uso del servicio ya que el usuario percibe beneficios más tangibles.

- Plan de ahorro:
La pasarela permite definir metas individuales, metas que recibirán acompañamiento con tips para lograrlos o recordatorio de los objetivos financieros, esto acompañado de recomendaciones que permitan ahorrar costos, dichas recomendaciones acompañadas de la cantidad de gente que las ha recibido, por ejemplo: "Ya que acabas de pagar tu servicio de internet, te recomendamos este plan de internet más acorde a tus necesidades. Otras 1000 personas ya lo tomaron y han ahorrado $ x los últimos 3 meses."

- Minimizar el uso de lenguaje altamente corporativo y financiero:
Este lenguaje puede causar repulsión en los usuarios ya que no se sienten identificados, lo que hace más difícil que logren comprometerse con la idea de realizar sus pagos a través de la plataforma.


## ¿cuál es el Job to be done?

Los usuarios usan el producto por las siguientes ventajas:

- Ahorro de tiempo: Evita traslados y eventuales filas en puntos de atención presenciales.
- Seguridad del dinero y transacciones: La pasarela de pagos funge también como validador de las transacciones.

Y de acuerdo a las estrategias anteriormente expuestas otra ventaja es:
- Tranquilidad financiera: Gracias al sistema de puntos, plan de ahorro y uso de un lenguaje más cotidiano, los usuarios tienen la oportunidad de:
    - Mejorar las finanzas personales al tener la posibilidad de escoger entre productos y servicios más acorde a sus necesidades.
    - Ahorrar. Tanto en reducción de gastos como en beneficios por eventuales retornos de dinero.



## De acuerdo a “Imperfect is perfect” ¿Cómo vas a lanzar las propuestas de feature de 7 estrellas establecida en tu plan?. Describe la estrategia a implementar.

La estrategia implica abordar distintos puntos para lograr lanzar un producto que desde el inicio logre cambios o solucione problemas de los usuarios.
Sobre la infraestructura ya existente, en primer lugar se tiene:
- Implementar notificaciones con bajo lenguaje técnico e identificar en la plataforma las quejas comunes por confusión del usuario y transformar la comunicación a algo más sencillo.
Esto con el fin de reducir la resistencia y baja confiabilidad que los usuarios tienen a los serviciosfinancieros.

Para lograr que el usuario adquiera beneficios económicos, la estrategia consta de:
    - Capturar toda la información disponible de transacciones, con alto respeto de la privacidad indivudual. Esto con el objetivo de crear el piloto de recomendaciones sobre lo que otros usuarios consumen y queda evidenciado en la pasarela.
    - Buscar empresas y llegar a acuerdos. Esto con el fin de incentivar la participación de las empresas al encontrar otro medio con el cual llegar a nuevos usuarios. Su participación queda supeditada a que los acuerdos se traduzcan como beneficios a al cliente, ya sea con ofertas más acordes a las necesidades de los consumidores o ofertas para las personas que logren mejores puntajes en la pasarela de pagos.
    - Implementación del sistema de puntos


## Referencias
[1] Wikipedia (2021, 9 Feb). Pasarela de pago. Available: https://es.wikipedia.org/wiki/Pasarela_de_pago. Consultado el 4 de Junio de 2021.