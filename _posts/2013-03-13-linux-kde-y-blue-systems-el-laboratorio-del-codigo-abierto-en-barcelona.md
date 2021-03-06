---
layout: post
title: "Linux, KDE y Blue Systems, el laboratorio del código abierto en Barcelona"
date: 2013-03-13
image: 
        feature: cover/linus.jpg
permalink: linux-kde-y-blue-systems-el-laboratorio-del-codigo-abierto-en-barcelona
figure: Linus Torvalds leyendo código / Athanasios Kasampalis
---
En 1991 Linus Torvalds, un joven estudiante de informática finlandés, dejó el siguiente mensaje en una lista de correo de Minix, un sistema operativo derivado de UNIX destinado al sector educativo:

_Hola a todos aquellos que usan Minix.
Estoy haciendo un sistema operativo (gratuito) (solamente una afición, no será grande ni profesional como el GNU) para clones 386 (486) AT. Este ha estado gestándose desde abril, y está comenzando a estar listo. Me gustaría recibir cualquier comentario sobre las cosas que gustan/disgustan en Minix, ya que mi SO (Sistema Operativo) se le parece un poco."_

Un simple correo electrónico se convirtió en el pistoletazo de salida para uno de los proyectos de ingeniería más importantes del mundo. El sistema operativo GNU/Linux está presente en cientos de máquinas, desde cajeros automáticos hasta aviones, pasando por ordenadores y teléfonos móviles. Su gran diferencia con Windows o Mac OS X reside en que tiene una licencia de software libre y en que sólo consiste en un kernel, a diferencia de sus competidores más cercanos, que también proporcionan una interfaz gráfica. Siguiendo los postulados de la licencia GPL creada por Richard Stallman, gurú del software libre, el núcleo de Linux se puede descargar, ver y modificar libremente, tal como hacen diariamente miles de programadores. Para ser usable necesita de un entorno de escritorio, que es el conjunto de interfaz visual y aplicaciones básicas que permiten realizar tareas en el ordenador.

## El escritorio KDE

