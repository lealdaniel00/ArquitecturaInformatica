# ArquitecturaInformatica
# Maestría en ciencias de la Información y las Comunicaciones

Informática Gr:195-2 <br>
Periodo académico: 2020-3 <br>
Integrante: 
<ol>
<li>Daniel David Leal Lara - 20202495012</li>
</ol>

# Instalación y Despliegue
Es necesario tener instalado docker, por lo tanto si no lo tiene instalado dentro de su maquina y usa ubuntu, es recomendable seguir las siguientes instrucciones: </br>
https://docs.docker.com/install/linux/docker-ce/ubuntu/ </br>
Adicionalmente en necesario contar tambien con docker-compose, si no lo tiene instalado, siga el siguiente tutorial. </br>
https://docs.docker.com/compose/install/ </br>
</br>
</br>
Para ejecutar la aplicación dockerizada es necesario seguir los siguientes pasos dentro de la terminal:
<ol>
  <li> Si tiene el proyecto en su maquina, acceda a la ubicacion del mismo por medio del comando CD, de lo contrario clonelo usando <b> sudo git clone https://github.com/lealdaniel00/GestionTecnologicaDocker.git </b> </li>
  <li> Acceda al la ubicacion del proyecto clonado por medio de <b>cd</b> </li>
  <li> Correr el proyecto usando <b>docker-compose up --build</b> </li>
  <li> desde el navegador acceda a la siguiente direccion </li>
  <li> http://0.0.0.0:5000/ </li>
  <li> podra <b>agregar, eliminar, actualizar y leer</b> los registros que cree </li>
</ol>

Codigo basado de: </br>
https://www.ibm.com/developerworks/community/blogs/2f9ef931-1ac3-4d9b-a8ca-6e3f01b13889/entry/Containarize_a_Python_Flask_web_application_with_MySQL_using_Docker_Compose?lang=en
