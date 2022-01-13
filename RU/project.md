# JokeR
  <p align="center">
  <img src="../img/Joker.png" width="120" height="142">
  </p>

[Главная](index) | Проект | [Публикации](publications) | [Партнеры](partners) | [Свяжитесь с нами](contact) | [Приложения](tools) | [<img src="../img/drapeau EN.png" width="20">](https://lepocci.github.io/joker-/EN/index) [<img src="../img/drapeau FR.png" width="20">](https://lepocci.github.io/joker-/FR/index)  [<img src="../img/drapeau ES.png" width="20">](https://lepocci.github.io/joker-/EN/index)  [<img src="../img/drapeau PT.png" width="20">](https://lepocci.github.io/joker-/EN/index) 
<br>
  <h1 align="center"><a href="https://lepocci.github.io/joker-/EN">Мастерклассы CLEF JOKER</a>:</h1>
  <h2 align="center">Автоматичесский перевод каламбуров и юмора</h2>

  <h3>Темы и цели</h3>
  
  Цель — объединить научное сообщество, заинтересованное в автоматической локализации юмора и каламбуров. Проект JokeR рассматривает вопрос европейской идентичности через изучение юмора в кросс культурной перспективе. Основной целью проекта JokeR является изучение стратегий локализации юмора и каламбуров и создание многоязычного параллельного корпуса, аннотированного в соответствии с этими стратегиями, открытого и свободно доступного, а также оценочных метрик.

  <h3>Мотивация & релевантность для CLEF и значимость для области</h3> 

  Межкультурная коммуникация в значительной степени зависит от перевода. Юмор, безусловно, остается одним из самых сложных аспектов. Чтобы понять юмор, часто приходится улавливать неявные культурные отсылки и/или улавливать двойные смыслы, что, конечно, поднимает вопрос о (не)переводимости юмора. Каламбуры являются распространенным источником юмора и используются писателями, поэтами и драматургами. Применяется в названиях оганизаций, в заголовках, топонимах, антропонимах и рекламе для привлечения внимания или мнемонических, игровых, пагубных и т.п. значений. Таким образом, перевод юмора и каламбуров пользуется повышенным спросом. Современный перевод в значительной степени опирается на технологические инструменты, однако лишь в нескольких работах изучалась автоматизация перевода юмора и каламбуров и создание юмористических корпора. Насколько нам известно, параллельного корпуса не существует.

   **Многоязычный параллельный корпус**, выпущенный по результатам семинара JokeR, станет шагом вперед в автоматизации локализации юмора для обучения и оценки моделей машинного перевода. **Монолингвальных** корпусов юмора существует немного; например, наборы данных, созданные для задач Международного семинара по семантической оценке SemEval [1]–[3] <a href="#note1">[1]–[3]</a>: #HashtagWars: Обучение чувству юмора (2017), Обнаружение и интерпретация английских каламбуров (2017), Оценка юмора в отредактированных заголовках новостей (2020), HaHackathon: Выявление и оценка юмора и оскорблений (2021). Михалча и Страппарава <a href="#note1">[4]</a> собрали 16 000 юмористических предложений и столько же отрицательных примеров из заголовков новостей, пословиц, British National Corpus и набора данных Open Mind Common Sense, а другой набор данных содержит 2 400 каламбуров и не-каламбуров из новостей, Yahoo!Answers и пословиц <a href="#note1">[5]</a>, <a href="#note2">[6]</a>. Большинство наборов данных на английском языке; несколько исключений на итальянском  <a href="#note2">[7]</a>,русском <a href="#note2">[8]</a>, <a href="#note2">[9]</a>, и испанском <a href="#note2">[10]</a>.

  <h3>Домен приложений</h3>

  Многоязычные данные и метрики, полученные в результате мастер-класса JokeR, станут шагом вперед в автоматизации локализации юмора для обучения и оценки моделей машинного перевода. Этот корпус также может быть полезен для студентов перевода. 

  <h3>Настройка оценки, метрики и пробные задания</h3>

  Цель мастер-класса JokeR - собрать вместе переводчиков и компьютерщиков для работы над системой оценки креативных языков. Будут приветствоваться все виды вкладов:
  - Исследовательские и обзорные работы
  - Позиционные, дискуссионные и демонстрационные доклады
  - Расширенные тезисы опубликованных статей

  <h3>Пробные задания</h3>

**Пробное задание 1**: Классифицируйте и объясните заданную каламбурную конструкцию в собственном существительном или неологизме. Классификация будет оцениваться по точности, а объяснение будет сравниваться с золотым стандартом (точное совпадение).

**Пробное задание 2**: Переведите заданный каламбур от собственного существительного или неологизма с английского на французский язык

**Пробное задание 3**: Переведите заданную каламбурную фразу с английского на французский язык.


Для задач 2 и 3 необходимо установить метрики для оценки качества перевода. Традиционно качество машинного перевода измеряется метрикой BLEU (Bilingual Evaluation Understudy), которая рассчитывает словарное дублирование между переводом-кандидатом и эталонным переводом <a href="#note2">[11]</a>. Однако ни одна метрика, основанная на словарном дублировании, не применима для оценки творческого языкового перевода. Во-первых, мы выберем анкету, которую будут заполнять аннотаторы ("присутствует ли игра слов в переводе?", "сохранено ли семантическое поле в переводе?" и т.д.). В конце мастер-класса мы изучим автоматизацию выбранных метрик.


<h3>Ожидаемая продолжительность мастер-класса на конференции - полдня:</h3>

Вступительное слово 15 мин
  - Приглашенный докладчик 1 ч
  - Презентации участников 15 минут + 5 минут на вопросы
  - Заключительная речь 15 мин

<p>
  <a href="./JOKER_CLEF_2021.pdf"><h3>Кампания по оценке CLEF (pdf)</h3></a>
</p>

<h3 id="note1">Ссылки:</h3>
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

 <iframe width="560" height="315" src="https://www.youtube.com/embed/lkLq8xc3hMc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<p>
<em>Этот проект получил государственный грант, управляемый Национальным исследовательским агентством в рамках программы «Investissements d'avenir» со ссылкой ANR-19-GURE-0001.</em>
</p>
<p>
<em>JokeR поддерживается Институтом гуманитарных наук в Бретани (MSHB).</em>
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
