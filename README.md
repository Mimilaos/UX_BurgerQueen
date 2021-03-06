# BurgerQueen 
![logo]().

Nos acaban de enviar un correo con una solicitud para un nuevo proyecto.
Hay un restaurante que nos ha contactado porque quieren que alguien les construya una interfaz donde puedan tomar pedidos usando una tablet.

Como punto de partida, nos comparten el siguiente correo recibido del cliente:
> Somos Burguer Queen, una cadena de comida rápida 24hrs.

> Nuestra propuesta de servicio 24hrs ha tenido muy buena acogida, y para expandirnos necesitamos un sistema que nos ayude a tomar los pedidos de los clientes.

> Tenemos 2 menús: uno para el desayuno, que es bien sencillo:

> **Desayuno**

> |Item|Precio|
> |:---|:---:|
> |Café Americano|$20|
> |Café con Leche| $28 |
> |Sandwich de Jamón y Queso| $35 |
> |Jugo Natural| $15 |


Y un menú para el resto del dia:

> **Diario**

> |Hamburguesas|Precio|Acompañamientos|+$15|Bebidas|Precio|
> |:---|:---:|:---|:---:|:---|:---:|
> |Sencilla|$40|Papas a la Francesa||Refresco|$15|
> |Doble| $55 |Onion Rings||Agua|$10|

> Los clientes pueden escoger entre hamburguesas de res, de pollo, o vegetariana. Y por $15 MXN pueden agregarle queso o huevo.

> Nuestros clientes son bastante indecisos, por lo que es muy común que cambien el pedido varias veces antes de finalizarlo.

## Introducción

La situación habitual en un restaurante en cuanto a pedidos, tiempo de espera, facturación correcta, entre otros, no es la más ideal en la mayoría de los casos, lo que hace que resulte difícil dar un buen servicio al cliente, sobre todo durante las horas de mayor ocupación del local. 

Los recursos con los que se cuentan en un local de este tipo (restaurante, bar, etc.) son escasos, y esto obliga al personal del restaurante a tener que desplazarse un gran un número de veces de un lugar a otro para poder cumplir con su labor, ocasionando deficiencias en el servicio, olvido de órdenes, retardos, y equivocaciones en los pedidos debido a que el sistema que se utiliza es manual.

 Todo lo anteriormente explicado conlleva pérdidas económicas y de clientela que pueden determinar el éxito o fracaso del negocio.

 Es por eso que se propone diseñar e implementar un sistema que brinde flexibilidad gracias al uso de terminales táctiles, las cual se automatizará el proceso del pedido, otorgará flexibilidad por medio de sus módulos configurables, ofrecerá información precisa garantizada por la aplicación, llevará a cabo el control de usuarios, la integración de los procesos del negocio por medio de los distintos módulos del sistema, optimización de los mismos debido a que el sistema reduce el tiempo de ejecución de los procesos y usabilidad.. En el actual ámbito de desarrollo, el sistema será implementado y testeado. 

Se asumen terminales con dispositivos táctiles. De esta forma, es posible el desarrollo de la funcionalidad completa del software.


## Metodología

Design Sprint es una metodología desarrollada por Google Ventures popularizada por Jake Knapp. Sirve para mejorar los problemas de diseño que afectan al negocio.

Con un proceso de 5 días, aunque a veces los podemos acortar a 3 días. En ellos a través de una serie de técnicas y de un estricto control del tiempo pasamos de la idea al producto diseñado y con un plan de validación en mercado con usuarios.

