# Выпуск №16. 15 мая 2016

Экономия батареи, оптимизация графики, прозрачность в HEX, `!important` можно, таблицы, полифилы.

- Вадим Макеев
- Алексей Симоненко

[Слушайте в iTunes](https://itunes.apple.com/ru/podcast/veb-standarty/id1080500016)
[Слушайте на SoundCloud](https://soundcloud.com/web-standards/episode-16)
[Обсуждайте в Слаке](http://slack.web-standards.ru/)

## События (00:15)

- [Лог трансляции с CSSConf в Будапеште](https://github.com/web-standards-ru/web-standards-up/blob/master/2016-05-11_cssconfbudapest.md)
- [WSD в Екатеринбурге 25 июня](https://wsd.events/2016/06/25/)
- [FrontendFellows в Перми 27 мая](https://frontendfellows.timepad.ru/event/299132/)
- [FrontendFellows в Астане 29 июля](https://frontendfellows.timepad.ru/event/328848/)
- [Rolling Scopes Summer Summit в Минске 4 июня](https://minsk.rollingscopes.com/)
- [Видео с PiterCSS №3](https://youtu.be/24EZOgySNRI?list=PLMBnwIwFEFHeDVHZJw7Y5WWVkAb1O_OwC)

## Как браузеры экономят батарейку (03:39)

- [Introducing power saving mode in Opera](https://www.opera.com/blogs/desktop/2016/05/introducing-power-saving-mode/)

## Оптимизация графики (16:50)

- [Reducing JPG File size](https://medium.com/p/e5b27df3257c)
- [ImageAlpha](https://pngmini.com/)
- [Can I Use: WebP](http://caniuse.com/webp)
- [APNG](https://wiki.mozilla.org/APNG_Specification)
- [MozJPEG](https://github.com/mozilla/mozjpeg)

## Прозрачность в HEX-цветах (33:44)

- [RGBA и RRGGBBAA в Firefox 49](http://codepen.io/malyw/pen/wGNOrd?editors=1100)
- [Color in Opera 10 — HSL, RGB and Alpha Transparency](https://dev.opera.com/articles/hsl-rgb-and-alpha-transparency/)

## !important можно, если нужно (43:06)

- [The Importance of `!important`: Forcing Immutability in CSS](http://csswizardry.com/2016/05/the-importance-of-important/)
- [Likely](https://github.com/ilyabirman/Likely)

## Фантомные страхи и адаптивные таблицы (48:27)

- [CSS only Responsive Tables](http://dbushell.com/2016/03/04/css-only-responsive-tables/)
- [Accessible, Simple, Responsive Tables](https://css-tricks.com/accessible-simple-responsive-tables/)

## Полифил через юзер-агент (52:06)

- [Polyfill.io](https://cdn.polyfill.io/)

---

**Вадим.** Привет, с вами 16-й выпуск подкаста «Веб-стандарты» и его постоянные ведущие: Алексей Симоненко из HTML Academy.

**Лёша.** И Вадим Макеев из Opera.

**Вадим.** А Ольги Алексашенко, верстальщика руками, сегодня с нами нет. У Ольги бал. Поэтому она занята.

## События (00:15)

**Вадим.** На этой неделе было много новостей по всяким событиям, а новостей по технологиям, по всяким браузерным новинкам, наверное было меньше обычного, все-таки приближается лето. Но, давайте поговорим про события. На этой неделе была текстовая трансляция с CSS Conf в Будапеште. Мы уже выложили логи в нашем репозитории на Гитхабе и там довольно много интересного, ссылки, всякие фоточки, и вы можете почувствовать как будто практически съездили на этот CSSConf в Будапешт. Довольно дешево для вас, просто открыть страничку.

Если вы будете сами на каких-нибудь конференциях, ваших локальных встречах, какие-нибудь митапы по чему угодно, околофронтендные, пишите нам, мы с удовольствием дадим вам ключи от нашего уютного Твиттера и вы сможете устроить там текстовую трансляцию сами.

На этой неделе мы анонсировали WSD в Екатеринбурге. Он пройдет 25 июня и мы ищем докладчиков. Пока на странице особо ничего нет, но есть регистрация, поэтому регистрируйтесь, а мы, я думаю, в понедельник-вторник анонсируем первых докладчиков и расскажем подробней про события.

WSD в Екатеринбурге немножко нетрадиционно проходит в июне. А мы, обычно, в июне проводим питерский WSD. Наверное мы проведем его в конце лета, начале осени, а в этот раз нам ребята из FrontendFellows и СКБ контур предложили сделать WSD в Екатеринбурге и мы сказали, а почему бы и нет.

Летом, я думаю, там будет хорошо и интересно. FrontendFellows сами проводят мероприятия регулярно и вот 27 мая будет в Перми их очередная встреча и 29 июля они поедут в Астану. Это будет первый FrontendFellows за пределами России и, по-моему, первое крупное мероприятие по фронтенду в Казахстане. Поэтому я немножко завидую ребятам и надо будет как-нибудь приехать с WSD в Казахстан. Зовите.

Еще в Минске 4 июня пройдет Rolling Scopes Summer Summit, тоже такая встреча регулярная с громким названием Summit. Я давно хочу съездить на конференцию Roolling Scopes, но вот не получается. Может как-нибудь загляну на Summit в Минске. В Минске тоже хорошо.

Еще смонтировали видео с PiterCSS №3 на этой неделе. Немножко поздновато, но лучше поздно, чем никогда, правда? И там, в общем-то, был доклад, который большинство из вас заинтересовал, как Слава Шебанов рассказывал про фронтенд ВКонтакте. Поэтому, если вы еще не добрались и не посмотрели, посмотрите.

Очень много хейтеров пришло, очень много всяких забавных комментариев, но главный плюс этого доклада в том, что он довольно откровенный, честный и, по-моему, интересный. Интересно посмотреть на то, как большие проекты разрабатываются, как они организованы и вообще.

Фронтенд, на самом деле, кажется скучным и маленьким со стороны, но он довольно сложный. Там Слава рассказывает как он, для того, чтобы компилировать CSS, поднимал кластеры на Node.js, в общем, забавно.

Ну и PiterCSS №4 мы проведем где-нибудь в конце мая, наверное, потом прервемся на каникулы. Дату мы анонсируем, я думаю, на днях, так что присылайте ваши заявки, у нас есть еще места для докладов на PiterCSS №4. Дизайн, стили, типографика, вот все вот это, можем даже немножко JS, хотя знаете, наверное не стоит.

## Как браузеры экономят батарейку (03:39)

**Лёша.** Как Вадим уже сказал, на этой неделе было не очень много статей про технологии, но, тем не менее, какая-то их часть была. Наверное, уже традиционно, начнем мы с Opera. Ну, почему бы и нет.

**Вадим.** Ну, да, у нас выпуски иногда превращаются в такую викторину «Спроси у Opera». Лёша задает каверзные вопросы, а я выкручиваюсь. Наверное сегодня тоже самое будет, да?

**Лёша.** Давай попробуем. Ведь статью про то, что в Opera появился режим сохранения батареи, явно писали маркетологи. Поэтому у меня есть несколько вопросов.

**Вадим.** Например?

**Лёша.** Ну, смотри. Меня немножко смутило то, что там сразу в первом абзаце было заявление о том, что Opera — это первый браузер, которая занялась оптимизацией расхода батареи. И мне показалось это немножко лукавством. Потому что, ведь это не так. Тот же самый Safari, и ты об этом когда-то говорил, он очень хорошо работает с сохранением батареи, отключает кучу вещей, отключает многие штуки даже если окно перекрывается. Они тоже этим занимаются и поэтому мне показалось небольшое лукавство, но возможно, там есть под капотом что-то более интересное.

**Вадим.** Ну, в общем-то, все браузеры пытаются экономить энергию, потому что это важная штука, если вы анонсировали, что у вас железка живет 12 часов, а потом пользователь открывает браузер, одну из самых популярных программ, и никаких 12 часов не получается, получается 2 часа, естественно, вы будете врать пользователям. И одной из самых больших проблем всегда в браузере были сторонние плееры, всякие Flash-плееры и SilverLight, в общем плагины, которые воровали-убивали, а в итоге пользователи винили браузер. Когда плагины практически ушли, у меня на макбуке не стоит никакого Flash очень давно и у меня нет встроенного Flash в Opera, поэтому мне регулярно сайты показывают вместо рекламы «Установите Flash-плеер», так приятно. Так вот сейчас эта проблема ушла. Сейчас есть другая проблема. Браузеры, с одной стороны, пытаются рендерить страницу очень быстро и очень круто. Показывать плавную анимацию 60 FPS и так далее. С другой стороны им нужно экономить батарейку. И вот, когда вы подключены к вашей розетке в стене, действительно, браузеры могут делать что хотят, потому что электричество дешевое. Вот, когда вы в дороге, электричество становится для вас дорогим, потому что вы хотите, чтобы ваша батарейка прожила дольше. И можно делать разные вещи. Можно, допустим, фоновые вкладки не загружать, когда вы только что открыли браузер. Можно, допустим, останавливать анимацию, можно останавливать видео. Такие базовые вещи делают все.

Мы пошли немножко дальше и поэтому решили поговорить об этом, потому что это не просто какой-то маркетинговый трюк, а там немножко есть веб-технологий.

Что мы делаем. Мы замедляем некоторую анимацию, _throttling_ так называемый, некоторые части. Допустим, где-то там 60 FPS, а мы снижаем их до 30 FPS. Это экономит очень много энергии. И не только в фоновых вкладках. Когда вы на текущей странице что-то делаете, мы замедляем некоторые вещи, если понимаем, что вы не подключены к розетке. Мы немножко меняем поведение браузеров. Когда вы заходите на YouTube, а YouTube вам говорить привет. Вы ему отправляете какие-то заголовки, ваш браузер отправляет заголовки, в которых вы говорите какие видео форматы вы поддерживаете. И смотрите, если у вас есть аппаратная поддержка кодека H.264, соответственно аппаратный рендеринг гораздо эффективнее с точки зрения энергии, чем софтверный рендеринг, поэтому, когда вы поддерживаете H.264 аппаратно, YouTube может посылать вам это видео, но он предлагает вместо H.264 VP8-кодек. Он лучше сжимается, но он более энергопотребляющий. Соответственно, с точки зрения вашей батарейки, лучше бы он вам отправил видео в H.264. Но YouTube, с точки зрения трафика, посылает вам VP8. И мы такие говорим «а VP8 не поддерживаем, присылай нам H.264». И таким образом экономим вашу батарейку, немножко привирая сайтам, что мы на самом деле поддерживаем.

И там есть еще другие трюки. Там, на самом деле, довольно большой список. И как это произошло. Мы просто посмотрели на средние страницы, посмотрели, куда утекает батарейка, в какие дырки, и позатыкали те дырки, но постарались, естественно, не сломать страницы.

Мы конечно еще экспериментируем с этой штукой. Она в канале Developer. Мы будем смотреть, не ломается ли что либо. Но опять же, мы делаем это не для того, чтобы навредить вам, дорогие разработчики, а для того, чтобы пользователи были довольны и у них батарейка длилась как обещано. Но так уж получилось что мы, приняв архитектуру проекта Chromium, вынуждены были принять и некоторые другие решения. Как то: многопоточность, каждая вкладка в отдельном процессе, какая-то прожорливость к памяти и так далее. Presto был в этом смысле эффективнее, чем Chromium, но Chromium и может больше и развивается быстрее и с точки зрения веб-технологий лучше. Поэтому, да, мы жрем батарейку, но мы делаем это не просто так и сейчас думаем о том, как бы все это дело улучшить. Т.е. не просто сохраняем батарею, а стараемся делать хитрее, как мы это уже делаем с трафиком, в ситуации с Opera Mini, с ситуацией с Opera Turbo, когда мы немножко подменяем трафик, немножко пытаемся сделать вещи, которые не так важны.

**Лёша.** Звучит, конечно, здорово, но у меня такой вопрос к тебе, может быть к вашим маркетологам. Может быть вы выпустите потом еще статью? Вот у вас в статье был хороший тест. Вы тестировали Chrome и Opera. И показали, как вы это делаете, показали на каком оборудовании вы это делаете и, в общем, показали результаты. Это, вроде бы, хорошо, но Chrome специально этим не занимается, сохранением энергии батареи. Почему бы вам не сравнить себя с Safari в похожем режиме? Мне даже самому было бы интересно, на сколько это лучше или хуже, потому что Safari правда очень хорошо сохраняет батарею. Когда совсем уже плохо, на ноутбуке нет энергии, там вообще уже вся система, по-моему, начинает сохранять батарею. И я понимаю, что сравнение с Safari, это только маленькая часть вашего рынка, потому что Opera работает и на Windows и, как я понимаю, сохраняет батарею она также и на Windows, правильно ведь?

**Вадим.** Да, это не просто Mac-фишечка.

**Лёша.** Это было бы более интересно, сравнить два браузера, которые занимаются этим, чем сравнивать браузер, который не занимается этим, с браузером, который этим занимается. Выигрыш понятен.

**Вадим.** Смотри. На самом деле Chromium тоже этим занимается. Ребята из Google тоже этим занимаются, энергоэффективностью. Потому что они в курсе, что у Chrome, по сравнению с другими браузерами память течет больше, прожорливость выше. Но мы сравнивали с Chrome потому что работаем на одной платформе. Можно было еще с Lynx сравнить, который текстовый браузер. Да, наверное, честнее было бы сделать что-то большое, более серьезное исследование. Но [это блог](http://www.opera.com/blogs/news/), он более такой, для пользователей. Если бы это был большой пост в какой-нибудь [ArsTechnica](http://arstechnica.com/) или еще где-нибудь, там нужно было бы серьезное сравнение, экспертов пригласить. Но это немножко другая история. Мы не пытаемся доказать всем разработчикам софта, всем технологическим гуру, что мы лучше. Мы пытаемся сделать продукт для пользователя лучше. Поэтому это было такое легкое маркетинговое исследование. Мы не наврали, но мы не углубились достаточно сильно.

**Лёша.** В плане пользователей это и правда им удобно, потому что, как я понял, как я прочитал, этот режим автоматически включается, когда батарейка уже садится.

**Вадим.** Да-да-да. Смотри. Safari экономит батарейку всегда, на сколько я понимаю. Возможно, она берет из системы информацию о том, что мы не на питании, а на батареи и как-то оптимизирует, но они об этом не рассказывают. Apple известны тем, что «браузер просто работает», «ноутбук просто работает», «ой, завис». Зато до этого просто работал. Поэтому тоже самое с браузером. Может они оптимизируют что-то. Пусть расскажут. Мы с удовольствием посоревнуемся с ними. Наша открытость, мне кажется, играет на нас, мы выглядим симпатичнее.

**Лёша.** Ну, это правда. У меня сейчас почему-то в голову вопрос влез. Раньше Opera славилась тем, что это был большой комбайн. В нем было много разных фич и кто-то Opera именно за это выбрал, кто-то по этой причине не хотел выбирать Opera, но это была такая отличительная особенность. Это браузер в котором было очень много всего. А потом вы это все отрезали, перейдя на Chromium, и сейчас последовательно начинаете добавлять фичу за фичей. И понятно, вы делаете это для удобства, для пользователей, с какой-то идеей, но, тем не менее, браузер так начинает все больше и больше пухнуть. В любом случае, какая бы это хорошая фича не была, их становится много. Это также как Firefox, если ты помнишь, когда он только начинался, там была версия 1.5, 2, там идеальный браузер был. Он был просто невероятно быстрый, молниеносный, хороший. А потом с каждой версией в нем стала появляться какая-то дополнительная фича. Сейчас это монстр, которым пользоваться тяжело. Не боитесь, что вот это может завести опять к тому времени, когда Opera была комбайном? Не то, чтобы это плохо, может это вернет какую-то часть аудитории, которой это нравилось, но вот что думаешь об этом? Не страшно?

**Вадим.** Можно это делать по разному. Смотри. Когда Opera была комбайном, она была комбайном с реактивными двигателями и прицепленными по бокам двумя ресторанами. Потому что, когда у тебя в браузере интегрирован почтовый клиент, торрент-клиент, IRC-чат, еще что-то такое, это совсем не то, когда у тебя висит какая-то штучка, которая определяет подключена у тебя батарейка или нет или какая-нибудь маленькая прокси, которая блокирует рекламу просто на уровне сетевых запросов. Это совсем не то. Мы не пытаемся вернуть аудиторию, которой нравился комбайн. Мы не пытаемся конкурировать с Vivaldi в этом смысле. Потому что у них то как раз все, что можно написать, будет написано и внедрено. А почему? Ну, потому что можем. Мы пытаемся сделать такие консьюмерские, пользовательские штучки, которые на самом деле просто работают. В большинстве случаев, нужно просто нажать кнопочку или она нажимается за вас, если это фича, которая сильно нужна. Многие из них - эксперименты. Я думаю, часть из них уйдет. У нас, долгое время есть такая фича как Turbo и она спрятана где-то далеко за меню и она не включается по умолчанию. Тем, кому это нужно, ее включают. По умолчанию она не мешает, она в глаза не лезет. Наверное, также фичи будут все остальные. По умолчанию, когда у нас появилась синхронизация, у нас на панели торчала иконка синхронизации и мозолила глаза. Сейчас она исчезает, когда вы авторизовались и все нормально. Фичи будут появляться, пользовательские, потому что это хороший способ конкурировать. А, поскольку у нас нет своей операционной системы, у нас нет какого-нибудь другого мощного канала дистрибуции, который бесплатно дает кучу пользователей, мы должны показывать, что мы лучше и умеем что-либо.

С точки зрения Firefox у них немножко другая проблема. Они все эти фичи делали медленными в браузере, потому что многие из них были реализованы на слишком гибких технологиях. Там тот же самый XUL, те же расширения, которые были легче, чем XUL, но слишком мощные. Мы вещи пишем все нативно. Берем и на Си пишем фичу и внедряем ее, компилируем. Т.е. это получается не какое-то расширение, вставочки или какая-то непонятная штука. А вещь, которая работает нативно, как софт. И не тормозит.

## Оптимизация графики (16:50)

**Вадим.** Ладно, хватит уже про Opera. Правда, от нас побегут читатели.

**Леша.** На этой неделе Коль МакАнлис, видимо, гордый шотландец из компании Google, написал такой большой достаточно пост на Medium про JPEG-файлы. Про то как можно уменьшать их размер. И, вроде бы, понятно, что размер JPEG можно уменьшить, и понятно как это делать, где делать, когда делать, но, тем не менее, даже я, когда прочитал эту статью, несколько для себя интересных моментов нашел.

Во-первых, он говорит хорошую правильную вещь о том, что JPEG, понятное дело, это жирный формат, он собирает в себе кучу-кучу данных, метаинформации, которая вообще не нужна в вебе. Локации, камера, которой была снята, очень много всего. Но, помимо этого, у JPEG есть уровень сжатия и чаще всего, если вы хотите, чтобы картинка хорошо показывалась, вы можете специально оставлять его на максимуме 100% и забивать.

Но, нем не менее, и как раз таки, автор это разбирает, в среднем этот параметр хорошо выглядит на уровне 75% и при этом картинка остается такой же четкой. Это, вроде бы, понятная информация, но то, что меня заинтересовало, он показал, например, что когда у вас картиночка очень маленькая, например, пиктограмма, или уменьшенная копия чего-то или аватарка, на ней детали и так очень плохо видны, поэтому степень сжатия там можно увеличивать. Прямо в разы увеличивать, потому что картинка сама по себе маленькая. Она и так плохо видна. Там видны только какие-то контуры, очертания, большие объекты. Поэтому большая степень сжатия не повлияет кардинальным образом на качество этой картинки. Меня, например, вот это очень заинтересовало. Логически до этого можно было дойти, но об этом никогда не думал.

**Вадим.** Мало кто знает, но JPEG это объединенная группа экспертов по фотографии (Joint Photographic Experts Group). Это не просто название формата, Portable Network Graphic какой-нибудь. А это, собственно, команда людей, которые собрались и выяснили много лет назад, как лучше всего человеческий глаз воспринимает изображение. Разобрались и придумали формат, который позволяет искажать ровно настолько, чтобы глаз человеческий на заметил, а информации на это тратилось меньше. Поэтому есть там всякие хитрые способы разбиения на отдельные кусочки, оптимизация каждого кусочка отдельно и так далее. Суть в том, что когда вы берете ставите какой-нибудь формат, у меня будет JPEG, и фотки будут сжиматься до 75, а если у вас там огромная белая картинка, на которой в центре нарисован квадратик и там два цвета всего, вы все равно сожмете ее неэффективно. Вы могли проанализировать как она выглядит и использовать какой-нибудь PNG-8 или даже GIF, который может в этой ситуации будет лучше. Естественно, это требует больших вычислений, мощностей на сервере. Но я не об этом. Я о том, что фотографию можно анализировать и предполагать, какой уровень сжатия лучше подходит.

Собственно, этот Butteraugli — страшное масло или как это называется? — в общем, эта утилита как раз анализирует подходящую степень сжатия JPEG и предлагает ее на основе каких-то там психофизиологических особенностей человеческого восприятия, т.е. все это _serious science_. Я надеюсь, что JPEG эта инициатива не ограничится. Потому что, если я загружаю скриншот кода в Twitter, они что делают, они такие «Хей! Привет! У нас есть JPEG». А там опять же 16 цветов. Я сам оптимизирую картинку в PNG-8, прохожусь ImageOptim, а они берут, пережимают ее в JPEG, ну, потому что могут. И, в итоге, файл вырастает в размерах. Может быть найдутся более эффективные способы анализировать картинки, и понимать, что они достаточно маленькие, они эффективно сжатые, пожалуйста, оставьте их в покое.

**Леша.** Давай еще затронем тему, что в проектах. Вот у тебя есть обычный проект сайта, там куча картинок. В какой момент, по твоему, лучше всего сжимать? Лучше это встраивать в какой-то билд-процесс? Держать ли сжатые картинки в репозитории? Уже сжатыми или держать исходники и постоянно при билде сжимать? Вот как ты считаешь, как лучше?

**Вадим.** Есть идеальный способ, на мой взгляд, хранить исходники в каком-нибудь 100% JPEG и сжимать их при сборке или даже в PNG-24 хранить, вообще без потерь идеальную картинку, где просто точечки, никакого сжатия. Но тогда процесс сборки начинает занимать много времени. Потому что если ты не просто одним пресетом проходишься по JPEG, а пытаешься проанализировать, как его сжать. Или какой-нибудь PNGOUT или TinyPNG проходится по всем PNG у тебя в проекте, получается, что ты тратишь очень много ресурсов сервера, у тебя сервер перегревается, твоя рабочая машина перегревается. Поэтому в собственных проектах я обычно оптимизирую картинки сам и кладу их уже в систему контроля версий самостоятельно. И когда у вас много картинок, наверное, их не стоит хранить в системе контроля версий, но версточные картинки точно у меня все оптимизированы, сразу готовы. Наверное, когда у вас есть SVG-исходники, в которые вы лазили руками и которые вы можете по редактировать, наверное стоит хранить их несжатыми, а оригинальными. Потому что SVG сжимается на лету довольно легко.

**Леша.** Я, на самом деле, тоже пришел к такому же выводу, что сжимать их в процессе билда это потеря времени ненужная. Особенно PNG, каждая картинка, особенно, если она большая, очень долго процессится.

**Вадим.** На самом деле, если один алгоритм, то даже PNG можно процессить быстро. Но суть в том, что есть разный PNG и для каждой из них разная утилита лучше подходит. Поэтому происходит анализ, сравнение.

**Леша.** Тогда получается, если мы делаем это заранее в проекте, то этот инструмент, который нам подсказывает степень сжатия, очень хорошо подходит. Потому что он не будет в билд-процессе. Это будет отдельный этап разработки проекта, когда ты просто оптимизируешь графику и можешь использовать этот инструмент, чтобы понять на сколько каждую картинку можно оптимизировать.

**Вадим.** Ну, у нас есть постоянная рубрика в нашем подкасте «наши пользователи ВКонтакте смеялись». И, естественно, когда мы опубликовали статью про этот Butteraugli, пришли ребята и сказали: «А, че? У меня Save for Web нормально работает в Photoshop. А зачем такие сложности?». Кто-то из вас может не знать, но есть такая проблема. Photoshop, когда сохраняет картинки даже с «Save for Web», кстати, это депрекейтед фича, Adobe не рекомендует экспортировать картинки с помощью «Save for Web», их нужно экспортировать с помощью генераторов, встроенной новой фичи в продуктах Adobe. И я не удивлюсь, если в следующих версиях они мой любимый «Save for Web» выпилят. У меня левая рука навсегда поломана этим сочетанием клавиш для вызова «Save for Web». Поэтому я не знаю, что буду делать.

**Леша.** Подожди-подожди. Но это ты о ком говоришь? О людях, смеющихся в ВКонтакте? Ты уверен, что у них последний Photoshop?

**Вадим.** Ну, гм, да. Так вот, если вы не знали, то Photoshop экспортирует картинки неэффективно. И как «Save for Web» и как экспорт Assets. Поэтому за Photoshop нужно подметать. На самом деле, ни один редактор не экономит ваши картинки по умолчанию. Он экспортирует их максимально быстро и эффективно. Если Photoshop при сохранении какого-нибудь PNG-8 начинал бы заниматься вычислениями «а какой эффективной утилитой мы можем сохранить у этой PNG», пользователи возненавидели бы, ну потому что, нам картинки экспортировать нужно. Поэтому это нужно принять как данность. Вы не пишите сразу сжатый HTML, вы не пишите сразу сжатые картинки. Вы экспортируете картинку примерно того же самого веса, чтобы представлять, а потом ее можно дожать. Видимо, нужен какой-то предварительный этап обработки, сборки. Какой-нибудь таск Gulp или Grunt напишите, который вам картинки после экспорта из Photoshop будет сжимать, но не в смысле «каждый раз», а его можно будет запустить один раз.

**Леша.** А мне в этом случае даже больше нравятся программки типа ImageMin, ImageOptim.

**Вадим.** Кстати, незаслуженно неизвестная программа, называется [ImageAlpha](https://pngmini.com/). Ее автор тот же самый, что и у ImageOptim. Ну, извините, ребята, мы говорим про софт для Mac, но наверняка есть аналоги для Windows, я уверен. Так вот, ImageAlpha, такая штука, которая позволяет реализовать малоизвестную фичу из PNG. Суть в том, что у нас есть два формата, их по разному все называют, ну, я назову их так, как они названы в Photoshop — PNG-8 и PNG-24. Так вот, PNG-8 умеет 256 цветов и не умеет альфа-прозрачность. А PNG-24 умеет миллионы цветов и альфа-прозрачность. Так вот, можно научить PNG-8 уметь альфа-прозрачность. И когда у вас иконка, в которой 256 цветов, на самом деле дофига для иконки, в которой 16 цветов и вам нужна альфа-прозрачность, вы можете засунуть альфа-прозрачность в вашу 16-цветную иконку и не хранить все цвета на свете. Для этого есть специальный софт, который позволяет вам конвертировать вашу PNG-24 в PNG-8, выбирать количество цветов и оставлять альфа-прозрачность. Так вот ImageAlpha на Mac позволяет это делать. По-моему, есть даже какие-то веб-сервисы для этого, но совершенно точно есть консольные утилиты тоже.

**Леша.** Кстати, есть же еще формат WebP. Вроде как, давно разработанный Google. Может даже кто-то видел, слышал, а может уже на самом деле забыли, потому что была когда-то волна, когда все говорили про WebP, ну, гугловые адвокаты технологий, рассказывали всем, как это классно, хорошо, как скоро светлое будущее придет. Они ведь анимированные, с альфа-каналом, степень сжатия есть.

**Вадим.** Они хороши тем, что сочетают в себе все, что только придумали в сжатии графики, в одном формате. Вы можете сказать «мне, пожалуйста, сожми как JPEG, наложи альфа-маску, а еще анимируй». Это вообще безумно хорошо. Как вообще все это появилось. Google разрабатывал формат графики, ну, потому что у них YouTube, самый большой видеосервис. Они, собственно, разработали себе формат графики WebM. А потом они такие «мы сделали классную вещь, а ведь тоже самое можно сделать для статической графики», ну, такой полустатической, т.е. не для видео. И они похожие алгоритмы использовали в формате WebP. Он вышел немножко позже. И по сути это такой же хитрый формат, как видеоконтейнер, который позволяет много чего внутри зашивать. Есть очень серьезная проблема в том, что в Photoshop WebP вы не откроете, проблема в том, что мало инструментов, есть проблема в том, и это гораздо серьезнее, что браузерная поддержка хромает. Но, формат очень-очень полезный и если у вас много трафика Chrome, ну, Леш, у тебя была мысль на эту тему.

**Леша.** У меня мысль была простая, что если взять весь трафик всех Chromium-браузеров, в которых WebP поддерживается и этот трафик, например, около 60%, 50%, а может где-то даже 70%, то почему бы не использовать. Это же гигантская экономия трафика и, видимо, YouTube именно поэтому его и использует, потому что они видят, кто к ним приходит и понимают эту экономию. Плюс они же раздают очень много трафика, а за трафик нужно платить и чем меньше трафика, тем лучше.

Мне очень интересно, почему этот формат как-то не пошел никуда. Я почему спрашиваю. Есть много разных технологий, например, тот же самый SPDY и HTTP/2 или еще каких-то технологий, когда какая-то компания для себя это придумывала, но потом как-то был запущен процесс стандартизации, как-то было всеми воспринято и как-то принято. С WebP такого не происходит. Например, на Can I Use вообще написано, что в Edge статус о том, что ни не планируют это внедрять. Они не думают, о том чтобы как-то внедрить это, они не планируют, сейчас, по крайней мере. И это странно, почему этот формат не пошел. Ведь не только с этим форматом проблема, были еще предложения. Было предложение про JPEG2000, еще один формат графики, где тоже пытались решить проблемы текущего веба, современного. Ведь все форматы очень старые, был разработаны очень давно. Почему не идет процесс стандартизации?

**Вадим.** Смотри. Стандартизация это когда у тебя есть одно решение о котором согласились все участники рынка. Но когда есть много решений конкурирующих, есть ведь еще формат MozJPEG, который Mozilla поддерживает, а есть APNG, анимированный PNG, его поддерживает Firefox, по-моему.

**Леша.** И Safari.

**Вадим.** Его раньше поддерживала Presto, потому что это был такой новый открытый тип развития PNG, ну, по сути, анимированный PNG. Потому что анимировать GIF, не эффективный формат, можем, а анимировать PNG, гораздо более эффективный формат не можем.

Почему не пошла стандартизация. Потому что у всех есть свой любимый формат графики, на сколько я понимаю, и все за него держаться. И есть еще другая история, когда какую-то технологию придумывают в отдельной компании и начинают использовать для собственных нужд, очень часто этой технологии ставят такую лицензию, которая не очень удобная для использования в собственных продуктах. Что удивительно, даже не удивительно, но это, в принципе, в манере Google, они этот формат открыли абсолютно. Т.е. есть независимая группа, он ни кому не принадлежит, он весь open source. Вы можете легко встроить поддержку WebP в свой DVD-плеер, вы можете легко встроить поддержку в свой браузер, в свой пылесос, куда угодно. Формат открытый.

**Леша.** Я кстати помню эту баталию, когда они выступали за открытость этого формата, как раз это было про видео, про WebM. В тот момент лицензия кодека H.264 заканчивалась. А он ведь лицензируется. Google на этой волне поднял идею, что это все плохо, это ужасно, вот как раз таки открытый формат, давайте все и поддержим. Тогда, конечно, H.264 сделала ход конем и сказала «да нет, вот вам», то ли пролонгировали лицензию, то ли еще как-то сделали. В общем, все остались на H.264 и эта идея не поперла. Но вот да, поэтому они за открытость тогда и выступали.

**Вадим.** Но знаете, с форматом H.264 просто ребята переставили таймер у этой бомбы. Принципиально ничего не изменилось. Формат по прежнему принадлежит этой MPEG-группе, куда входят Microsoft, Google, Apple и многие другие. У Microsoft, у Apple и даже у Google все в порядке. Аппаратная поддержка H.264 есть практически во всех устройствах. Действительно во всех устройствах. Все платят отчисления MPEG, формат эффективный, работает классно и так далее. Но Google не любить проприетарные вещи, он любит разрабатывать форматы более эффективные, которые для них работают, потому что у них есть мощности, это огромная компания. И они пошли в сторону этой открытости и за что им огромное спасибо. Благодаря этому веб действительно можно делать быстрее с точки зрения видео, графики и прочего. Видимо, Microsoft и Apple эта ситуация не беспокоит, потому что у них все работает. А особенно у Apple, потому что у них собственные железки, у них собственный аппаратный H.264 и они для Opus и Vorbis поддержку аппаратную внедрять не будут, потому что «а зачем?». Есть миллион форматов, а есть хороший формат. У нас все работает, не трогай.

Я точно знаю, что открытые форматы живут долго и всем полезны. Полезны отрасли. Поэтому, если вы, как разработчики, поддержите открытый форматы, WebP, WebM и иже с ними, вы поможете процессу стандартизации и появлению их в браузерах.

**Леша.** Ну, по крайней мере, если на вашем проекте много браузеров на Chromium, это, по-моему, хорошая идея.

**Вадим.** Да, вы можете даже с помощью элемента `<picture>` — который уже немодный, про него все знают, но никто не использует — легко подставлять нужные картинки. Вам не нужно даже на сервере это отдавать. Вы можете просто вставлять два `<source>` отдельных, указывать там разные типы и браузер подберет ту картинку, которая ему подходит больше. Там, конечно, порядок нужно правильный выставить. Допустим, сначала WebP, потом JPEG, а потом фолбэк на что-нибудь, можно даже MozJPEG вставить, если вы хотите. Если у вас есть задача оптимизировать отдачу картинок и сэкономить трафик в разы, правда, можно сэкономить трафик очень сильно, используя новые форматы графики, вы можете этим заняться и все инструменты для этого есть. Но если у вас есть опыт использования на реальном проекте WebP, поделитесь, будет интересно. А если вы напишете или расскажете где-нибудь, будет вдвойне интересно. Мы обязательно дадим ссылки.

 **Леша.** У нас как раз PiterCSS скоро и «Веб-стандарты» в Екатеринбурге, отличный доклад бы получился.

## Прозрачность в HEX-цветах (33:44)

TODO

## !important можно, если нужно (43:06)

TODO

## Фантомные страхи и адаптивные таблицы (48:27)

TODO

## Полифил через юзер-агент (52:06)

TODO
