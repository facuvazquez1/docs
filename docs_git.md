# Configuración Inicial de Git

1. Descarga Git en Visual Studio Code (VSC).
2. Abre la terminal y configura tu nombre y correo con estos comandos:

   
   `git config --global user.name "Facundo Vazquez"`
   
   `git config --global user.email "xxxx@gmail.com"`
   

## Creación del Primer Repositorio

1. *Inicializa un repositorio:*  
   `git init`

2. *Añade archivos al área de preparación:*  
   	`git add .`

3. *Crea un commit con una descripción:*  
   `git commit -m "Inicio Proyecto"

4. *Conecta el repositorio local a GitHub:*  
   `git remote add origin URL

5. *Sube los cambios a GitHub:*  
   `git push -u origin main

## Creación y Gestión de Ramas

1. *Crea una nueva rama y cámbiate a ella:*  
   `git checkout -b nombre-de-la-rama

2. *Sube la nueva rama a GitHub:*  
   `git push -u origin nombre-de-la-rama

3. *Cambia de rama:*  
   `git checkout nombre-de-la-rama

4. *Verifica las ramas locales:*  
   `git branch

5. *Verifica las ramas remotas en GitHub:*  
   `git branch -r

## Unificación de Ramas y Envío a GitHub

*Nota: Debes estar en la rama donde quieres hacer la unificación (no siempre tiene que ser en main).*

1. *Cámbiate a la rama de destino:*  
   `git checkout main  
   *(puede ser main u otra rama donde quieras hacer la unificación)*

2. *Une la otra rama a la actual:*  
   `git merge nombre-de-la-rama

Si hay errores o conflictos en el merge, resuélvelos manualmente:

- *Añade y guarda los cambios:*  
  `git add .  
  `git commit -m "Resolviendo conflictos"

3. *Sube los cambios con la unificación realizada:*  
   `git push origin main

## Eliminación de una Rama Fusionada

1. *Elimina la rama de forma local:*  
   `git branch -d nombre-de-la-rama

2. *Elimina la rama de forma remota en GitHub:*  
   `git push origin --delete nombre-de-la-rama
