Este proyecto consiste en la creacion de un pipeline declarativo en Jenkins usando un script escrito en Groovy, este script busca crear usuarios dentro de un sistema Linux.
Para ejecutar este proyecto, los pasos a realizar son los siguientes; 
 Requerimientos previos:
1. Tener un sisteuna maquina virtual con algun sistema operativo Linux preferiblemente Ubuntu
2. Instalar Jenkins
3. En la terminar de su sistema Linux correr correr el siguiente comando: sudo nano /etc/sudoers
4. Verifique que este documento tenga la siguien te configuracion
5. su archivo sudors deberia verse similar al de esta imagen.
    ![image](https://github.com/Kidbuut/Desafio1/assets/120615998/73b3f140-daf4-4604-a406-b9a527eed8db)

Pasos para ejecutar el script

1. Clonar este repositorio
2. Solicitar la llave creada en Github
3. iniciar sesion en Jenkins en la direccion de su IP con la salida por el puerto 8080.
  ![image](https://github.com/Kidbuut/Desafio1/assets/120615998/f150c602-7aa7-4947-9890-739473732dde)
5. Crear pipeline con el su nombre de preferencia
  ![image](https://github.com/Kidbuut/Desafio1/assets/120615998/16b1a8e0-e955-4ff9-ac49-daf76bd2d9c7)
6. Una vez creado el script y cargado en el repositorio de Github hay que ir a Jenkins para hacer la ejecicion de dicho script en el boton que dice "Build With Parameters"
  ![image](https://github.com/Kidbuut/Desafio1/assets/120615998/5b3dab9e-935f-46bd-b82a-f87d08032e33)
7. Al ejecutar el script se mostrara algo similar a esta imagen. si el resultado es correcto la se vera de la siguiente forma.
  ![image](https://github.com/Kidbuut/Desafio1/assets/120615998/dd762bb8-ddb5-4044-898f-f2a395665063)
  y si es incorrecto asi.
  ![image](https://github.com/Kidbuut/Desafio1/assets/120615998/b33f54cc-96f4-4f5f-9e4a-7ac76b7251f7)

  una vez finalizado estos pasos ya nuestro Pipeline esta listo para ser desplegado.
