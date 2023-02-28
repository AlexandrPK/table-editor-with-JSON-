## Примитивный редактор табличных данных

[Просмотр приложения](https://alexandrpk.github.io/table-editor-with-JSON/)

Это приложение представляет собой примитивный редактор табличных данных, который позволяет пользователю загружать данные в формате JSON, просматривать их в виде таблицы, редактировать, добавлять и удалять строки, а также перемещать их вверх и вниз.


## Инструкция по использованию

1. Откройте файл index.html в браузере.

2. Введите данные в формате JSON в поле ввода и нажмите кнопку "Загрузить данные".

3. Данные будут загружены в таблицу. Вы можете редактировать, добавлять и удалять строки, а также перемещать их вверх и вниз.

4. Когда вы закончите редактирование, нажмите кнопку "Сохранить данные", чтобы сохранить изменения в формате JSON.

## Описание функционала

Приложение содержит следующий функционал:

* Загрузка данных в формате JSON

* Отображение данных в виде таблицы

* Редактирование данных в таблице (нажатие на ячейку таблицы)

* Добавление новых строк в таблицу

* Удаление строк из таблицы

* Перемещение строк вверх и вниз в таблице

* Сохранение измененных данных в формате JSON

## Инструкция по развертыванию

Для развертывания приложения необходимо выполнить следующие шаги:

1. Cкачайте или клонируйте репозиторий на свой компьютер.
2. Откройте файл index.html в браузере.

## Ответы на вопросы

### Вопрос 1

Вывод
```
Cool
true
```
И «&&» находит первое ложное значение

ИЛИ "||" находит первое истинное значение

### Вопрос 2

Метод preventDefault() используется для отмены стандартного поведения браузера при возникновении определенного события в DOM. Например, при нажатию по ссылке, браузер переходит на страницу, указанную в атрибуте href этой ссылки. Использование метода preventDefault() может предотвратить это поведение браузера и выполнить другие действия, например, показать модальное окно. Часто используется для отмены перезагрузки страницы.

Пример

```html
<a href="#" id="link">Нажми меня</a> 
```

```javascript
const link = document.getElementById('link');

link.addEventListener('click', (event) => {
  event.preventDefault(); // отменяем стандартное поведение браузера
  console.log('Ссылка была нажата');
});

```

В данном примере мы добавляем обработчик события на ссылку и используем метод preventDefault(), чтобы предотвратить переход на другую страницу при нажатии по ссылке. Вместо этого мы выводим сообщение в консоль браузера.



