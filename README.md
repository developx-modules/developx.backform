# developx.backform

Developx: компонент формы обратной связи
с использованием инфоблоков и ГуглКаптчи 3

Для работы ГуглКаптчи требуется модуль https://marketplace.1c-bitrix.ru/solutions/developx.gcaptcha

Установка модуля:

1) Скачать модуль из https://marketplace.1c-bitrix.ru/solutions/developx.backform и установить.

2) Добавить новый инфоблок в админке, который будет использоваться для сохранения заявок.

3) В новом инфоблоке добавить нужные свойства, которые будут являться полями формы. Поддерживаются 
только типы "Строка" и "HTML/Текст".

4) Добавить компонент developx.backform на нужную страницу
Инструкция https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=34&LESSON_ID=9163&LESSON_PATH=3905.4457.6945.9163

5) Для подключения ГуглКаптчи в настройках модуля должна быть отмечена опция "Подключить ГуглКаптчу". 
А также установлен, настроен и активирован модуль ГуглКаптчи(developx.gcaptcha)

6) Модуль автоматически создает тип почтового события (DEVELOPX_NEW_FEEDBACK) и почтовый шаблон.
Отредактировать шаблон можно в настройках почтовых шаблонов /bitrix/admin/message_admin.php?lang=ru