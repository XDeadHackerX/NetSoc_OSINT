# 🔍 The spy's job 🔍

[Español](https://github.com/XDeadHackerX/The_spy_job) | [English](https://github.com/SobrioRiot/The_spy_job)

> Herramienta creada por XDeadHackerX

[![The-Spy-s-Job-2-1.png](https://i.postimg.cc/Xv2dY0Zt/The-Spy-s-Job-2-1.png)](https://postimg.cc/QBTHfwJq)

---

*Buenas, soy* **XDeadHackerX** *y quiero presentaros mi nueva herramienta llamada* **The_Spy´s_Job**. *Esta Tool está enfocado al* **OSINT** *de casi todos los ámbitos* **(Personas, Nicknames, Redes Sociales, Emails, Números de Teléfono, Páginas Webs, IPs Públicas e Imágenes)** *Mi idea era recopilar y automatizar todas las técnicas de OSINT más Avanzadas posibles en una sola Herramienta y así trabajar de la forma más cómoda y rápida posible, ya que solo tenemos que dar un par de clics y él solo se pondrá a recopilar y mostrar de forma ordenada y clasificada toda la Información. Todos los Apartados están separados por partes por si solo quieres extraer un tipo de información en concreto, pero también cuenta con la penúltima opción que combina todas las Opciones para que saque todo lo que sea capaz del dato que le hemos introducido. Deciros que iré actualizando el repositorio, añadiendo cosas nuevas y solucionando errores. Todas las Técnicas de sustracción de datos e información que aparecen en la Herramienta las he ido estudiando y almacenando durante los últimos 5 años.*
<p align="center"> <img width="350px" src="https://i.postimg.cc/0yrH4qG6/pc1.webp"> </p>
*Os pido por favor que si os ha gustado este gran Proyecto lo apoyéis dándole una* **Estrella** ★, *al final del repositorio también está la opción de invitarme a un café, pero sinceramente me apoyáis más dándole una* **Estrella** ★, *así veré valorado mi esfuerzo en este Proyecto.* **[NO ME HAGO RESPONSABLE DEL MAL USO DE ESTA HERRAMIENTA]**

---

## 💡 Funciones 💡

:ballot_box_with_check: **OSINT a Páginas Webs** --> [*WhatWeb, Whois, Scaner de Puertos Avanzado, Información del Servidor, Intentar Extraer IP real de Servidor con CloudFlare, Encriptado SSL, Listar Todas las URLs de un Dominio, Información Web de WordPress, Extraer Trabajadores, Correos Electrónicos y Números de Teléfono, Listar Dominios, Google Dorks, Ping a una Web desde varios Países*]

:ballot_box_with_check: **OSINT a Personas** --> [*Google Dorks, Redes Sociales, Imágenes, Posts, etc*]

:ballot_box_with_check: **OSINT a Nicknames/Alias** --> [*Google Dorks, Buscar en 574 Redes Sociales una cuenta con ese Nick, Imágenes, Posts*]

:ballot_box_with_check: **OSINT a Redes Sociales** --> [*Información de una Cuenta de Instagram/TikTok/Twitter/Twitch/(GitHub + email) = sin tener una cuenta*]

:ballot_box_with_check: **OSINT a Emails** --> [*Información de un Email, Verificar la existencia de un Email, Buscar en 121 Redes Sociales una cuenta con ese Email, Buscar Cuenta de GitHub enlazada al Email, Google Dorks*]

:ballot_box_with_check: **OSINT a Números de Teléfono** --> [*Compañía (ISP), Ver si está registrado en Instagram/Amazon/Snapchat, Google Dorks, Intentar extraer el Nombre del Dueño*]

:ballot_box_with_check: **OSINT a IPs Públicas** --> [*Compañía (ISP), Geolocalización de la ciudad exacta, Buscar puertos abiertos con sus servicios/versión, Ping de la Web desde varios Países*]

:ballot_box_with_check: **OSINT a Videos/Canales YouTube** --> [**Videos:** *Fecha y Hora de la Publicación, Título, Descripción, URL de la Imagen de la Miniatura (Varios tamaños), Estadísticas (visualizaciones, likes, comentarios y favoritos), Geolocalización (Si la puso), Status, Detalles del Video (Duración, dimensiones, definición, proyección), Categoría del video, Miniaturas.* **Canal:** *Fecha y Hora de la creación del Canal, Título, Descripción, URL de la Imagen de la Miniatura (Varios tamaños), Localización (Si la tiene activada), Estadísticas (Visualizaciones totales de los videos, subscriptores, videos totales), Palabras claves (#), Playlists, Status, Categorías*]

:ballot_box_with_check: **OSINT a Imágenes** --> [*Metadatos, Motor de Búsqueda de Google, Buscador específico de Imágenes, Ampliar una imagen x5 sin casi perder calidad de la Imagen*]

## 🛠 Instalar Herramienta 🛠

**0)** Instalar y usar la Herramienta con **Root**

**1)** sudo apt update && apt -y full-upgrade

**2)** sudo apt-get install git

**3)** git clone https://github.com/XDeadHackerX/The_spy_job.git 

**4)** cd The_spy_job

**5)** chmod 777 the_spy_job.sh

**6)** bash the_spy_job.sh

**7)** Marcamos la Opción 0 y luego 1 para instalar las dependencias (Solo marcar la primera vez)

**8)** Dentro de la Opción 0 nos encontramos con los apartados 2 y 3 los cuales podemos configurar 
dichas APIs gratuitas para sacar el máximo partido a The_spy_job

**9)** Ya podemos disfrutar de la herramienta

## 🎲 Tener en Cuenta 🎲

