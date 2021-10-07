Тестовое Задание выполнила Малиновская Ангелина Александровна 

В первую очередь хотела бы отметить, что в реальной ситуации прежде, чем приступать к заданию, я бы спросила пару уточняющих вопросов:
1. В Техническом задании указан Android and IOS. Однако в задании тестирования адаптивности не указано. Необходимо ли провести данный вид тестирования?
2. Почему в техническом задании указаны браузеры с версией (устаревшей на данный момент). Как необходимо использовать эту информацию. 


Соответствие исходному макету и техническому заданию:
1. Ссылка «Софт для быстрого создания скриншотов» ведет на неверный сайт
Шаги воспроизведения:
1.Открыть http://csssr.github.io/qa-engineer/
2. Открыть блок «Находить несовершенства»
3.Нажать на ссылку «Софт для быстрого создания скриншотов»
ФР: открывается страница сайта https://app.prntscr.com/ru/
ОР: открывается страница сайта  https://getsharex.com/
Окружение: Google Chrome Версия 94.0.4606.71
Приложения: ./screen_1
 

2. При сабмите кнопки в форме обратной связи не происходит отправка POST запроса на сервер 
Шаги воспроизведения:
1.Открыть http://csssr.github.io/qa-engineer/
2. Выполнить скролл страницы вниз
3. Запомнить форму обратной связи (Поле «Email» и «хотите что-то рассказать о себе»)
4. Открыть консоль сайта
5. Перейти во вкладку «Network»
6. Поставить фильтр «method:POST»
7.Нажатьь на кнопку «отправить» форму обратной связи
ФР: Отправка отправка POST запроса на сервер не происходит
ОР: происходит отправка POST запроса на сервер 
Окружение: Google Chrome Версия 94.0.4606.71
Приложения: 
 

3. Блок «Сопровождать проекты» не загружается 
Шаги воспроизведения:
1.Открыть http://csssr.github.io/qa-engineer/
2. Открыть блок «Сопровождать проекты»
ФР: блок не загружается
ОР: открывается информация о блоке«Сопровождать проекты»
Окружение: Google Chrome Версия 94.0.4606.71
Приложения: 

 

Далее приведу примеры еще пары критичных багов, без описания

4. Ссылка на страницу «Следите за новыми вакансиями: vk.com/csssr» не активна
 
5.Ошибка в консоре браузера «404»
 
Так же мною были выявлены ошибки по несоответствию макету ( Текст расположен в ином виде, цвет текса является более блеклым чем в макете и т.д.) и другие ошибки.

Кроссбраузерность:

Тестирование кроссбраузерности было проведено в трех наиболее распространенных браузерах: Ghrome, Safari, Firefox

1. В форме обратной связи некорректная верстка
Шаги воспроизведения:
1.Открыть http://csssr.github.io/qa-engineer/
2. Выполнить скролл страницы вниз
3. Запомнить форму обратной связи (Поле «Email» и «хотите что-то рассказать о себе»)
ФР: Поле «Email» находится не в соответствии с макетом
ОР: Поле «Email» находится в соответствии с макетом
Окружение: Safari 5.1.7
Приложения: 

 

2. Ссылка на страницу «Следите за новыми вакансиями»: ведет на некорректно работающую страницу
Шаги воспроизведения:
1.Открыть http://csssr.github.io/qa-engineer/
2. Выполнить скролл страницы вниз
3. Нажать на ссылку страницу «Следите за новыми вакансиями»: 
ФР: открывается новая вкладка с некорректными данными 
ОР: открывается новая вкладка корректной информации на странице ВКонтакте
Окружение: G Safari 5.1.7
Приложения: 
 


 





Юзабилити:
1. Исправить шаблон письма при отправке в службу поиска талантов hr@csssr.com
Шаги воспроизведения:
1.Открыть http://csssr.github.io/qa-engineer/
2.Проскролить вниз страницы
3. Нажать на «hr@csssr.com»
ФР: открывается сторонне приложение для отправки письма с именем отправителя
ОР: открывается стороннее приложение для отправки письма с заполненным именем отправителя и темой.
Окружение: Google Chrome Версия 94.0.4606.71
 
 
Иные идеи для правок:
2. Добавить информацию о компании
3.Добавить цветовую гамму. Сделать текст более ярким, выделить важные моменты
4.В поле email добавить проверку на корректность данных
5.В поле «хотите что-то рассказать» добавить пример или наводящие вопросы. Так пользователю будет проще понять, что писать в данной графе.

Хочу отметить, что мною было выполнено не полное тестировано. В документе были указаны и оформлены не все найденные мною ошибки.

Спасибо за уделенное моей работе время
