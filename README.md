# front_appSupermarket

Hola, en este README dejare algunas anotaciones para tener en cuenta.
Seria optimo instalar primero el back y luego el front, para cuando despliegue el front se cargue la tabla de inmediato.

# Versiones de las tecnologias utilizadas
SO Windows = Windows 10
Angular = v11.2.14

# Pasos para compilar el proyecto
1. Seleccionar la branch de master
2. Seleccionar el boton verde "Code" y dar clic en "Download ZIP"
3. Descomprimir el proyecto
4. Abrir una consola CMD e navegar a la ruta raiz del proyecto que acaba de descomprimir.
      "cd ../front_appSupermarket-master"
5. Si desea ver el codigo del proyecto y tiene Visual Studio, en la consola puede poner lo siguiente "code .", este comando le abrira esta carpeta en Visual Studio
6. Estando en la carpeta "front_appSupermarket-master", escriba lo siguiente en la consola:
      "npm install"
   Este comando le permitira instalar todas las dependencias y librerias necesarias para compilar el proyecto back en su maquina
7. Despues de que se finalice el proceso, escriba lo siguiente en consola:
      "ng serve"
   Este comando desplegara el proyecto de manera local y por lo general en el puerto 4200.
   Para comprobar el funcionamiento, abra su navegador y vaya a este link
      http://localhost:4200/
   Se debera mostrar una tabla con diferentes botones y campos para rellenar que permitiran realizar el CRUD solicitado en la prueba.
   Quiero aclarar que los campos vacios de la primera fila, son para realizar un filtrado y busqueda en los diferentes campos ya registrados, para crear un nuevo campo es necesario oprimir el boton (+) y se desplegara una nueva fila vacia para poder llenar y confirmar el registro con el icono del (check).
   
# Gracias
Para cualquier duda o inquietud no dude en escribirme para darle solución lo más pronto posible.
jorgeagui216@gmail.com
Att, Jorge Aguilar
