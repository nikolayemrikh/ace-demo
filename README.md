## Демо: передаем данные из ace-редактора в iframe

1. Подключим редактор HTML, как [говорится на сайте](https://ace.c9.io/#nav=embedding), приделаем iframe
2. Приделаем кнопку, попишем HTML и вставим в редактор
3. Повесим обработчик изменений на редактор, при изменениях будем обновлять контент фрейма
4. Сделаем отработчик отложенным, чтобы не срабатывал, пока пользователь пишет код
5. Подключим редактор JS и напишем функцию обработчик для вставки HTML и JS в iframe.
