---
title: CSS Preprocessors
localeTitle: Препроцессоры CSS
---
## Препроцессоры CSS

Препроцессоры CSS все чаще становятся основой в процессе работы веб-разработчиков в интерфейсе. CSS - это невероятно сложный и нюансный язык, и, чтобы облегчить его использование, разработчики часто обращаются к препроцессорам, таким как SASS или LESS.

Препроцессоры CSS компилируют код, который написан с использованием специального компилятора, а затем используют его для создания файла css, который затем может быть заменен основным документом HTML. При использовании любого препроцессора CSS вы сможете запрограммировать обычный CSS так же, как если бы препроцессор не был на месте, но у вас также есть больше доступных для вас вариантов. Некоторые из них, такие как SASS, имеют определенные стандарты стиля, которые означают, что упрощение написания документа, например, возможность опустить фигурные скобки, если вы решите это сделать.

Конечно, препроцессоры CSS также предлагают другие функции. Многие предлагаемые функции невероятно похожи в препроцессорах с небольшими отклонениями в синтаксисе. Таким образом, вы можете выбрать практически любого, кого пожелаете, и сможете достичь того же. Некоторые из наиболее полезных функций:

### переменные

Одним из наиболее часто используемых элементов на любом языке программирования является переменная, чего не хватает CSS. Имея переменные в вашем распоряжении, вы можете определить значение один раз и повторное использование, если на протяжении всей программы. Примером этого в SASS будет:

```SASS
$yourcolor: #000056 
 .yourDiv { 
  color: $yourcolor; 
 } 
```

`SASS yourcolor` переменную `SASS yourcolor` один раз, теперь можно повторно использовать этот точный точный цвет во всем документе без необходимости повторного определения определения.

### Loops

Другим распространенным элементом на языках являются петли, чего-то еще недостает CSS. Петли могут использоваться для повторения одних и тех же инструкций несколько раз без повторного ввода нескольких раз. Пример с SASS:

\`\` \`SASS @for $ vfoo 35px to 85px { .margin - # {vfoo} { margin: $ vfoo 10px; } }
```
This loop saves us from having the to write the same code multiple times to change the margin size. 
 
 ### If/Else Statements 
 Yet another feature which CSS lacks are If/Else statements. These will run a set of instructions only if a given condition is true. An example of this in SASS would be: 
```

SASS @if ширина (тело)> 500px { цвет фона: синий; } else { цвет фона: белый; } \`\` \` Здесь цвет фона изменит цвет в зависимости от ширины тела страницы.

Это лишь некоторые из основных функций препроцессоров CSS. Как вы можете видеть, препроцессоры CSS являются невероятно полезными и универсальными инструментами. Многие веб-разработчики используют их, и настоятельно рекомендуется изучить хотя бы один из них.

#### Дополнительная информация:

SASS: http://sass-lang.com/

МЕНЬШЕ: http://lesscss.org/

Стилус: http://stylus-lang.com/

MDN Страница: https://developer.mozilla.org/en-US/docs/Glossary/CSS\_preprocessor