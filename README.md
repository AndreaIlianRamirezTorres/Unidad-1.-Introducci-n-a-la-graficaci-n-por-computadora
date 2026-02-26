# Unidad-1.-Introduccion-a-la-graficacion-por-computadora
En este repositorio se desglosan la serie de temas de la primera unidad del temario, así como la mención de las practicas realizadas.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="author" content="">
    <h1 class="page-header">Temario <small>Unidad 1</small></h1>
    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.css" rel="stylesheet">
    <!-- Custom CSS for the '3 Col Portfolio' Template -->
  </head>
  <body>
    <nav class="navbar navbar-fixed-top navbar-inverse" role="navigation">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-ex1-collapse">
            <span class="sr-only">Indice</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
        <div class="collapse navbar-collapse navbar-ex1-collapse">
          <ul class="nav navbar-nav">
            <li><a href="#1.1">1.1. Historia y evolución de la graficación por
computadora.</a></li>
            <li><a href="#1.2">1.2 Areas de aplicación.</a></li>
            <li><a href="#1.3">1.3 Aspectos matemáticos de la graficación.</a></li>
            <li><a href="#1.4">1.4. Modelos del color: RBG, CMY, HSV y HSL.</a></li>
            <li><a href="#1.5">1.5. Representación y trazo de líneas y polígonos.</a></li>
            <li><a href="#1.5.1">1.5.1. Formatos de imagen.</a></li>
            <li><a href="#1.6">1.6. Procesamiento de mapas de bits.</a></li>
            <li><a href="#bib">Bibliografia.</a></li>
          </ul>
        </div><!-- /.navbar-collapse -->
      </div><!-- /.container -->
    </nav>
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
        </div>
      </div>
      <h2 id="1.1">1.1. Historia y evolución de la graficación por
computadora.</h2>
La Graficación por Computadora es una de las áreas más interesantes de las Ciencias de la computación y su principal objetivo es establecer los principios, técnicas y algoritmos para la generación y manipulación de imágenes mediante una computadora. Dichas imágenes pueden ser de distinta complejidad, desde imágenes en dos dimensiones hasta modelos tridimensionales donde se requiere producir imágenes de aspecto real. De esta manera, la graficación por computadora permite establecer una interacción especial entre el hombre y la computadora.<br>
El viejo adagio de que “una imagen vale más que mil palabras” es tan cierto en nuestros días como lo era hace 100 años, por ello no debe sorprendernos que desde que las computadoras aparecieran se haya intentado producir imágenes que pudieran verse a través de sus pantallas. A lo largo de más de cuarenta años de evolución de los componentes electrónicos digitales y demás dispositivos computacionales, la habilidad de generar imágenes por computadora también se ha incrementado. Se ha llegado a un punto tal, que hoy no podemos concebir una computadora, por muy sencilla y modesta que sea, sin alguna capacidad gráfica.<br>
En la actualidad las computadoras son una herramienta eficaz en cuanto a graficación y creación de imágenes ya que pueden hacerlo de manera sencilla, rápida y económica. Es casi imposible encontrar un ambiente en donde no se requiera implementar o ya se haya implementado alguna técnica o algoritmo de graficación. Por ello nos topamos con el hecho de que las gráficas por computadora se han convertido en un elemento cotidiano en diversas áreas tales como la industria, arte, televisión, gobierno, educación, publicidad, ciencia, ingeniería,... cuya finalidad va desde entretenernos hasta capacitarnos.<br>
Pero para entender cómo es que la graficación ha llegado a ser una rama tan fascinante es necesario hacer un breve recorrido a través del tiempo presentando su origen, desarrollo histórico hasta llegar al auge que se vive hoy en día.<br>
<b>1. Inicios y Cimientos (1950 - 1960)</b><br>
1950-1951: Nacimiento con los primeros experimentos en computadoras analógicas y digitales, destacando el simulador de vuelo Whirlwind del MIT.<br>
1960: William Fetter de Boeing acuña el término "gráficos por computadora" para describir su trabajo en el diseño de cabinas.<br>
1961: Steve Russell crea Spacewar!, uno de los primeros videojuegos con salida visual.<br>
<b>2. El Surgimiento de la Interactividad (1960 - 1970)</b><br>
1963: Ivan Sutherland desarrolla Sketchpad en el MIT, el primer programa de dibujo interactivo que permitía usar un lápiz óptico para manipular formas en pantalla.<br>
1963: Se crea el algoritmo de Bresenham para el dibujo de líneas, un estándar que sigue vigente.<br>
1968: Se funda Evans & Sutherland, pioneros en hardware gráfico comercial.<br>
<b>3. La Era del 3D y la Fotorrealismo (1970 - 1990)</b><br>
Década de 1970: Se desarrollan los algoritmos fundamentales de iluminación y sombreado (como el sombreado de Gouraud y Phong).<br>
1983: Apple Lisa se convierte en la primera computadora personal comercial con una interfaz gráfica de usuario (GUI).<br>
1985: Se funda ATI Technologies, impulsando el mercado de tarjetas gráficas.<br>
<b>4. La Revolución de la GPU (1990 - Presente)</b><br>
1993: Fundación de Nvidia, con el objetivo de revolucionar el procesamiento visual.<br>
1999: Lanzamiento de la Nvidia GeForce 256, comercializada como la primera GPU (Unidad de Procesamiento Gráfico) del mundo, capaz de procesar 10 millones de polígonos por segundo.<br>
2007: Introducción de CUDA, permitiendo usar la potencia de las GPUs para cálculos científicos y, más tarde, para Inteligencia Artificial. <br>
      <h2 id="1.2">1.2 Areas de aplicación.</h2>
