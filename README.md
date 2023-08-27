## Recuerda instalar [ Termux de F-droid ] para seguir este proceso ` la app de termux de play store no sirve` 

https://github.com/XxCmbRxX/Test/assets/125222572/4ff18d5d-04a9-45c0-8833-43e0f7152f43

https://github.com/XxCmbRxX/sm64ex-coop-32-64-Bits/assets/125222572/5d498f00-fb8f-4096-a1b9-62c756419208


# aqui enlace de descarga para hacer el tutorial

Descarga este TERMUX dando click en el enlace de abajo ⬇️

https://f-droid.org/repo/com.termux_118.apk
______________________________________________
## [`Si ya habias descargado termux anteriormente y habias tenido errores, borralo e instalalo de nuevo desde el enlace de aqui arriba 👆👆 y vuelve a instalarlo y haz el proceso desde cero`]
______________________________________________

* Ejemplo - [COMPILACION ANDROID PARTE 1 ](https://youtu.be/qPx6AOsRWNw)

* Video Tutorial dando click en la siguiente imagen.
[![link](https://cdn.discordapp.com/attachments/1118222325054181457/1119422417941569557/Picsart_23-06-16_17-24-30-978.png)](https://youtu.be/qPx6AOsRWNw "[TUTORIAL] Compilar (descargar) La nueva actualización para sm64ex-coop Android Parte 1 ")

__________________________________________________
## COMO OBTENER SM64EX-COOP ANDROID DESDE  CERO   👀
__________________________________________________

# REQUISITOS:
* 1- Termux de [`f-droid`]
* 2- 1GB de almacenamiento disponible
* 3- Tu juego Original Versión USA sin modificaciones (Tiene que ser la auténtica y la que termina en ` .z64 ` la que termina en ` .n64 ` no te servira)
* 4- WI-FI en todo momento (Para las descargas de herramientas y repositorio)
* 5- Administrador de archivos Zarchiver enlace de descarga aqui abajo
______________________________________________
[Click aqui para descargar ](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver)
______________________________________________
`CUANDO EJECUTES UN COMANDO Y TERMUX ESTE REALIZANDO UN PROCESO NO DEBERÁS SALIRTE DE TERMUX, ASEGURATE DE TENER LA SUFICIENTE BATERIA PARA QUE NO SE TE APAGUE EN EL PROCESO Y TAMPOCO DEJES QUE EL TELÉFONO BLOQUEE LA PANTALLA, ESPERA A QUE TERMINE LOS PROCESO PARA PODER CONTINUAR CON LAS INSTRUCCIONES`
# NOTA:
* Una vez que obtengas tu Juego Version USA sin modificaciones tendras que moverla y cambiarle el nombre como verás a continuación ⬇️

## EJEMPLO
* TENDRÁS QUE COLOCAR EN ESTA RUTA TU `baserom.us.z64` EN TU MEMORIA `storage/emulated/0` de tu dispositivo. RECUERDA SOLO SE CAMBIA LA PRIMERA PARTE... el formato no se debe cambiar asi que ` no intentes cambiar tu room si termina en .n64 a .z64 ` se cambia el nombre antes del .z64 ya que si intentas cambiarlo de .n64 a .z64 romperas el room y no funcionara el proceso 

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119411623724056699/Picsart_23-06-16_16-40-48-619.jpg)


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

__________________________________________________
PROCEDEREMOS A PONER EL SÉPTIMO COMANDO EN NUESTRO TERMUX

⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️⬇️

SÉPTIMO COMANDO ⬇️
__________________________________________________

```bash
cp /storage/emulated/0/baserom.us.z64 sm64ex-coop/baserom.us.z64
```
__________________________________________________

# RECORDATORIO
## Si no tienes tu juego original versión USA renombrado a `baserom.us.z64` y puesto en la siguiente ruta, tendras un error y no te va a funcionar el [`SÉPTIMO COMANDO`] 

![image](https://cdn.discordapp.com/attachments/1118222325054181457/1119411623724056699/Picsart_23-06-16_16-40-48-619.jpg)


______________________________________________

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
make distclean
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

