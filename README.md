# REMOND-Q-GUI-Software
Este software GUI interactivo es útil para realizar lecturas y calibración manual del sensor de pH de fabricante REMOND. Puede descargar el software instalador a traves de este enlace : https://mega.nz/file/GIAn1DiB#znWqsebPLKcxgb-lkbsD4WXA764g35RIPI5cW5CjKfQ

# Vista Previa

![image](https://user-images.githubusercontent.com/106831539/177463360-39113bcb-9ea1-4b7c-aae4-42a9f35f1de0.png)

# Nota
Se requiere una conexion USB- RS485 a fin de comunicarse con el bus de los sensores REMOND. O alguna interfaz equivalente capaz de bypasear los Seriales 0 y 1 y asi los dispositivos esclavos respondan a los comandos Modbus. Puede ver un codigo de ejemplo aqui : https://docs.arduino.cc/built-in-examples/communication/SerialPassthrough

# Pasos

1.- En los rings de "Address(1)" , "BaudRate(9600)" asegurese que son correctos. Luego click en OpenCOM
![image](https://user-images.githubusercontent.com/106831539/177829231-4a656c36-74c6-4433-bcdb-5421465bd1d3.png)

2.- Le saldra un mensaje de confirmacion de apertura de puerto. De en "Aceptar"
3.- Para iniciar las lecturas , de click en el boton "GO ". Acepte el mensaje de confirmacion.
4.- Para detener las lectura, presione el boton CloseCOM .

Hasta este punto, deberia estar tomando las lecturas de "pH", Temperatura" y "CurrentOutput"

# OBS
Para salir del programa, debe primero cerrar el puerto COM. Luego click en "EXIT" . 




