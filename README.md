# canvas-shapes

Задача

Да се напише анимация, която да позволи на потребителя да създава динамични анимирани обекти чрез клик върху повърхността на канваса с приложена гравитация дърпаща ги надолу.

Пример: При клик на x: 200 и y: 200, да се създаде нов обект на точния координат и да започне да се анимира надолу.


- Канвасът да е с размер 512х512
- Да се поддържат квадрат или кръг. На всеки нов клик да се решава динамично с `Math.random()` дали обекта, който ще се създаде, ще бъде квадрат или кръг.
- Когато докоснат долния край на канваса, да подскачат обратно (обръщане на velocity)
- Да не се позволява на обектите да излизат извън рамките на канваса.
- Да има брояч, визуализиран с `fillText` в горния десен ъгъл на канваса, който да брои колко обекти са създадени
- Всеки обект да има random цвят, ширина и височина (за квадрат) и радиус (за кръг)
- Да има отделно `<input type=``"``number``"` `/>` поле което да позволява динамично да се контролира стойността на гравитацята
- Да се позволи интеракция с touch screens.
- Да се позволи оразмеряване за retina screens.
- Да се използва времето изминало от миналия фрейм за плавна анимация.
- Да се използва Javascript билд система. Може да ползвате `gulp`, `webpack`, `rollup` или каквато друга пожелаете. Да се генерира финален build файл.
- Да се използва git с ясно подредени commits. Да може да се проследи всяко направено подобрение и да има възможност да се върне към конкретна фаза на проекта.
- Да има package.json файл, който да позволява проекта да се стартира локално с `npm run start` команда.
