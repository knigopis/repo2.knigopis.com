# List of books read by [rnixik](https://plus.google.com/u/0/116191270391964650818/)<sup>76</sup>
---

## 2024

### Столпы Земли
Кен Фоллетт
> [2024-05] Одна из лучших для меня книг именно из-за удержания моего внимания. Если кратко, это история о строительстве собора в монастыре, а также несколько историй любви. В книге описана жизнь нескольких поколений. В книге довольно много жестокости.
> Понравилось, как описана жизнь в замках, передвижение по опасным большим дорогам и многое другое.



## 2023

### Building Microservices: Designing Fine-Grained Systems
Sam Newman
> [2023-10-04] По содержанию книга во многом пересекается с книгой с кабанчиком. Но здесь сложнее слог, размытее обороты и поверхностнее описаны ситуации и концепции.
> В этой книге со многих сторон описано то, с чем можно столкнуться при разработке микросервисов. 
> Есть отдельная глава о том, как проводить границы между сервисами, то есть, чем должен заниматься отдельный сервис, а чем нет. Но это довольно размыто и вся рекомендация сводится к использованию bounded contexts из DDD.
> Есть про разные виды тестирования и их пропорции, но при этом не затронута проблема того, как конкретно или какими инструментами можно удобно собирать систему под тестирования из самых разных версий микросервисов. А дело в том, что там много нюансов и многое зависит от конкретного продукта, поэтому в такой тонкой книге этого не описать. 
> Книга старается давать универсальные советы, но из-за этого они поверхностные.
> В целом, книгу можно почитать, особенно если заинтересовали какие-то конкретные разделы.


### Designing Data-Intensive Applications
Martin Kleppmann
> [2023-06-07] Очень понравилась книга подробным списком различных проблем, которые могут случиться при работе с данными, как на одной ноде, так и в распределенных системах. 
> Из простого, например, чтение из реплики того, что только что записали в мастер.
> Из интересного, например, что нельзя полностью полагаться на время для упорядочивания событий в распределенных системах.
> Но книга понравилась не только описанием проблем, но и довольно конкретными примерами, как некоторые сложные проблемы можно решить. Например, в последней главе книги описан способ избежания распределенной транзакции при выполнении операции перевода денег в распределенной системе (с партицированием и очередью сообщений). Еще запомнилась критика популярных терминов ACID и CAP-теоремы.
> Книга не только про проблемы, она еще хорошо описывает много разных технологий, таких как форматы данных (binary json), схемы взаимодействия, серверное ПО, типы баз данных, разницу в брокерах сообщений и прочее. Много внимания уделяется поддержанию консистентности данных и устойчивости системы к сбоям. 
> 
> В книге упоминаются способы достижения консенсуса, но не так глубоко. То есть, рассматривается только распределенная система из нод, которым можно доверять. Случай с криптосистемами лишь упоминается мельком.
> 
> Книгу рекомендую тем, кому интересно проектирование распределенных систем хранения и обработки данных.



## 2022

### Разработка через тестирование
Кент Бек
> Книга весьма объемная, но суть довольно краткая. Есть три шага:
> 1. Напиши тест, пусть падает
> 2. Напиши наиболее простую реализацию под тест, чтобы он проходил
> 3. Отрефактори реализацию
> Остальное вокруг этого: как выбирать размер теста, насколько простой должна быть реализация и тому подобное с конкретными примерами.
> На мой взгляд, глава с примером написания тестера очень неудачная, легко запутаться где тест, где код. 
> Для себя понял, что размер теста и сложность реализации выбирать нужно по своему опыту. Если пока нет опыта, то выбирать поменьше и потом наращивать.


### Вальсируя с медведями
Том ДеМарко, Тимоти Листер
> Прочитал половину. В книги про то, как нужно работать с рисками. А именно, как их находить, как определять важность, как подготавливаться к их наступлению или не наступлению и тому подобное.


### Девять принцев Амбера
Роджер Желязны
> Прошел год и я почти полностью забыл содержание, чтобы что-то здесь указать



## 2021

