# Instalar Node.js en Visual Studio Code mediante la Terminal de Git

**Nota:** Durante la instalación, asegúrate de que esté seleccionada la opción NPM (Node Package Manager).

## Verificar que Node.js se ha instalado correctamente
`node -v`

## Verificar que NPM se ha instalado correctamente
`npm -v`

**REVISAR:** Extensión "Node.js Extension Pack"

# Crear un Proyecto con Node.js

1. Abre la terminal de Bash y navega a la carpeta donde deseas iniciar el proyecto.

### Ejecuta y crea un archivo `package.json` 
`npm init` o `npm init -y`

*Nota: con opción `-y` se completa la informacion de las dependecias de forma automatica sin configurarlas de manera*

# Instalar Paquetes o Dependencias en NPM de Node.js

## Instala el paquete o dependencia especificado
`npm install nombre-del-paquete`

# Instalar SASS con NPM de Node.js

**Nota:** Antes de instalar SASS, es necesario haber iniciado Node.js en tu proyecto, lo cual creará el archivo `package.json`.

## Instalar SASS
`npm install sass`

## Mostrar la versión de SASS instalada
`npx sass --version`

## Compilar tu archivo `styles.scss` en un archivo `styles.css`
`npx sass styles.scss styles.css`

## Habilitar la compilación automática cada vez que guardes cambios en tu archivo SASS (en carpetas separadas)
`npx sass --watch styles.scss:styles.css`

## Compilar todo en un solo archivo CSS
`npx sass --watch scss:css`
