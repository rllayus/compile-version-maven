# compile-version-maven
Pasos para compilar un proyecto con versiones

## Comando maven para subir de version 
Este comando cambia la versión de todos los submódulos del proyecto maven, por lo que despues de la ejecución tendrá que ejecutar mvn clean install y actualizar el proyecto o recargar desde disco en su IDE. 

     mvn versions:set -DnewVersion=4.0.4-COLIBRI
     
## Comando para confirmar los cambios
Este comando confirma los cambios y la nueva versión es visible a nivel de los archivos maven

     mvn versions:commit

