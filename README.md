##Trabajo Grupal de Sistemas distribuidos de IIN.
##Proyecto para el Sistema Departamental de Suministros de NIS.

##Colaboradores
Pablo César Bordón Battilana
Maria Soledad Decoud Barrios
Denis Amilcar Giménez
Emanuel Antonio Ayala Ruiz
María Laura Capdevila Castro


##Requerimientos
Como mínimo JDK 1.8 y un IDE que soporte proyectos Java Maven como por ejemplo Netbeans, Eclipse o IntelliJ.

Ubuntu OS

   Actualizar repositorio
    
    sudo apt update
   Instalar el JDK (Java development kit)
    
    sudo apt install default-jdk
   Instalar un IDE de Java (en este ejemplo netbeans)
   
    sudo apt install netbeans


WindowsNT-based OS (Windows 10, Windows 11, etc)
   Usar los instaladores
   
   JDK por Oracle:
   https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html
   
   Netbeans por Apache:
   https://netbeans.apache.org/download/nb120/nb120.html
   
##Estructura de Base de Datos

Se utilizó un array como base de datos, donde se van concatenando y almacenando para poder reutilizarse o tener como registro.

##Como poblar

Para poblar la base de datos lo que se hace es que los datos iniciales cargados automáticamente se almacenan en nuestra estructura (array) designada como base de datos.


 
 ##Compilación y Ejecución
    
#Para el servidor

java -jar ServerNIS/target/ServerNIS-1.0-SNAPSHOT.jar 

#Para el/los clientes

java -jar ClienteNIS/target/ClienteNIS-1.0-SNAPSHOT.jar


