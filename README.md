# Instalaci-n-de-nginx-con-PHP
Realiza la configuración básica de nginx que ejecute scripts PHP creando una receta ansible. Utilizando como base la receta ansible que utilizaste para el taller 4, modifícala para añadir las siguientes funcionalidades:

    Instalación de los servicios (cada servicio se instalará y configurará en un rol diferenciado).
    Además de copiar un index.html en el DocumentRoot, copiará también un fichero info.php que muestre la información de la configuración de PHP.
    Como hace la receta original, creará virtualhost que tengas definido en una lista. Estos virtual host estarán configurados para ejecutar PHP.
    La receta debe poder desactivar los virtualhost que tengas definido en otra lista.

Configura sobre una máquina virtual, usando la receta de ansible, un servidor nginx + PHP con dos virtualhost:

    www.pagina1.org, cuyo DocumetRoot estará en /srv/www/pagina1.
    www.pagina2.org, cuyo DocumetRoot estará en /srv/www/pagina2.
