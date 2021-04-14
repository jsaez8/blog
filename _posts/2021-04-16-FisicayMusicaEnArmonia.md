---
title: "Música y física en armonía"
header:
  image: /assets/images/CientificasErbias_reducida.jpg
  caption: "Créditos: [**@Chir_ii**](https://www.instagram.com/chir_ii/?hl=en)"
  og_image: /assets/images/posts/2021-04-16-FisicayMusicaEnArmonia/cover.jpg 
categories:
  - Lo cotidiano es ciencia
comments: true
author_profile: true
tags:
  - Física
  - Música
date: 2021-04-02 15:30:00 +0200
--- 

¿Serías capaz de reconocer tu canción favorita si un músico la toca con distintos instrumentos? Seguro que sí. En principio, sabiendo la sucesión de notas de esa canción y dónde se encuentran en el instrumento podemos tocar nuestra canción favorita. Sin embargo, siendo las mismas notas, somos capaces de diferenciar si el instrumento es una guitarra, un piano o una flauta. Pero, un momento, ¿qué es lo que diferencia una nota La en un piano, de la nota La en un violín? Esta simple pregunta esconde gran cantidad de física y es uno de los puntos de unión entre las matemáticas, la física y la música.

En nuestro anterior post de música y física aprendimos que cada nota de la escala musical tiene una frecuencia fundamental distinta, por lo que su sonido es distinto. Los sonidos con mayor frecuencia los percibimos más agudos que los que tienen una frecuencia menor. También aprendimos que lo que define una nota en la escala musical es su frecuencia fundamental, por ejemplo el La tiene una frecuencia de 440 Hz mientras que un Do 262 Hz. Como vimos en el caso de los instrumentos de cuerda, la frecuencia fundamental depende de algunas propiedades de las cuerdas y podemos conseguir la misma frecuencia en dos instrumentos distintos. Pero un momento, hemos dicho que cada nota se identifica con una frecuencia y que ajustando las propiedades de las cuerdas podemos conseguir la misma frecuencia fundamental en dos instrumentos distintos, entonces: ¿cómo puede ser que ambos instrumentos suenen distinto? Parece ser que la frecuencia fundamental no lo es todo.

Además de vibrar en la frecuencia fundamental, una cuerda puede vibrar a otras muchas frecuencias mayores, siempre y cuando sean múltiplos enteros de la frecuencia fundamental. Imaginemos que la frecuencia fundamental de nuestra cuerda son 100 Hz, por lo tanto también podrá vibrar a 200 Hz , 300 Hz, 400 Hz… produciendo sonidos más agudos. A estas frecuencias las llamaremos armónicos. Esto matemáticamente lo escribimos como:

<p>f_n = n f_0</p>

Donde n indica el armónico, F_n la frecuencia del armónico y f_0 es la frecuencia fundamental. Aunque esto de los armónicos parezca raro, solo quiere decir que la cuerda puede vibrar de muchas formas distintas pero muy bien definidas, como podemos ver en la siguiente imagen. En el fundamental, o primer armónico, toda la cuerda se mueve de un lado para otro manteniendo fijos sus extremos, el segundo armónico mantiene un punto fijo en mitad de la cuerda y un lado se mueve para arriba y el otro para abajo; el tercer armónico tiene dos puntos fijos mientras que el resto de la cuerda oscila, etc. Cuando vemos una cuerda de la guitarra vibrar lo está haciendo de todas esas maneras que vemos al mismo tiempo.

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-16-FisicayMusicaEnArmonia/Arm_wiki.png"/>
</figure>


Un punto muy importante es que cada armónico tendrá una amplitud distinta, es decir, que algunos armónicos sonarán más bajos y otros más altos. Este punto es fundamental para entender por qué la misma nota suena diferente en distintos instrumentos. Imaginemos que tenemos el primer armónico en nuestra cuerda a 100 Hz y le asignaremos amplitud (o volumen sonoro) de 1. Si capturamos una imagen de la cuerda cuando está en uno de los extremos tendrá esta pinta:

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-16-FisicayMusicaEnArmonia/Fundamental.jpg"/>
</figure>

Cuando existen distintos armónicos en una misma cuerda, las ondas se suman superponiendo la forma de los distintos armónicos. Podemos ver un ejemplo sencillo en la siguiente figura, donde se representa en verde el resultado de sumar el primer y el segundo armónico. Esa cuerda sonaría a 100 Hz con un volumen de 1 y a 200 Hz con un volumen de 0.5, aunque podríamos haber elegido otra amplitud.

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-16-FisicayMusicaEnArmonia/Armonicos1.jpg"/>
</figure>

