# REMOND-Q-GUI-Software
Este software GUI interactivo es útil para realizar <B>LECTURAS</B> y <B>calibración manual interactiva</B> de los sensores de calidad de agua REMOND. Puede descargar el software instalador a traves de los enlaces mostrados abajo en imagen: 

# Vista Previa de los GUI 

<B>Lector-Calibrador del PHimetro:</B>
![image](https://user-images.githubusercontent.com/106831539/177463360-39113bcb-9ea1-4b7c-aae4-42a9f35f1de0.png)

<A HREF="https://drive.google.com/file/d/16fVAK4XWTegzOCGfbD2lVhxzkK7gzxvU/view?usp=sharing">Link de descarga del instalador GUI DO REMOND</A>

<B>Lector-Calibrador del Oxigeno disuelto DO:</B>
![image](https://user-images.githubusercontent.com/106831539/188742999-8080a448-2db9-4156-a4c5-f20f3e37d568.png)

<A HREF="https://drive.google.com/file/d/1jzi43oPj0_-aAN5n_KG1g0KCgBXX3ivA/view?usp=sharing">Link de descarga del instalador GUI pH REMOND</A>

# NOTA
Se requiere una conexion USB- RS485 a fin de comunicarse con el bus de los sensores REMOND; como se muestra a continuacion:
![image](https://github.com/user-attachments/assets/eca27f5f-8e7b-4b43-8dde-be487a69ff47)

Convertidor USB-485. Podemos adquirilo en paginas como <A HREF="https://es.aliexpress.com/item/1005007334186563.html?src=google&pdp_npi=4%40dis%21PEN%216.55%214.20%21%21%21%21%21%40%2112000040634267926%21ppc%21%21%21&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&&albagn=888888&&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=es1005007334186563&ds_e_product_merchant_id=107671097&ds_e_product_country=PE&ds_e_product_language=es&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=19373953645&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gclid=Cj0KCQiAouG5BhDBARIsAOc08RQwFG47GjZah3Qh850c7dq9VEpjG932lM3P1clwjpyNrbK9o2Fo0v8aAt0-EALw_wcB">ALIEXPRESS</A>

# PASOS PARA LECTURA

1.-Una vez que se instalen los software GUI, abrimos uno de ellos y en los rings de <B>"Address(1)"</B> , <B>"BaudRate(9600)"</B> asegurese que son correctos.  Luego click en <B>OpenCOM</B>

2.- Le saldra un mensaje de confirmacion de apertura de puerto, como se muestra a continuacion. De Clic en "Aceptar".

![image](https://user-images.githubusercontent.com/106831539/177829231-4a656c36-74c6-4433-bcdb-5421465bd1d3.png)

3.- Si el puerto se abrio sin errores ya puede iniciar las lecturas , haciendo clic en el boton <B> "GO "</B>, como se muestra a continuacion:

![REMOND Studio_pH Water Q vi 15_11_2024 17_33_14](https://github.com/user-attachments/assets/cc8474f1-9c0a-4d79-a8e6-50e406a935bc)

<I>Lectura del sensor de pH. Note como el boton <B>GO</B> ahora se muestra como <B>STOP</B></I>

4.- Para detener las lecturas de "Measurements", presione el boton <B>STOP</B>. Notara como los indicadores son puestos a cero.

# NOTA
Hasta este punto, deberia estar tomando las lecturas de <B>"pH"</B>, "Temperatura" y "CurrentOutput". Si queremos iniciar la calibracion, 
debemos detener la toma de muestras <B>STOP</B>

# PASOS PARA CALIBRAR EL SENSOR DE pH

1.- Ante de iniciar con la calibracion, debe asegurarse que el sensor este lavado y sumergido con agua destilada o agua desionizada. Asimismo, debe contar con por lo menos 2 Liquidos Sol. Estandar de calibracion que el fabricante ; tanto para el punto ZERO como para el punto SLOPE. Los mismos que puede elegir desde los menu ring desplegable:

![image](https://github.com/user-attachments/assets/017a2680-af55-4401-be60-7b1f716de2cd)

2.- Una vez elegidos los puntos a calibrar, debemos dar clic en los botones <B>"SetZero"</B> y <B>"SetSlope"</B>.Debemos recibir el mensaje de confirmacion:

![image](https://github.com/user-attachments/assets/214b90f6-8249-4a39-8a99-952637489b05)

<I>Botones de confirmacion de punto ZERO y SLOPE</I>

![image](https://github.com/user-attachments/assets/76883ab2-8098-4923-af4e-9f2f4f1c2f18)

<I>Mensaje de confirmacion de punto ZERO</I>

![image](https://github.com/user-attachments/assets/af069053-daaa-4a00-bec5-237a2f31e45b)

<I>Mensaje de confirmacion de punto SLOPE</I>

3.- Sumerga el sensor pH en el primer punto de calibracion ZERO (pH=6.86 o pH=7.00). Y haga Clic en el boton de <B>Start</B> en el apartado <B>Calibracion</B>. Recibira un mensaje de confirmacion de Inicio de calibracion : 

![image](https://github.com/user-attachments/assets/6961a9bd-b95e-445a-b179-a9c654d87e7f)

<I>Boton de START calibracion</I>

![Screenshot 15_11_2024 18_01_48](https://github.com/user-attachments/assets/4949cca4-d4e1-4f51-a381-2e5c3f759eaf)

<I>Mensaje de confirmacion de calibracion.</I>

4.- El valor de la muestra del ADC empezara a mostrar su valor asi como una marca de tiempo que se habilita su muestra. Debe esperar dicho valor se estabilie:

![image](https://github.com/user-attachments/assets/d1a234bf-5b90-4d01-b610-1467c385705d)

5.- Si el valor ya es estable, haga clic en <B>Confirm Zero</B>

![image](https://github.com/user-attachments/assets/120c5a46-9ec5-4639-96b4-08b0948989de)

6.- Ahora Limpie con agua destilada y  sumerga el sensor pH en el segundo punto de calibracion SLOPE (ex. pH=4.01 o el que haya elegido). Tenga en cuenta que el valor ADC se seguira leyendo, pero ahora con el nuevo punto. Debe esperar a que dicho valor sea estable.

7.- Si el valor ya es estable, haga clic en <B>Confirm SLOPE</B>

![image](https://github.com/user-attachments/assets/53f34495-9d05-4ef2-8d81-8e1b557b88d8)

8.- Recibira un <B>mensaje de confirmacion de RE-establecimiento de la lectura de muestras</B>, por lo que ya puede sumergir el sensor en agua destilada nuevamente.

# OBS
1.- Es indispensable este instalado los divers(CH340) del puerto USB RS485 para que este GUI pueda enlazarse al puerto serial. Los instaladores no instalan el driver.

2.- Para salir del programa, debe primero detener o <B>STOP</B> la lectura de muestras, luego cerrar el puerto COM--->>> click en "EXIT". Asi se evita que cuelgue el puerto.

3.- En la capreta /../LoggedData/ puede ver el reporte de calibracion de las muestras separado por coma, lo que es posible llevar a un archivo excel.