La computación gráfica o gráficos por ordenador es el campo de la informática visual, donde se utilizan computadoras tanto para generar imágenes sintéticamente como integrar o cambiar la información visual y especial probada del mundo real.En la actualidad casi todo lo que es para uso de gráficos es una computadora. El CAD se utiliza casi siempre en el diseño de automóviles, aeronaves, embarcaciones, naves espaciales, computadoras, telas, construcciones, software y muchos otros productos.<br>
El diseño asistido por computadora en siglas DAO o mejor conocido como CAD (Computer Aided Desing) se trata básicamente de una base de datos de entidades geométricas como puntos, líneas o arcos, etc. Con el CAD se puede operar una interfaz gráfica para diseñar lo que se pida.<br>
<b>1. Entretenimiento y Medios</b><br>
Es el área más visible y donde la tecnología avanza más rápido debido a la alta demanda de realismo.<br>
Videojuegos: Renderizado en tiempo real de entornos 3D complejos.<br>
Cine y Efectos Visuales (VFX): Creación de personajes digitales, escenarios fantásticos y composición de imágenes generadas por computadora (CGI) con acción real.<br>
Animación Digital: Producción de largometrajes y series íntegramente digitales (como las de Pixar o Dreamworks).<br>
<b>2. Diseño, Ingeniería y Manufactura</b><br>
Estas áreas utilizan la precisión matemática para crear objetos del mundo real.<br>
CAD (Diseño Asistido por Computadora): Utilizado por ingenieros y arquitectos para diseñar desde microchips hasta rascacielos.<br>
CAM (Manufactura Asistida por Computadora): Traducción de modelos 3D en instrucciones para maquinaria industrial y cortes láser.<br>
Prototipado Virtual: Pruebas de aerodinámica o resistencia de materiales sin necesidad de construir un prototipo físico.<br>
<b>3. Medicina y Ciencia</b><br>
La graficación aquí salva vidas y ayuda a la comprensión de fenómenos complejos.<br>
Visualización Médica: Reconstrucción 3D a partir de tomografías (TC) y resonancias magnéticas para planificar cirugías.<br>
Simulación Molecular: Modelado de proteínas y nuevas drogas para la industria farmacéutica.<br>
Visualización Científica: Representación de datos abstractos (clima, flujos oceánicos, astrofísica) para detectar patrones imposibles de ver en tablas numéricas.<br>
<b>4. Educación y Entrenamiento</b><br>
Se enfoca en el aprendizaje mediante la experiencia visual segura.<br>
Simuladores de Vuelo y Manejo: Entrenamiento de pilotos y conductores en entornos controlados.<br>
E-learning y Museografía: Reconstrucciones históricas interactivas y modelos educativos 3D que facilitan la comprensión de conceptos abstractos.<br>
<b>5. Interfaces de Usuario (GUI) y Visualización de Datos</b><br>
Es el uso más común y cotidiano.<br>
GUI: El diseño de ventanas, iconos y menús que nos permiten interactuar con computadoras y smartphones.<br>
Infografía e Infovis: Transformación de grandes volúmenes de datos (Big Data) en gráficos comprensibles para la toma de decisiones empresariales.<br>
      <h2 id="1.3">1.3 Aspectos matemáticos de la graficación.</h2>
