# APACHE 
# para instalar apache en ubuntu tenemos que hacer lo siguite:
# sudo apt update
# sudo apt install apache2
para tener en cuenta... 
Para detener tu servidor web, digita:
# sudo systemctl stop apache2
Para iniciar tu servidor web, digita:

# sudo systemctl start apache2
Para detener y reiniciar el servicio en un solo paso, puedes ingresar:

# sudo systemctl restart apache2
Si únicamente estás realizando cambios en la configuración, puedes recargar Apache sin necesidad de perder las conexiones que pudieran estar activas. Para ello, usa el comando:

# sudo systemctl reload apache2
Por defecto, Apache se configura para iniciarse automáticamente cuando el servidor arranca. Si no se quiere esto, se puede deshabilitar este comportamiento, ingresando:

# sudo systemctl disable apache2
Para rehabilitar el servicio durante el arranque, digita:

# sudo systemctl enable apache2
Después de ingresar este comando, Apache debería iniciarse automáticamente durante el arranque del servidor.
Para ver el estado es el siguites.
# sudo systemctl status apache2
