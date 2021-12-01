<h1>Etiquetas y atributos para recordar</h1>
<ul>
<li><em>(em) Sirve para dar enfasis al texto</em></li>
<li><strong> (strong)Sirve para dar grosor al texto</strong></li>
<li><i> (i) se usa para transmitir el significado que tradicionalmente transmite la itálica: extranjerismos, clasificaciones taxonómicas, conceptos técnicos, un pensamiento...
</li>
<li><b> (b) se usa para transmitir el significado que tradicionalmente transmite la negrita: palabras clave, nombres de productos, frases principales...</li>
<li><u> (u) se usa para transmitir el significado que tradicionalmente conlleva el subrayado: nombres propios, errores ortográficos...</li>
<li># selector de id</li>
<li><code>: Para marcar fragmentos genéricos de código informático.</li>
<li><pre>: Para respetar los espacios en blanco (en general, en los bloques de código) — si utilizas la sangría o diversos espacios en blanco consecutivos dentro de un texto, los navegadores los ignorarán y no se mostrarán en la página. Sin embargo, si delimitas el texto con las etiquetas <pre></pre>, los espacios en blanco se representarán de forma idéntica a como se ven en tu editor de texto.</li>
<li><var>: Para marcar específicamente nombres de variables.</li>
<li><kbd>: Para marcar entradas de teclado (y de otro tipo) en el ordenador.</li>
<li><samp>: Para marcar la salida de un programa de ordenador.</li>
<li>encabezado: <header>.
<li>menú de navegación : <nav>.</li>
<li>contenido principal: <main>, con varias subsecciones (además de la barra lateral) representadas por los </li>
<li>elementos <article>, <section>, y <div>.</li>
<li>barra lateral: <aside>; a menudo colocada dentro de <main>.</li>
<li>pie de página: <footer>.</li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<ul/>
<header>
      <h1>Encabezado</h1>
    </header>
    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Nuestro equipo</a></li>
        <li><a href="#">Proyectos</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
       <!-- Un formulario de búsqueda es una forma no-lineal de hacer búsquedas en un sitio web. -->
       <form>
         <input type="search" name="q" placeholder="Buscar">
         <input type="submit" value="¡Vamos!">
       </form>
     </nav>
 <!-- Aquí está el contenido principal de nuestra página -->
    <main>
 <!-- Contiene un artículo -->
      <article>
        <h2>Título del artículo</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec a diam lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt congue enim, ut porta lorem lacinia consectetur.</p>

<h3>Subsección</h3>

<p>Donec ut librero sed accu vehicula ultricies a non tortor. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aenean ut gravida lorem. Ut turpis felis, pulvinar a semper sed, adipiscing id dolor.</p>

 <p>Pelientesque auctor nisi id magna consequat sagittis. Curabitur dapibus, enim sit amet elit pharetra tincidunt feugiat nist imperdiet. Ut convallis libero in urna ultrices accumsan. Donec sed odio eros.</p>

 <h3>Otra subsección</h3>

<p>Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum soclis natoque penatibus et manis dis parturient montes, nascetur ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at sem facilisis semper ac in est.</p>

<p>Vivamus fermentum semper porta. Nunc diam velit, adipscing ut tristique vitae sagittis vel odio. Maecenas convallis ullamcorper ultricied. Curabitur ornare, ligula semper consectetur sagittis, nisi diam iaculis velit, is fringille sem nunc vet mi.</p>
      </article>
<!-- el contenido aparte también se puede anidar dentro del contenido principal -->
      <aside>
        <h2>Relacionado</h2>
 <ul>
          <li><a href="#">Oh, me gusta estar junto al mar</a></li>
          <li><a href="#">Oh, me gusta estar junto al mar</a></li>
          <li><a href="#">Aunque en el norte de Inglaterra</a></li>
          <li><a href="#">Nunca deja de llover</a></li>
          <li><a href="#">Oh, bueno...</a></li>
        </ul>
      </aside>
</main>
  <!-- Y aquí está nuestro pie de página principal que se utiliza en todas las páginas de nuestro sitio web -->
 <footer>
      <p>©Copyright 2050 de nadie. Todos los derechos revertidos.</p>
    </footer>
-------------------------------------------------
<br>
<ul>
<li><article>  (article)encuadra un bloque de contenido que tiene sentido por sí mismo aparte del resto de la página (por ejemplo una entrada en un blog).</li>
<li><section> (section) es parecido al elemento (article) <article>, pero se usa más para agrupar cada parte de la página que, por su funcionalidad, constituye una sección en sí misma (por ejemplo un minimapa o un conjunto de titulares y resúmenes). Se considera una buena práctica comenzar cada una de estas secciones con un título de encabezado (heading); observa que podemos subdividir artículos (<article>) en distintas secciones (<section>), o también secciones en distintos artículos, dependiendo del contexto.</li>
<li><aside> (aside) incluye contenido que no está directamente relacionado con el contenido principal, pero que puede aportar información adicional relacionada indirectamente con él (resúmenes, biografías del autor, enlaces relacionados, etc.).</li>

<li><h2>Control de la herencia</h2></li>
<li>inherit
    Establece que el valor de la propiedad que se aplica a un elemento determinado sea exactamente igual al del elemento padre. En la práctica, esto "activa la herencia".</li>
<li>initial
    Establece que el valor de la propiedad que se aplica a un elemento seleccionado tenga el mismo valor que esté establecido para esa propiedad en la hoja de estilo por defecto del navegador</li>
<li>unset (en-US)
    Restablece la propiedad a su valor natural, lo que significa que si la propiedad se hereda de forma natural, actúa como inherit, y en caso contrario como initial.</li>
<li></li>
<li></li>
</ul>