## Calc lib

Библиотека для создания калькулятора в веб приложении.<br>
В данном примере это калькулятор калорий, где нужно выбрать: пол,возраст, вес, рост, образ жизни. На основе образа жизни буде выбран коэффициент, который запишется в ratio.

### localStorage:
Значения переменных хранятся в localStorage. В случае если запись есть, значения переменных считываются из localStorage. Если нет, то мы их задаем.ы

### Переменные:
`result` - переменная, в которую считали элемент '.calculating__result span' - окно с выводом результата.<br>
`sex` - переменная: пол.<br>
`height` - переменная: рост.<br>
`weight` - переменная: вес.<br>
`age` - переменная: возраст.<br>
`ratio` -переменная: коэффициент, взяли на сайте расчета калорий.<br>

### Содержит функции:
`initLocalSettings()` - установка зеленых блок (зеленым блоком подсвечиваются выбранные квадратики).<br>
`calcTotal()` - расчета калорий.<br>
`getStaticInformation()` - фунция получения данных: пол и физическая активность.<br>
`getDynamicInformation()` - фунция получения данных: рост, вес и возраст.<br>

### Функции принимают:
`selector` - передаваемый селектов.<br>
`active class` - класс активности.<br>
`parentSelector` - div c данными ( в примере калькулятора калорий - коэффициент активности).<br>