### Мифический человеко-месяц
Фредерик Брукс
> [2021-01-04] Книга об управлении разработкой очень крупных программных проектов. В ней описываются организационные сложности, пути их решения. Много уделяется внимания срокам разработки. А именно, из чего они формируются, как их контролировать, из-за чего срываются. Также описаны рекомендации по иерархии ролей в команде, организация обмена информацией внутри проекта и многое другое. Опыт автора получен в разработке проекта на 1000+ человек.
> 
> Книга больше подойдёт тем, кто интересуется менеджерской составляющей разработки ПО, чем самим программистам. Но даже для них многое может показаться устаревшим. Если читать поздние переиздания, то после основного содержания автор подробно разбирает спорные моменты, указывает на устаревшие моменты, а иногда и вовсе меняет точку зрения на противоположную.
> 
> Для меня наиболее запоминающимися стали рекомендации о важности единообразия архитектуры и только одного главного архитектора (как способ достичь единообразия), об отделении проектировщиков от реализаторов, о нисходящем проектировании ("наращивать программу, а не строить сразу", то же, что "трассирующие пули" из Программист-прагматик), об одинаковых привилегиях менеджерам и проектировщикам, об устаревании блок-схем и их бесполезности.
> 
> Много уделено внимания серебряной пуле увеличения производительности программистов, а именно тому, что её не существует и скоро не появится. Это основано на том, что основная сложность - это создание высокоуровневых структур в голове программиста при проектировании, а написание кода - это второстепенное.
> 
> Всё же книга для меня показалась скучной, а многие выводы слабоподкреплёнными.



## 2020

### Грокаем алгоритмы. Иллюстрированное пособие для программистов и любопытствующих
Бхаргава Адитья
> [2020-11-27] Потрясающая книга о структурах данных и алгоритмах. Понравилось тем, как доступно все объясняется, примеры простые и от этого понятные. Массивы, списки, хеш-таблицы, графы - то, что нужно. И к этому добавляются еще и популярные задачи и алгоритмы, которыми они решаются. Книга при этом небольшая.


### Программист-прагматик. Путь от подмастерья к мастеру
Дейв Томас и Энди Хант
> [2020-11-22] Книга состоит из практических советов программистам. Для тех, кто уже научился писать на каком-либо языке программирования какие-то программы и теперь хочет стать профессиональным разработчиком, книга затрагивает очень много аспектов. Часть из них покажется весьма банальными, например, использовать систему контроля версий, постоянно учиться, писать тесты и многие другие. Но это только если программист уже получил эти знания в каком-то другом месте. Как и говорят авторы, в книге очень много тем, но из-за количества они описаны поверхностно. При этом по темам даны ссылки для дальнейшего более глубокого изучения.
> 
> Отмечу список наиболее важных по моему мнению практик, которые описаны в этой книге: брать на себя ответственность за свою работу; предотвращать "разбитые окна"; оценивать успех проекта через надежды пользователей; стрельба трассирующими и отличие от прототипа; глубокое изучение редактора исходного кода; оценка скорости алгоритмов; уровни тестирования; важность извлечения корректных требований; важность автоматизации.


### Чистая архитектура. Искусство разработки программного обеспечения
Роберт Мартин
> [2020-11-02] Книга рассказывает, что такое архитектура, из чего она состоит и как проводить границы между составными частями. Довольно подробно рассказано о SOLID и о применении похожих принципов к архитектурным компонентам. Многие правила разделения весьма конкретны. К сожалению, четких правил, когда нужно нагромождать архитектурные слои, а когда нет, не существует. Такие решения нельзя однозначно принять на старте проекта. Автор об этом тоже говорит. Только иногда он приводит примеры архитектуры, где жалуется на излишнюю сложность поддержки, а немного далее он описывает требования к качественной архитектуре, которые влекут за собой те же сложности поддержки. Книга мне понравилась, всё-таки конкретные и понятные концепции в ней есть.



## 2019

### Кровь, пот и пиксели
Джейсон Шрейер
> [2019-07-15] Слушал аудиокнигу. Послушал предисловие, про Witcher 3, Diablo 3 и заключение. Я ожидал от книги большего. В основном рассказывали о том, что выпускать игры сложно. Разработка игр без кранчей не бывает, потому что точно спланировать разработку никому не удается. Из разработки игр говорили больше о сценариях и гейм-дизайнах, чем о технической стороне. Возможно, в историях других игр больше хардкора.


