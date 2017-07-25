# projectMaven
mi primer proyecto con maven

crear un proyecto con maven:
1. crear el proyecto desde la terminal
mvn archetype:generate -DgroupId=com.maven -DartifactId=testMaven -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false

--> -DgroupId:nombre del paquete
--> -DartifactId:nombreDelProyecto
--> -DarchetypeArtifactId=maven-archetype-webapp :::Indica que el proyecto es tipo web
--> -DinteractiveMode=false ::: evita las preguntas y utiliza todo por defecto

2. generar el proyecto para eclipse
mvn eclipse:eclipse -Dwtpversion=2.0

