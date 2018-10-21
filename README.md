# ElizabethShch
В данном репозитории Вы можете найти выполненные задания по курсу **"Гуманитарные науки в цифровую эпоху" (2018)**:

1. [Расшифровка](https://github.com/ElizabethRadeckaya/Elizabeth/blob/master/%D0%A0%D1%83%D0%BA%D0%BE%D0%BF%D0%B8%D1%81%D1%8C%20%D0%9F%D1%83%D1%88%D0%BA%D0%B8%D0%BD%D0%B0.xml) стихотворения А.С. Пушкина "Близ мест, где царствует Венеция златая...", выполненная в программе [Текстограф](http://textograf.ru/textograf/editor/#/transcript/98e6084b-b32e-4371-85af-dc135f2e484c).

_Примечание_: При линковании изображения с текстом, в ряде случаев приходилось разбивать вставочную строку на несколько отрезков, а именно вместо того, чтобы записывать "надъ бездной мрачной" в одну строку, мы разбивали её на три вставки друг над другом ("надъ" + "бездной" + "мрачной"), т.к. программа не могла линковать два разных слова по-отдельности в одной "вставочной" строке. 

2. [Сеть персонажей](https://github.com/ElizabethRadeckaya/Elizabeth/blob/master/Untitled.png), сделанную с помощью программы Gephi по роману Мариэм Петросян **"Дом, в котором..."** (Книга 1: "Курильщик").

_Статистика сети следующая:_

* Средняя степень - 5, 913
* Средняя взвешенная степень - 15, 652
* Диаметр графа - 4
* Плотность графа - 0, 131
* Модулярность - 0, 306

Поскольку исходным материалом послужил роман, а не пьеса, следует сделать несколько замечаний. 

Подсчёт персонажей делался в рамках "глав" (поименованных отрывков), далее -- в рамках отдельных эпизодов, отделённых друг от друга пустой строкой в тексте. Зачастую, каждое взаимодействие персонажа с двумя другими, при условии что двое других никак в данный момент не общаются, приходилось считать как отдельную сцену. Специфика пьесы обязала бы автора начать новый акт с появлением нового действующего лица, что в романе никак не наблюдается, из-за чего такое деление приходилось делать искусственно. Например, если _Курильщик_ общается с _Табаки_, после чего _Табаки_ вступает в перебранку с _Лордом_, который, в свою очередь с _Курильщиком_ не заговаривает, эта ситуация разбивалась на две отдельные сцены взаимодействия: 1) Курильщик -- Табаки; 2) Табаки -- Лорд. Если после этого _Лорд_ всё же заговаривал с _Курильщиком_, а _Табаки_ напротив замолкал, это записывалось в отдельную сцену: 3) Курильщик -- Лорд.

Упоминаемые вместе персонажи, если о них ведётся повествование, но прямых диалогов между ними нет, считались вместе, а не по отдельности. Например, если ведётся связный рассказ о _Сфинксе, Лосе, Слепом и Волке_, где они описываются вместе взаимодействующими, они записывались в один ряд: 1) Сфинкс -- Лось -- Слепой -- Волк. В редких случаях группа отдельных персонажей, с которыми взаимодействует герой, именовалась не по количеству известных лиц, включённых в группу, а как отдельная сущность, например: вместо "Сфинкс -- Слепой -- Пышка -- Крючок -- Рекс -- Спортсмен" вводилось "Сфинкс -- Слепой -- Хламовник". Это делалось для того, чтобы разграничить реальное взаимодействие _Сфинкса_ или _Cлепого_ с _Черным_, _Стервятником_ и пр. (выраженное в обмене репликами), с "мнимым" (когда речь идёт о преследовании героев). 

В составлении сети не брались в расчёт упоминания персонажей (размышления о них), если только герой не наблюдает за ними (как зачастую это делает _Курильщик_; он может смотреть как на отдельного персонажа -- например, _Стервятника_ -- так и на группу лиц (например, Крыс, Псов, Фазанов и т.п.).

Поскольку текст книги разбит на два временных пласта: 1) прошлое _Сфинкса_ (от лица Сфинкса=Кузнечика) и 2) настоящее (от лица _Курильщика_), то персонажи из прошлого считались нами по именам, известным в настоящем (Сфинкс=Кузнечик, Табаки=Вонючка, Черный=Спортсмен). Примечательно, что _Горбач_ сохраняет своё прозвище в обеих частях произведения.

**Выводы.** Главными героями первой книги выступили _Курильщик_ и _Сфинкс_. Размер узлов _Курильщика_ составил 36.5, _Сфинкса_ - 45.5, отсюда вывод, что центральным героем повествования является всё-таки _Сфинкс_. _Сфинкс_ чаще всего связан со _Слепым_ (размер узла - 23), _Курильщик_ -- с _Табаки_ (размер узла - 21.5). Эта парность объясняется исходя из сюжета книги: _Сфинкс_ и _Слепой_ растут вместе, _Табаки_ является непосредственным "наставником" _Курильщика_, вовлекающим того в жизнь группы. Неожиданно появление _Горбача_ (размер узла - 24,5), который по ходу повествования не является активным участником событий, однако постоянно упоминается. По частотности упоминаний он сопоставим с _Черным_ (размер узла - 26).