### Открывая организации будущего
Фредерик Лалу
> [2019-05-12] Слушал аудиокнигу. Дослушал только половину. Автор рассказывает о типах компаний и делает подробное описание бирюзовых компаний - там, где нет руководителей, только самоорганизация. Приводит много примеров существующих компаний и примеров того, как в них решаются самые разные ситуации. В целом, заманчиво, но для меня осталось много вопросов.



## 2018

### Процесс
Франц Кафка
> [2018-06-05] Это книга, в которой показано, как главный герой переживает свой судебный процесс в немного сюрреалистическом мире. При этом ни главному герою, ни читателю не дают привычной информации об этом процессе. Стоит отметить, что произведение не было закончено самим автором, но, тем не менее, концовка есть, при этом она проясняет существенные детали процесса.
> 
> В целом, это произведение мне не понравилось. Форма повествования сложная. Масса деталей, для которых не так просто найти объяснение, зачем они описаны. Но книга хороша тем, как в ней создаётся отчаяние, уныние, безнадежность. Этим напомнила даже мир Dark Souls 2, где люди теряют свою человечность, когда бросают попытки двигаться к своей цели.


### Мы
Евгений Иванович Замятин
> [2018-05-07] В книге нам показывают устройство мира, где все под жестким контролем, где жизнь у всех расписана. В этом мире распорядок жизни у обычных людей одинаковый: встают, работают, гуляют в одно и то же время строго до минуты. Но такая жизнь им очень нравится, они чувствуют мощь единства, верят в окончательную победу на всеми проблемами своего мира.
> Форма повествования специфична, в книге используются математические термины, чтобы показать, что все в жизни рассчитано, все математически верно. К сожалению, чем дальше, тем шизофреничнее становится повествование. Такой подход выполняет свои цели, но для меня это создавало трудности при прочтении.


### Гроздья гнева
Джон Стейнбек
> [2018-02-25] Книга показывает очень тяжелую жизнь семей, которые были вынуждены бросить свои дома и переехать в другой штат в поисках работы. Уровень и количество проблем плавно нарастает с самого начала. Люди массово борятся за своё существование, переживают серьезные трудности. Прочтение помогает почувствовать некоторые свои проблемы незначительными.


### Ветер в ивах
Кеннет Грэм
> [2018-02-22] Простая сказка о животных. Похожа на Винни-Пуха. В этой сказки Крот, дядушка Рэт, мистер Барсук и Тоуд (Джабс) ходят друг к другу в гости, решают всякие житейские проблемы и пытаются перевоспитать друг друга.


### Сто лет одиночества
Габриэль Гарсиа Маркес
> [2018-02-09] Эта довольно большая книга рассказывает о жизни одного рода в городе Макондо. Рассказывается о нескольких поколениях одной семьи, в которой принято называть детей одними и теми же именами, что поначалу создает трудности для чтения. Некоторые герои не запоминаются совсем, отчего позже сложно читать про них. Книга показывает, насколько по-разному человек может быть одинок. Но часто одиночество героев не сопровождается их несчастьем, а в основном, успокоением их бурной жизни. Местами написано забавно, но иногда встречается описание жутких вещей.



## 2017

### Винни-Пух
Алан Милн
> [2017-12] Это та самая сказка про Винни-Пуха. Сюжеты легко узнаются из советского мультфильма, который снят по этой книге. Но с мультфильмом есть некоторые расхождения, например, один из главный героев - это Кристофер Робин, которого в мультфильме нет. Понравились забавные песенки Винни-Пуха.


### Лев, колдунья и платяной шкаф
Клайв Стейплз Льюис
> [2017-11-23] Милая, добрая сказка. Довольно короткая, интригующая. Это сказка о Нарнии, куда герои попали через шкаф. Так как это сказка, то здесь не поднимаются проблемы наказаний, поощрений, королевских интриг, сложного выбора, кого спасти, а кого нет.


### Уловка-22
Джозеф Хеллер
> [2017-11-15] Начав читать, я подумал, что это забавная комедия, в которой показывают слегка сумасшедших героев. Чем больше прочитывал, тем жестче происходили события. Веселые формы повествования пересекаются с описанием сцен отчаяния, мучений, безнадежности, смерти. Каждый герой одержим одной идеей до такой степени, что это больше похоже на сумасшествие. Книга об американской эскадрильи во времена Второй мировой. Не так много внимания уделено общей обстановке, сколько показано отношение отдельных людей к ней. В книге поднимаются вопросы о патриотизме, долге Родине, храбрости, стремлении выжить. Объяснение содержания самой уловки упоминается в самом начале, довольно, в шутливой форме. Последний раз она упоминается уже совсем в другом формате и подразумевает жуткое.


