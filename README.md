# Рубежный контроль №2
01.06.2020
## УЧАСТНИКИ
Студенты первого курса образовательной программы "Веб-технологии"
## ОПИСАНИЕ ЗАДАНИЯ
* Создание страниц по текстовому описанию: посадочная страница по направлениям повестки Точки кипения и две дополнительные страницы.
* Направление задается вариантом, который указан в вашей ведомости по успеваемости. Ссылки по группам: [321](https://docs.google.com/spreadsheets/d/1M8INQUANI1W7B-jV0uJTg1cImmRhlN3lj54HOIFswnA/), [322](https://docs.google.com/spreadsheets/d/1i9jjWOgjJ9nFKk880niIAEhuJrLW27DVl7L7-FKNEw0/).
* Для создания страницы использовать информацию из папки source согласно своему варианту задания.
## ЗАДАНИЕ
Сформировать посадочную страницу по направлениям повестки "Точки кипения" и две дополнительные страницы.

Меню содержит пункты других направлений, а также ссылки на другие страницы вашего задания.

На первом экране используется большое изображение с ключевым текстом и кнопкой с призывом к действию.
![Пример](https://i.imgur.com/kwAIicT.png)

Нажатие на кнопку направляет на форму (якорная ссылка или модальное окно). Форма позволяет отправить заявку на участие в точке кипения.

В основной части есть сайдбар с фиксированным положением и содержащий якорные ссылки на разделы страницы.

На странице расписаны:
* повестка
* как есть сейчас
* как планируется в будущем
* эффекты

Также описаны:
* миссия
* цели
* задачи
* стратегическая цель
* роль в вузе
* Возможности для сотрудников
* Возможности для университета

Элементы страницы следует оформить в разных стилях (карточки, простой текст, списки), используя при этом flexbox или grid.
Изображения можно искать, например, [тут](https://www.pexels.com/ru-ru/) или в [Google Картинки](https://www.google.ru/imghp).

В интерфейсе предусмотреть элементы для передачи доп. информации по направлениям - как подать заявку на проведение мероприятия, информация как подключиться к сообществу по направлению, информация о конкретном сообществе.

Вторая страница содержит блок ссылок на профильные группы, экспертов (ссылки на соц сети - группы, личные страницы, либо отдельные сайты) и выпускников университета.

Третья страница об университете 2035 в Московском Политехе (новости, мероприятия, активности) - информацию можно взять в группе ВК и сайте университета 2035.

На всех страницах в футере указаны ваше ФИО, группа и дата выполнения задания.

## ТРЕБОВАНИЯ
1. При разработке необходимо периодически сохранять результаты в репозиторий git:
```
git add
git commit -m "комментарий к версии"
git push
```
Рекомендованная периодичность сохранения результата — не более 60 минут.

2. Использованы семантические теги html5.

3. В форме корректно использованы ярлыки (label), задействованы разные типы полей (radio, checkbox, text).

4. В репозитории сформирована четкая структура: в корне находится index.html, изображения в отдельной папке...

5. Подключен и использован внешний шрифт (Google Fonts)

6. На странице есть меню.

7. Использован SVG.

8. Для какого-либо элемента задана анимация (animation) или переход (transition).

9. На странице использованы Flexbox и Grid.

10. Применяется методология [БЭМ](https://ru.bem.info/) для именования классов.

11. Страница соответствует принципам отзывчивой верстки (RWD).

12. Допустимо использование фреймворков, но страница должна при этом перестраиваться при изменении ширины экрана.

13. Страница должна соответствовать принципам доступности и отсутствуют ошибки в:
    * Lighthouse Accessibility (Chrome),
    * Developer tools Accessebility (Firefox),
    * [Webaim](https://wave.webaim.org/).

14. Создана печатная версия страницы.

15. Отсутствуют ошибки при проверке на [валидаторе](https://validator.w3.org/).
