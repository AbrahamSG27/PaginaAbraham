---
title: "Instalación de Hugo"
date: 2022-10-20T20:52:24+02:00
draft: false
---

![hugo logo](https://imgs.search.brave.com/F5Ufn2nWMTzb_hRMl23hLGv1zW-rIWtNZ8sXHVzRLiE/rs:fit:565:151:1/g:ce/aHR0cHM6Ly93d3cu/Ymxlc3RhLmNvbS91/cGxvYWRzLzIwMTYv/MDYvaHVnby1sb2dv/LnBuZw)

# ¿Qué es Hugo?

Hugo es un generador de sitios estáticos que permite crear un sitio web sin apenas código. Los generadores de sitios estáticos suelen permitirte escribir tu contenido en un lenguaje de marcado sencillo, como Markdown. Hugo convierte el contenido en archivos HTML estáticos. 

Con Hugo, puedes elegir entre una biblioteca de temas y diseños de sitios que otras personas ya han creado. Una vez que hayas descargado un tema, puedes empezar a escribir tu contenido. Hugo acepta diferentes formatos para que escribas tu contenido.

# Beneficios de usar Hugo

- Como Hugo es bastante ligero y genera páginas web estáticas, tu sitio web final y su contenido pueden cargarse muy rápidamente. Esto significa que los usuarios tendrán poco tiempo de espera al navegar por tu sitio.

- Todo el contenido es estático y no cambia una vez que el usuario está viendo la página. Por lo tanto, no tiene que preocuparse por las constantes peticiones a un servidor. Tampoco tiene que preocuparse de las bases de datos, ni de contabilizar los datos dinámicos.

- No necesita conocimientos avanzados de programación para poder trabajar con un sitio Hugo. Sin embargo, como tienes acceso directo al código, puedes personalizarlo completamente como quieras si decides hacerlo.

# Instalación de Hugo

Hugo cuenta con un sistema de instalación relativamente sencillo que cambiará en función a tu sistema operativo.

## Windows 

1. Para instalar hugo en sistemas operativos Windows, una de las mejores maneras es usar el gestor de archivos ***Chocolatey*** que en caso de que no lo tengas instalado, puedes hacer uso de esta pequeña guía [*Instalar Chocolatey en Windows*](https://www.solvetic.com/tutoriales/article/8886-instalar-chocolatey-en-windows-10/) y luego seguir con la instalación de hugo.

2. El siguiente paso para culminar la instalación de hugo es introducir el comando de instalación de chocolatey para la versión de hugo que desees ***hugo*** o ***hugo-extended***:

    > choco install hugo -confirm
    > choco install hugo-extended -confirm

3. Por último, es recomendable comprobar la correcta instalación de hugo con el comando: 

    > hugo version

## Linux 

1. Una de las mejores formas de instalar Hugo para Linux, es mediante el gestor de paquete ***Snap***. Por lo que el primer paso para llevar a cabo esta instalación es desde luego, comprobar que tengamos snap instalado en el dispositivo. Para ello introduciremos el siguiente comando en un terminal:  
    
    > snap version

2. Habiendo comprobado de esta manera la presencia de snap, solo nos quedará instalar ***hugo*** o su versión extendida ***hugo-extended*** haciendo uso de este gestor de paquetes con alguno de estos dos comandos:

    > snap install hugo 
    > snap install hugo --channel=extended

3. Por último, es recomendable comprobar la correcta instalación de hugo con el comando: 

    > hugo version

## MacOS

1. Para instalar hugo en un sistema operativo MacOS bastará con usar el gestor de paquetes ***Brew*** que seinstala con el siguiente comando:

    > ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2. Habiendo hecho esto solo debemos introducir el comando:

    > brew install hugo

3. Escribir el siguiente comando para comprobar la instalación: 

    > hugo version

![2](https://imgs.search.brave.com/2cVV6Sd3VPovUPXKCVC0gxZ_sutmaw9ZetzEM9dn_AQ/rs:fit:369:157:1/g:ce/aHR0cHM6Ly93d3cu/cG9ja2V0c29sdXRp/b24ubmV0L2ltZy9t/YWMtbGludXgtd2lu/ZG93cy5wbmc)