Это переведенный МодПак Кенана на русский. Помощь в переводе приветсвуется.

This is ModPak Kenan translated into Russian. We are very grateful for the help in translation.

Итак, эта часть чисто посвящана тем кто хочет начать перевод МодПака Кенана.

Вы должны запомнить что отсебятина приветсвуется в том случае, если оно не искажает смысл предложения или названия предмета "Хотя, лучше попытатсься перевести Предмет достаточно точно, но это уже на ваше усмотрение" и моды игры построенны на языке Js что для меня довольно комфортная среда обидания "я учу язык js, и для меня не составило проблем изучить строение". 

Итак, теперь перейдем к примерам: 

"name": { "str": "Баттоуджицу" },

"description": "Техника быстрого убийства. \n\n Стиль боя на мечах, основанный на ловкости, с упором на точные и мощные атаки. Большие бонусы к точности, режущему урону, пробиванию брони и уклонению - все зависит от вашей ловкости. Через некоторое время становится чрезвычайно OP, как и положено йодзинбо или уличным самураям.",
"initiate": [ "Вы размахиваете своим мечом.", "%s готовится нарезать мелкими кубиками." ],

Итак, данные строки являются для нас первостеменными так как носят смысловой характер "такие теги как id носят логический так как они нужны чисто для опредления названия предмета, их лучше не трогать"

"name": Это названия предмета в единичном или многочисленном ввиде, для наглядного примера могу привести это.
"name": { "str": "Пара ботинок К.Р.И.Т", "str_pl": "Пар ботинок К.Р.И.Т" }, 
после "str" это предмет в ввиде одной штуки Например "1 Пара ботинок К.Р.И.Т"
А вот "str_pl" является определением в многочисленном, пример "8 Пар ботинок К.Р.И.Т"

Обговорив этот момент с BrettD, в пример я ему дал "1 Журнал" "2 Журнала" "55 Журналов" на что он мне ответил, что встроенные и переведенные моды имеют такую возможность, но сторонние имеют только множественную и еденичную систему. Потому мы имеем только "1 Журнал" и "55 Журналов". Иммейте это ввиду.

Теперь "description": Это описание всего чего угодно где он есть. Тут просто нужно перевести и всё, особых правил кроме не корявого перевода нет.

"initiate": "Это насколько я могу понять, описание события, тут главное не затрагивать спец символы, вы их узнаете.
Чтобы вы поняли точно, что конкретно происходит в этом теге я опишу его детально.

"initiate": [ "Вы размахиваете своим мечом.", "%s готовится нарезать мелкими кубиками." ], Как вы можете заметить, ("Вы размахиваете своим мечом.",) оно находится в двойных ковычках, а после ковычек идёт (,) запятая, после чего идёт ("%s готовится нарезать мелкими кубиками.")  это второй варинт, который будет проигрываться. Как мне кажется там может быть больше двух. Кому будет не лень протестить могут это проверить на практике. Теперь о (%s) это вывод имени того кто это применяет, чтобы вы поняли точно о что я имею ввиду (Вова тракторист готовится нарезать мелкими кубиками.) Примерно это выйдет в список событий в игре после применения на вашим или ещё каким персонажем.

Для связи со мной вы можете использовать мой ВК https://vk.com/harmarius
Или написать мне на почту herman.nothero@gmail.com
Заранее спасибо за любую помощь! И так же, если есть моды для Каты на перевод, предлагайте!

П.С. Так же те кто работают через GitHab, не забывайте добавить в мод текстовый файл Translate.txt Где прошу вас написать ваш ник и состояние перевода "Перевод начат" И в случае окончания "Перевод готов"

К сожалению json не поддерживает комментарии, потому я всегда есть оригинал мода Кенана.

Так же я буду читать ВК тех кто переводит не через GitHab и буду добавлять эти файлы сам, когда вы озвучите над каким модом работаете.