3. [Карту](https://github.com/ElizabethRadeckaya/Elizabeth/blob/master/map.geojson), сделанную с помощью ресурса <http://geojson.io> по песне "Волк" группы "Бергтора".

Песня "Волк" вышла в альбоме группы "Бергтора" в 2005 г. Полный текст приведён ниже. В этом тексте, героиня проходит путь "из Варяг в Греки" -- из скандинавских фьордов в угорские степи и, возможно, в Константинополь. В этом тексте нас интересуют географические названия. 

В песне упоминается вещий Олег (Вольгаст) и Аскольд -- таким образом, действие разворачивается в 80-х годах IX века. В это время правит конунг Харальд Прекрасноволосый (а также один шведский конунг, но, вероятнее, всё же, что речь идёт о Норвегии; Исландия к этому времени ищё не заселена, во всяком случае, никаких указаний на это в песне нет). При дворе Харальда были скальды, см.: 

> В "Саге об Эгиле" (гл. VIII) рассказывается, например, о том, как относился к состоявшим при нем скальдам Харальд Прекрасноволосый: "Из всех дружинников конунг отличал больше всего своих скальдов (Af ollum hirðmonnum virði konungr mest skáld sín). Они занимали почетное сиденье напротив конунга. Дальше всего от входа на этой скамье сидел Аудун Дурной Скальд, старейший из них. Он был еще скальдом Хальвдана Черного, отца Харальда. Следующим сидел Торбьёрн Хорнклови, а дальше Эльвир Хнува". Согласно другим источникам, скальдом Харальда был и автор "Перечня Инглингов" Тьодольв из Хвинира, по прозванию Мудрый, "сердечный друг конунга" и приемный отец одного из его сыновей".(Источник: <http://svr-lit.ru/svr-lit/gurevich-matyushina-skaldy/glava-2-skald-druzhinnik-bond.htm>)

**Расшифровка названий**: "Варягов море" = Балтийское море; "Адельгьюборг" = Ладога (Старая Ладога); "город на холмах" = Хольмгард (букв. 'город на холме (sic!)'= Новгород Великий; "дом Аскольда" = Киев; "Миклогард" = Константинополь.

    Молчит унылая семья и горько плачет мать,
    Несут рождённое дитя под елью умирать,
    Младенцам чаща – мёртвый дом: голодный год пришёл!
    Но волк с серебряным клыком в лесу меня нашёл.

    Меня воспитывал слуга у конунга в дому,
    Он скальдом был, он много знал и научил всему.
    Слагала висы на пирах весёлой злой толпе,
    Мой серый друг один в горах бродил, скучал по мне. 

    Когда, как виру, рыжий свейг хотел забрать с собой,
    Умчал меня во тьму полей мой волк, как резвый конь.
    В Варягов море нас купец увёл за много дней
    Мы шли, и я, и мой храбрец, дорогой лебедей.

    Я в Адельгьюборге была, и Вольгаст молодой
    Нам в чаши мёду наливал, он был хорош собой.
    Потом был город на холмах и был Аскольда дом,
    Мне баял греческий монах про византийский трон.

    Сын воеводы стал отцом двоих моих детей.
    В Купалы ночь вдруг грянул гром среди густых ветвей,
    Степные ветры принесли беду в поля славян!
    Мой ясноглазый воин спит, сокрыл его курган.
    Мой ясноглазый воин спит... А с ним и сыновья.

    Угорский плен, угорский князь, шатры и степь вокруг,
    Стреляли угры, веселясь, мишенью был мой друг.
    Подол рубахи был в крови, на лапах кровь спеклась -
    Вдвоём бежали по степи, мешая кровь и грязь.

    Я знаю, что во фьорд родной я не вернусь теперь.
    Прощай, Гардарика, любовь, прощай, угорский плен!
    Но я увижу Миклогард, есть гусли за плечом
    И рядом верный серый брат с серебряным клыком.
    И рядом волк, седой, как я, с серебряным клыком...

    Молчит унылая семья и горько плачет мать,
    Несут рождённое дитя под елью умирать
    Младенцам чаща - мёртвый дом: голодный год пришёл!
    Но волк с серебряным клыком в лесу меня нашёл...

В процессе составления карты, мы использовали инструмент "область", чтобы показать примерные территории происхождения героини (территории Норвегии, принадлежащие Харальду Прекрасноволосому) и её пленения уграми. 

4. [Краткий критический разбор](https://github.com/ElizabethRadeckaya/Elizabeth/blob/master/%D0%9E%20%D1%81%D1%82%D0%B0%D1%82%D1%8C%D0%B5%20%D0%90.%D0%92.%20%D0%9A%D1%83%D0%BF%D1%80%D0%B8%D1%8F%D0%BD%D0%BE%D0%B2%D0%B0-1.pdf) статьи А.В. Куприянова "От просопографии университетской профессуры до цифрового следа философского парахода: "средние данные" и формальные подходы в истории науки" (2017).