<b>1. Álgebra Lineal: El Motor Gráfico.</b><br>
Es la base de todo. Los objetos en 3D se definen como conjuntos de vértices (puntos en el espacio).<br>
Vectores: Se usan para representar posiciones, direcciones y velocidades. Por ejemplo, el vector normal (perpendicular a una superficie) es crucial para calcular cómo rebota la luz.<br>
Matrices: Son herramientas para transformar puntos. Si quieres mover, rotar o escalar un objeto, multiplicas el vector de sus vértices por una matriz de transformación.<br>
Coordenadas Homogéneas: Se añade una cuarta dimensión a los vectores para permitir que las traslaciones y las proyecciones se realicen mediante multiplicaciones de matrices simples.<br>
<b>2. Geometría de Transformaciones.</b><br>
Para llevar un modelo desde la "mente" del software a la pantalla, se sigue una cadena de transformaciones:<br>
Espacio de Modelo: Coordenadas locales del objeto.<br>
Espacio de Mundo: Posición del objeto respecto a otros.<br>
Espacio de Cámara (Vista): Reorientar todo según el punto de vista del observador.<br>
Proyección: Aquí es donde ocurre la magia. Se usa la proyección perspectiva para que los objetos lejanos se vean más pequeños, dividiendo las coordenadas por su profundidad.<br>
<b>3. Curvas y Superficies (Cálculo).</b><br>
No todo son triángulos rectos. Para crear formas suaves como la carrocería de un coche o personajes orgánicos, se utilizan:<br>
Curvas de Bézier y Splines: Ecuaciones paramétricas que definen curvas suaves basadas en puntos de control.<br>
Cálculo Vectorial: Se usa para calcular gradientes y cambios en la superficie, esenciales para el sombreado y las texturas.<br>
<b>4. Trigonometría</b><br>
Es indispensable para cualquier rotación. Si un objeto gira un ángulo, las nuevas coordenadas se calculan usando funciones seno y coseno.<br>
<b>5. Iluminación y Física (Óptica Matemática).</b><br>
Para que una imagen sea realista, se debe calcular cómo interactúa la luz con la materia:<br>
Producto Punto (Dot Product): Determina el ángulo entre la luz y la superficie. Si el ángulo es pequeño, la superficie brilla más (Ley de Coseno de Lambert).<br>
Producto Cruz (Cross Product): Se usa para encontrar vectores perpendiculares, necesarios para generar mallas de polígonos.<br>
Ecuación de Renderizado: Una integral compleja que suma toda la luz que llega a un punto desde todas las direcciones posibles.<br>
      <h2 id="1.4">1.4. Modelos del color: RBG, CMY, HSV y HSL.</h2>
