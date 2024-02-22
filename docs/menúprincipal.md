# Este sitio web está creado por Juan José Guirado Mañas.

## Introducción.

Aquí podemos encontrar información sobre como crear una arquitectura de forma automática en aws, empleando terraform, construyendo instancias de forma automática sin necesidad de hacerlo a mano, también, se ha establecido un post el cual instala prestashop con bitnami.

## ¿Qué se pretende?
Se busca automatizar una creación de instancias y un proceso de instalación de prestashop a traves de docker, empleando la imagen oficial de bitnami.

## ¿Que se ha hecho?
Se ha automatizado, los dos procesos, desde la automatización de la creación de las instancias de aws, y la creación de los contenedores de bitnami/prestashop para la supuesta automatización de la creación de bitnami.

## ¿Qué se ha conseguido?
Se ha conseguido que la ejecución de los scripts y creación de docker funcionen eficientemente, además de que prestashop dispone de un certificado firmado por una autoridad certificadora de confianza.

La autoridad certificadora de confianza usada es no ip.

En caso de que quieran crear un dominio de forma gratuita recomiendo visitar --> [Enlace a no-ip](https://www.noip.com/es-MX/login)

Otros enlaces interesantes.



Documentación de terraform para instalación --></li> [Terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli) 

Documentación de no-ip --> [No-ip](https://www.noip.com/support/knowledgebase/getting-started-video-tutorial-how-to-configure-a-free-dns-account)

Documentación de bitnami-prestashop --> [Instalación de Prestashop con bitnami](https://hub.docker.com/r/bitnami/prestashop)

Documentación de docker --> [Docker](https://josejuansanchez.org/iaw/practica-docker/index.html)

