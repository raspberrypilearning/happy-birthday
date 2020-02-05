## تصميم بطاقة عيد ميلاد

دعونا نستخدم ما تعلمته حول HTML و CSS لإنشاء بطاقة عيد ميلاد مخصصة.

+ افتح [هذا الـ trinket](https://trinket.io/html/bb6d8905b8){:target="_blank"}.

لقد كتبنا الكثير من التعليمات البرمجية للبدء، لكن بطاقة عيد الميلاد تبدو مملة جدًا حتى الآن ، لذلك ستجري بعض التغييرات على النص البرمجي HTML و CSS.

+ انقر فوق الزر الموجود في مقدمة البطاقة، وستراها تُفتح للكشف عن الداخل.

![لقطة الشاشة](images/birthday-click.png)

+ انتقل إلى السطر 14 من النص البرمجي HTML. حاول تغيير النص لتخصيص بطاقتك.

![لقطة الشاشة](images/birthday-card-html.png)

+ هل يمكنك العثور على النص البرمجي HTML لصورة الروبوت، وتغيير كلمة `robot` إلى `sun` ؟

--- hints ---
 --- hint ---

+ انظر على السطر 17 للعثور على النص البرمجي.
+ قم بتغيير `robot` إلى `sun` و سترى الصورة تتغير!

![لقطة الشاشة](images/birthday-card-sun.png)

--- /hint ------ /hints ---

يمكنك استخدام أي من الكلمات `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` for a birthday card, or `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, or `snowman` إذا كنت تفضل عمل بطاقة عيد الميلاد.

يمكنك أيضًا تعديل النص البرمجي CSS لبطاقة عيد الميلاد.

+ انقر فوق علامة التبويب `style.css`. الجزء الأول هو كل من أنماط CSS للشكل الخارجي **outside** من البطاقة.

+ قم بتغيير `background-color` إلى `lightgreen`.

![لقطة الشاشة](images/birthday-card-outside.png)

+ يمكنك أيضًا تغيير حجم الصورة. اذهب الى `#outside-pic` في النص البرمجي لـCSS, و قم بتغيير `width` و `height` للصورة الخارجية الى `200px` (`إن px` تعني pixels).

![لقطة الشاشة](images/birthday-card-size.png)

+ يمكن تغيير الخط أيضا. اذهب الى `#outside-title` لـCSS و قم بتغيير `font-family` إلى `Comic Sans MS` و ال `font-size` to `16pt`.

![لقطة الشاشة](images/birthday-card-font.png)

يمكنك استخدام خطوط أخرى ، على سبيل المثال:

+ `<span style="font-family: Arial;">Arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`