# Paquete DEB vx-dga-l-visor-imagenes-predeterminado

Paquete encargado de configurar un visor de imagenes predeterminado para los usuarios de Lubuntu/Vitalinux diferente del que trae por defecto el sistema.  La razón del cambio es dar la opción de imprimir la imagen desde el propio Visor, ya que el que viene por defecto no lo permite.

# Usuarios Destinatarios

Cualquier usuarios de Vitalinux

# Aspectos Interesantes:
```
Ninguno
```
# Como Crear el paquete DEB a partir del codigo de GitHub
Para crear el paquete DEB será necesario encontrarse dentro del directorio donde localizan los directorios que componen el paquete.  Una vez allí, se ejecutará el siguiente comando (es necesario tener instalados los paquetes apt-get install debhelper devscripts):

```
apt-get install debhelper devscripts
/usr/bin/debuild --no-tgz-check -us -uc
```

# Como Instalar el paquete generado vx-dga-l-*.deb:
Para la instalación de paquetes que estan en el equipo local puede hacerse uso de ***dpkg*** o de ***gdebi***, siendo este último el más aconsejado para que se instalen también las dependencias correspondientes.
```
gdebi vx-dga-l-*.deb
```