Los modelos de color son sistemas matemáticos que permiten representar y reproducir colores de forma estandarizada. Se dividen principalmente en modelos basados en componentes físicos (luz o pigmento) y modelos basados en la percepción humana.<br>
<b>1. RGB (Red, Green, Blue).</b><br>
Naturaleza: Modelo aditivo basado en la luz.<br>
Funcionamiento: Los colores se crean sumando luces de color rojo, verde y azul. Al mezclarse todos en su máxima intensidad se obtiene el blanco.<br>
Uso: Dispositivos que emiten luz propia como monitores, pantallas de teléfonos, cámaras digitales y proyectores.<br> 
<b>2. CMY (Cyan, Magenta, Yellow).</b><br>
Naturaleza: Modelo sustractivo basado en pigmentos o tintas.<br>
Funcionamiento: Los colores se obtienen restando (absorbiendo) longitudes de onda de la luz blanca. La mezcla de cian, magenta y amarillo en teoría produce negro, aunque en la práctica se añade una cuarta tinta negra (K) para mayor profundidad, formando el modelo CMYK.
Uso: Medios impresos, desde impresoras domésticas hasta prensas industriales.<br> 
<b>3. HSV y HSL (Basados en la percepción).</b><br>
Ambos son representaciones cilíndricas del modelo RGB diseñadas para ser más intuitivas para el ojo humano que el sistema numérico de canales.<br>
HSV (Hue, Saturation, Value):<br>
Tono (H): El color puro (rojo, azul, etc.), medido de 0° a 360° en un círculo cromático.<br>
Saturación (S): La pureza del color (de gris a color vivo).<br>
Valor (V): La intensidad de la luz (del negro al color puro).<br>
HSL (Hue, Saturation, Lightness):<br>
Tono (H) y Saturación (S): Similares a HSV.<br>
Luminosidad (L): Define la claridad. A diferencia de HSV, una luminosidad máxima (100%) siempre da como resultado el blanco, mientras que en HSV depende de la saturación.<br>
      <h2 id="1.5">1.5. Representación y trazo de líneas y polígonos.</h2>
La representación y el trazo de líneas y polígonos son los pilares de la computación gráfica. Básicamente, se trata de decidir qué píxeles en una pantalla de cuadrícula (raster) deben "encenderse" para aproximar una forma geométrica continua:<br>
<b>1. Representación de Líneas.</b><br>
Una línea se define matemáticamente por dos puntos: X y Y.<br>
Sin embargo, como las pantallas están compuestas por píxeles discretos, necesitamos algoritmos de rasterización.<br>
Algoritmos Principales:<br>
DDA (Digital Differential Analyzer): Se basa en el cálculo de la pendiente, es simple pero utiliza aritmética de punto flotante (decimales), lo que lo hace lento para procesadores antiguos.<br>
Algoritmo de Bresenham: Es el estándar de la industria. Utiliza únicamente aritmética de números enteros, lo que lo hace extremadamente rápido. Decide qué píxel elegir basándose en un "parámetro de decisión" que evalúa qué píxel está más cerca de la línea ideal.<br>
<b>2. Representación de Polígonos.</b><br>
Un polígono es una secuencia de puntos (vértices) conectados por líneas (aristas) que forman una figura cerrada.<br>
Tipos de Representación:<br>
Basada en Vértices: Se almacena una lista ordenada de puntos, es la forma más común en formatos de archivos.<br>
Estructura de Datos de Aristas (Edge List): Se almacena una tabla con las conexiones entre puntos. Es útil para evitar la redundancia cuando dos polígonos comparten un lado.<br>
<b>3. Trazo y Relleno de Polígonos.</b><br>
Una vez que tenemos los bordes, el reto es "pintar" el interior. Existen dos enfoques principales:<br>
A. Algoritmo de Línea de Escaneo (Scan-line):<br>
Recorre la pantalla fila por fila (de arriba hacia abajo).<br>
Calcula las intersecciones de la fila actual con las aristas del polígono.<br>
Ordena las intersecciones de izquierda a derecha.<br>
Pinta los píxeles que están entre pares de intersecciones (regla de paridad).<br>
B. Algoritmo de Inundación (Flood Fill):<br>
Se utiliza cuando ya tenemos un contorno definido.<br>
Se elige un "punto semilla" dentro del polígono.<br>
El algoritmo se expande recursivamente pintando los píxeles vecinos hasta encontrar el color del borde.<br>
      <h3 id="1.5.1">1.5.1 Formatos de imagen.</h3>
