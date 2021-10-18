# ejercicio_6
Utilizando docker compose generar una configuración para correr dos instancias de passwordapi
(https://hub.docker.com/repository/docker/nicopaez/password-api) balanceadas por Nginx.
La aplicación tiene un endpoint /health que indica la ip/host de la instancia que atendió el pedido,
se puede usar esto para verificar el correcto balanceo.
