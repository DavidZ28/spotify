Manual de Despliegue para un Proyecto Spotify 
Requisitos Previos
- Tener instalado *Node.js* y *npm*. Puedes verificarlo con los siguientes comandos:
  node -v
  npm -v
  
- Tener acceso a un terminal (como Command Prompt, PowerShell, o terminal de Visual Studio Code).
 1. Clonar el Repositorio
Primero, clona el repositorio del proyecto. Por ejemplo, para el *spotify-proyect* 
git clone colocas  http que te de
2. Navegar al Proyecto
Accede al directorio del proyecto:

cd spotify-proyect
 3. Instalar Dependencias
Instala las dependencias necesarias usando *npm*:
pm install

Si encuentras conflictos de dependencias, puedes intentar instalar usando:
npm install --legacy-peer-deps

Si el problema persiste, puedes forzar la instalación de las dependencias utilizando:

npm install --force


4. Ejecutar el Proyecto en Desarrollo
Para iniciar el servidor de desarrollo, utiliza el siguiente comando:
npm run dev

5. Verificación del Despliegue
Accede a tu dominio o dirección URL donde has desplegado la aplicación para asegurarte de que todo funcione correctamente.
