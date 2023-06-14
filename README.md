# StarWars
Html страница, на которой, как в StarWars, плывет текст снизу вверх.
## Скриншот
![image](https://github.com/Sazzukki/StarWars/assets/133952979/21b348f5-5ae3-4c04-b409-a25a7f6c3604)
##Теория
<h2>Стиль фона:</h2>

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/c32a64f6-5256-4bf5-bd9b-b294661d0bfa)

<h2>Стиль текста:</h2>

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/cb089296-4791-484e-ba41-f94f875a29dc)

- `font-size` устанавливает размер шрифта на 400% от стандартного размера;
- `font-weight` определяет толщину шрифта 600 (жирный);
- `letter-spacing` устанавливает расстояние между символами в 6 пикселей;
- `line-height` устанавливает высоту текстовой строки на 150%;
- `perspective` устанавливает перспективу для 3D-преобразований на 400 пикселей;
- `text-align` выравнивает ширину текста в пределах ширины элемента (распределяет символы по блоку);
- `display:flex` устанавливает контейнер уровня блока с дочерними элементами, расположенными вдоль главной оси, начальную начальную точку в начале контейнера и перемещает ключевой элемент на следующую строку, когда пространство в строке заполнено.
- `justify-content` выравнивает содержимое созданного контейнера блочного уровня по центру;
- `position` определяет способ позиционирования элемента на странице, в данном случае позиционируется относительно, то есть позиционирует элемент относительно его исходного положения;
- `height` устанавливает высоту элемента в 800 пикселей;
- `color`устанавливает желтый цвет текста;
- `font-family` указывает, что в тексте должен использоваться шрифт Pathway Gothic One, который является шрифтом без засечек.

<h2>Анимация:</h2>
CSS-анимация работает, определяя ключевые кадры, которые определяют, как элемент должен отображаться в определенные моменты времени во время анимации. В приведенном примере правило обхода @keyframes определено с двумя ключевыми кадрами — один на 0% и один на 100%. Внутри каждого блока ключевого кадра вы можете определить свойства CSS, которые должны применяться к элементу в этой точке анимации.

Анимация пролета определяет следующие свойства:

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/8bf65dd0-5b49-4a80-8431-206f788a94da)

- `top`: This property controls the vertical position of the element. At the start of the animation (0%), the element is positioned at the top of the page (top: 0), and by the end of the animation (100%), it has moved up 6000 pixels (top: -6000px).

- `transform`: This property allows you to apply various types of transformations to an element, such as rotating, scaling, or translating it. In this case, the transform property is used to rotate the element around the X-axis by a certain degree, as well as translate it along the Z-axis by a certain distance. By the end of the animation, the element is rotated slightly more and translated much further than at the beginning, creating a crawling effect.

- `-webkit-transform`, `-moz-transform`, `-ms-transform`, and `-o-transform`: These vendor-prefixed versions of the transform property are included for cross-browser compatibility, as some older browsers require them to apply CSS animations correctly.

By changing the values of these properties across the keyframes, you can create many different types of animations. Other properties that can be animated using CSS include opacity, color, width, height, and background, among others.

<h4>To change annimation time you need change these values in "style.css" file:</h4>

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/a3fdc14c-48f4-439e-a3ca-cbf73b5a0734)

## Как установить
- Скачайте файлы index.html и style.css
- Запустите index.html
- Наслаждайтесь
## Контакты
- VK : [Изнаирова Рина](https://vk.com/sadzzuki)
- Telegram: @suzzki
- mail : tekashiki.kijimi@gmail.com
