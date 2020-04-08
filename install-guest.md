# adecuación de **_Guest_**

	1.	Descargar e instalar [VirtualBox](https://virtualbox.org/wiki/Downloads).

<p align="center">
  <img width="460" src="images/install_guest1.png">
</p>


2.	Abrir VirtualBox, ir a File y seleccionar la opción correspondiente como se muestra a continuación:

<p align="center">
  <img width="460" src="images/install_guest2.png">
</p>

3.	Luego, seleccione el archivo ALSE1.ova y haga click en siguiente.

<p align="center">
  <img width="460" src="images/install_guest3.png">
</p>

4.	Luego, revisar las siguientes opciones, seleccionar la opción para reinicializar las tarjetas de red y click en importar.

<p align="center">
  <img width="460" src="images/install_guest4.png">
</p>

Una vez finalizado el proceso de importación y luego de iniciar la máquina virtual, ingresar las credenciales asignadas

<p align="center">
  <img width="460" src="images/install_guest5.png">
</p>


### Configuración de red.
Para permitir la conectividad a internet desde el **_guest_** y al mismo tiempo permitir la comunicación con el **_host_**.

Ir a la configuración de la _máquina virtual_.

<p align="center">
  <img width="460" src="images/config_guest1.png">
</p>

Seleccionar en la configuración de red la opción NAT para el acceso a internet y luego hacer click en _Port Forwarding_ para configurar la comunicación con el _host_.

<p align="center">
  <img width="460" src="images/config_guest2.png">
</p>

La configuración de la comunicación con el _host_ se establece a través de la dirección IP de _Host IP_. Ver IP.

<p align="center">
  <img width="460" src="images/config_guest3.png">
</p>