**[1]** En el Apartado ([0] Instalar y Configurar Requisitos) cuando le demos a la Opción 1 para Instalar los Requisitos nos pedirá que pongamos a un usuario que **no** tenga permisos root, este paso es muy importante, ya que si ponemos a un usuario con permisos root, o lo escribimos mal o lo ponemos doble no funcionarán las Opciones que tengan que abrir un Navegador desde la Terminal.

**[2]** En el Apartado ([0] Instalar y Configurar Requisitos) podemos Configurar la API de veriphone.io, shodan.io y zoomeye.org para sacar el mejor partido de esta Herramienta, las dos son gratuitas.

**[3]** En el Apartado ([7] Información de una IP Pública) con el uso de VPN la mayoría de servidores dan respuestas erróneas sobre sus puertos. Para solventar esto he puesto varios Scanners y 2 de ellos te dan los puertos correctos a pesar de la VPN.

**[4]** Usar la herramienta con Firefox cerrado, esto se debe a que la herramienta abre múltiples pestañas y si Firefox ya está en ejecución se producir aun error.

**[5]** Personalmente recomiendo usar la Herramienta con la Terminal en Pantalla Completa (Gráficamente más bonito).

## 🔎 Versiones 🔎

**(v1.0)** ---> Versión Original.

**(v1.1)** ---> Nuevas Opciones en el Apartado [4] llamadas (Información + email de una cuenta de GitHub) y (Información de una cuenta de TikTok), Nueva Opción en el Apartado [1] llamado (Google Dorks), Nuevo Opción en el Apartado [5] Comprobar si tiene GitHub y saber su Username, Reparados los errores de los Apartados 6 y 7, solucionado el Bug al abrir un navegador en el SO Parrot, eliminación de que era la Opción 2 dentro del Apartado 4.

**(v1.2)** ---> Ampliación de Google Dorks en los Apartados 1, 2 y 6. 1=(Nueva búsqueda, filtra las URLs y fotos de toda la Web), en el Apartado 2 (Permite añadir una palabra clave a la búsqueda para hacerla más avanzada y específica) y por último en el Apartado 6 (También permite añadir una palabra clave a la búsqueda para hacerla más avanzada y específica), Reparación de error que afectaba a la penúltima Opción (Todas las opciones/Todo) de Todos los Apartados el cual cuando lanzaba un Navegador la Herramienta se paraba y no seguía hasta que cerrabas el Navegador.

**(v1.3)** ---> Incorporación del famoso Motor de Búsqueda Zoomeye (API) en el Apartado [1] la Opción [3] y en el Apartado [7] la Opción [3], Nuevo Opción en el Apartado [8] llamada [3] Usar Buscador específico, el cual usa un Motor de Búsqueda específico de imágenes, Mejoras visuales, Reparaciones varias.

**(v2.0)** ---> Nueva Opción en el Apartado 5 llamado ([1] Información de un Email) este nos mostrará información muy interesante, Mejora en el Apartado 4 Opción ([2] Información de una cuenta de Instagram) ahora puedes ver la foto de perfil de una cuenta aunque sea privada, Mejoras en el apartado [4] Información de una Red Social, ahora aparte de abrir la web con información avanzada sobre esa cuenta te muestra el 95% de la información también por Terminal, te mostrara el Nombre (Si lo tiene), el número de Posts, número de publicaciones, seguidores y seguidos, y un link para descargar la Imagen de Perfil, también se a incorpororado la Red Social Telegram, Nueva opción en el Apartado 8 llamado [4] Ampliar una Imagen con calidad, logra ampliar la imagen x4 sin perder apenas calidad, Reparado error que había al abrir dos navegadores dentro de una opción, Mejora visual en el Apartado 6 la opción ([1] Ver la Compañía y el País del Número de Teléfono).

**(v2.1)** ---> Nuevo Apartado llamado ([8] Información de un Video/Canal de YouTube) este nuevo apartado es capaz de extraer mucha información interesante de un Video o Canal de YouTube, como puede ser (**Videos:** *Fecha y Hora de la Publicación, Título, Descripción, URL de la Imagen de la Miniatura (Varios tamaños), Estadísticas (visualizaciones, likes, comentarios y favoritos), Geolocalización (Si la puso), Status, Detalles del Video (Duración, dimensiones, definición, proyección), Categoría del video, Miniaturas.* **Canal:** *Fecha y Hora de la creación del Canal, Título, Descripción, URL de la Imagen de la Miniatura (Varios tamaños), Localización (Si la tiene activada), Estadísticas (Visualizaciones totales de los videos, subscriptores, videos totales), Palabras claves (#), Playlists, Status, Categorías*), dentro de este apartado también te da la posibilidad de Generar Estadísticas de un Video o un Canal. La mejor parte de este nuevo apartado es que no requiere de una API de YouTube, la parte negativa es que todos estos resultados se tiene que visualizar en un navegador y no por Terminal, a pesar de esto seguiré estudiando la forma de mostrar los resultados por Terminal al igual que en el Apartado 4. En el apartado 4 ahora tambien extrae informacion de las cuentas privadas de Instagram y Twitter, convirtiendose en la primera herramienta gratuita en GitHub en poder extraer esta informacion sin necesidad de API ni cuenta. Limpieza en los resultados de los Apartados 1, 4, 6, se eliminan los caracteres especiales que rodeaban los resultados de dichos apartados.

## ⭐☕ Creado por XDeadHackerX ☕⭐

**Si consideras que este proyecto ha sido útil, te agradecería que me apoyaras dándole una estrella a este repositorio o invitándome a un café.**

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/XDeadHackerX)

Copyright © 2022, XDeadHackerX