¿Qué ocurre si seguimos superponiendo armónicos? Pues que la vibración de nuestra cuerda tendrá una forma algo distinta y como consecuencia emitirá sonido también en las frecuencias de esos armónicos. En la siguiente figura podéis ver la forma resultante de 3 armónicos:

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-16-FisicayMusicaEnArmonia/Armonicos2.jpg"/>
</figure>

A medida que añadimos más armónicos las vibraciones de la cuerda se vuelven algo más complejas y es complicado diferenciar qué armónicos contiene y qué amplitud tiene cada uno de ellos. Para solucionar este problema, también podemos representar la amplitud de cada modo de vibración en función de la frecuencia, de esta manera podemos saber cómo de alto suena cada frecuencia de una manera sencilla. A esto le llamamos espectro de frecuencias y así sería para la última onda que representamos con los tres primeros armónicos.

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-16-FisicayMusicaEnArmonia/Espectro.jpg"/>
</figure>

En general, las cuerdas de los instrumentos musicales vibran en muchos armónicos distintos, por lo que el espectro de frecuencias constará de más puntos. Es ahora cuando llega el momento crucial en el que podemos contestar a la pregunta inicial: **¿Por qué la misma nota en diversos instrumentos suena distinto, pero sin embargo es la misma nota?** Porque los armónicos de distintos instrumentos poseen distintas amplitudes. En la siguiente gráfica podéis ver los espectros de frecuencia de la misma nota en un piano y en una guitarra.

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2021-04-16-FisicayMusicaEnArmonia/Piano_Guitarra.jpg"/>
</figure>

Podemos observar que, aunque la nota es la misma, la cantidad de armónicos y la intensidad de estos es distinta en el piano y en la guitarra. ¡Esto es lo que les otorga su sonido característico a cada uno! La guitarra presenta un mayor número de armónicos y con mayor intensidad, lo que significa que tiene más sonidos agudos y más altos que el piano. Esta distribución de armónicos e intensidades se denomina timbre y es la que nos permite diferenciar dos sonidos que tienen la misma frecuencia fundamental.

Quizás algunos os estéis preguntando si todo esto es aplicable a los instrumentos de viento. La respuesta es sí, cada instrumento de viento tiene su timbre característico. En este caso no hay ninguna cuerda que vibre, sino que son las propias ondas sonoras dentro del instrumento las que vibran con distintas frecuencias fundamentales y distintos armónicos. ¿Y qué hay de los tambores? Hoy ya no tenemos espacio para esto, pero podéis encontrar un link en ‘Para saber más’.

Por supuesto que todos los sonidos tienen un espectro de frecuencias, por lo que podemos obtener el espectro de un coche, de una canción o incluso de nuestra propia voz. Aunque todo esto suene exótico, es algo que podemos hacer en nuestra propia casa con una aplicación en el móvil. Os dejamos el enlace a una app tanto para Android y para IOS para que juguéis y exploréis los espectros de frecuencias de distintos sonidos.

&nbsp;  
&nbsp;

<span style="font-size:1.5em"><a id="target" style= "color:black"><b>Glosario</b></a></span>
&nbsp;   
<span style="font-size:1.25em">
**Hercio**: el hercio es la unidad de medida de la frecuencia y su abreviatura es Hz. Cuando decimos que algo vibra con 10 Hz de frecuencia significa que en un segundo completa 10 oscilaciones. Al igual que 1 kg son 1000 gramos, 1 kHz son 1000 Hz.
<br>
**Amplitud y frecuencia**: como hemos mencionado, la amplitud y la frecuencia de una onda definen cómo de alto o bajo es un sonido y como de grave o agudo lo escuchamos, respectivamente. La frecuencia es el número de oscilaciones que una partícula realiza en un segundo. En cambio, la amplitud de oscilación es la distancia entre los entre los dos puntos más alejados de la partícula cuando vibra.  <br>
</span>
{: .notice--primary}   

---
**Para saber más**
* Anteriormente hemos escrito la ecuación que nos da la frecuencia fundamental en función de la longitud de la cuerda, su tensión y su densinsidad lineal. Esta expresión no es completamente exacta, puesto que no contiene otros parámetros que también afectan a dicha frecuencia; sin embargo, da un resultado bastante preciso para el objetivo de este post. 

* Para más información sobre cómo vibra una cuerda de una guitarra: [link](http://citharaworld.blogspot.com/2017/03/ecuacion-para-una-cuerda-de-guitarra.html){:target="_blank"}

* [Matemáticas, música y Pitágoras](https://www.palermo.edu/ingenieria/downloads/CyT6/6CyT%2003.pdf){:target="_blank"}

* Como podéis ver en esta [tabla de Wikipedia](https://es.wikipedia.org/wiki/Frecuencias_de_afinaci%C3%B3n_del_piano){:target="_blank"}, cada nota tiene asociada una frecuencia con mucha precisión.
