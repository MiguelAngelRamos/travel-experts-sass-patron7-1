## Documentación
### Comando para inicializar un proyecto de node

#### Inicializar un proyecto de Node.js (crear el package.json)
  
  ```sh
  npm init -y
  ```
## El proyecto cuenta con las siguientes dependencias

Instalar sass

 ```sh
 npm install sass
 ```

 ## Configurar el package.json
 
 ```json
  {
    "name": "aplicando-patron-7-1",
    "version": "1.0.0",
    "description": "1. Inicializar un proyecto de Node.js (crear el package.json)",
    "main": "index.js",
    "scripts": {
      "start": "sass --watch scss:css"
    },
    "keywords": [],
    "author": "Miguel Ramos",
    "license": "MIT",
    "dependencies": {
      "sass": "^1.72.0"
    }
  }
 ```

## En caso que quieres descargar el proyecto de Github, puedes reconstruir la carpeta node_modules con el comando

```sh
  npm install
```


