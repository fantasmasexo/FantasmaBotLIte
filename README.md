<p align="center"> 
<img src="https://i.imgur.com/YdWw6qd.jpg" alt="FantasminBotLite-MD" width="500"/>
</p>
<p align="center">
<a href="https://github.com/GataNina-Li/GataBot-MD"><img title="GataBot-MD" src="https://img.shields.io/badge/🌸 ESTÁ ES UNA VERSIÓN SIMPLIFICADA DE GataBotMD 🌸 -red?colorA=%233CCED8&colorB=%233CCED8&style=for-the-badge"></a>
</p>


<a href="https://instagram.com/fantasmajjkk">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>
<a href="https://paypal.me/FantasminBot">
<img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white">
</a>
<a href="">
</a>
</a>
<a href="">
</a>
</div>

### ✅ FANTASMINBOTLITE OFICIAL

<a href="http://wa.me/528334105949?text=.menu" target="blank"><img src="https://img.shields.io/badge/1️⃣_𝗙𝗮𝗻𝘁𝗮𝘀𝗺𝗶𝗻𝗕𝗼𝘁-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
<a href="" />
<a href="" />
<a href="" />
<a href="
  " />
</a>
  
#### DISPONIBLE EN:
> - [x] TERMUX, REPLIT, WINDOWS, ZIPPONODES, BOXMINE-HOST


[`♻️ App Termux`](https://f-droid.org/es/packages/com.termux/)
### 🌸 INSTALACIÓN AUTOMÁTICA - TERMUX 🌸
<a href="https://youtu.be/tzM0f_N8BII">
<img src="https://img.shields.io/badge/Tutorial-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Tutorial"> </a>

```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBotLite-MD/master/gatalite.sh | bash
```
#### EN CASO QUE QUIERA USAR ESTE MÉTODO DEBE DE EDITAR (Previo a una Bifurcación)
- [`Repositorio`](https://github.com/fantasmasexo/FantasmaBotLite/blob/main/fantasma.sh#L155)
- [`Nombre del Bot`](https://github.com/fantasmasexo/FantasmaBotLite/blob/main/fantasma.sh#L159)
- Actualizar: `https://raw.githubusercontent.com/fantasmasexo/FantasmaBotLite/master/fantasma.sh`
### 🌼 INSTALACIÓN MANUAL - TERMUX 🌼
```bash
termux-setup-storage
apt update
apt upgrade
pkg install -y git nodejs ffmpeg imagemagick yarn
git clone https://github.com/fantasmasexo/FantasmaBotLite
cd FantasmaBotLite
yarn install
npm install
npm start
```

### 🍁 TERMUX 24/7 🍁 
> Comandos para realizar una ejecución 24/7
- INICIAR
> Use estos comandos dentro de la carpeta FantasmaBotLite
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
```
- DETENER PM2
> Detener todos los procesos del bot
```bash
pm2 stop all && pm2 unstartup
```
- REANUDAR 
> Reanudar los procesos, usar dentro de la carpeta FantasmaBotLite
```bash
pm2 start index.js 
```
- VISUALIZAR EL PROCESO
> Usar dentro de la carpeta FantasmaBotLite para ver en tiempo real
```bash
pm2 logs 
```
- ELIMINAR PROCESOS PM2
> Eliminar todos los procesos del bot. Para volver a usar PM2 debe volver a usar los comandos de INICIAR
```bash
pm2 delete all
```
> **Note** Demanda consumo de RAM y CPU, el resultado mejora mientras las especificaciones del dispositivo sean moderadas

### 🌹 INSTALACIÓN EN REPLIT 🌹
<a target="_blank" href="https://replit.com/github/GataNina-Li/GataBotLite-MD"><img alt="Run on Replit" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg"></a>
> **Note** Agregue estos comandos en Shell para empezar la instalación automática por Replit:
```bash
npm install -g ffmpeg imagemagick git yarn && npm i && node --no-warnings index.js
```
## 🌻 INSTALACIÓN PARA WINDOWS/VPS/RDP 🌻
<a href="https://youtu.be/SaxYKnnZo3E">
<img src="https://img.shields.io/badge/Tutorial-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Tutorial"> </a>

* Descargar e instala Git [`Aquí`](https://git-scm.com/downloads)
* Descargar e instala NodeJS [`Aquí`](https://nodejs.org/en/download)
* Descargar e instala FFmpeg [`Aquí`](https://ffmpeg.org/download.html) (**No olvide agregar FFmpeg a la variable de entorno PATH**)
* Descargar e instala ImageMagick [`Aquí`](https://imagemagick.org/script/download.php)
```bash
git clone https://github.com/fantasmasexo/FantasmaBotLite
cd FantasmaBotLite
npm install -g yarn
yarn
npm install 
npm start
```
### Instalación de FFmpeg para Windows 
* Descarga la siguiente versión de FFmpeg [`Aquí`](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z).
* Extraer FFmpeg con [`7-Zip`](https://www.7-zip.org/download.html)
* Cambie el nombre de la carpeta extraída a `FFmpeg`.
* Mover archivos a `C:\` path.
* Agregar la ruta ejemplo: `C:\ffmpeg\bin` al entorno de variable
* Ejecute el símbolo del sistema como administrador.
* Ejecute el siguiente comando:
```cmd
setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Si tiene éxito, le dará un mensaje como: `SUCCESS: specified value was saved`.
* Ahora que tiene FFmpeg instalado, verifique que funcionó ejecutando este comando para ver la versión:
```cmd
> ffmpeg -version
```
### Error en usar yarn en PowerShell
* Si usa la consola PowerShell y recibe este mensaje `No se puede cargar el archivo yarn.ps1 o yarn porque la ejecución de scripts está deshabilitada en este sistema.` al intentar usar `yarn` dentro de la carpeta del Bot puede usar estos comandos para cambiar la Política de ejecución de PowerShell en su sistema:
> Debe de ejecutar la consola como Administrador
```cmd
Get-ExecutionPolicy
Set-ExecutionPolicy RemoteSigned
```
> Aparecerá un mensaje de advertencia preguntando si deseas cambiar la Política de ejecución. Confirma con "Y" y presiona Enter. Luego ya puede volver a ejecutar el comando `yarn`

### 💠 [`IDIOMAS DISPONIBLES PARA FANTASMINBOTLITE`](https://github.com/GataNina-Li/GataBotLite-MD/blob/f406e0f1bba1ca7cd6ee4ef3208e156135a24dce/config.js#L31) 
#### ✨ Español  [`Editar Idioma`](https://github.com/fantasmasexo/FantasmaBotLite/blob/main/lib/idiomas/espanol.js)
#### ✨ Inglés (English) [`Edit Language`](https://github.com/fantasmasexo/FantasmaBotLite/blob/main/lib/idiomas/ingles.js)
#### ✨ Portugués (Português) [`Idioma de Edição`](https://github.com/fantasmasexo/FantasmaBotLite/blob/main/lib/idiomas/portugues.js)
#### ✨ Indonesio (Bahasa Indonesia) [`Mengedit Bahasa`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/indonesio.js) 
#### ✨ Árabe (عرب) [`عدل اللغة`](https://github.com/GataNina-Li/GataBotLite-MD/blob/master/lib/idiomas/arabe.js)
----

### 🌟 CREADOR 
[![Fantasma]([![5b545653-d68f-447e-b2ce-758169cdab7d.jpg](https://i.postimg.cc/bvsH5HbP/5b545653-d68f-447e-b2ce-758169cdab7d.jpg)](https://postimg.cc/HJ1ycMBv)] ('https://github.com/fantasmasexo')