Los formatos de imagen se dividen principalmente en dos categorías: ráster (basados en píxeles) y vectoriales (basados en fórmulas matemáticas).<br>
<b>1. Formatos Ráster (Mapa de bits). </b><br>
Son ideales para fotografías y gradientes complejos. <br>
JPG / JPEG: El más común para fotos web debido a su alta compresión, aunque pierde calidad al guardarse.<br>
PNG: Perfecto para logotipos y gráficos con transparencia. Ofrece compresión sin pérdida de calidad.<br>
WebP: Formato moderno optimizado para la web que ofrece archivos más pequeños que JPG y PNG manteniendo una alta fidelidad.<br>
GIF: Utilizado para animaciones sencillas; está limitado a una paleta de 256 colores.<br>
TIFF: Preferido en impresión profesional por su altísima calidad y ausencia de compresión.<br>
RAW: Formato "crudo" de cámaras profesionales que contiene toda la información del sensor para edición avanzada. <br>
<b>2. Formatos Vectoriales.</b><br>
Permiten escalar la imagen infinitamente sin que pierda nitidez. <br>
SVG: El estándar para iconos y gráficos en sitios web, ya que es escalable y ligero.<br>
EPS / AI: Formatos profesionales utilizados en diseño gráfico (Adobe Illustrator) e impresión a gran escala.<br>
PDF: Aunque es un contenedor, suele usarse para enviar artes finales a imprenta manteniendo vectores y fuentes intactas.<br> 
<b>Ejemplos de practicas realizadas:</b><br>
"Dibujo de un poligono"<br>
<img width="2735" height="1642" alt="Captura de pantalla 2026-02-15 090710" src="https://github.com/user-attachments/assets/0162d427-3c0b-42b8-a0f6-461817a0c3c5" />
"Flor de vida"<br>
<img width="799" height="597" alt="Captura de pantalla 2026-02-13 084345" src="https://github.com/user-attachments/assets/4a967107-1a15-4980-ab1e-a8134b1d0551" />
      <h2 id="1.6">1.6. Procesamiento de mapas de bits.</h2>
El procesamiento de mapas de bits (o imágenes rasterizadas) en graficación se basa en la manipulación de una cuadrícula o matriz de píxeles, donde cada unidad contiene información específica de color, ubicación y, a veces, opacidad.<br>
Formatos de mapa de bits (también denominados mapas de píxeles o ráster) utilizan una rejilla de puntos de píxel para representar una imagen. El valor de cada píxel, que representa su grado de oscuridad o de color, se registra de forma individual. Los formatos de mapa de bits funcionan bien para imágenes con variaciones de color, tonalidades o formas complejas. Las fotografías de tono continuo son un ejemplo de gráfico que se beneficia de su almacenamiento en formato de mapa de bits.<br>
Los ficheros de imagen de mapa de bits requieren un espacio de almacenamiento relativamente grande y, para su procesamiento y visualización, se requiere más memoria.<br>
A continuación, los conceptos y procesos clave:<br>
<b>1. Estructura Fundamental.</b><br>
Píxel: Es la unidad mínima de una imagen digital. Su color se define mediante bits; a mayor profundidad de bits, mayor es la gama cromática disponible (ej. 24 bits permiten más de 16 millones de colores).<br>
Resolución: Se refiere a la cantidad de píxeles en un área determinada. Define el nivel de detalle, pero hace que la imagen sea dependiente de la resolución: al ampliarla, se pierde calidad y aparece el "pixelado".<br>
<b>2. Procesos Comunes en Graficación.</b><br>
Rasterización: Es el proceso de convertir gráficos vectoriales (fórmulas matemáticas) en un mapa de bits para que puedan ser mostrados en pantalla.<br>
Transformaciones Espaciales: Incluye el escalado, rotación y traslación. Al escalar hacia arriba, el software debe realizar una interpolación (inventar información basada en píxeles adyacentes) para rellenar los huecos, lo que suele difuminar los bordes.<br>
Filtrado y Mejora: Aplicación de algoritmos para modificar la imagen, como ajustes de contraste, desenfoque (blur), reducción de ruido y corrección de color (ej. de RGB a escala de grises).<br>
Compresión: Debido a que los mapas de bits ocupan mucho espacio, se procesan mediante métodos de compresión (como en los formatos JPG o PNG) para reducir el tamaño del archivo sin perder excesiva fidelidad visual.<br>
<b>3. Herramientas de Procesamiento.</b><br>
Para realizar estas tareas de forma profesional, se utilizan aplicaciones de edición rasterizada como Adobe Photoshop, GIMP o Pixlr.<br>
      <h2 id="bib">Bibliografia.</h2>
