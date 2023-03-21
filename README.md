# Turnkey-Repair-Landing-page
Ссылка на gh-pages:
https://kivavlad.github.io/Turnkey-Repair-Landing-page/

Учебный проект верстки лендинга, который был в рамках курса SkillFactory. 
Ссылка на макет в Figma 
https://www.figma.com/file/TdXgADLSbn7npH24qcjkAg/IC-%22Repair-Design-Project%22?node-id=0-1&t=72H8CWEGtvs7xgm2-0

Инструкции и требования:

1) Макет можно разделить на логические части (секции), которые должны растягиваться на всю ширину экрана.

2) Контент каждой секции должен быть обёрнут в контейнер с фиксированной максимальной шириной (max-width: 1440px) и автоматическими отступами справа и слева (margin: 0 auto). Фон блоков (цвет, изображения) должен растягиваться на весь экран.

3) Все кнопки должны быть кнопками (<button>), списки — списками (<ul> или <ol>), а ссылки — ссылками (<a>).

4) Для понимания того, как выглядит макет на широких экранах и мобильных устройствах, используем chrome devtools. 

5) Их же используем для просмотра элементов вёрстки и применённых стилей.

6) Для уменьшения количества стилей пользуемся принципом DRY (Don’t Repeat Yourself). Например, выносим все общие стили для кнопок в стиль .button { … } и для каждой конкретной кнопки определяем дополнительно свой модифицирующий стиль .button-bla-bla { ... }, в котором описываем, какие свойства нужно поменять или добавить. Тогда наша кнопка будет иметь вид <button class=”button button-bla-bla”>, то есть мы применяем к ней общий стиль и стиль-модификатор. То же самое нужно сделать для заголовков, инпутов и иконок (по возможности).
