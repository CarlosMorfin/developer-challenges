# Support Engineer challenge

## Contexto

Actualmente, los usuarios de la plataforma web tienen que realizar el rastreo de sus envíos por varios medios. Páginas web de rastreo, correo electrónico, teléfono, etc. Es importante ofrecer a los usuarios un medio centralizado para revisar el estado de sus envíos, ya que se utilizan diferentes proveedores y cada uno utiliza tecnologías diversas.

## Objetivo

Desarrollar una aplicación que consulte la API de una paquetería, para poder consultar el _tracking_ de cada guía de envío. Es necesario persistir la información de manera local en una base de datos, para construir una vista al usuario en donde pueda consultar la información de sus envíos.

La vista que se mostrará al usuario deberá contener lo siguiente:
- Nombre de la paquetería.
- Número de guía.
- _Status._
- Descripción.

Es importante mostrar al usuario de manera organizada la información, ya sea en una tabla o algún otro componente.

## Requisitos

- Debes usar RubyOnRails para la solución.
- Se debe consultar el _tracking_ en la API de FedEx.
- Debe subirse a un repositorio privado en GitHub.

## Recursos
- Puedes usar una gema para consumir la API de FedEx y rastrear los envíos: [Gema de FedEx](https://github.com/jazminschroeder/fedex)
- Utiliza las guías que vienen en formato JSON dentro de esta carpeta.
- Las credenciales que puedes usar son las siguientes:

    ```  
      Fedex test keys
      Key: VZ0tu2xxC4LKxZY6
      Password: AKOh8wjdYsJtNI6CFKaxPFLka
      Account_number: 802388543
      Meter: 100495015
      Mode: test
    ```


## Puntos a evaluar

- Organización y estructuración del código y la información.
- Uso de una API de tercero.
- Git log.

## Opcional/Bonus

- Mientras más pruebas, mejor.
- Una manera fácil de cargar un archivo JSON para probar diferentes números de guía.
- Una interfaz de usuario amigable.
- Comentarios en el código