Antecedentes y evolución de la graficación por computadora. (s. f.).<br> 
https://grafidepc.blogspot.com/p/blog-page.html<br>
Wikipedia contributors. (2026, 28 enero). Computer graphics. Wikipedia.<br> 
https://en.wikipedia.org/wiki/Computer_graphics<br>
Wikipedia contributors. (2026b, febrero 3). History of video games. Wikipedia.<br>
https://en.wikipedia.org/wiki/History_of_video_games#:~:text=Spacewar!%20se%20considera%20el%20primer%20videojuego%20de,de%20rayos%20cat%C3%B3dicos%20(CRT)%20o%20un%20osciloscopio.<br>
Área de aplicación de la graficación por computadora. (s. f.).<br>
https://grafidepc.blogspot.com/p/area-de-aplicacion-de-la-graficacion.html<br>
Client challenge. (s. f.).<br>
https://es.scribd.com/document/595159409/Informe-1-2-Areas-de-aplicacion-de-la-graficacion<br>
Notas para el curso de graficación por computadora. (s. f.).<br>
https://prometeo.matem.unam.mx/recursos/VariosNiveles/iCartesiLibri/recursos/Notas_Graficacion_por_Computadora/index.html<br>
Introducción a la graficación por computadora. (s. f.).<br>
https://proyectodescartes.org/iCartesiLibri/materiales_didacticos/GraficacionComputadora/index.html<br>
Curso: Cálculo (Análisis) Vectorial. (2016, 26 diciembre). Compilando Conocimiento.<br>
https://compilandoconocimiento.com/analisisvectorial/#:~:text=Gradiente%20Este%20es%20la%20operaci%C3%B3n%20m%C3%A1s%20f%C3%A1cil,Gradiente%2C%20vectores%20normales%20a%20superficies%2C%20derivada%20direccional.<br>
Client challenge. (s. f.-b).<br>
https://es.scribd.com/document/612259775/1-5-Representacion-y-trazo-de-lineas-y-poligonos-para-los-equipos#:~:text=El%20Algoritmo%20de%20Bresenham%20es%20un%20m%C3%A9todo,los%20ejes%20horizontales%20identifican%20columnas%20de%20pixel.<br>
Error - elbibliote.com. (s. f.).<br>
https://elbibliote.com/resources/Temas/Matematica/MATEMATICAS_poligonos.pdf#:~:text=A%20continuaci%C3%B3n%2C%20marcamos%20este%20%C3%A1ngulo%20en%20la,dibujamos%20uno%20de%20los%20lados%20del%20pol%C3%ADgono).<br>
Client challenge. (s. f.-c).<br>
https://es.slideshare.net/slideshow/poligonos-regulares-10053702/10053702#:~:text=Un%20pol%C3%ADgono%20es%20una%20figura%20plana%20delimitada,PDF%2C%20PPTX%20o%20ver%20en%20l%C3%ADnea%20gratis<br>
Clase 4 – Tecnología de Gráfica Digital 1. (s. f.).<br>
https://tecnologiadegraficadigital1.faud.unsj.edu.ar/clase-4/#:~:text=Los%20gr%C3%A1ficos%20de%20mapa%20de%20bits%20est%C3%A1n%20formados%20por%20unidades,opacidad%20(grado%20de%20transparencia).<br>
Centro de ayuda de Arbortext. (s. f.).<br>
https://support.ptc.com/help/arbortext/r8.1.2.0/es/index.html#page/editor/editor_help/help6066_help6066_1.html<br>
    </body>
</html>
