# Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?

La aplicación elegida responde al problema de dar acceso al usuario para controlar el telescopio de la UPM. Es parte de mi TFG, y el patrón que utiliza es de microservicios, utilizando contenedores en Docker.

Sin embargo, una parte de los servicios están unificados en un solo Docker, por tanto su patrón difiere del resto, ya que proporciona una API donde se agregan varios servicios simultáneos.

Para poder evolucionar a un patrón de microservicios, se debe separar este conglomerado utilizando un sistema de paso de mensajes que así lo permita.

