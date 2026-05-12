# EDD_UML_Mu-oz_Herrera_Antonio
María Dolores Barba López y Antonio Muñoz Herrera
## Explicacion técnica del proceso modelado
1. El cliente ha decidido finalizar la compra del carrito
2. Una vez fianlizada, se procede a la validación de dos aspectos de la compra, serían la verificación de que haya stock y de la sesión del cliente sea correcta. Ambas validaciones se dan de forma simultáneas.
3. En caso de que alguna de estas verificaciones falle, se procede a la finalización del proceso debido a que si un fallo en uno de los dos, provoca que el cliente retroceda al anterior paso y no entre en la continuación del proceso, debiendo repetir este último paso.
4. Si los dos son correctos, se procederá al pago.
5. Existen dos posibilidades, la primera de ellas es el fallo del pago, para que este caso se de deben de pasar unas circustancias que sería la revisión de los datos de la tarjeta y si en la misma queda la cantidad de dinero que se pide en la compra, si no es así, se dará un fallo de no completada la compra y el cliente deberá de de repetir todo este proceso con una nueva tarjeta. La segunda posibilidad es la aceptación de la tarjeta. En esta posibilidad debe de suceder tres pasos, el registro del pedido en la base de datos, gerenar un PDF con la factura para el cliente y enviar una notificación por correo con la compra aceptada. Una vez se cumpla, el pago ha sido un éxito.
6. Una vez se acepta la tarjeta y con ella la finalización de la compra, se le da al cliente un mensaje de que la compra ha sido completada.

<img width="1383" height="523" alt="image" src="https://github.com/user-attachments/assets/00bb235a-6f39-42f1-9fe0-e12fdb2ff087" />

## Bibliografía
Bibliografía

[1]	«About the Unified Modeling Language Specification Version 2.5.1», Omg.org. [En línea]. Disponible en: https://www.omg.org/spec/UML/. [Accedido: 12-may-2026].
[2]	«IBM engineering systems design rhapsody», Ibm.com. [En línea]. Disponible en: https://www.ibm.com/docs/en/rhapsody/9.0.1?topic=diagrams-uml-activity. [Accedido: 12-may-2026].
[3]	«Visual paradigm - AI-powered visual modeling», Visual-paradigm.com. [En línea]. Disponible en: https://www.visual-paradigm.com/guide/uml/what-is-activity-diagram/. [Accedido: 12-may-2026].
