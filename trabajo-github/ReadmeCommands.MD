Comandos de Git mas utilizados, tambien se encuentran en PDF

|Crear|
|-------------|
|Clonar un repositorio existente|
|$ git clone ssh://usuario@domain.com/repo.git |
|Crear un nuevo repositorio local|
|$ git init |
|Crear un nueva rama|
|$ git branch "branch-name" |
|Subir rama a repositorio remoto|
|$ git push -u remote "branch-name" |



|Branch|
|-------------|
|listar ramas existente|
|$ git branch or git branch --list |
|eliminar rama|
|$ git branch -d "branch-name" |
|cambiar a otra rama|
|$ git checkout "name-of-your-branch"|
|crear a otra rama y cambiar a esta|
|$ git checkout -b "name-of-your-branch"|


|adicionar cambios|
|-------------|
|adicionar cambios por archivo|
|$ git add "file" |
|adicionar todos cambios de la direccion donde se encuentra|
|$ git add . |
|adicionar todos los cmabios realizados|
|$ git add ALL |


|actualizar repositorio|
|-------------|
|actualizar cambios en remoto|
|$ git push "remote" "branch-name" |
|actualizar cambios en remoto de rama recien creada|
|$ git push -u origin "branch_name" |
|actualizar cambio en local|
|$ git pull "remote" |
|Realizar merge entre ramas|
|$ git merge "branch-name" |