### Трилогия "Тёмные начала"
Филип Пулман
> [2017-10-03] В романе рассказывается о приключениях девочки в мире, где у людей есть внешняя отдельная часть их самих существующая в виде говорящих животных. В самом начале книги обнаруживается, что в этом мире видны другие миры, что можно попробовать открыть к ним переход. Об этом первая книга - Северное Сияние. Первая книга для меня очень сильно отличается от остальных. Может, это связано с тем, что она не в переводе Росмэн, а может лучше удалась сама. В первой книге очень захватывающее приключение девочки, полное опасностей, неожиданных поворотов, интригующих тайн. Этим напомнило "Посёлок" Кира Булычева. Но со второй книги повествование стало более серьезным. Подключились проблемы вмешательства церкви, роль Создателя, добавились новые формы жизни. Дочитывать было интересно, но уже не так сильно. В третье книге повествование стало местами нелогичным, появились некоторые противоречия.
> В целом, трилогия хороша, но можно ограничиться только Северным Сиянием.


### Стража! Стража!
Терри Пратчетт
> [2017-07-06] Наконец-то я добрался до истории о страже. Эта книга была о драконе. В ней же познакомили с городской стражей и новеньким служащим Моркоу.  К сожалению, мне не понравилась книга. Почти до самого конца она была для меня скучной. Мне больше по душе пришлись другие ветки приключений Плоского Мира. Хотя Эррол, конечно, забавный.


### Гарри Поттер и Орден Феникса (аудиокнига)
Джоан Роулинг
> [2017-06-27] Занимательно, но под конец книги появилось отвращение к Гарри Поттеру за его поступки и реакции. Хотелось поскорее закончить.


### Автостопом по галактике (роман)
Дуглас Адамс
> [2017-05-18] Прочитал лишь первую книгу из серии. Юмор мне показался похожим на Пратчетта, разве что тема вместо фентези - научная фантастика. Здесь есть шутки о прокладывании межзвездных магистралей, невероятностном двигателе, о компьютере, который создан, чтобы ответить на Главный вопрос. В целом книгу я бы не назвал очень смешной, но местами она интересная.


### Повелитель мух
Уильям Голдинг
> [2017-03-29] Книга о выживании детей без взрослых на острове. В книге показано, как организуется племя, какие трудности испытывает при выполнении совместных задач, а также, как сложно бывает одному донести мысль до остальных. В племени два лидера, их противостояние набирает обороты. Жалости нет.


### О дивный новый мир
Олдос Хаксли
> [2017-02-03] В книге автор создает версию мира, в котором люди почти всегда счастливы. Мир, в котором прогресс достиг некоторого фиксированного уровня, позволяющий утолить все потребности человека. Люди умирают не старея. Размножение контролируется искусственным выведением, нравственные устои формируются гипнозом в состоянии сна. В этом мире нет ограничений на секс, он доступен в любом возрасте и с любым партнером. Семей нет. Отцов и матерей нет. В этот мир попадает Дикарь - человек, выросший в резервации, где сохранилось многое привычное нам.
> 
> Несмотря на то, что это может быть интересным для прочтения, мне показалось это очень скучным. Скучно было все почти до самого конца. Лишь в финале, в диалоге с Главноуправителем, который объяснял, почему нужно убрать религию, литературу и прочее, есть интересные мысли. Приведу лишь один пример:
> "В натуральном виде счастье всегда выглядит убого рядом с цветистыми прикрасами несчастья. И, разумеется, стабильность куда менее колоритна, чем нестабильность. А удовлетворенность совершенно лишена романтики сражений со злым роком, нет здесь красочной борьбы с соблазном, нет ореола гибельных сомнений и страстей. Счастье лишено грандиозных эффектов."


