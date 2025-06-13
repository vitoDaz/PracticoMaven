      ###Descripción del Proyecto.
      
Se generaron prueba unitarias con Junit Se generaron gestión de dependencias con Maven Se agregaron una dependencia externa. Se Modificó una clase principal.


      ###Comandos usados con Maven.

Se generó instalación: mvn -v
Se creo proyecto: mvn archetype:generate -DgroupId=com.equipo.taskmaster -DartifactId=taskmaster DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
Se Ejecutó pruebas mvn test
Limpiar y empaquetar mvn clean package
Se Ejecutó aplicación mvn exec:java
Se Ejecutó con perfil mvn exec:java -Pdev -Denv.name=Dev

     ###¿Qué aprendiste sobre el ciclo de vida de Maven?

Aprendimos ciclo de vida de Maven está compuesto por fases bien definidas como validate, compile, test, package, verify, install y deploy, que automatizan y estandarizan el proceso de construcción del software. Al usar estos comandos, Maven se encarga de cada paso, desde compilar el código hasta empaquetarlo y distribuirlo, lo que facilita el control del flujo de trabajo y reduce errores manuales.

     ###¿Cómo facilita Maven el trabajo en equipo y la reproducibilidad?

Maven permite que todos los miembros del equipo trabajen con la misma configuración del proyecto a través del archivo pom.xml. Este archivo centraliza la gestión de dependencias, plugins y configuraciones del build. Así, cualquier desarrollador puede clonar el proyecto y construirlo exactamente igual que los demás, sin importar el entorno local, lo que garantiza reproducibilidad y coherencia en el desarrollo colaborativo.

     ###¿Cuál fue el mayor reto al trabajar con dependencias?

El mayor reto fue gestionar los conflictos de versiones entre diferentes librerías. A veces, una dependencia requería una versión específica de otra librería que entraba en conflicto con otra ya usada en el proyecto. Resolver estos conflictos requería entender la jerarquía de dependencias y, en algunos casos, forzar versiones específicas en el pom.xml.

     ###¿Por qué crees que Maven es tan usado en entornos empresariales?

Porque ofrece una forma estandarizada y automatizada de construir, probar y empaquetar aplicaciones Java. Su capacidad de gestionar dependencias de manera centralizada, integrarse con herramientas de integración continua y garantizar builds reproducibles lo hace ideal para equipos grandes y proyectos complejos. Además, su amplia adopción significa que tiene buena documentación, soporte de comunidad y compatibilidad con muchos entornos empresariales.

     ###¿Qué harías diferente si tuvieras que automatizar otro proyecto?

Intentaría aplicar una estructura modular desde el inicio si el proyecto lo permite, separando en módulos como core, interfaz y pruebas, lo que facilita el mantenimiento. También documentaría más claramente las versiones de dependencias y configuraría perfiles de Maven (profiles) para distintos entornos (desarrollo, testing, producción). Por último, integraría herramientas de análisis de calidad de código (como Checkstyle o SonarQube) en el ciclo de build para mejorar la calidad del software.

Dependencias y plugins utilizados.

Integrantes: Ingrid Oñate - Victor Diaz - Gabriel Balbontín
