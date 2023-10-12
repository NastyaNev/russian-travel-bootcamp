# **Проект: Путешествие по России**

## *Сайт, рассказывающий о путешествии по России на поезде.*

Ссылка на [**demo**](https://nastyanev.github.io/russian-travel-bootcamp/ "Ссылка на GitHub Pages").

Что было сделано:
  * Создана разметка сайта в html.
  * Реализована анимация главной картинки через CSS.
    <img src="https://github.com/NastyaNev/russian-travel-bootcamp/assets/129982615/2c4219c4-ecb3-41b0-a8d5-f18f0678f9ae" height="300px" />
    
  * В вёрстке использован Grid Layout.
  * Сайт адаптирван под разные размеры экрана через медиа-запросы.
    <img src="https://github.com/NastyaNev/russian-travel-bootcamp/assets/129982615/b4c6e8bb-68bb-478c-9106-5a17ea463596" height="300px" />
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
  * К некоторым ссылкам применены эффекты наведения через псевдокласс :hover.
    <img src="https://github.com/NastyaNev/russian-travel-bootcamp/assets/129982615/f29e96aa-b4fb-40a7-81f8-50fc01654f57" height="300px" />

**Код организован** согласно БЭМ методологии.

**В планах** - доработать адаптивную верстку и сделать сайт кроссбраузерным.
