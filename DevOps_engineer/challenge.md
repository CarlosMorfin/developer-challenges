# DevOps Engineer challenge

## Objetivo

Crea una instancia EC2 debajo de un balanceador de carga en AWS

## Requisitos

1. Crear una VPC la cual debe tener dos subnets una privada y una publica
3. Lanzar una instancia EC2 dentro de la subnet privada
4. Instalar nginx y agregar un contexto en la configuracion, que muestre la ip local
5. Crear un balanceador en la subnet publica
6. Agregar la instancia EC2 al balanceador

## Puntos a evaluar

- Nivel de automatizacion del proceso. Preferible usar: ansible, chef, puppet, terraform, codedeploy, etc.
- Considerar las mejores practicas en el diseño de tu arquitectura. Implementa el AWS Well-Architected framework
- Se realizara una peticion curl a la URL del balanceador, la cual deberá devolver la ip privada de la(s) instancia(s) EC2
- Uso de Git.

## Opcional/Bonus

1. Crear un grupo de auto escalado con un minimo de 2 instancias
2. Apuntar el balanceador al grupo de auto escalado
3. Crear una life cycle policy con los siguientes parametros

scale in : CPU utilization > 40%
scale out : CPU Utilization < 20%
