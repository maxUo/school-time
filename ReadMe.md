{::nomarkdown}
<html><head><meta charset='utf-8'>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/2.4.1/github-markdown.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/9.11.0/styles/default.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.8.3/katex.min.css">
<link rel="stylesheet" href="https://gitcdn.xyz/repo/goessner/mdmath/master/css/mdmath.css">

</head><body class="markdown-body">
<h2 data-line="0" class="code-line" id="%D0%BC%D0%B5%D0%BD%D1%8E">Меню</h2>
<!-- TOC -->


<!-- /TOC -->
<h2 data-line="10" class="code-line" id="%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0-%D1%81%D0%B4%D0%B0%D1%87%D0%B8-%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F">Правила сдачи задания:</h2>
<ol>
<li data-line="11" class="code-line">Задание считается заданым в день мероприятия</li>
<li data-line="12" class="code-line">Задание за прошлую неделю можно сдать включительно до <code>23:59</code> след. дня мероприятия</li>
<li data-line="13" class="code-line">Первые три сдавших получают какие-либо бонусы на усмотрение того, кто проводит тематический мастер-класс</li>
<li data-line="14" class="code-line">Копирайты работ других людей оцениваются в 2 балла</li>
<li data-line="15" class="code-line">Просроченное на неделю задание не может быть оцененно на <code>отлично</code></li>
<li data-line="16" class="code-line">Каждая неделя просрочки понижает максимальную оценку на балл, вплоть до <code>2-х</code> баллов</li>
</ol>
<h2 data-line="17" class="code-line" id="%D0%BA%D0%B0%D0%BA-%D1%81%D0%B4%D0%B0%D0%B2%D0%B0%D1%82%D1%8C-%D0%BD%D0%B0-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D1%83-%D1%81%D0%B2%D0%BE%D0%B8-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F">Как сдавать на проверку свои решения</h2>
<ul>
<li data-line="18" class="code-line">Рекомендация
<ul>
<li data-line="19" class="code-line">Завести себе репозиторий на <a href="https://github.com">GitHub</a>/<a href="https://bitbucket.org">BitBucket</a> и скинуть ссылку на него лично тому, кто принимает <code>В дальнейшем активные люди будут занесены в список и привязаны к своим репозиториям, где будут проверяться их дз</code></li>
</ul>
</li>
<li data-line="20" class="code-line">Как делать можно, но не желательно
<ul>
<li data-line="21" class="code-line">Скидывать проект сжатый в архив <code>zip</code>/<code>7z</code>/<code>rar</code> лично принимающему</li>
<li data-line="22" class="code-line">Вставлять свой код в <a href="https://pastebin.com">PasteBin</a> и отправлять ссылку лично принимающему</li>
</ul>
</li>
</ul>
<h2 data-line="24" class="code-line" id="gui-%D0%B4%D0%BB%D1%8F-%D1%8D%D1%84%D1%84%D0%B5%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D0%B9-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-%D1%81-git">GUI для эффективной работы с Git</h2>
<ul>
<li data-line="25" class="code-line"><a href="https://tortoisegit.org">Tortoise Git</a></li>
<li data-line="26" class="code-line"><a href="https://www.gitkraken.com">GitKraken</a></li>
<li data-line="27" class="code-line">Встроенный в Visual Studio Code Git</li>
<li data-line="28" class="code-line">Встроенный в Visual Studio 15/17 TeamServices</li>
</ul>
<h2 data-line="30" class="code-line" id="%D1%82%D0%B5%D0%BA%D1%81%D1%82%D1%8B-%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D1%8F">Тексты задания</h2>
<ul>
<li data-line="31" class="code-line">
<h3 data-line="31" class="code-line" id="2009-2709">20.09-27.09</h3>
<ul>
<li data-line="32" class="code-line"><code>C#</code> Написать две отдельные программы :
<ul>
<li data-line="33" class="code-line">Реализовать перемножение двух квадратных матриц размера <code>N</code> (т.е одна матрица <code>NxN</code> и вторая <code>NxN</code>) - вводимого с клавиатуры, сами матрицы можно генерировать случайно, или же задавать руками с клавиатуры, с выводом на экран всех трех матриц.</li>
<li data-line="34" class="code-line">Создать 2 класса:
<ul>
<li data-line="35" class="code-line">Класс Point должен иметь два публичных свойства (или автосвойства) <code>X</code> и <code>Y</code></li>
<li data-line="36" class="code-line">Второй должен уметь делать 3 вещи с объектами типа Point:
<ol>
<li data-line="37" class="code-line">Cкладывать два объекта и возвращать новый, получать на вход List<Point> находить там элемент у которого X+Y максимальный из всей коллекции,</li>
<li data-line="38" class="code-line">Уможать два объекта типа <code>Point</code> таким образом:  <eq><span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>X</mi><mtext>новый</mtext></msub><mo>=</mo><msub><mi>X</mi><mn>1</mn></msub><mo>∗</mo><msub><mi>X</mi><mn>2</mn></msub></mrow><annotation encoding="application/x-tex">X\_{\\text{новый}}=X\_{1}\*X\_{2}</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:0.68333em;"></span><span class="strut bottom" style="height:0.83333em;vertical-align:-0.15em;"></span><span class="base"><span class="mord"><span class="mord mathit" style="margin-right:0.07847em;">X</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.151392em;"><span style="top:-2.5500000000000003em;margin-left:-0.07847em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord text mtight"><span class="mord mathrm mtight">новый</span></span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mrel">=</span><span class="mord"><span class="mord mathit" style="margin-right:0.07847em;">X</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.07847em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathrm mtight">1</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mbin">∗</span><span class="mord"><span class="mord mathit" style="margin-right:0.07847em;">X</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.07847em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathrm mtight">2</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span></span></span></span></eq> <eq><span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>Y</mi><mrow><mtext>новый</mtext><mo>=</mo></mrow></msub><msub><mi>Y</mi><mn>1</mn></msub><mo>∗</mo><msub><mi>Y</mi><mn>2</mn></msub></mrow><annotation encoding="application/x-tex">Y\_{\\text{новый}=}Y\_{1}\*Y\_{2}</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:0.68333em;"></span><span class="strut bottom" style="height:0.83333em;vertical-align:-0.15em;"></span><span class="base"><span class="mord"><span class="mord mathit" style="margin-right:0.22222em;">Y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.151392em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord text mtight"><span class="mord mathrm mtight">новый</span></span><span class="mrel mtight">=</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mord"><span class="mord mathit" style="margin-right:0.22222em;">Y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathrm mtight">1</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mbin">∗</span><span class="mord"><span class="mord mathit" style="margin-right:0.22222em;">Y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.30110799999999993em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathrm mtight">2</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span></span></span></span></eq>,</li>
<li data-line="39" class="code-line">Находить факториал от X и складывать его с <eq><span class="katex"><span class="katex-mathml"><math><semantics><mrow><msup><mi>π</mi><mi>Y</mi></msup></mrow><annotation encoding="application/x-tex">\\pi^Y</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:0.8413309999999999em;"></span><span class="strut bottom" style="height:0.8413309999999999em;vertical-align:0em;"></span><span class="base"><span class="mord"><span class="mord mathit" style="margin-right:0.03588em;">π</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height:0.8413309999999999em;"><span style="top:-3.063em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight" style="margin-right:0.22222em;">Y</span></span></span></span></span></span></span></span></span></span></span></eq> и возвращать новый объект типа Point(<eq><span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>X</mi><mtext>новый</mtext></msub><mo separator="true">,</mo><msub><mi>Y</mi><mtext>новый</mtext></msub><mo>)</mo></mrow><annotation encoding="application/x-tex">X\_{\\text{новый}},Y\_{\\text{новый}})</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:0.75em;"></span><span class="strut bottom" style="height:1em;vertical-align:-0.25em;"></span><span class="base"><span class="mord"><span class="mord mathit" style="margin-right:0.07847em;">X</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.151392em;"><span style="top:-2.5500000000000003em;margin-left:-0.07847em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord text mtight"><span class="mord mathrm mtight">новый</span></span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mpunct">,</span><span class="mord"><span class="mord mathit" style="margin-right:0.22222em;">Y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.151392em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord text mtight"><span class="mord mathrm mtight">новый</span></span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mclose">)</span></span></span></span></eq>, такой что <eq><span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>X</mi><mtext>новый</mtext></msub><mo>=</mo><mi>F</mi><mi>a</mi><mi>c</mi><mi>t</mi><mi>o</mi><mi>r</mi><mi>i</mi><mi>a</mi><mi>l</mi><mo>(</mo><mi>X</mi><mo>)</mo></mrow><annotation encoding="application/x-tex">X\_{\\text{новый}}=Factorial(X)</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:0.75em;"></span><span class="strut bottom" style="height:1em;vertical-align:-0.25em;"></span><span class="base"><span class="mord"><span class="mord mathit" style="margin-right:0.07847em;">X</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.151392em;"><span style="top:-2.5500000000000003em;margin-left:-0.07847em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord text mtight"><span class="mord mathrm mtight">новый</span></span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mrel">=</span><span class="mord mathit" style="margin-right:0.13889em;">F</span><span class="mord mathit">a</span><span class="mord mathit">c</span><span class="mord mathit">t</span><span class="mord mathit">o</span><span class="mord mathit" style="margin-right:0.02778em;">r</span><span class="mord mathit">i</span><span class="mord mathit">a</span><span class="mord mathit" style="margin-right:0.01968em;">l</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.07847em;">X</span><span class="mclose">)</span></span></span></span></eq>, <eq><span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>Y</mi><mtext>новый</mtext></msub><mo>=</mo><msup><mi>π</mi><mi>Y</mi></msup><mo>+</mo><mi>F</mi><mi>a</mi><mi>c</mi><mi>t</mi><mi>o</mi><mi>r</mi><mi>i</mi><mi>a</mi><mi>l</mi><mo>(</mo><mi>X</mi><mo>)</mo></mrow><annotation encoding="application/x-tex">Y\_{\\text{новый}}=\\pi^Y+Factorial(X)</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height:0.8413309999999999em;"></span><span class="strut bottom" style="height:1.0913309999999998em;vertical-align:-0.25em;"></span><span class="base"><span class="mord"><span class="mord mathit" style="margin-right:0.22222em;">Y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.151392em;"><span style="top:-2.5500000000000003em;margin-left:-0.22222em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord text mtight"><span class="mord mathrm mtight">новый</span></span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"></span></span></span></span></span><span class="mrel">=</span><span class="mord"><span class="mord mathit" style="margin-right:0.03588em;">π</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height:0.8413309999999999em;"><span style="top:-3.063em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathit mtight" style="margin-right:0.22222em;">Y</span></span></span></span></span></span></span></span><span class="mbin">+</span><span class="mord mathit" style="margin-right:0.13889em;">F</span><span class="mord mathit">a</span><span class="mord mathit">c</span><span class="mord mathit">t</span><span class="mord mathit">o</span><span class="mord mathit" style="margin-right:0.02778em;">r</span><span class="mord mathit">i</span><span class="mord mathit">a</span><span class="mord mathit" style="margin-right:0.01968em;">l</span><span class="mopen">(</span><span class="mord mathit" style="margin-right:0.07847em;">X</span><span class="mclose">)</span></span></span></span></eq>.</li>
</ol>
</li>
</ul>
</li>
</ul>
</li>
<li data-line="40" class="code-line"><code>Git</code>
<ul>
<li data-line="41" class="code-line">Завести аккаунт на github</li>
<li data-line="42" class="code-line">Создать публичный репозиторий для демонстрации своих дз всему миру</li>
<li data-line="43" class="code-line">Скопировать ваш репозиторий на свой компьютер</li>
<li data-line="44" class="code-line">Сделать дз по C#</li>
<li data-line="45" class="code-line">Отправить изменения на свой репозиторий в git</li>
<li data-line="46" class="code-line">Кинуть ссылку на свой репозиторий принимающему</li>
</ul>
</li>
</ul>
</li>
<li data-line="47" class="code-line">
<h3 data-line="47" class="code-line" id="1309-2009">13.09-20.09</h3>
<ul>
<li data-line="48" class="code-line"><code>C#</code> Написать две отдельные функции :
<ol>
<li data-line="49" class="code-line">Получает на вход <code>int</code> количество цифр и выдает на выходе <code>List&lt;int&gt;</code> (динамический массив), состоящий из последовательных чисел Фибоначчи.</li>
<li data-line="50" class="code-line">Получает на вход <code>int</code> факториал какого числа посчитать, и возвращает <code>int</code> значение факториала.</li>
</ol>
</li>
</ul>
</li>
</ul>
</body></html>
{:/}