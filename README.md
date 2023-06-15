```bash
termux-change-repo
```

Con el primer comando tenernos que cambiar el repositorio de Termux al siguiente: 

Mirrors by Tsinghua UniversityHosted on mirrors, tuna.tsinghua.edu.

Después darás [ENTER] y continuas con el vídeo ejemplo [parte - 1]

```bash
yes|pkg update && yes|pkg upgrade
```


Aquí empieza la [PARTE -2]
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
 si te hace una pregunta como en el video solo responde `Y` y das enter para continuar porqie este comando de abajo te hara una pregunta 

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

YA NOMAS QUEDARA INSTALAR EL JUEGO Y LISTO A DISFRUTAR


Gracias a OWOKITTY por el Port a Android y XxCmbRxX Por traerles el tutorial en español
