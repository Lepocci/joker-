# JokeR
  <p align="center">
  <img src="../img/Joker.png" width="120" height="142">
  </p>

[Início](index) | Projeto | [Publicações](publications) | [Parceiros](partners) | [Contactos](contact) | [Ferramentas](tools) | [<img src="../img/drapeau EN.png" width="20">](https://lepocci.github.io/joker-/EN/index) [<img src="../img/drapeau FR.png" width="20">](https://lepocci.github.io/joker-/FR/index)  [<img src="../img/drapeau ES.png" width="20">](https://lepocci.github.io/joker-/ES/index)  [<img src="../img/drapeau RU.png" width="20">](https://lepocci.github.io/joker-/RU/index) 
<br>
  <h1 align="center"><a href="https://lepocci.github.io/joker-/EN">CLEF Workshop JOKER</a>:</h1>
  <h2 align="center">Tradução automática de trocadilhos e de humor</h2>

  <h3>Tópicos e Objetivos</h3>
  
  O objetivo é unificar a comunidade científica interessada na localização automática de humor e trocadilhos. O projeto JokeR aborda a questão da identidade europeia através do estudo do humor numa perspetiva transcultural. O objetivo principal do projeto JokeR é estudar as estratégias de localização de humor e trocadilhos e criar um corpus paralelo multilíngue, anotado de acordo com essas estratégias, aberto e disponível gratuitamente, bem como métricas de avaliação.

  <h3>Motivação e relevância para o CLEF e Importância para a área:</h3> 

 A comunicação intercultural depende muito da tradução. O humor, sem dúvida, continua a ser um dos seus aspectos mais difíceis, para compreender o humor é preciso apreender as referências culturais implícitas/ou trocadilhos, o que, claro, levanta a questão da (in)traduzibilidade do humor.
 Os trocadilhos são um elemento muito comum no humor usado por romancistas, poetas e dramaturgos, bem como em títulos, rótulos, nomes de lugares, antropônimos, organizações e publicidade, com o objetivo de atrair atenção ou mnemônicos, engraçados, subversivos etc. .. A tradução de humor e trocadilhos se encontra, portanto, em alta procura. A tradução moderna é fortemente auxiliada por ferramentas tecnológicas, mas poucos trabalhos estudaram a automação da tradução de humor e trocadilhos e a criação de corpora de humor. Até onde sabemos, não existe nenhum corpus paralelo.

  O **corpus paralelo multilingue** emitido como resultado do workshop JokeR será um avanço na automação da localização de humor para treinar e avaliar modelos de tradução automática. Existem poucos corpora de humor **monolingue**; por exemplo, conjuntos de dados criados para as tarefas do Workshop Internacional de Avaliação Semântica SemEval <a href="#note1">[1]–[3]</a>: #HashtagWars: Learning a Sense of Humor (2017), Detection and Interpretation of English Puns (2017), Assessing Humor in Edited News Headlines (2020), HaHackathon: Detecting and Rating Humor and Offense (2021). Mihalcea e Strapparava <a href="#note1">[4]</a> coletaram 16.000 frases humorísticas e um número igual de amostras negativas de títulos de notícias, provérbios, British National Corpus e o conjunto de dados Open Mind Common Sense, enquanto outro conjunto de dados contém 2.400 trocadilhos e não trocadilhos das notícias, Yahoo! Respostas e provérbios <a href="#note1">[5]</a>, <a href="#note2">[6]</a>. A maioria dos conjuntos de dados está em inglês; poucas exceções em italiano <a href="#note2">[7]</a>, Russo <a href="#note2">[8]</a>, <a href="#note2">[9]</a>, e Espanhol <a href="#note2">[10]</a>.

  <h3>Domínio do aplicativo</h3>

  Os dados e métricas multilíngues resultantes do workshop JokeR serão um passo à frente na automação da localização de humor para treinar e avaliar modelos de tradução automática. Este corpus também pode ser útil para estudantes de tradução. 

  <h3>Configuração de avaliação, métricas e tarefas piloto</h3>

  O objetivo do workshop JokeR é reunir tradutores e cientistas da computação para trabalhar em uma estrutura de avaliação para linguagem criativa. Todos os tipos de contribuições serão bem-vindos:
  - Documentos de pesquisa
  - Documentos de posição, discussão e demonstração
  - Resumos estendidos de artigos publicados

  <h3>Tarefas piloto</h3>

**Tarefa piloto 1**: Classificar e explicar uma dada construção de trocadilhos em um nome próprio ou um neologismo. A classificação será avaliada pela precisão, enquanto a explicação será comparada com o padrão-ouro (correspondência exata).

**Tarefa piloto 2**: Traduzir um trocadilho de um substantivo próprio ou um neologismo do inglês para o francês

**Tarefa piloto 3**: Traduzir uma determinada frase de trocadilho do inglês para o francês. 

Para as tarefas 2 e 3, é necessário estabelecer métricas para avaliar a qualidade da tradução. Tradicionalmente, a qualidade da tradução automática é medida pela métrica BLEU (Bilingual Evaluation Understudy), que calcula a sobreposição de vocabulário entre a tradução candidata e a tradução de referência <a href="#note2">[11]</a>. No entanto, nenhuma métrica baseada na sobreposição de vocabulário é aplicável para avaliar a tradução criativa de idiomas. Primeiramente, optaremos por um questionário a ser preenchido pelos anotadores ("o trocadilho está presente na tradução?", "o campo semântico está preservado na tradução?" etc.). estudará a automação das métricas selecionadas. 

<h3>A duração prevista do workshop na conferência é de meio dia:</h3>

Discurso de abertura 15 min
  - Palestrante convidado 1h
  - Apresentações dos participantes 15 min + 5 min para perguntas
  - Discurso de encerramento 15 minutos

<p>
  <a href="./JOKER_CLEF_2021.pdf"><h3>Campanha de avaliação CLEF (pdf)</h3></a>
</p>

<h3 id="note1">Referências:</h3>
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
  
<iframe width="560" height="315" src="https://www.youtube.com/embed/_yPhOGyPI7o&t=3s" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<p>
<em>Este projeto recebeu um subsídio do governo administrado pela Agência Nacional de Investigação no âmbito do programa "Investissements d'avenir" com a Referência ANR-19-GURE-0001</em>
</p>
<p>
<em>JokeR é apoiado pelo Instituto de Ciências Humanas da Bretanha (MSHB)</em>
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
