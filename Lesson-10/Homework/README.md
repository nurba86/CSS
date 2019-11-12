## Homework


Сверстать макеты [table-2b.psd](https://github.com/dbaktiyar/js-courses/blob/master/Lesson-10/Homework/img/table-2b.psd)
Для оформления внешнего вида содержимого ячеек, желательно использовать
псевдоклассы: **:first-child**; **:last-child**; **nth-child()**, но можно также при необходимости
использовать и обычные классы.
В макете [table-2b.psd](https://github.com/dbaktiyar/js-courses/blob/master/Lesson-10/Homework/img/table-2b.psd) - в ячейках текст должен размещаться всегда в одну строку, для
этого нужно использовать следующие CSS свойства:
**white-space: nowrap;
overlow: hidden;
text-overflow: ellipsis;**
Чтобы свойства overlow: hidden; и text-overflow: ellipsis; сработали, текст который
предусмотрено обрезать (в том случае если он не помещается в одну строку в ячейке
таблицы) нужно дополнительно заворачивать в див или спан, но спану при этом
нужно задавать **display: block**
Для выравнивания текста по вертикали в ячейках таблицы можно использовать
свойства CSS **vertical-align: top**, **bottom** или **middle**
Текст который по смыслу является ссылкой, должен быть выполнен ссылкой,.
в макете [table-2b.psd](https://github.com/dbaktiyar/js-courses/blob/master/Lesson-10/Homework/img/table-2b.psd) ссылками являются **“View Location on Map”**