### Дюна
Френк Герберт
> [2017-01-05] "Здесь чары и месть, отвага и честь, дворцы и песок" (из Алладина). Песка особенно много. Но книга все равно очень интересная.
> Интриги, заговоры, предательства. Начало очень захватывающее, к середине слабее, а дальше опять интереснее и интереснее. Концовку читал залпом. Жду теперь нового сериала по книги. Есть, что показать так же красиво, как в Аватаре.
> Оказалось интересным и послесловие от переводчика, где он обосновывал перевод имён, приводил примеры неудач других переводчиков.



## 2016

### Слимп
Михаил Бабкин
> [2016-12-08] Осилил 28%. Не так уж и мало, чтобы понять, что я читаю скучное, непривлекательное произведение с простым, "дворовым" слогом. В книге у нас любители выпить водки и вина с пивом, а такое красивое многообещающее понятие как волшебство направить для воровства со взломом и ничего больше. А службу порядка здесь представляют "полименты". 
> Переключился на чтение Дюны, где после 10 минут стало понятно, что есть варианты для чтения гораздо интереснее, чем Слимп.


### Martian, The
Andy Weir
> [2016-11-30] Как мне и рекомендовали, английский здесь действительно оказался легким к чтению. 
> Сама история интересная, фразы Марка забавные.
> Читал после просмотра фильма, всё хорошо.


### Убить пересмешника
Харпер Ли
> [2016-10-20] Рассказ идёт глазами маленькой девочки, которая растёт в провинции со своим братом, отцом и несколькими другими персонажами. По началу я даже не понял, какая серьезная проблема может быть поднята в этих детских повествованиях, но к середине книги она обнаружилась. Здесь об предрассудках людей.
> Книгу интересно читать, местами очень захватывает.
> Понравилось.


### Некрещеный поп
Николай Лесков
> [2016-10-01] Просто небольшая интересная история. Неплохо показывает быт казаков лет так 150 назад, их отношение к религии. В книге в диалогах было очень много неизвестных мне слов, но в большинстве случаев удавалось понять их значение по контексту.
> Рекомендовать бы, пожалуй, всем не стал.


### Последний герой
Терри Пратчет
> [2016-09-28] Снова приключения Коэна и его Орды. Довольно интересная книга, забавная. Понравилось описание драконов и фразы Хемиша Стукнутого. Книга короче предыдущих раза в два. Ринсвинд здесь уже второстепенный персонаж, его история здесь никак не заканчивается.


### Астровитянка
Ник Горькавый
> [2016-09-20] Ох, какое начало у книги! Я был впечатлён. Автор не дал скучать с самого начала. Смена места действия, приключения, опасность, всё это с бурными эмоциями. Я думал, это станет моей еще одной любимой книгой. 
> Основная проблема, которая портила моё впечатление от второй половины книги - это ярко выраженное превосходство главного героя над всеми остальными. Она быстрее и умнее всех. Временами, конечно, на неё сваливаются неприятности, и её становится жаль. Но оправившись от неприятностей, она снова всех побеждает во всём. В книге есть научные факты, интересные теории, но, мне кажется, и без них получилось бы неплохо, если бы не OVERPOWERED герой.
> Эта книга первая из трёх в серии. Вот конкретно она хорошая. Пока не знаю, буду ли читать другие.


### Серия книг о Ринсвинде (от Цвет волшебства до Последний континент)
Терри Пратчет
> [2016-08-23] Начало серии хорошее, дальше даже лучше. "Интересные времена" прям отлично. 
> А вот "Последний континент" совсем плохой, очень скучная часть. Напомнило быстро наскучившую книгу Макс Фрай "Гнезда Химер".
> Осталась одна книга из серии - "Последний герой". Про неё я забыл, прочитаю потом.


### Страна багровых туч
Братья Стругацкие
> [2016-06-20] В книге описано покорение Венеры: подготовка команды, описание технологий, само посещение Венеры и трудности, которые пришлось испытать героям. Книга понравилась, хорошее космическое путешествие, интересно читать мечты о покорении космоса человечеством.


### Цвет волшебства
Терри Пратчетт
> [2016-03-10] Книга оставила противоречивые впечатления. С одной стороны, это была интересная история с забавными персонажами. С другой стороны, повествование местами было скучное, вводились некоторые персонажи, которые оставались очень недолго. Возможно, дело в том, что эта книга только часть одной большой истории, и все персонажи ещё вернутся. Почитаю дальше, может будет лучше.


