# **Проект: Путешествие по России**

## *Сайт, рассказывающий о путешествиях по России.*

Ссылка на [**demo**](https://nastyanev.github.io/russian-travel-bootcamp/ "Ссылка на GitHub Pages").

 ## *Стек*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://www.w3.org/TR/html5/" title="HTML5"><img src="https://img.shields.io/badge/HTML-%23000000?logo=html5&logoColor=%23FFFFFF%20&color=%23E34F26" alt="HTML5" height="25px"></a>
<a href="https://www.w3.org/TR/CSS/" title="CSS3"><img src="https://img.shields.io/badge/CSS-%23000000?logo=css3&logoColor=%23FFFFFF%20&color=%231572B6" alt="CSS3" height="25px"></a>
<a href="https://www.figma.com/" title="Figma"><img src="https://img.shields.io/badge/Figma-%23FFFFFF%20?logo=figma&logoColor=%23FFFFFF%20&color=%23F24E1E" alt="Figma" height="25px"></a>

Россия богата не только природными ландшафтами, но и прекрасными историческими местами, достойными посещения. Будь то старинные церкви Пскова или северные пейзажи Карелии - каждый найдет для себя здесь много неизведанного и, конечно, невероятно интересного. Путешествия по России - это сайт, где собрана галерея уникальных мест нашей страны и историй путешественников.

***Что было сделано:***
  * Создана разметка сайта в html.
  * Реализована анимация главной картинки через CSS.
  
    <img src="https://github.com/NastyaNev/russian-travel-bootcamp/assets/129982615/2c4219c4-ecb3-41b0-a8d5-f18f0678f9ae" width="70%" />
    
  * В вёрстке использован Grid Layout.
  * Сайт адаптирван под разные размеры экрана через медиа-запросы.
    
    <img src="https://github.com/NastyaNev/russian-travel-bootcamp/assets/129982615/b4c6e8bb-68bb-478c-9106-5a17ea463596" width="70%" />
    
  * В частности, галерея с картинками создана при помощи свойств auto-fill и minmax() в сочетании с repeat().
   ```css
   .photo-grid {
       display: grid;
       gap: 16px;
       grid-template-columns: repeat(auto-fit, minmax(284px, 1fr));
       margin-top: 92px;
   }
   ```
  * Сайт создан по макету [Figma](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0 "Ссылка на макет в Figma").
  * К ссылкам применены эффекты наведения через псевдокласс :hover.
    
    <img src="https://github.com/NastyaNev/russian-travel-bootcamp/assets/129982615/f29e96aa-b4fb-40a7-81f8-50fc01654f57" width="70%" />

**Код организован** согласно БЭМ методологии.

**В планах** - добавить пользовательскте события с помощью JS (сделать попапы с открывающимися изображениями) и сделать сайт кроссбраузерным.
