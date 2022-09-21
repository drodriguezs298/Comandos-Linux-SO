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
```cat [name].txt``` | imprime el contenido del archivo de texto|
```mkdir [name]``` | crear una carpeta nueva|
```rm [name]``` /``` rm [name] -R``` | remueve archivos o carpetas, +```f``` al final es forzado|
```history``` | ver el historial de comandos en la termial|
```clear``` | vacia la terminal|
```htop``` o ```top```| muestra los procesos corriendo en vivo|
```ps -aux``` | imprime los procesos de ese momento|
```pstree``` | imprime los procesos en árbol|
```kill -9 [PID]``` | para matar un proceso|
