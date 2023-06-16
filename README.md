## Recuerda instalar [ Termux de F-droid ] para seguir este proceso ` la app de termux de play store no sirve` 

# aqui enlace de descarga para hacer el tutorial

termux que sirve 

https://f-droid.org/repo/com.termux_118.apk

* Ejemplo - [COMPILACION ANDROID PARTE 1 ](https://youtu.be/qPx6AOsRWNw) cómo uso los comandos de Termux android

```bash
termux-change-repo
```
te aparecera un recuadro como este a continuación, lo siguiente que tendrss que realizar es 
pulsar [ `ENTER` ] Para continuar con el siguiente punto que sera seleccionar el servidor donde nos vamos a conectar.
![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119162505613283459/207103623-82f57c13-c0c9-486b-b3bc-529ff13e4e3a.png)
 

Con el primer comando tenernos que cambiar el repositorio de Termux al siguiente: 

Mirrors by Tsinghua UniversityHosted on mirrors, tuna.tsinghua.edu.

Después darás [ENTER] y continuas con el vídeo ejemplo [parte - 1]

```bash
yes|pkg update && yes|pkg upgrade
```


Aquí empieza la [PARTE -2]
* Ejemplo - [COMPILACION ANDROID PARTE 2 ](https://youtu.be/nJFD_KKfXpA) cómo uso los comandos de Termux android
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️
## cuando ejecutes este comando tendrás que darle permitir acceso

```bash
termux-setup-storage
```

Con este comando eliminaremos está herramienta que no sirve para nada y nos ocaciona un gran error, para solucionarlo y podamos continuar tendrás que ejecutar este comando a continuación
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

```bash
pkg remove libglvnd
```
## Con este comando podrás instalar las herramientas que necesitaremos para compilar nuestro juego[NECESITARAS 1GB] recomendable.
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️
 si te hace una pregunta como en el video solo responde `Y` y das enter para continuar porque este comando de abajo te hara una pregunta 

```bash
pkg install git wget make python getconf zip apksigner clang binutils libglvnd-dev aapt which
```

Con este comando clonaras el repositorio de OWOKITTY para poder compilar el juego

⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

```bash
git clone https://github.com/robertkirkman/sm64ex-coop.git
```

Esto te ayudará a copiar el baserom que te muestro en el video de la parte 2
Tendrás que colocarlo en tu almacenamiento raíz memoria del dispositivo para poder copiarlo de una manera correcta y no haya errores 

⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

```bash
cp /storage/emulated/0/baserom.us.z64 sm64ex-coop/baserom.us.z64
```
Aquí entraremos a la carpeta donde están los archivos para la creación del juego
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

```bash
cd sm64ex-coop
```
ponemos este comando para actualizar si es necesario el juego y git 

```bash
git pull
```
Con este comando actualizaremos archivos si es necesario de sm64ex coop
Nos ayudará a cargar los archivos de coopnet y actualizar el juego [ SI ESQUE HAY ACTUALIZACIONES ] ponlo si o si
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

```bash
git submodule update --init --recursive
```
Con este comando `make` compilaremos el juego para 32 bits y 64 bits OJO solo poner `make` para compilarlo de lo contrario no funcionará para dispositivos de 32 bits ⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

```bash
make
```

Enhorabuena ya para finalizar ejecuta este comando para sacar el sm64ex coop Android a tu DISPOSITIVO MEMORIA INTERNA

```bash
cp build/us_pc/sm64.us.apk /storage/emulated/0
```

## para salirnos de termux pondremos el siguiente comando 
```bash
exit
```

## una vez terminado si quieres a futuro actualizar sm64ex coop Android no borres termux para que no se te complique y sigue estos pasos para actualizarlo

# paso 1

entrar a termux y escribir el siguiente comando

```bash
yes|pkg update && yes|pkg upgrade
```

Después pondras esto a continuación para entrar a la carpeta 

```bash
cd sm64ex-coop
```

```bash
make clean
```

```bash
git pull
```

```bash
git submodule update --init --recursive
```

```bash
make
```

# ahora esperaras y tendras de nuevo tu sm64ex coop Android actualizada solo deberas poner el siguiente comando para sacarla pero antes deberas borrar el antiguo para despues poner este comando

```bash
cp build/us_pc/sm64.us.apk /storage/emulated/0
```



YA NOMAS QUEDARA INSTALAR EL JUEGO Y LISTO A DISFRUTAR


Gracias a OWOKITTY por el Port a Android y XxCmbRxX Por traerles el tutorial en español