![Design Sprint](https://i.ibb.co/8BNdzgD/design-sprint.jpg).


## Objetivo


Desarrollar una aplicación web capaz de dar soporte a la gestión de los pedidos de  un restaurante.


## Investigación de campo

Las necesidades más básicas para un restaurante son: disponer de un sitio donde ofertar los productos, un sistema para la gestión de pedidos, y un registro donde poder almacenar dichos pedidos y el coste de los mismos.

Para conocer los principales problemas y situaciones a los que se enfrentan los brindadores de dichos servicios se realizó una visita a uno de estos establecimientos.

## McDonald´s

Se realiza una visita guiada al establecimiento ubicado en la calle Génova 56, Juárez, CDMX, de una de las cadenas más representativas dentro de la industria de la comida rápida.

A lo largo del recorrido la gerente de la sucursal en cuestión nos mostró las instalaciones mientras nos narraba cada una  de las medidas y procesos de limpieza y organización que llevan a cabo en cada una de las áreas (comedor, cocina, almacenes, cajas, etc).
Actualmente, en el mercado se pueden encontrar numerosas soluciones software, las cuales se dedican a la gestión de restaurantes, cumpliendo con las necesidades más básicas mencionadas previamente, con esto en mente y como la parte final de dicho recorrido nos dirigimos al área de cajas, donde amablemente nos mostró el software que utilizan y el proceso que llevan a cabo dentro de la interfaz para realizar un pedido tanto de manera presencial como de manera remota como lo ofrecen las aplicaciones de Rappi o Postmate por citar un ejemplo.

Con ello encontramos una serie de características:
## Gains
Sincronización con orden de cocina

Total y forma de pagos

Sincronización con aplicaciones de comida

Menú de Botones Grandes

Te muestra el resumen del pedido

Flujo simple
 
## Pains

Diseño poco amigable

No es intuitiva 

Inconsistencias en la Interfaz

Desordenada

Contraseña larga para ingresar

No tiene secciones definidas

Filtros confusos

Orden arbitrario

Sin actualizaciones continuas (promociones)

Visualmente poco atractiva 


La gerente del establecimiento nos comento lo que desearía y facilita su trabajo:

Consistencia en el diseño

Orden de los productos

Actualización de las Promociones

Una navegación más intuitiva

## Mapa de Empatía

A través de la exploración de campo se realizó un empathy map para definir el perfil de nuestro usuario
![Empathy Map](https://i.ibb.co/GRKst9V/Captura-de-Pantalla-2019-05-06-a-la-s-0-58-50.png).

## Benchmarking


Por medio de la colaboración de las compañeras interesadas en desarrollar una mejor interfaz con respecto al proyecto  de Burguer Queen se elaboró el siguiente benchmark para así poder generar un producto que cubra con las necesidades de dichos brindadores de estos servicios:

![Empathy Map](https://i.ibb.co/TRc9GNg/Benchmark-BQ.jpg).


Posteriormente se realizó  una búsqueda de diferentes soluciones y aplicaciones que cumplen con las necesidades básicas, a continuación se van a citar las diferentes soluciones encontradas:

• AZHosteleria o http://www.softpyme.net/software-bar-restaurante.php
 • RestaWeb o http://www.techni-web.es 
• RestBar o http://www.restbar.com/ 

A continuación se detallan las principales características y carencias de dichas soluciones: 

![Benchmark](https://i.ibb.co/zr1dsPf/Captura-de-Pantalla-2019-05-06-a-la-s-1-10-26.png).


En conclusión, todos las soluciones vistas, complacen las necesidades básicas, disponer de un sitio donde ofertar los productos, un sistema para la gestión de pedidos, y un registro donde poder almacenar dichos pedidos y el coste de los mismos, pero ninguno de ellos cumple con una interfaz amigable o un proceso intuitivo donde el usuario pueda realizar un proceso rápido y de fácil entendimiento. 


## Prototipo de Alta Fidelidad 


## Presentación con Cliente

Visualizar la presentación con cliente *[aqui](https://docs.google.com/presentation/d/1WvAPVs9h6t70PwkL1gr9VOuSlxq66HfNiThcVU4W86E/edit#slide=id.g56605a8ff6_0_4).


### Requerimientos

- Entender cómo se realizan los pedidos en un restaurante similar a BQ y cuáles son las necesidades del personal de cocina y del personal de atención al público (meser@s y cajer@s).
  - Ideal si dentro de la investigación toman fotos de las formas en que se toman pedidos actualmente.
- Diseñar la versión para tablets de esta aplicación, teniendo en cuenta el modo de uso de esta tablet (por ej. El uso de la     pantalla táctil) y los distintos tipos de usuarios.
  - El diseño se debe adaptar a dos tamaños de tablets 9.7 y 7 pulgadas.
  - Crear un ícono para poder agregar la pantalla al home de la tablet. Puedes usar [appicon](https://appicon.co/#app-icon) y     agregar las especificaciones para   el equipo de desarrollo.
- El estado actual del pedido siempre visible mientras tomamos un pedido.
- Necesitamos hacer una web app, así será accesible y funcionará bien en tablets iOS y Android.
- Testear e iterar los diseños con personal de restaurantes similares a BQ.
- Entregar las especificaciones de diseño al equipo de desarrollo en Figma, Zeplin ó XD.
- Hacer seguimiento y QA a la implementación realizada por el equipo de desarrollo.
- Realizar pruebas de usabilidad de la aplicación web al final de cada entrega del equipo de desarrollo.


