Ссылка на задание:

https://developer.android.com/codelabs/basic-android-kotlin-compose-material-theming?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-3-pathway-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-material-theming#0

Unit3: Display lists and Use Material Design 3 -> 3: Build Beautiful apps -> 7 Activities and Quiz -> 2 Activity (Woof app)

Скринты получившегося приложения в светлой и темной теме:

![image](https://github.com/gipnozhard/WoofCompose/assets/71705375/ebc988d1-7b17-4cea-b834-873b15942bb0)
![image](https://github.com/gipnozhard/WoofCompose/assets/71705375/6196faec-f07c-4dc3-b84d-70f6fedc6e1c)

создали пользовательскую цветовую палитру как для светлых, так и для темных тем, создали формы для различных компонентов, загрузили шрифты и добавили их в приложение, а также создали красивую верхнюю панель, чтобы связать все это воедино. Воспользуйтесь навыками, полученными в этой кодовой лаборатории, и меняйте цвета, формы и типографику, чтобы создавать приложения полностью по своему усмотрению!

Краткие сведения
Тематизация материалов позволяет использовать Material Design в вашем приложении с рекомендациями по настройке цветов, типографики и форм.
В файле Theme.kt определяется тема с помощью составного файла с именем [your app name]+Theme()—WoofTheme() в случае этого приложения. В рамках этой функции MaterialTheme объект задает color, typography, shapes и content приложения.
Color.ktLightColorPaletteDarkColorPalette
Ваше приложение может подписаться на Включение режима "Затемнение", что означает, что система установит для вас темную тему. Однако для ваших пользователей будет удобнее, если вы внедрите темную тему, чтобы сохранить полный контроль над темой приложения.
Shape.kt - это место, где вы определяете формы вашего приложения. Существует три размера формы (маленькая, средняя, большая), и вы можете указать, как закругляются углы.
Формы привлекают внимание, идентифицируют компоненты, передают состояние и выражают бренд.
Type.kt - это место, где вы инициализируете свои шрифты и назначаете fontFamily, fontWeight и fontSize для шкалы типов Material Design.
Шкала типов дизайна материалов включает в себя ряд контрастирующих стилей, которые соответствуют потребностям вашего приложения и его контента. Шкала типов представляет собой комбинацию из 15 стилей, поддерживаемых системой типов.

В этом приложении добавлена анимация 
Unit3: Display lists and Use Material Design 3 -> 3: Build Beautiful apps -> 7 Activities and Quiz -> 3 Activity (Woof app)