### 11.22.63
Стивен Кинг
> [2016-02-20] Книга понравилась, несмотря на обилие локальных наименований и событий, с которыми я не был знаком: марки авто, типы кафе, музыканты, писатели, футбольные команды, политические персонажи и события и т.п.. Первое время это отвлекало, но концентрация понижается ближе к первой четверти.
> Сюжет подаётся хорошо, держит внимание. Любовная линия есть. Ужастиков нет, жести почти тоже. Концовка всей книги удачная, мне понравилась.
> Книга хорошая, но не назвал бы одной из лучших.



## 2015

### Гнезда Химер
Макс Фрай
> [2015-11-29] Осилил 61% этого бреда. Большую часть прочтения выжидал, что начнётся что-нибудь интересное. Грязный мир, непонятные имена, трешёвые ругательства, например, "Фундераст", нет интересных персонажей, нет интересной завязки, нет чудес, Мир Хомана скучен. Все эти описания людей, обычаи больше напоминают какую-то Кин-дза-дза. Читать такое мне было очень тяжело, скучал по Лабиринтам Эхо. А здесь подсовывают человекоподобных говноедов, ветер с именем "Овётгана и как бы Хугайда". Срань и как бы отстой.


### Лабиринты Ехо (цикл книг)
Макс Фрай
> [2015-11-06] Начал читать в июле, дочитал в ноябре. Читать много, но очень интересно.
> Произведение мне очень нравится, в нём есть магия, путешествия между мирами, юмор, приключения. Больше всего мне, наверное, нравятся диалоги персонажей. 
> Концовка очень красивая, не ожидал. Жаль, что кончилось, читал бы ещё. Попробую соседние произведения.


### Голод
Кнут Гамсун
> [2015-06-12] Главный герой просто слегка сумасшедший. Много проблем удалось избежать, если бы не его странные поступки. Причем, в начале их даже нельзя оправдать голодом. Но, видимо, причиной столь затянувшихся проблем стало именно стремление к мечте, иначе бы всякие трудности можно было бы преодолеть быстрее. Да ещё эти deus ex machina в конце каждой главы.
> В целом, не понравилось.


### "Маска Красной смерти" и другие рассказы
Эдгар Аллан По
> [2015-06-11] Сборник мне попался, начинающийся с рассказа о полете на Луну, затем о гигантском водовороте, а потом и сама Маска Красной смерти.
> После многотомных саг читать короткие рассказы очень непривычно. Ощущение, что есть только спецэффекты без сюжета. В полете на Луну это не совсем верно, там достаточно много действий, а вот в следующих - активных действий очень мало, одни эффекты.
> Следующие рассказы уже читать не смог.


### Гордость и предубеждение
Джейн Остин
> [2015-06-05] Хороший роман, интересный. Хотя, конечно, в начале пришлось делать над собой усилие, чтобы вычитывать довольно длинные формулировки. А ещё была проблема отличать "Беннет" и "Бингли", но это индивидуально.
> На английском не потянул.


### Шестой дозор
Сергей Лукьяненко
> [2015-05-22] Всё действительно необычное кончилось в предыдущей части. Здесь уже удивить было нечем. В целом, скучнее, но завершение вполне годное.
> Слегка противоречит первым книгам: по темной сущности Дневного дозора, по планам Завулона.


### Новый Дозор
Сергей Лукьяненко
> [2015-05-13] Всё как и раньше. Хорошо.


### Последний дозор
Сергей Лукьяненко
> [2015-04-28] Неплохо. Всё в том же духе дозоров.


### Сумеречный дозор
Сергей Лукьяненко
> [2015-04-20] Простенько, но не скучно. В духе первого (Ночного) дозора.


### Дневной дозор
Сергей Лукьяненко
> [2015-04-08] Первая часть книги содержит не то, что хотелось бы видеть в этом цикле. А вот дальше интерес возобновился. Вторая и третья часть получились хорошими. Все эти загадки, отгадки, интриги хороши.


### Ночной дозор
Сергей Лукьяненко
> [2015-03-25] Книга интересная, понравилась сразу. Магия, спецэффекты, сомнения и немного ревности. Всё не такое мрачное и грязное, как фильме.


