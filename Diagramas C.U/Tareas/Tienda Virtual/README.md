# Tienda Virtual.

![<>](img/6-consejos-para-hacer-tu-tienda-online-mas-segura1663690225.jpg)

El sistema tendrá que gestionar las cuentas de los clientes que realizan pedidos de productos del negocio. Cada producto tiene un stock determinado. Generalmente un cliente tiene una o varias cuentas para pagar los pedidos y cada cuenta tiene asociada una tarjeta de crédito con una cantidad disponible de dinero. Esa cantidad puede aumentarse por parte del cliente para poder realizar más pedidos.

Los clientes que quieran realizar un pedido tendrán que tener alguna cuenta con saldo disponible.

Los pedidos pueden ser simples o compuestos. Un pedido simple solamente tendrá una cuenta de pago y como mucho tendrá 20 productos.

Un pedido compuesto puede tener dos o más pedidos (simples o compuestos). Obviamente un pedido compuesto se tiene que pagar con la cuenta de un mismo cliente.

Solamente se pueden pedir productos que estén en stock.

Los cobros se hacen diariamente a las 23:59 horas. En ese procedimiento de cobro se comprueban todos los pedidos pendientes de cobro y se cobran de las cuentas de los clientes. Si una cuenta de cliente NO tiene dinero suficiente se RECHAZA el pedido (tanto si es simple como si forma parte de un pedido compuesto).

Una vez superado este proceso se genera la orden de distribución y confirma los pedidos.

Los pedidos listos de reparto se entregan y una vez entregados su estado pasa a estar confirmado.

Un cliente puede o no estar registrado previamente, con lo cual la realización de pedidos supone realizar un registro, para más tarde autenticarse.

## Diagrama CU:

![<>](img/Yienda%20%20Online.png)

| Actor  | Cliente  |   |   |   |
|---|---|---|---|---|
| Descripción  | El cliente ha de registrarse, asociar una tarjeta y establecer un límite, una vez hecho eso, obtiene la posibilidad de realizar pedidos. |
| Características | Una vez registrado, puede poner en marcha todo el proceso de de pedido del producto. |
| Relaciones  |   |   |   |   |
| Referencias |   |   |   |   |
| Notas | El registro es necesario para realizar un pedido |
| Autor  | Jaime León García |

| Actor  | Sistema de cobro  |   |   |   |
|---|---|---|---|---|
| Descripción  | El sistema de cobro se encarga de gestionar las cuentas y comprobar el saldo para efectuar los cobros y permitir la efectuación de pedidos. |
| Características | Puede aprobar o rechazar la efectuación de un pedido en caso de que el cliente no tenga suficiente saldo |
| Relaciones  |   |   |   |   |
| Referencias |   |   |   |   |
| Notas | |
| Autor  | Jaime León García |

| Actor  | Reparto  |   |   |   |
|---|---|---|---|---|
| Descripción  | El encargado de reparto recibe los pedidos confirmados y efectúa su envío. |
| Características | Ha de confirmar la entrega una vez esta haya sido realizada |
| Relaciones  |   |   |   |   |
| Referencias |   |   |   |   |
| Notas | Se asume que la confirmación es un paso obligatorio |
| Autor  | Jaime León García |

