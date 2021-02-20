# BryanPacheco
Implemtacion de AWS-CLOUDWATCH
# IMPLEMENTACION DE AMAZON KINESIS-CLOUDWATCH
A continuacion mostraremos los pasos necesarios para crear una alrma en AWS-CLOUDWATCH
Antes de comenzar con la implementacion debemos saber que aws cloudwatch  es un servicio de monitorización y observación que ofrece datos e información procesable para monitorizar sus aplicaciones, responder a cambios de rendimiento que afectan a todo el sistema, optimizar el uso de recursos y lograr una vista unificada del estado de las operaciones.
![](https://p2zk82o7hr3yb6ge7gzxx4ki-wpengine.netdna-ssl.com/wp-content/uploads/Amazon-Cloudwatch-2.png)
## Requisitos previos
- Tener una cuenta en AWS
- Tener creado Ec2 (maquina virtual)
### Primer paso
- Una vez que tengamos creado EC2 debemos dirigirnos en donde se encuentra Monitore de CPU utilizacion
- Luego hacemos click en "Ver metricas" esta nos lleva hacia el panel de metricas.
### Segundo Paso
- En el panel de metricas observaremos toda la utilizacion que tiene el CPU del EC2 creado.
- Luego nos dirigimos al grafico de matrices y seleccionamos crear alarma (icono de alarma).
### Tercer Paso
- Una vez seleccionado crear alarma nos mostrara un panel con 3 opciones que debemos configurar.
- Primero configuramos la metrica con el nombre que deseamos observar luego el tiempo que se mostrara en la grafica tambien el tipo de umbral que para esta implementacion lo dejamos en static.
- Como segundo paso configuramos la notificacion que es la direccion de correo donde queremos tener la informacion y el nombre que tendra la configuracion
- Posteriormente nos llegara al correo que asignamos la invitacion para suscribirnos a aws-cloudwatch.
### Cuarto paso
- Regresamos al panel de aws-cloudwatch en la opcion alarma de matrices donde seleccionamos agregar tablero.
- Nos mostrara otro panel con las formas en que se mostrara toda la informacion de nuestra maquina EC2.
### Quinto paso
- Luego seleccionamos la opcion guardar que sera la forma del tablero que seleccionamos anteriormente.
- Por ultimo ya tenemos anexado nuestro correo con aws-cloudwatch el cual nos mostrara toda la informacion temporalmente.
![](https://dmhnzl5mp9mj6.cloudfront.net/security_awsblog/images/solutiondiagram_saurabh_a.png)






