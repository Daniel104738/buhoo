Requisitos previos

Un sistema operativo compatible: Windows, macOS o Linux.
Un editor de código como Visual Studio Code, Sublime Text o Atom.
Git instalado en tu sistema.

Paso 1: Instalar Node.js

Descarga el instalador de Node.js desde la página oficial: https://nodejs.org/en/download/
Ejecuta el instalador y sigue las instrucciones en pantalla.
Verifica que Node.js se ha instalado correctamente ejecutando el siguiente comando en tu terminal:
node -v
Deberías ver una versión de Node.js superior a la 8.

Paso 2: Instalar NPM

NPM (Node Package Manager) viene incluido con Node.js. Puedes verificar que está instalado correctamente ejecutando el siguiente comando en tu terminal:

npm -v
Deberías ver una versión de NPM.

Paso 3: Instalar Docusaurus

Crea un nuevo directorio para tu proyecto Docusaurus.
Accede al directorio y ejecuta el siguiente comando para instalar Docusaurus globalmente:
npm install --global docusaurus-cli
Crea un nuevo proyecto Docusaurus ejecutando el siguiente comando:
npx docusaurus create my-docusaurus-project
Accede al directorio del proyecto y ejecuta el siguiente comando para iniciar el servidor de desarrollo:
npm start
Abre tu navegador web y ve a la dirección http://localhost:3000. Deberías ver la página de inicio de tu sitio web Docusaurus.

paso 4: cambiar logo

Dentro del archivo "docusaurus.confij.js" en la lina 66 se encuentra la url de la imagen del logo, solo hace falta cambar el enlace por otra imagen

![image](https://github.com/Daniel104738/buhoo/assets/157811587/72f4c234-50b8-4b12-a80a-99755f34f5de)



