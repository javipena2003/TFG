# Breve guía preparación repositorio
Documentos y códigos sobre mi TFG

## Paso 0
Instalar git: https://git-scm.com/install/windows
Extensiones recomendadas (completar): pylance   git Graph


## Clonar repositorio
cd C:\Users\Javier %Ruta a la carpeta
git clone https://github.com/tu-usuario/nombre-del-repo.git

## Flujo día a día
_1. Descargar los últimos cambios (importante si usas varios ordenadores)_
git pull

_2. ... trabajas, editas archivos ..._

_3. Ver qué archivos has cambiado_
git status

_4. Añadir los cambios que quieres guardar_
git add .          # el punto significa "todo"

_5. Hacer un "commit" (guardar con mensaje descriptivo)_
git commit -m "Descripción de lo que hice"

_6. Subir los cambios a GitHub_
git push


## Subir los archivos en local que ya tenía antes de crear el repositorio
_1. Clonar repositorio:_ cd...    git clone...
_2. Mover archivos a la nueva carpeta_
