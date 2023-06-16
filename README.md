## Recuerda instalar [ Termux de F-droid ] para seguir este proceso ` la app de termux de play store no sirve` 

# aqui enlace de descarga para hacer el tutorial

Descarga este termux que sirve dando click en el enlace 

https://f-droid.org/repo/com.termux_118.apk

* Ejemplo - [COMPILACION ANDROID PARTE 1 ](https://youtu.be/qPx6AOsRWNw)

## COMO OBTENER SM64EX-COOP ANDROID DESDE  CERO   👀

PRIMER COMANDO ⬇️
```bash
termux-change-repo
```
te aparecera un recuadro como este a continuación, lo siguiente que tendrás que realizar es 
pulsar [ `ENTER` ] Para continuar con el siguiente punto que sera seleccionar el servidor donde nos vamos a conectar.

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119162505613283459/207103623-82f57c13-c0c9-486b-b3bc-529ff13e4e3a.png)
 

Con el primer comando tenernos que cambiar el repositorio de Termux al siguiente: 

Mirrors by Tsinghua UniversityHosted on mirrors, tuna.tsinghua.edu.

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119164767609831465/207103874-9ab3eed7-c2c5-47da-89df-1b9e14cc95da.png)


Después darás [ENTER] y continuas con el vídeo ejemplo [parte - 1]

SEGUNDO COMANDO ⬇️
```bash
yes|pkg update && yes|pkg upgrade
```
asi como se muestra a continuación en pantalla tendrás que copiar y pegar en Termux el comando

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119171803810627654/Picsart_23-06-16_00-47-58-067.jpg)


Aquí empieza la [PARTE -2]
* Ejemplo - [COMPILACION ANDROID PARTE 2 ](https://youtu.be/nJFD_KKfXpA) cómo uso los comandos de Termux android
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️
## cuando ejecutes este comando tendrás que darle permitir acceso

TERCER COMANDO ⬇️
```bash
termux-setup-storage
```
COMO SE MUESTRA A CONTINUACIÓN
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119176215811600404/Screenshot_20230616-0057533.png)

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119174738246377542/Picsart_23-06-16_01-00-24-632.jpg)




Con este comando eliminaremos está herramienta que no sirve para nada y nos ocaciona un gran error, para solucionarlo y podamos continuar tendrás que ejecutar este comando a continuación
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

CUARTO COMANDO ⬇️
```bash
pkg remove libglvnd
```
Como se muestra a continuación y presionamos [ `ENTER` ]

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119179813203226624/Picsart_23-06-16_01-20-34-392.jpg)


## Con este comando podrás instalar las herramientas que necesitaremos para compilar nuestro juego[NECESITARAS 1GB] recomendable.
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

 QUINTO COMANDO ⬇️
```bash
pkg install git wget make python getconf zip apksigner clang binutils libglvnd-dev aapt which
```
# Ejemplo a continuación de como se tiene que visualizar una vez copiado y pegado en Termux o escrito manualmente ⬇️⬇️⬇️⬇️⬇️⬇️

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119181665663717406/Picsart_23-06-16_01-28-08-338.jpg)


# si te hace una pregunta como en el video solo responde [ `Y` ]  para continuar enseguida pulsa [ `ENTER` ] para confirmar 
![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119184784543993886/Picsart_23-06-16_01-40-28-221.jpg)

Con este comando clonaras el repositorio de OWOKITTY para poder compilar el juego

⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

SEXTO COMANDO ⬇️
```bash
git clone https://github.com/robertkirkman/sm64ex-coop.git
```

Esto te ayudará a copiar el baserom que te muestro en el video de la parte 2
Tendrás que colocarlo en tu almacenamiento raíz memoria del dispositivo para poder copiarlo de una manera correcta y no haya errores. Si aun no tienes tu `baserom.us.z64`, [Aqui la guía para obtener uno](https://github.com/sanni/cartreader/wiki/What-to-order):

⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

SÉPTIMO COMANDO ⬇️
```bash
cp /storage/emulated/0/baserom.us.z64 sm64ex-coop/baserom.us.z64
```
Aquí entraremos a la carpeta donde están los archivos para la creación del juego
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

OCTAVO COMANDO ⬇️
```bash
cd sm64ex-coop
```
ponemos este comando para actualizar si es necesario el juego y git 

NOVENO COMANDO ⬇️
```bash
git pull
```
Con este comando actualizaremos archivos de coopnet para evitar errores de compilación es necesario de sm64ex coop para jugarlo
Nos ayudará a cargar los archivos de coopnet.
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

DÉCIMO COMANDO ⬇️
```bash
git submodule update --init --recursive
```
Con este comando `make` compilaremos el juego para 32 bits y 64 bits OJO solo poner `make` para compilarlo de lo contrario no funcionará para dispositivos de 32 bits ⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

COMANDO NÚMERO 11⬇️
```bash
make
```

Enhorabuena ya para finalizar ejecuta este comando para sacar el sm64ex coop Android a tu DISPOSITIVO MEMORIA INTERNA

COMANDO 12⬇️
```bash
cp build/us_pc/sm64.us.apk /storage/emulated/0
```

## para salirnos de termux pondremos el siguiente comando 

COMANDO 13⬇️
```bash
exit
```

## una vez terminado si quieres a futuro actualizar sm64ex coop Android no borres termux para que no se te complique y sigue estos pasos para actualizarlo

# PASOS PARA ACTUALIZACIONES DE SM64EX COOP ANDROID 

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

# ahora esperaras y tendras de nuevo tu sm64ex coop Android actualizado, solo deberas poner el siguiente comando para sacarlo de termux, pero antes deberas borrar el antiguo sm64ex coop que tengas para despues poner este comando

```bash
cp build/us_pc/sm64.us.apk /storage/emulated/0
```

`Y procedes a instalarlo nuevamente como la última vez`

## Y LISTO A DISFRUTAR


Gracias a OWOKITTY por el Port a Android y XxCmbRxX Por traerles el tutorial en español

## UNETE A NUESTRA COMUNIDAD ANDROID

* [DISCORD](https://discord.gg/tmTdjhaB)

