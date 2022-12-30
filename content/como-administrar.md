
---
title: "Como hacer andar esta cosa"
description: "Perdon"
aliases: ["tech"]
author:
    name: "Capu"
    email: "hi@capu.tech"
date: 2022-12-30
buttonimage: "img/apocalipsis.jpg"
imagealt: "no importa"
draft: false
weight: 2
---

Hola Juan,

te habla capu. Hice este sitio para hacerte mejor el dia, y voy a intentar
explicarte a continuación cómo hacerlo andar como una cosa tuya, pero quiero
irte avisando de que cómo se configura el sitio en sí probablemente sea
sumamente inadecuado. Sin más preambulos:

El dominio
==========
Lo registré yo, a nombre mio, y eso es sumamente poco ideal para vos, porque yo
soy quien tiene el control del dominio. Para que te lo pueda transferir,
deberías tener una cuenta en un _domain registrar_ [^1], y lo que hago es hacer
la transferencia desde mi registrar al tuyo. Yo uso
[namecheap](https://namecheap.com) y lo recomiendo.

El sitio
========
Es un sitio hecho con [hugo](https://gohugo.io/), el tema se llama [ticky tacky
dark](https://github.com/kc0bfv/ticky_tacky_dark).

Hugo tiene un montón de ventajas, y respecto a las forma de hacer páginas web
que hay allá afuera, es de las mas simples desde un punto de vista
estrictamente técnico. El tema es que para no developers, es sumamente poco
accesible. Para construir un sitio con hugo vas a necesitar:

- saber usar una linea de comandos
- saber usar un editor de texto
- tener conocimientos de como de hecho subir archivos a un servidor que de
hecho lo _hostee_. Yo ya tengo un servidor andando y uso scp. Pero esto implica
por ejemplo también tener una _clave ssh_ y que el servidor las acepte

Y además aprender como funciona hugo en si.

Por qué elegí hugo? Ni idea, es algo que un poquito ya conocía y que pude hacer
andar en un rato como para hacerme el pistola mandandote un link a 'tu pagina'
como primer mensaje.

[El _código_ en si está aca](https://github.com/juanpcapurro/juansemueve)

El hosting
==========
Está hosteado en un servidor mio, si tenés ganas y una compu y unas claves ssh
configuradas y que se yo, podría hacerte un acceso para hostearlo yo y que vos
subas lo que vayas modificando, pero me parece un re tough sell

Dale capu, y esto como me ayuda entonces?
=========================================
No se, imagino que puede ayudarte a tu proceso de tener un sitio el hecho de ir
familiarizandote con los distintos legos que hacen a una pagina web andar, y en
el proceso quizas encuentres algo que te haga más sentido.

En el medio supongo que podría ayudarte armando algo medio intermedio, subiendo
algun articulo o haciendo una modificación para poner alguna imagen o link que
quieras, pero no quiero ser _webmaster_ ni nada parecido, porque:

- si es mucho tiempo lo debería cobrar
- no te lo quiero cobrar
- me gustaría que tengas mas independencia que 'le pago a capu y capu se encarga'

[^1]: La autoridad máxima de los dominios de internet se llama ICANN, y es
  quien decide a dónde va a parar cada dominio. Vos y yo no interactuamos con
  la ICANN, sino que nos hacemos cuentas en otras entidades, _registrars_ que
  se compran dominios al por mayor de la ICANN u otra gente, y luego nos los
  revenden. 
