## Recuerda instalar [ Termux de F-droid ] para seguir este proceso ` la app de termux de play store no sirve` 

# aqui enlace de descarga para hacer el tutorial

Descarga este termux dando click en el enlace ⬇️

https://f-droid.org/repo/com.termux_118.apk
______________________________________________

* Ejemplo - [COMPILACION ANDROID PARTE 1 ](https://youtu.be/qPx6AOsRWNw)

* Video Tutorial dando click en la siguiente imagen.
[![link](https://cdn.discordapp.com/attachments/1118222325054181457/1119422417941569557/Picsart_23-06-16_17-24-30-978.png)](https://youtu.be/qPx6AOsRWNw "[TUTORIAL] Compilar (descargar) La nueva actualización para sm64ex-coop Android Parte 1 ")

__________________________________________________
## COMO OBTENER SM64EX-COOP ANDROID DESDE  CERO   👀
__________________________________________________

* REQUISITOS:
* Termux de [`f-droid`]
* 1GB de almacenamiento disponible
* Tu juego Original Versión USA sin modificaciones (Tiene que ser la auténtica)
* Administrador de archivos Zarchiver enlace de descarga aqui abajo
______________________________________________
[Click aqui para descargar ](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver)
______________________________________________


PRIMER COMANDO ⬇️

```bash
termux-change-repo
```
te aparecera un recuadro como este a continuación, lo siguiente que tendrás que realizar es 
pulsar [ `ENTER` ] Para continuar con el siguiente punto que sera seleccionar el servidor donde nos vamos a conectar.

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119162505613283459/207103623-82f57c13-c0c9-486b-b3bc-529ff13e4e3a.png)
 
__________________________________________________
Con el primer comando tenernos que cambiar el repositorio de Termux al siguiente: 

`Mirrors by Tsinghua UniversityHosted on mirrors, tuna.tsinghua.edu.`
__________________________________________________
![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119164767609831465/207103874-9ab3eed7-c2c5-47da-89df-1b9e14cc95da.png)

__________________________________________________
Después darás [ENTER] y continuas con el vídeo ejemplo [parte - 1]

SEGUNDO COMANDO ⬇️
__________________________________________________
```bash
yes|pkg update && yes|pkg upgrade
```
__________________________________________________
asi como se muestra a continuación en pantalla tendrás que copiar y pegar en Termux el comando
__________________________________________________
![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119171803810627654/Picsart_23-06-16_00-47-58-067.jpg)

__________________________________________________
Aquí empieza la [PARTE -2]
* Ejemplo - [COMPILACION ANDROID PARTE 2 ](https://youtu.be/nJFD_KKfXpA) cómo uso los comandos de Termux android
__________________________________________________
Video Tutorial:
__________________________________________________
[![link](https://cdn.discordapp.com/attachments/1118222325054181457/1119418201500024832/Picsart_23-06-16_17-06-20-319.jpg)](https://youtu.be/nJFD_KKfXpA "[TUTORIAL] Compilar (descargar) La nueva actualización para sm64ex-coop Android ")

__________________________________________________
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️
## cuando ejecutes este comando tendrás que darle permitir acceso

TERCER COMANDO ⬇️
__________________________________________________
```bash
termux-setup-storage
```
__________________________________________________
COMO SE MUESTRA A CONTINUACIÓN
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️
__________________________________________________

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119176215811600404/Screenshot_20230616-0057533.png)

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119174738246377542/Picsart_23-06-16_01-00-24-632.jpg)


__________________________________________________
Con este comando eliminaremos está herramienta que no sirve para nada y nos ocaciona un gran error, para solucionarlo y podamos continuar tendrás que ejecutar este comando a continuación
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

CUARTO COMANDO ⬇️
__________________________________________________

```bash
pkg remove libglvnd
```
__________________________________________________
Como se muestra a continuación y presionamos [ `ENTER` ]
__________________________________________________

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119179813203226624/Picsart_23-06-16_01-20-34-392.jpg)

__________________________________________________
## Con este comando podrás instalar las herramientas que necesitaremos para compilar nuestro juego [NECESITARAS 1GB Disponible].
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

 QUINTO COMANDO ⬇️
 __________________________________________________
 
```bash
pkg install git wget make python getconf zip apksigner clang binutils libglvnd-dev aapt which
```
__________________________________________________
# Ejemplo a continuación de como se tiene que visualizar una vez copiado y pegado en Termux o escrito manualmente ⬇️⬇️⬇️⬇️⬇️⬇️
__________________________________________________

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119181665663717406/Picsart_23-06-16_01-28-08-338.jpg)


__________________________________________________
# si te hace una pregunta como en el video solo responde [ `Y` ]  para continuar enseguida pulsa [ `ENTER` ] para confirmar 
__________________________________________________
![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119184784543993886/Picsart_23-06-16_01-40-28-221.jpg)

__________________________________________________
Con este comando clonaras el repositorio de OWOKITTY para poder compilar el juego

⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

SEXTO COMANDO ⬇️
__________________________________________________

```bash
git clone https://github.com/robertkirkman/sm64ex-coop.git
```
__________________________________________________
Esto te ayudará a copiar el baserom que te muestro en el video de la parte 2
Tendrás que colocarlo en tu almacenamiento raíz memoria del dispositivo para poder copiarlo de una manera correcta y no haya errores. Si aun no tienes tu `baserom.us.z64`, [Aqui la guía para obtener uno](https://github.com/sanni/cartreader/wiki/What-to-order):

 PERO ANTES DE PONER EL COMANDO QUE VERÁS A CONTINUACIÓN TENDRÁS QUE COLOCAR EN ESTA RUTA TU `baserom.us.z64` EN TU MEMORIA `storage/emulated/0` de tu dispositivo
__________________________________________________

* EJEMPLO A CONTINUACIÓN 

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119411623724056699/Picsart_23-06-16_16-40-48-619.jpg)

__________________________________________________
AHORA SI PROCEDEREMOS A PONER EL SÉPTIMO COMANDO EN NUESTRO TERMUX

⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

SÉPTIMO COMANDO ⬇️
__________________________________________________

```bash
cp /storage/emulated/0/baserom.us.z64 sm64ex-coop/baserom.us.z64
```
__________________________________________________
Aquí entraremos a la carpeta donde están los archivos para la creación del juego
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

OCTAVO COMANDO ⬇️
__________________________________________________

```bash
cd sm64ex-coop
```
__________________________________________________
ponemos este comando para actualizar si es necesario el juego y git 

NOVENO COMANDO ⬇️
__________________________________________________

```bash
git pull
```
__________________________________________________
Con este comando actualizaremos archivos de coopnet para evitar errores de compilación es necesario de sm64ex coop para jugarlo
Nos ayudará a cargar los archivos de coopnet.
⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

DÉCIMO COMANDO ⬇️
__________________________________________________

```bash
git submodule update --init --recursive
```
__________________________________________________
Con este comando `make` compilaremos el juego para 32 bits y 64 bits OJO solo poner `make` para compilarlo de lo contrario no funcionará para dispositivos de 32 bits ⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

COMANDO NÚMERO 11⬇️
__________________________________________________

```bash
make
```
__________________________________________________
Enhorabuena ya para finalizar ejecuta este comando para sacar el sm64ex coop Android a tu DISPOSITIVO MEMORIA INTERNA

COMANDO 12⬇️
__________________________________________________

```bash
cp build/us_pc/sm64.us.apk /storage/emulated/0
```
__________________________________________________

## para salirnos de termux pondremos el siguiente comando 

COMANDO 13⬇️
__________________________________________________

```bash
exit
```
__________________________________________________
## una vez terminado si quieres a futuro actualizar sm64ex coop Android no borres termux para que no se te complique y sigue estos pasos para actualizarlo

# PASOS PARA ACTUALIZACIONES DE SM64EX COOP ANDROID 

entrar a termux y escribir el siguiente comando
__________________________________________________

```bash
yes|pkg update && yes|pkg upgrade
```
__________________________________________________
Después pondras esto a continuación para entrar a la carpeta 
__________________________________________________
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
__________________________________________________
# ahora esperaras y tendras de nuevo tu sm64ex coop Android actualizado, solo deberas poner el siguiente comando para sacarlo de termux, pero antes deberas borrar el antiguo sm64ex coop que tengas para despues poner este comando
__________________________________________________

```bash
cp build/us_pc/sm64.us.apk /storage/emulated/0
```
__________________________________________________
`Y procedes a instalarlo nuevamente como la última vez`

## Y LISTO A DISFRUTAR


Gracias a OWOKITTY por el Port a Android y XxCmbRxX Por traerles el tutorial en español

## UNETE A NUESTRA COMUNIDAD ANDROID
__________________________________________________

* [DISCORD](https://discord.gg/tmTdjhaB)

