---
title: "Microscopía de superresolución o cómo reírnos de los límites de la física"
header:
  image: /assets/images/CientificasErbias_reducida.jpg
  caption: "Créditos: [**@Chir_ii**](https://www.instagram.com/chir_ii/?hl=en)"
  og_image: /assets/images/posts/2020-05-17-superresolucion/comparison.jpg
categories:
  - Viaje al centro de la ciencia
comments: true
author_profile: true
tags:
  - Microscopía fluorescencia
  - Superresolución
  - STED
  - SMLM
date: 2020-07-17 15:30:00 +0200
--- 
<style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>

A finales del siglo XIX, el físico alemán Ernst Abbe postuló que “es imposible discernir dos elementos más cercanos entre sí que la mitad de la <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/viaje%20al%20centro%20de%20la%20ciencia/superresolucion/index.html#target">longitud de onda</a> de la luz empleada”.  Y durante muchos años, así fue. Pero como os imaginaréis, los biólogos necesitaban ver las estructuras más finas de sus células y a los físicos no les gustaba eso de que la naturaleza les impusiera un límite —¡¿Quién se cree que es?!, decían.

Más de 150 años después, en 2014, [Stefan Hell](https://www.nobelprize.org/prizes/chemistry/2014/hell/biographical/){:target="_blank"}, [Robert Eric Betzig](https://www.nobelprize.org/prizes/chemistry/2014/betzig/biographical/){:target="_blank"} y [William E. Moerner](https://www.nobelprize.org/prizes/chemistry/2014/moerner/biographical/){:target="_blank"} recibieron el premio Nobel de Química por “el desarrollo de la microscopía de fluorescencia de superresolución”, demostrando que podíamos ver moléculas sin tener *demasiado* en cuenta el límite de Abbe usando microscopía óptica. ¡Abbe ha muerto, larga vida a la <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/viaje%20al%20centro%20de%20la%20ciencia/superresolucion/index.html#target">nanoscopía</a>!

Es tan bonito lo que consiguieron Hell, Betzig y Moerner… No solo abrieron un mundo nuevo hasta ahora imposible de ver, sino que rompieron los límites de lo que creíamos posible. Fijaos.
<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/imagen_top.jpg" style="width:400px" class="center">
	<figcaption> Imagen superresolutiva de neuronas hipocampales en las que las proteínas actina (fuego), map2 (azul) y neurofascina (cian) han sido marcadas con fluoróforos. Fuente: <a href="http://www.neurocytolab.org/" target="_blank">NeuroCyto Lab</a>.</figcaption>
</figure>
¿Qué narices significa el postulado de Abbe? Dejadnos dar un pequeño rodeo, solo serán un par de conceptos físicos.

Cuando visualizamos un objeto más pequeño que la longitud de onda de la luz que utilizamos, la imagen que se forma es más grande que el tamaño real del objeto: se forma un “halo”. Esto sucede porque la luz cambia de dirección al chocar con los bordes del objetivo del microscopio y la partícula, provocando que el <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/viaje%20al%20centro%20de%20la%20ciencia/superresolucion/index.html#target">frente de onda</a> se extienda. Este fenómeno se conoce como difracción.
<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/combined2.gif"/>
	<figcaption> <b>Izquierda</b>:Patrón de difracción. El punto central se conoce como Disco de Airy y su radio solo depende de la longitud de onda y de la <a style="color:lightslategray" href="https://juditsastre.github.io/blog-copy/viaje%20al%20centro%20de%20la%20ciencia/superresolucion/index.html#target">apertura numérica</a> del objetivo de nuestro microscopio. <b>Derecha</b>: Difracción de una onda al pasar por una abertura. Fuente: Wikicommons.</figcaption>
</figure>
Ahora sí. Lo que el bueno de Ernst quería decir es que no podremos diferenciar dos puntos si no están lo suficientemente separados.
<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/FIG_limiteBIEN.jpg"/>
	<figcaption> Fuente: Adaptada de <a href="http://physwiki.apps01.yorku.ca/index.php?title=Main_Page/BPHS_4090/microscopy_I" target="_blank">Undergraduate Physics - York University</a> y <a href="http://hyperphysics.phy-astr.gsu.edu/hbase/phyopt/diflim.html" target="_blank">HyperPhysics</a> </figcaption>
</figure>
En microscopía óptica se usa luz visible, la cual tiene un rango de longitud de onda de entre 380 y 780 nanómetros. Por lo tanto, usando el límite de difracción de Abbe, la máxima <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/viaje%20al%20centro%20de%20la%20ciencia/superresolucion/index.html#target">resolución</a> teórica que se podría alcanzar es de unos 200 nm.

Vale, tenemos un problema. Y gordo. ¿Cómo podemos ver más allá de esos 200 nm?

<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/FIG_escala.jpg"/>
	<figcaption> Fuente: Adaptada de <a href="https://commons.wikimedia.org/wiki/File:Biological_and_technological_scales_compared-en.svg" target="_blank">Wikicommons</a></figcaption>
</figure>
Los físicos pensaron que podían solucionar el problema usando longitudes de onda menores. Por desgracia, la luz con longitudes de onda más cortas también es más energética y tiene la fea costumbre de ser nociva para los especímenes biológicos. Y no queremos freír nuestras muestras.

La luz no quiere ayudarnos. Pero… un momento. Si nos deslumbra, ¿por qué no apagarla? ¿Cómo hacemos eso? Podemos aprovecharnos del comportamiento de las “bombillas moleculares” o “pulsar un interruptor”. Dos opciones y las dos son correctas. ¡Bingo! Pues premio Nobel para las dos.

Moerner y Betzig usaron las <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/viaje%20al%20centro%20de%20la%20ciencia/superresolucion/index.html#target">fotopropiedades</a> de los <a style="color:lightslategray" href="https://cientificaserbias.github.io/blog/viaje%20al%20centro%20de%20la%20ciencia/superresolucion/index.html#target">fluoróforos</a> —nuestras “bombillas moleculares”—; a mí me gusta decir que resolvieron el problema *desde la química*. Hell, en cambio, diseñó ese “interruptor”; así que diré que encontró una solución *desde la física*.

La *aproximación química* de Moerner y Betzig dio lugar a un conjunto de técnicas que se conocen como *Single Molecule Localisation Microscopy* —SMLM, por sus siglas en inglés—. Estas técnicas burlan los límites de la física empleando el comportamiento de las moléculas o partículas fluorescentes. 

¿Cuál es ese comportamiento que permite que la química se ría de la física? Cuando irradiamos un fluoróforo con luz de una determinada longitud de onda, este se excita; lo que significa que sus electrones pasan a un nivel de energía superior al absorber la cantidad de energía justa —ni un poco más, ni un poco menos— para hacer ese salto. Pero sus electrones no están cómodos en este nuevo estado (S<sub>1</sub>) así que buscan la manera de volver a bajar al estado fundamental (S<sub>0</sub>). Si decaen emitiendo luz, se produce la fluorescencia; pero a veces buscan otros caminos más intrincados. Por ejemplo, pasando del estado S<sub>1</sub> al T<sub>1</sub> por un proceso denominado cruce entre estados. En este estado T<sub>1</sub>, la molécula queda apagada: temporalmente (*blinking*, parpadeo en inglés) si puede volver al estado S<sub>1</sub> o permanentemente (*photobleaching*, fotoblanqueamiento en inglés) si sufre una reacción química que la transforma en una nueva molécula no fluorescente.
<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/FIG_Fluorescencia.jpg"/>
</figure>
Todas estas transiciones entre diferentes estados son procesos estocásticos, que es una manera muy estirada de decir que son probabilísticos, azarosos o, para que nos entendamos todos, que pasan cuando les da la gana. En la práctica, esto hará que no ocurra en todas las moléculas a la vez; lo que permitirá que, en un sistema donde las moléculas apagadas están demasiado juntas, podamos localizarlas de una en una, cuando se enciendan, para saber dónde están con una resolución de unos 20 nm. ¡Acabamos de conseguir 10 veces más resolución!

Dejémonos de rodeos físicos y químicos, ¿cómo se obtiene una imagen superresolutiva usando SMLM? 
<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/FIG_SMLM.jpg"/>
	<figcaption> Fuente: Adaptada de <a href="https://github.com/superresolusian/NEUBIAS-webinar/blob/master/A%20guided%20tour%20for%20analyzing%20and%20quantifying%20single-molecule_short.pdf" target="_blank">Superesolusian</a>. Podéis ver  una demo interactiva en <b>«Para saber más»</b>.</figcaption>
</figure>
Nuestra muestra seguirá teniendo los fluoróforos apagados demasiado cerca pero, gracias a su peculiar comportamiento, podremos separarlos **en el tiempo**. Así, iremos capturando imágenes limitadas por la difracción en las que solo algunas de las moléculas están encendidas.  Ajustaremos cada uno de los puntos-moléculas a una función matemática, una gaussiana, para determinar el centro de ese punto. Y es, justo aquí, donde ya no nos importa el límite de difracción: la exactitud con la que determinemos su posición dependerá principalmente de lo bien que hayamos detectado cada molécula —del número de fotones detectados—. Después de capturar muchas imágenes y calcular el centro de muchos puntos, podremos reconstruir una imagen superresolutiva de nuestra muestra “pintando” las coordenadas de cada una de las moléculas que hemos localizado.

Separar la fluorescencia de las moléculas en el tiempo, localizar su centro computacionalmente y reconstruir la imagen usando las coordenadas de todas las moléculas detectadas: esta es la base de todas las técnicas clasificadas como *Single Molecule Localisation Microscopy* (SMLM), entre las que se incluyen *Photoactivated Localization Microscopy, Stochastic Optical Reconstruction Microscopy, DNA-Paint*, etcétera.

En la *aproximación física*, Hell sorteó el límite de difracción de Abbe usando dos láseres. El primero excita las moléculas fluorescentes de la misma forma que hemos descrito arriba. El segundo, que tiene forma de dónut, apaga algunas de las moléculas que han sido encendidas por el primer láser usando un proceso conocido como emisión estimulada. En este proceso, los electrones que se encuentran en el estado excitado (S<sub>1</sub>) son forzados a decaer al estado fundamental (S<sub>0</sub>) al interaccionar con los fotones del láser-dónut. La diferencia entre este proceso y la fluorescencia es que, en la emisión estimulada el electrón se relaja hasta un nivel vibracional superior del estado fundamental (ver la figura siguiente). Esto supone que, aunque ambos procesos impliquen transiciones S<sub>1</sub>→S<sub>0</sub> en las que se emiten fotones (luz), la emisión de cada uno de ellos tiene una longitud de onda (color) diferente; lo que permite separarlas y, en última instancia, ver solo la emisión que corresponde a la fluorescencia.
<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/FIG_STED2.jpg"/>
	<figcaption> Fuente: Adaptada de <a href="https://www.sciencedirect.com/science/article/abs/pii/S1359029417301309" target="_blank">Aloi et al. (2018)</a>. Podéis ver  una demo interactiva en <b>«Para saber más»</b>.</figcaption>
</figure>
Al usar el láser-dónut y apagar los fluoróforos de los alrededores, lo que hacemos es reducir el tamaño del área en la que pueden emitir los fluoróforos —reducimos el tamaño de nuestro “halo”—. Es decir, separamos la fluorescencia **en el espacio**; lo que provoca que podamos distinguir dos elementos cuya distancia sea menor al límite de difracción. Esto no significa que apartemos un fluoróforo de otro, sino que lo que hacemos es ir iluminando nuestra muestra “a cachitos”. Así, la muestra es barrida por el dúo de láseres para formar una sola imagen superresolutiva cuya resolución alcanza fácilmente los 50 nm.

Después de esta técnica, conocida como STED (*STimulated Emission Depletion*), llegaron muchas otras: *Ground State Depletion, Saturated Structured Illumination Microscopy*… Todas ellas tienen en común el uso de efectos ópticos no lineales —lo que habitualmente implica usar más de un láser para controlar la geometría del láser de excitación— para sortear el límite de difracción. 
<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2020-07-17-superresolucion/comparison.jpg"/>
	<figcaption> Comparación de una imagen de microscopía de fluorescencia convencional (izquierda) y microscopía de superresolución (derecha). Ambas imágenes son microtúbulos de una célula de <i>Drosophila</i>. Las imágenes están disponibles en <a href="http://www.cellimagelibrary.org/home" target="_blank">The Cell: An image library</a> </figcaption>
</figure>
Ni la *aproximación química* ni la *física* rompen el límite de difracción, sino que exploran condiciones en las que este ya no se cumple para ir más allá de esos 200 nm. Para ello, además del ingenio de los premiados, es necesario usar técnicas avanzadas de microscopía que permitan limitar el volumen de muestra excitado para restringir la cantidad de luz indeseada que recibe la cámara; si no las usáramos, sería como intentar ver una estrella a plena luz del día. Además, esas cámaras son muy sensibles pues la cantidad de luz que emite una molécula es muy pequeña. Para que os hagáis una idea, un fluoróforo orgánico típico emite unos 60.000 fotones cada segundo mientras que una bombilla de 100W como las que tenemos en casa emite unos 100.000.000.000.000.000.000 fotones/segundo (¡cien trillones!); para rematar, de los tristes 60.000 fotones que emite nuestra molécula solo detectaremos un 12% porque se van perdiendo a lo largo del camino óptico del microscopio. Por último, aunque no por ello menos importante, también hay que tener en cuenta las fotopropiedades de los fluoróforos: lo brillantes que son, su estabilidad, etc. Así que, aunque nosotros hemos hablado sobre todo de física y química en este post, este gran avance fue, es y será fruto del trabajo multidisciplinar de biólogos, bioquímicos, ingenieros, desarrolladores de software… Y físicos y químicos. 


<span style="font-size:1.5em"><a id="target" style= "color:black"><b>Glosario</b></a></span>
&nbsp;   
<span style="font-size:1.25em">
**Longitud de onda**: La distancia entre las crestas de la onda. En nuestro caso, la onda es electromagnética ya que hablamos de luz.  
**Nanoscopía**: Otro nombre para la microscopía de superresolución, que comprende el conjunto de técnicas que permiten distinguir objetos cuya separación ronda las decenas de nanómetros, es decir, 0’00000001 metros.  
**Frente de onda**: Imaginad que tiráis una piedra en un estanque. ¿Véis las circunferencias concéntricas que se forman en torno al punto en el que ha caído la piedra? Cada una de estas circunferencias es un frente de onda.  
**Apertura numérica**: Este número es una medida de la capacidad de un objetivo para recoger la luz y resolver detalles finos de muestras a una distancia fija del objeto.  
**Resolución**: la distancia mínima entre dos objetos para poder distinguirlos.  A mayor resolución mayor detalle en la imagen.  
**Fotopropiedades**: Este término es de cosecha propia. Me refiero a las propiedades fotoquímicas y fotofísicas de las moléculas fluorescentes: el tiempo que permanecen en el estado temporalmente apagado, cuánto tiempo tardan en apagarse definitivamente, cuántas veces pueden apagarse y encenderse antes de apagarse definitivamente, cuántos fotones emiten por segundo, etcétera.   
**Fluoróforo**: Cualquier molécula o partícula que, al ser iluminada, emita luz. En microscopía de fluorescencia se suelen usar moléculas orgánicas, proteínas intrínsecamente fluorescentes o puntos cuánticos.  
</span>
{: .notice--primary}

---
**Para saber más**

* [Demo interactiva de SMLM](http://lewlab.wustl.edu/resources/superresolution_web_app/index.html){:target="_blank"} y de [STED](http://zeiss-campus.magnet.fsu.edu/tutorials/superresolution/stedfundamentals/indexflash.html){:target="_blank"}. No os las perdáis, ¡son preciosas!

* Anuncio del premio Nobel. En esta página podéis encontrar un montón de información: Una breve explicación de su importancia, información para el público, background científico, etc. En inglés.  
[The Nobel Prize in Chemistry 2014](https://www.nobelprize.org/prizes/chemistry/2014/press-release/){:target="_blank"}

* Artículo sobre la nanoscopía escrito por José Ramón Isasi Allica (Profesor de Química Física de la Facultad de Ciencias de la Universidad de Navarra). En castellano.  
[Superresolución nanoscópica](https://www.unav.edu/web/vida-universitaria/detalle-opinion2?articleId=5371534){:target="_blank"}

* Otro artículo, un poco más extenso. Explicando la importancia de este descubrimiento. En castellano.  
[Premio Nobel de Química 2014: Microscopía de fluorescencia con super-resolución](https://www.sciencedirect.com/science/article/pii/S0187893X15720987){:target="_blank"}

* Esta web de Nikon tiene un montón de artículos muy educativos sobre microscopía. En ella podéis encontrar más información sobre el límite de difracción, las diferentes técnicas que hemos comentado y, en general, sobre microscopía. En inglés.  
[Nikon's MicroscopyU - The Source for Microscopy Education](https://www.microscopyu.com/){:target="_blank"}

* ¿Os acordáis de las proteínas intrínsecamente fluorescentes que os he mencionado en el «Glosario»? Pues son tan importantes que sus descubridores recibieron su propio Nobel de Química en 2008. En inglés.  
[The Nobel Prize in Chemistry 2008](https://www.nobelprize.org/prizes/chemistry/2008/press-release/){:target="_blank"}

---
