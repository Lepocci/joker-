# JokeR
  <p align="center">
  <img src="../img/Joker.png" width="120" height="142">
  </p>

[Pagina principal](index) | Proyecto | [Publicaciones](publications) | [Socios](partners) | [Contáctanos](contact) | [Herramientas](tools) | [<img src="../img/drapeau EN.png" width="20">](https://lepocci.github.io/joker-/EN/index) [<img src="../img/drapeau FR.png" width="20">](https://lepocci.github.io/joker-/FR/index)  [<img src="../img/drapeau RU.png" width="20">](https://lepocci.github.io/joker-/RU/index)  [<img src="../img/drapeau PT.png" width="20">](https://lepocci.github.io/joker-/PT/index)
<br>
  <h1 align="center"><a href="https://lepocci.github.io/joker-/EN">CLEF Workshop JOKER</a>:</h1>
  <h2 align="center">Traducción Automática de Juegos de Palabras y Humor</h2>

  <h3>Tópicos y Objetivos:</h3>
  
  El objetivo es unir la comunidad científica interesada en la localización automática de humor y juegos de palabras. El proyecto JokeR aborda la cuestión de la identidad europea a través del estudio del humor en una perspectiva transcultural. El principal objetivo del proyecto JokeR es estudiar las estrategias de localización de humor y juegos de palabras de modo a crear un corpus multilingüe paralelo, anotado según estas estrategias, de libre acceso y libremente accesible, así como las métricas de evaluación.

  <h3>Motivación y relevancia para el CLEF e Importancia para el campo:</h3> 

  La comunicación intercultural depende muchísimo de la traducción. El humor se mantiene sin duda en unos de sus aspectos más difíciles, para entender el humor, uno tiene que captar las referencias culturales implícitas/o doble significados, lo que, por supuesto, plantea la cuestión de la (in)traducibilidad del humor. Los retruécanos son un elemento muy común en el humor los cuales son usados por novelistas, poetas, y dramaturgos, así como en títulos, manchetas, topónimos, antropónimos, organizaciones y publicidad, con el objetivo de llamar la atención o mnemónica, divertida, subversiva etc...  La traducción del humor y retruécanos esta por lo tanto muy solicitada. La traducción moderna se ve muy favorecida por las herramientas tecnológicas, pero son pocos los trabajos que han estudiado la automatización de la traducción de humor, retruécanos y la creación de corpus de humor.

  Hasta onde sabemos no existe ningún corpus paralelo. El **corpus multilingüe paralelo** publicado como resultado del workshop de JokeR será un paso adelante en la automatización de la localización del humor para entrenar y evaluar modelos de traducción automática. Hay pocos corpusw **monolingües** de humor;  por ejemplo, conjuntos de datos creados para las tareas del Workshop Internacional de Evaluación Semántica SemEval <a href="#note1">[1]–[3]</a>: #HashtagWars: Learning a Sense of Humor (2017), Detection and Interpretation of English Puns (2017), Assessing Humor in Edited News Headlines (2020), HaHackathon: Detecting and Rating Humor and Offense (2021). Mihalcea y Strapparava <a href="#note1">[4]</a> colectaron 16.000 frases humorísticas y un idéntico número de muestras negativas de titulos de noticias, proverbios, el Corpus Nacional Britanico, y un conjunto de datos del Open Mind Common Sense, mientras otros conjuntos de datos contenían 2.400   retruécanos y no-retruécanos del noticiario, Yahoo!Answers, y proverbios <a href="#note1">[5]</a>, <a href="#note2">[6]</a>. La mayoría de los conjuntos de datos están en Ingles, aunque haya algunas excepciones para el Italiano <a href="#note2">[7]</a>, Russo <a href="#note2">[8]</a>, <a href="#note2">[9]</a>, y Español <a href="#note2">[10]</a>.

  <h3>Dominio de aplicación</h3>

  Los datos y métricas multilingües resultantes del taller JokeR serán un paso adelante en la automatización de la localización del humor para entrenar y evaluar modelos de traducción automática. Este corpus también puede ser útil para estudiantes de traducción. 

  <h3>Configuración de evaluación, métricas y tareas piloto</h3>

  El objetivo del taller JokeR es reunir a traductores y informáticos para trabajar en un marco de evaluación del lenguaje creativo. Todo tipo de contribuciones serán bienvenidos:
  - Documentos de investigación y encuestas
  - Documentos de posición, debate y demostración
  - Resúmenes ampliados de artículos publicados

  <h3>Tareas piloto</h3>

**Tarea piloto 1**: Clasifica y explica una construcción de un juego de palabras en un nombre propio o un neologismo. La clasificación será evaluada por la precisión, mientras que la explicación será comparada con el estándar de oro (coincidencia exacta).

**Tarea piloto 2**: Traducir um juego de palabras de un sustantivo o neologismo del Ingles al Francés.

**Tarea piloto 3**: Traduce un juego de palabras de inglés para francés. 

Para las tareas 2& 3, es necesario establecer métricas para evaluar la calidad de la traducción. Tradicionalmente, la calidad de la traducción automática se mide por la BLEU (Bilingual Evaluation Understudy) métrica, que calcula solapamiento de vocabulario entre la traducción candidata y la traducción de referencia <a href="#note2">[11]</a>. Sin embargo, ninguna métrica basada en el solapamiento de vocabulario es aplicable para evaluar la traducción creativa de idiomas. Primeramente, optaremos por un cuestionario que rellenarán los anotadores(“está presente el juego de palabras en la traducción?”, “se conserva el campo semántico en la traducción?” etc.). En el final del taller, estudiaremos la automatización de las métricas seleccionadas. 

<h3>La duración prevista del taller en la conferencia es de media jornada:</h3>

Discurso de apertura 15 min
  - Orador invitado 1 h
  - Presentaciones de los participantes 15 min + 5 min para preguntas
  - Discurso de clausura 15 min

<p>
  <a href="./JOKER_CLEF_2021.pdf"><h3>CLEF campaña de evaluación (pdf)</h3></a>
</p>

<h3 id="note1">Referencias:</h3>
  <p>
<p>[1]	‘SemEval-2021 Tasks’, SemEval-2021. https://semeval.github.io/SemEval2021/tasks.html (accessed Mar. 02, 2021).</p>
<p>[2]	‘Tasks < SemEval-2017’. https://alt.qcri.org/semeval2017/index.php?id=tasks (accessed Mar. 02, 2021).</p>
<p>[3]	‘Tasks < SemEval-2020’. https://alt.qcri.org/semeval2020/index.php?id=tasks (accessed Mar. 02, 2021).</p>
<p>[4]	R. Mihalcea and C. Strapparava, ‘Making Computers Laugh: Investigations in Automatic Humor Recognition’, in Proceedings of Human Language Technology Conference and Conference on Empirical Methods in Natural Language Processing, Vancouver, British Columbia, Canada, Oct. 2005, pp. 531–538. Accessed: Mar. 02, 2021. [Online]. Available: https://www.aclweb.org/anthology/H05-1067</p>
<p>[5]	A. Cattle and X. Ma, ‘Recognizing Humour using Word Associations and Humour Anchor Extraction’, in Proceedings of the 27th International Conference on Computational Linguistics, Santa Fe, New Mexico, USA, Aug. 2018, pp. 1849–1858. Accessed: Mar. 02, 2021. [Online]. Available: https://www.aclweb.org/anthology/C18-1157</p>
<p id="note2">[6]	D. Yang, A. Lavie, C. Dyer, and E. Hovy, ‘Humor Recognition and Humor Anchor Extraction’, in Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing, Lisbon, Portugal, Sep. 2015, pp. 2367–2376. doi: 10.18653/v1/D15-1284.</p>
<p>[7]	A. Reyes, D. Buscaldi, and P. Rosso, ‘An Analysis of the Impact of Ambiguity on Automatic Humour Recognition’, in Text, Speech and Dialogue, Berlin, Heidelberg, 2009, pp. 162–169. doi: 10.1007/978-3-642-04208-9_25.</p>
<p>[8]	V. Blinov, V. Bolotova-Baranova, and P. Braslavski, ‘Large Dataset and Language Model Fun-Tuning for Humor Recognition’, in Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, Florence, Italy, 2019, pp. 4027–4032. doi: 10.18653/v1/P19-1394.</p>
<p>[9]	A. Ermilov, N. Murashkina, V. Goryacheva, and P. Braslavski, ‘Stierlitz Meets SVM: Humor Detection in Russian’, in Artificial Intelligence and Natural Language, Cham, 2018, pp. 178–184. doi: 10.1007/978-3-030-01204-5_17.</p>
<p>[10]	S. Castro, L. Chiruzzo, A. Rosá, D. Garat, and G. Moncecchi, ‘A Crowd-Annotated Spanish Corpus for Humor Analysis’, in Proceedings of the Sixth International Workshop on Natural Language Processing for Social Media, Melbourne, Australia, Jul. 2018, pp. 7–11. doi: 10.18653/v1/W18-3502.</p>
<p>[11]	K. Papineni, S. Roukos, T. Ward, and W.-J. Zhu, ‘BLEU: a method for automatic evaluation of machine translation’, in Proceedings of the 40th annual meeting on association for computational linguistics, 2002, pp. 311–318.<p/>
  </p>
  
<p>
<em>Este proyecto ha recibido una subvención gubernamental gestionada por la Agencia Nacional de Investigación dentro del programa "Investissements d'avenir" con la referencia ANR-19-GURE-0001
</em>
</p>
<p>
<em>JokeR cuenta con el apoyo del Instituto de Ciencias Humanas de Bretaña (MSHB)</em>
</p>
<div align="center">
  <a href="https://www.mshb.fr"><img src="../img/MSHB.jpg" height="120"></a>
  <a href="https://sea-eu.org/?lang=fr"><img src="../img/SEA-EU.png" height="120"></a>
  <a href="https://www.gouvernement.fr/le-programme-d-investissements-d-avenir"><img src="../img/Investissement avenir.jpeg" height="120"></a>
</div>
<br />
<div align="center">
  <a href="https://clef2022.clef-initiative.eu/index.php"><img src="../img/CLEF2022.png" height="90"></a> 
</div>
