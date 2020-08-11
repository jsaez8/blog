---
layout: splash
permalink: /
hidden: true
header:
  image: /assets/images/CientificasErbias_reducida.jpg
  caption: "Créditos: [**@Chir_ii**](https://www.instagram.com/chir_ii/?hl=en)"
feature_row:
  - image_path: /assets/images/homepage/locotidianoesciencia.jpg
    alt: "Lo cotidiano es ciencia"
    title: "Lo cotidiano es ciencia"
    excerpt: "La ciencia que vemos en nuestras casas."
    url: "https://cientificaserbias.github.io/blog/categories/#lo-cotidiano-es-ciencia"
    btn_class: "btn--primary"
    btn_label: "Echa un vistazo"
  - image_path: /assets/images/homepage/viajealcentrodelaciencia.jpg
    alt: "Viaje al centro de la ciencia"
    title: "Viaje al centro de la ciencia"
    excerpt: "Tralla de la buena."
    url: "https://cientificaserbias.github.io/blog/categories/#viaje-al-centro-de-la-ciencia"
    btn_class: "btn--primary"
    btn_label: "Rómpete la cabeza"
  - image_path: /assets/images/homepage/loquelacienciasellevo.jpg
    alt: "Lo que la ciencia se llevó"
    title: "Lo que la ciencia se llevó"
    excerpt: "Aquí hablamos de científicos muertos (o no)."
    url: "https://cientificaserbias.github.io/blog/categories/#lo-que-la-ciencia-se-llevó"
    btn_class: "btn--primary"
    btn_label: "Habla con los (no) muertos"
  - image_path: /assets/images/homepage/cronicasdeuncientificoencerrado.jpg
    alt: "Crónica de un científico encerrado"
    title: "Crónica de un científico encerrado"
    excerpt: "Nuestro día a día, con sus luces y sombras."
    url: "https://cientificaserbias.github.io/blog/categories/#crónica-de-un-científico-encerrado"
    btn_class: "btn--primary"
    btn_label: "Esto es lo que hacemos"  
  - image_path: /assets/images/homepage/frikadas.jpg
    alt: "Breaking Lab"
    title: "Breaking Lab"
    excerpt: "Nuestro particular cajón de sastre."
    url: "https://cientificaserbias.github.io/blog/categories/#breaking-lab"
    btn_class: "btn--primary"
    btn_label: "Únete al lado oscuro de la ciencia"  
  - image_path: /assets/images/homepage/TwitterLogo.jpg
    alt: "Nuestros hilos en Twitter"
    title: "Nuestros hilos en Twitter"
    excerpt: "También escribimos cosas por aquí."
    url: "https://jsaez8.github.io/blog/hilosTwitter/"
    btn_class: "btn--primary"
    btn_label: "Esperamos que no pierdas el hilo de la historia"  
---
<ul class="social-icons">
  {% if site.data.ui-text[site.locale].follow_label %}
    <strong>{{ site.data.ui-text[site.locale].follow_label }}</strong>
  {% endif %}

  {% if site.author.links %}
    {% for link in site.author.links %}
      {% if link.label and link.url %}
        <a href="{{ link.url }}" rel="nofollow noopener noreferrer"><i class="{{ link.icon | default: 'fas fa-link' }}" aria-hidden="true"></i> {{ link.label }}</a>
      {% endif %}
    {% endfor %}
  {% endif %} 
</ul>


   <div style="text-align: right;color:#668c99; font-size:0.9em;">"La ciencia, hijo mío, está llena de errores; pero de errores que conviene conocer, porque conducen poco a poco a la verdad."<br>
 <i>Viaje al centro de la tierra</i>, Jules Verne.</div>
  
&nbsp;
<html>
<head>
<style>

div.ex2 {
  width: 70%;
  margin-left: auto;
  margin-right: auto;
}
</style>
</head>
<body>

<div class="ex2"><p>&nbsp;&nbsp;¡Bienvenido al club de las científicas Erbias! Este club está formado por un grupo de amigos que provenimos de distintas ramas científicas, con el objetivo común de transmitir nuestra pasión por la ciencia a todo tipo de público. Como no todo en ciencia reluce, además de compartir temas de interés científico, os contaremos cómo es la vida de un investigador y los retos y dificultades que conlleva.</p>
 
<p>&nbsp;&nbsp;Y como la ciencia es colaborativa, estaremos siempre encantados de oir vuestras opiniones. ¡No dudéis en sugerirnos temas que sean de vuestro interés! Y si además tú también eres científico y quieres unirte a nosotros o hacernos sugerencias sobre cómo mejorar alguna de nuestras entradas, toda idea será más que bienvenida. ¡Nosotros también queremos aprender!</p>
</div>

</body>
  
&nbsp;

{% include feature_row %}


Todas las imágenes bonitas son obra de <a href="https://www.instagram.com/chir_ii/?hl=en" target="_blank">@Chir_ii</a>, los demás hacemos lo que podemos.