### Град обреченный
Стругацкие
> [2015-03-13] Тяжело начинал. Пересилил себя, дошел до второй главы, втянулся. Дальше пошло лучше. 
> Дочитал с интересом, но после прочтения остался недоволен. Такое ощущение, будто бы пропустил целую главу.
> Много осталось неясно, даже гуглил. Говорят, книга хороша атмосферой. Но нет, это не для меня. 
> Мне не понравилось.


### Трое в лодке, не считая собаки
Джером К. Джером
> [2015-03-02] В основном очень смешная, но иногда разбавляется наискучнейшими историческими вставками.


### Возвышение Хоруса
Дэн Абнетт
> [2015-02-24] Тяжело начинать. Действующих лиц очень много, все имеют имена. К середине, когда запомнил всех, стало легче. К концу и вовсе захватило всё внимание.


### Спектр
Сергей Лукьяненко
> [2015-02-10] Отличная книга. Очень понравилось, как автор показал другие миры. С самого начала была озвучена идея перемещения между мирами за рассказанную историю. Это меня и зацепило. Дальше только интереснее. Хотя и были нудные моменты снобизма, например, про пельмени. 
> А ещё остались у меня некоторые вопросы о содержании, но может в обсуждениях где-нибудь найду ответы.


### Понедельник начинается в субботу
Братья Стругацкие
> [2015-01-22] Первую часть я принял как лихорадочный бред исследователя. Затем мнэ-э-э пошло легче и интереснее. В целом, получилось неплохо.


### Второе Основание
Айзек Азимов
> [2015-01-15] Лучшая из трёх книг об Основании



## 2014

### Основание и Империя
Айзек Азимов
> [2014-12-31] 


### Торговый дом Гердлстон
Артур Конан Дойль
> [2014-12-23] 


### Цветы для Элджернона
Дэниел Киз
> [2014-12-08] 


### Основание
Айзек Азимов
> [2014-11-30] 


### Вино из одуванчиков
Рэй Брэдбери
> [2014-11] Местами скучно, но некоторые истории очень трогательные.
> "Смерть — это когда он месяц спустя стоял возле ее высокого стульчика и вдруг понял, что она никогда больше не будет тут сидеть, не будет смеяться или плакать"


### Дети подземелья
Владимир Короленко
> [2014-10-30] Коротко, но грустно. Хорошая книга.


### 451 градус по Фаренгейту
Рэй Брэдбери
> [2014-10-08] 


### 1984
Джордж Оруэлл
> [2014-10] 


### Gerald's Game
Stephen King
> [2014-10] Не осилил. 40% прочитал и начал пролистывать дальше.


### The Catcher in the Rye
J. D. Salinger
> [2014-09-30] Читал из-за того, что название на слуху. Разочарован.


### Animal Farm
George Orwell
> [2014-09] "I will work harder"


### The Old Man and the Sea
Ernest Hemingway
> [2014-09] 


### Сага "Ведьмак"
Анджей Сапковский
> [2014-08] Сначала скучал. Но когда дело дошло до Предназначения, сильно увлёкся.


### Посёлок
Кир Булычев
> [2014-06-25] Та книга, где Олег, Сергеев и другие.
> Моя любимая. Не из-за каких-то идей, а просто интересно читать.


### Марсианские хроники
Рэй Брэдбери
> [2014-06-21] Будет ласковый дождь - это очень круто


### Трудно быть богом
Братья Стругацкие
> [2014-06-10] Не понравилось


### Пикник у обочины
Братья Стругацкие
> [2014-06-04] Понравилось. Как минимум, читать интересно, не скучал.


### Сага "Песнь Льда и Огня" (от Игры престолов до Танцев с драконами)
Джордж Р. Р. Мартин
> [2014-06-01] 


### Сами Боги
Айзек Азимов
> [2014-01-22] Дочитал до второй главы. Затем пошло столько описаний, что я не выдержал и начал засыпать.


### Конец вечности
Айзек Азимов
> [2014-01-19] 


### Под куполом
Стивен Кинг
> [2014-01-16] Читать интересно было, но в итоге разочарован.
> P.S.: с сериалом мало общего.



## 2004

### Властелин Колец: Братство Кольца, Две Башни, Возвращение Короля
Джон Р. Р. Толкиен


