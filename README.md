# Comandos-Linux-SO
Repositorio de comandos de Linux del curso Sistemas Operativos, Ulacit, 2022.
***Comando*** | Usos | Ejemplo
|-------|------|--------|
```sudo``` | ejecuta el comando como administrador | ```sudo``` ./VBoxLinuxAdditions.run
```apt``` | instala desde el repertorio de ubuntu| sudo ```apt``` install -y build-essential linux-headers-$(uname -r)
```ls``` | imprime en pantalla los nombres de las carpetas|![image](https://user-images.githubusercontent.com/114045975/191426987-6f1f2adc-147a-4900-aa24-de9975b6aa29.png)
```pwd``` | muestra la ruta en la que se ubica|![image](https://user-images.githubusercontent.com/114045975/191427026-45001100-8e9f-4805-9dae-36f57688c508.png)
```/``` | dentro están todas las carpetas del sistema operativo, "carpetas madre"| ![image](https://user-images.githubusercontent.com/114045975/191427070-d3463c29-a4f2-4858-991c-e8893d713bb8.png) _Cambió de ~$ a /$ y se imprimen las carpetas madre_
```cd [name carpeta]``` | significa cambiar directorio, es para cambiar la ruta| ```cd``` Documents/, ```cd``` Music/, ```cd``` Pictures/, ```cd``` /, etc.
```cd .. ```| ir hacia atrás en las carpetas| ![image](https://user-images.githubusercontent.com/114045975/191427408-129c3428-bb62-4d4b-8d16-87aea6e3b51d.png)
```cd [x] tab^2``` | autocompleta o muestra sugerencias de carpetas/archivos segun la letra digitada | ![image](https://user-images.githubusercontent.com/114045975/191427225-fb44940d-f992-4406-9b94-fb72929e933e.png)
```nano ([name])```| abre un archivo de texto .txt, puede agregarle nombre previo o después a la hora de guardarlo|[Nano command - Diana Rodriguez.webm](https://user-images.githubusercontent.com/114045975/191427576-d46cf8e9-c930-46d3-9c67-d6fa56c5956d.webm)
```cat [name].txt``` | imprime el contenido del archivo de texto|![image](https://user-images.githubusercontent.com/114045975/192120525-4b14ddda-1bb6-4860-952a-95146f80eb6e.png)
```mkdir [name]``` | crear una carpeta nueva| mkdir FotosS1
```rm [name]``` /``` rm [name] -R``` | remueve archivos o carpetas, +```f``` al final es forzado| rm FotosS1
```history``` | ver el historial de comandos en la termial|![image](https://user-images.githubusercontent.com/114045975/192120793-836944c1-1d86-4f2a-883d-0ac6b4a84c2b.png)
```clear``` | vacia la terminal| [clear command - Diana Rodriguez.webm](https://user-images.githubusercontent.com/114045975/192121086-b1753874-d6df-424c-b6b1-4c48a0a74c2d.webm)
```htop``` o ```top```| muestra los procesos corriendo en vivo|[htop command - Diana Rodriguez.webm](https://user-images.githubusercontent.com/114045975/192121092-0eb2fa8a-77cc-4bd7-b35f-13994d75ea25.webm)
```ps -aux``` | imprime los procesos de ese momento| [ps -aux command - Diana Rodriguez.webm](https://user-images.githubusercontent.com/114045975/192121161-92a7cbe7-0867-44f2-b9bd-784d45b1e1f4.webm)
```pstree``` | imprime los procesos en árbol| ![image](https://user-images.githubusercontent.com/114045975/192121185-2ae33390-9c15-4a64-aa45-b741c51e861d.png)
```kill -9 [PID]``` | para matar un proceso| ![image](https://user-images.githubusercontent.com/114045975/192121211-56b7f054-360b-4fae-81db-33f7d5746b50.png)
sudo apt install```openssh-sever``` | instala el openssh | ```sudo``` ./VBoxLinuxAdditions.run
```man``` | abre un manual de lo que se indique | ```man``` apt ![image](https://user-images.githubusercontent.com/114045975/206005741-8c2381ac-a775-4332-bad8-b92433d292ce.png)
```sudo su``` | para volverse super administrador |![image](https://user-images.githubusercontent.com/114045975/206005983-3e9b65e9-e29c-411a-b08b-7cf7e6d8ec76.png)
```whoami``` | mostrar el usuario que somos | ![image](https://user-images.githubusercontent.com/114045975/206006258-70eb41b9-15e7-4387-a638-2511c015d404.png)
```exit``` | salir de donde estamos, cerrar la terminal, etc. Es como ir hacia atras | ![image](https://user-images.githubusercontent.com/114045975/206006495-03e5b2fa-c7c6-40b2-896e-0fd64e4fda3a.png)
```more [name].txt ``` | imprime el contenido del archivo, para archivos que son muy largos | cat /var/log/dmesg ```|``` ```more```
```less```| opuesto a more |
```|``` | concatena dos comandos | cat /var/log/dmesg ```|``` more
```tail``` | ver el final del archivo segun x cantidad de lineas | ```tail``` -n 5 [name].txt (imprime las ultimas 5 lineas)
```head``` | ver el principio de un archivo segun x cantidad de lineas | ```head``` -n 5 [name].txt
```cp``` | copiar un archivo a x archivo | ```cp``` prueba1.txt resultados.txt
```mv``` | mover un archivo a x ruta | ```mv``` resultados.txt Semana11
```adduser``` | agregar un nuevo usuario | sudo ```adduser``` maria
```passwd``` | cambiar la contraseña de un usuario | sudo ```passwd``` maria
```cntrl + c``` | detener un proceso | 
```ls -l``` | lista los archivos del directorio y sus permisos | ![image](https://user-images.githubusercontent.com/114045975/206014425-a3b5592b-0d8a-478e-b162-5d628748f338.png)
```file``` | muestra el tipo de un archivo | ![image](https://user-images.githubusercontent.com/114045975/206014816-e73d4feb-2461-40aa-9d1b-80455d48303b.png)
```echo``` | imprime un mensaje en pantalla |![image](https://user-images.githubusercontent.com/114045975/206015102-0697d1c5-ef50-4e62-914f-fec58768b5f4.png)
```startx``` | inicia el etorno grafico | ![image](https://user-images.githubusercontent.com/114045975/206015700-8afd3e44-1b21-4805-bc93-89675bc30eb0.png)
```tar``` | comprime archivos o carpetas | tar nom_archivo.tar nom_archivo
```chmod``` | cambiar los permisos de una carpeta o archivo | chmod 777 /media/raid5
```chown``` | modificar el propietario de una carpeta o archivo | chown [OPTIONS] USER[:GROUP] FILE, sudo ```chown``` nobody:nogroup /home/drodriguezs298/ftp
```unzip``` | extrae el contenido de unarchivo comprimido | unzip images.zip
```whatis``` | descripcion corta de un comando u objeto | ![image](https://user-images.githubusercontent.com/114045975/206018506-9a6776fd-e7a1-4b10-b604-8b5b36e7942b.png)
```neofetch``` | imprime informacion del sistema | ![image](https://user-images.githubusercontent.com/114045975/206018695-265933bd-a6d0-42b8-b5e3-bd6f7ecb298b.png)
```wget``` | recuperar/descargar contenido de internet | wget https://raw.githubusercontent.com/DaniDiazTech/Object-Oriented-Programming-in-Python/main/object_oriented_programming/cookies.py
```alias``` | para ver los alias creados o crear uno | ![image](https://user-images.githubusercontent.com/114045975/206019371-655b4b68-ead8-452e-9486-6ef633ad19c3.png)
```shutdown``` | apagar la maquina |
```reboot``` | reiniciar la maquina |
```wc``` | cuenta las palabras de un archivo, imprimiendo cantidad de lineas, palabras y tamaño en bytes | ![image](https://user-images.githubusercontent.com/114045975/206019970-55b3e168-079f-4458-8bb9-13a01b105bab.png)
```uname``` | imprime la informacion del sistema operativo | ![image](https://user-images.githubusercontent.com/114045975/206020502-24ecc2b1-8f86-499e-a34b-18fa3c5badbe.png)
```ufw``` | firewall | sudo ufw enable, sudo ufw disable, sudo ufw allow 22 (puerto)
```mdadm``` | administrar discos y dispositivos | ![image](https://user-images.githubusercontent.com/114045975/206021337-c59e8d3a-7068-4f78-b63c-0d315504b106.png)

