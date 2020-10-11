# En la aplicación que se ha usado como ejemplo en el ejercicio anterior, ¿podría usar diferentes lenguajes? ¿Qué almacenes de datos serían los más convenientes?

Sí, se pueden utilizar diferentes lenguajes, cada uno de los microservicios podría estar escrito en cualquier lenguaje y ser accesible mediante una API Gateway que se comunica con el cliente.

Por otro lado, la parte de Front-End está escrita en Angular, utilizando exclusivamente Typescript como lenguaje principal.

En cuanto al almacenamiento de la aplicación, se opta por bases de datos NoSQL concretamente MongoDB, ya que se integra perfectamente con el lenguaje utilizado en todos los microservicios, escritos en Node.js.

Los almacenes pueden ser aislados en Docker independientes si es necesario el acceso desde diferentes microservicios.
