---
title: "Proceso de Comunicación Cliente/Servidor"
date: 2022-10-20T20:44:15+02:00
draft: false
---

![i1](https://imgs.search.brave.com/WWctKwWKXeISWIpEu5GuZentuoOx-ZFqdf4OqiLXS6A/rs:fit:800:555:1/g:ce/aHR0cHM6Ly93d3cu/a3JlYXRpYnUuY29t/L3dwLWNvbnRlbnQv/dXBsb2Fkcy9yZXNw/b25zaXZlLXdlYi1k/ZXNpZ24tZGlzZW5v/LWRlLXBhZ2luYXMt/d2ViLWtyZWF0aWJ1/LTEucG5n)

## ¿Cómo se visualizan las páginas web?
Basicamente el funcionamiento de una página web comienza desde tu ordenador, este se conecta ya sea alámbrica o inalámbricamente a un router que establece una conexión generalmente no directa hacia proveedor de internet o ISP, esta conexión suele pasar por una serie de saltos o hops en el camino por lo que en algunos gráficos se usa una nube para representar simplificadamente este punto.

De está manera, se establece una conexión a internet en tu ordenador y ya se puede realizar actividad en línea. En el caso de las páginas web, esta actividad comienza por escribir desde un navegador, una URL (localizador de recursos uniforme) que generalmente suele estar compuesta por tres partes:

Ejemplo: https://es.wikipedia.org/wiki/Desarrollo_web

- Protocolo: http://, https://, fip://, ldad://, ...
- Dominio: (IE. host): es.wikipedia.org
- Ruta: Recurso del servidor (wiki/Desarollo_web).

Luego de esto, la máquina con la URL concedida, se encarga de iniciar el proceso de busqueda para traducir el dominio a una dirección IP. Primero pasa la información del dominio al router y el router lo envia a la ISP o proveedor, quien se encarga de preguntar a su servidor DNS, este se compone principalmente por tablas que traducen los dominios a direcciones IP y de igual forma las direcciones IP a dominios. En caso de que la primera ISP no tenga dicha información en su servidor DNS, pasa la solicitud a los servidores de quien le provee acceso a ella y así sucesivamente hasta dar con la información solicitada (la IP del dominio). Ahora bien, se realiza este mismo proceso pero a la inversa, la IPS guarda una copia en sus tablas y envía la IP al router para que este lo envíe a tu ordenador. 

Teniendo ya en tu ordenador la dirección IP del servidor correspondiente a la página que buscas, puedes acceder a la información que se encuentra allí, pudiendo visualizar todo el contenido que contenga.

![Imgur](https://i.imgur.com/KiBRmYr.png)

## Composición de una URI

Aunque cotidianamente se suela utilizar la abreviación de las siglas URL (Uniform Resource Locator) para referirnos a la dirección que recive un navegador, esto es un error que se ha normalizado con el paso del tiempo, ya que la URL es solamente una parte de esta dirección.

Si vamos a la correcta terminología, el término adecuado para referirnos a dicha dirección es URI (Uniform Resource Identifier), ya que este realmente contiene el conjunto de la famosa URL y la URN. Ésta es la que sufre cambios dependiendo de la ubicación de la página en la que estés.

![g2](https://imgs.search.brave.com/2hNDWEGDyDa2jsubyVBrQ0g1DVjf7jscxzHo1bHux88/rs:fit:1200:498:1/g:ce/aHR0cHM6Ly9oYW5z/ZXVsLWxlZS5naXRo/dWIuaW8vMjAyMC8x/Mi8yNC8yMC0xMi0y/NC1VUkwvdXJpLnBu/Zw)

El URN (Uniform Resource Name) tiene algo en común con el URL (Uniform Resource Locator); ambos son subcategorías del URI. Sin embargo, ambos formatos difieren en que el URN añade un identificador permanente a un recurso, mientras que el URL se limita a indicar su localización. Mientras que el URN está diseñado para ser invariable e independiente del lugar donde se almacenen los datos, el URL indica la ubicación concreta donde se encuentra el recurso. Por lo tanto, ambas secuencias tienen una estructura similar, pero diferentes propósitos.
