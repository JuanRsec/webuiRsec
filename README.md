# webuiRsec
OpenWebUi Rsec
# Instalación de Ollama Web UI

Una vez que hayas instalado estas herramientas, puedes proceder con el resto de los pasos de instalación según se describe en el tutorial.
(Git (https://git-scm.com/downloads)
Node.js y npm (o Bun) (https://nodejs.org/en/learn/getting-started/how-to-install-nodejs))

##Instalación:
 1. Clonar repositorio:
    git clone https://github.com/ollama-webui/ollama-webui.git
    
 3. Navegar al directorio del proyecto:
    cd ollama-webui/
    
 4. Copiar el archivo del entorno:
    cp -RPp example.env .env
    
 5. Compilar el front end
    npm i
    npm run build
    
      a) Utilizando BUN
         bun install
         bun run build
    
 6. Iniciar el backend
    cd ./backend
    pip install -r requirements.txt -U
    sh http://start.sh

 7. Acceder a la interfaz
    Abra http://localhost:8080/ en su navegador web.

    
 
