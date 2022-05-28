# Стили 
## CSS 

Аббревиатура CSS расшифровывается как Cascading Style Sheets, что в переводе означает «каскадные таблицы стилей». Это язык разметки, используемый для визуального оформления веб-сайтов. 

Объекты, расположенные на странице, размещаются с помощью HTML. А вот CSS отвечает за то, как эти объекты выглядят. Их размер, цвет, фоновое изображение, степень прозрачности, расположение относительно других элементов, поведение при наведении курсора, визуальное изменение кнопок при нажатии и т.п. 

## Куда писать ваш CSS код
У вас есть 3 возможности использовать ваш CSS:
1. Писать внутри тега, добавив атрибут `style` на ваш тег пример: `<span style="Здесь_Можно_Писать_CSS_Код"> Текст </span>`
2. Писать внутри тега `<head>`
3. Писать отдельно в файле

## Как подключить ваш CSS код написанный в отдельном файле?
Чтобы подключить ваш CSS документ вам необходимо внутри тега `<head>` вставить тег: <br/>
`<link href:"_Здесь_Указывается_Путь_До_Вашего_CSS_Документа_" rel:"stylesheet">`

## Как создать ваш CSS документ
Для создания CSS документа вам необходимо дать ему расширение `.css`, пример: `style.css`
 
## Классы
Для любого тега можно дать класс, с помощью него вы можете обратиться именно к тому тегу, которому вы дали данный класс. Класс можно дать с помощью атрибута `class:"_Здесь_Имя_Класса"`<br>
Пример: <br>
`<p class:"GreenText"> Никуликолай </p>` <br/>
Как мы видим я дал класс тегу `<p>` и теперь могу обращаться к именно этому тегу, когда буду писать CSS код

## Как писать CSS код
Теперь переходим в ваш CSS документ и может начинать работу.<br/>

В предыдущем пункте я дал класс тегу <p>, и теперь чтобы стилизовать его я обрушусь к этому тегу через его класс:
 
 ```html
.GreenText{
  color: red,
  background: blue
}
 ```
Хочу заметить что я обратился к своему теге через `.`
 
 
 
 
 
 