![KDE no está dirigido sólo a GNU/Linux. También funciona en Windows y MacOSX.](https://dl.dropboxusercontent.com/u/55065502/kde1.jpg)

KDE es un proyecto comunitario que elabora un entorno de escritorio de código abierto para GNU/Linux, y en fase experimental para Windows y Mac OS X. El entorno de escritorio [KDE](http://kde.org), nació en 1996, bajo la mano del alemán Matthias Ettrich, que buscaba una alternativa en Linux a las arcaicas interfaces de la época, austeras y poco amigables.

Tras más de quince años de desarrollo y cientos de versiones liberadas, KDE es junto a GNOME, el líder indiscutible del escritorio Linux. Miles de empresas, usuarios finales y corporaciones gubernamentales emplean actualmente su tecnología, presente en millones de tabletas, móviles y navegadores web.

![Aleix Pol y Àlex Fiestas en las oficinas de Blue Systems.](https://dl.dropboxusercontent.com/u/55065502/2.jpg)

Por ello, que [Blue Systems](http://www.blue-systems.com/) haya abierto recientemente una oficina en Barcelona es un motivo de alegría para los seguidores del software libre. Esta empresa es, junto a [Digia](http://www.digia.com/), una de las más activas en el soporte de las tecnologías que sustentan a KDE. Su fundador, Clemens Tönnies Jr, decidió invertir en el proyecto porque lo considera la plataforma perfecta para desarrollar nuevas aplicaciones informáticas. A corto plazo pretende limpiar y mejorar el código de KDE e integrar las redes sociales en el escritorio.

Situada en la calle Sepúlveda, entre Universitat y Plaza España, la sede de Blue Systems en Barcelona está localizada en una zona plagada de tiendas de informática y ¡sorpresa! de bicicletas. Allí trabajan a tiempo completo [Aleix Pol](https://twitter.com/aleixpol), el flamante presidente de KDE España, y [Àlex Fiestas](https://twitter.com/afiestas), prolífico desarrollador de KDE.

![](https://dl.dropboxusercontent.com/u/55065502/aleix1.jpg)

Según Aleix “KDE es una comunidad, gente que elabora programas y los pone en común para que lleguen a los usuarios finales.” Este joven programador completó con creces nada menos que tres Google Summer of Code, el programa con el que la empresa de Mountain View premia a estudiantes de informática para que diseñen e integren una nueva funcionalidad en el proyecto de código abierto de su elección durante el verano. Desde su época de universitario colabora activamente en KDE, creando aplicaciones como KAlgebra, una calculadora que permite plasmar de forma visual gráficas y funciones matemáticas.

## KDE España

La gran actividad que mantiene en la comunidad lo llevó a ser elegido el año pasado presidente de [KDE España](http://kde-espana.org), asociación creada en el 2009 con el fin de promocionar y dinamizar el desarrollo del proyecto KDE en nuestro país. Para ello hace una llamada: “necesitamos mucha gente que sepa hacer cosas distintas de programar. Gente que sepa dibujar, que sepa escribir y vender lo que hacemos, gente que organice la comunidad”, además, asegura que “en Barcelona es donde se localizan el mayor número de desarrolladores de toda España.”

Àlex Fiestas también forma parte de la junta directiva de KDE España por derecho propio. Actualmente contribuye en el desarrollo de Accounts, Kamoso, KScreen, Solid, User-Manager, y Bluedevil. Afirma que Accounts “fusionará las cuentas online con el escritorio. En solo un sitio se añadirán las cuentas online -Google, Skype, Messenger, Facebook- y automáticamente se integrarán las notificaciones, el chat, los eventos, el calendario…”

A pesar de esta integración con la web, desde KDE se está intentando llevar la ‘nube’ a los ordenadores personales, para no depender tanto de las grandes corporaciones. “Google cerró Reader sin pestañear, una aplicación con millones de usuarios.” Hace tres años surgió en el seno de KDE [ownCloud](http://owncloud.org/), un proyecto de código abierto que persigue la creación de una ‘nube’ personal, pudiéndola instalar en el servidor de tu elección. Ya es una realidad, y el desarrollo se ha separado de KDE para intentar monetizar el servicio. Cualquier empresa puede ofertar servicios en línea empleando ownCloud, que cuenta con aplicaciones de calendario, reproductor de música, navegador de archivos, y lector RSS funcionales desde el navegador. Es un Dropbox vitaminado, pero eso sí, totalmente libre.

![ownCloud es una alternativa de código abierto a Dropbox](https://dl.dropboxusercontent.com/u/55065502/owncloud.jpg)

## El desarrollo

El modelo de desarrollo de KDE no está basado en un gran bloque de desarrolladores que tomen decisiones en conjunto, sino en pequeños grupos que toman sus decisiones independientemente. Este modelo permite lanzar nuevas versiones estables cada seis meses, y publicar versiones de mantenimiento y corrección de errores cada dos. De ahí pasan a las distribuciones, que son las encargadas de proporcionar KDE a los usuarios finales. Las distribuciones son la pieza final del engranaje de GNU/Linux. Integran el kernel con el entorno de escritorio, y proporcionan a los usuarios acceso a unos repositorios centralizados donde se recogen todos los programas disponibles. De esta manera, si los empaquetadores actualizan la versión del programa en losrepositorios la actualización llegará al instante a todos los usuarios de la distribución vía Internet. 

Este sistema de distribución de paquetes tiene sus ventajas y desventajas. Según Àlex Fiestas “en KDE actualmente tenemos un problema con las distribuciones. Cada una de ellas tiene sus propias normas”. 

Hay algunas como Arch Linux, que actualizan los programas y el kernel a un ritmo frenético, y otras como Debian, que son extremadamente conservadoras y pueden tardar muchos meses en actualizar a una nueva versión del software en cuestión. Esto provoca que los usuarios se queden en versiones antiguas de los programas, y tengan una experiencia de usuario muy distinta a la que debería ser. “Es una cuestión de confianza, de si piensas que nosotros vamos a mejorar el software o si vamos a romperlo con cada nueva versión”, remacha.

Actualmente el proyecto KDE está dividido en varias partes. Además del entorno de escritorio en sí, el denominado Workspace, están las Applications, que son las aplicaciones básicas como el navegador de archivos o el editor de texto. Por último, las librerías que requieren los programas KDE están reunidas en las KDE Libs. Desde educación hasta redes, pasando por gráficos y accesibilidad, los desarrolladores de KDE han elaborado centenares de programas, que pasan oficialmente a formar parte del proyecto, o se mantienen en los repositorios Playground y Extragear. Según constata Aleix Pol, “como programador, no puedes esperar a que te digan qué es lo que tienes que desarrollar, pero si la idea es buena, seguro que tendrá futuro en la comunidad.”

Bajo el paraguas de KDE han surgido aplicaciones como Amarok, considerado ampliamente el mejor reproductor de música del mundo GNU/Linux, o KHTML, el motor de renderizado de páginas web en el que Apple se basó para crear WebKit, uno de los proyectos de software libre más importantes del mundo, empleado en los navegadores Safari y Google Chrome.

## Hacia el futuro

Próximamente esperan hacer una suave transición a la nueva versión de la librería Qt. “Si la experiencia de usuario es la misma habremos conseguido nuestro objetivo.” A partir de ese momento de inflexión desde Blue Systems se apuesta por un cambio radical del concepto de escritorio. “Si ahora quiero mandarle un correo electrónico a por ejemplo, Pepito, tengo que abrir la aplicación de correo, seleccionar al contacto en la lista y redactar el email. Podríamos cambiar la manera de pensar. Vertebrar todo alrededor de una aplicación de contactos, para simplemente seleccionar al contacto Pepito y hacer clic en enviar correo.” 

Aleix Pol concluye remarcando una de las grandes ventajas del código abierto. Asegura que “no tiene que rebajarse a comprometer los datos del usuario” ya que “no necesita sacar provecho de ello.” En la era post-Snowden los ciudadanos son cada vez más celosos de su privacidad, y el software libre se ha convertido en la herramienta que permite recuperar el control sobre los datos personales. Desde luego, KDE tiene todas las papeletas para jugar un papel importante en esta nueva vuelta de tuerca al escritorio. Y los chicos de Blue Systems estarán allí.