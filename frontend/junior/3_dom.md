# DOM

* Что такое DOM, BOM и `window`?
* Как происходит построение DOM дерева?
* Что такое `document` и в чем его отличия от `window`? Когда лучше использовать `document`, а когда `window`?
* Как происходит навигация по DOM-элементам?
  * Для чего используются объекты node и element? В чем их сходства и различия?
  * Что такое: `previousSibling`/`nextSibling`, `children`, `childNodes`, `firstChild`/`lastChild`, `firstElementChild`/`lastElementChild`?
  * Рассказать про методы навигации по DOM: `getElementById`, `getElementsByClassName`, `getElementsByTagName`, `getElementsByName`, `querySelector`, `querySelectorAll`, `closest`.
  * Рассказать про навигацию внутри `HTMLTable​Element` и `HTMLFormElement`.
* Добавление/удаление/клонирование/вставка элементов и узлов. Какими способами это можно сделать?
* Атрибуты и свойства
  * Как взаимодействовать с атрибутами HTML элемента через JS?
  * Что от чего зависит: свойство от атрибута или атрибут от свойства?
  * Могут ли не совпадать значения в свойстве объекта и в атрибуте одного и того же HTML элемента?
  * Что выведет данный код:
    ```html
    <div id="topId" href="http://123.com" foo="bar"></div>

    <script>
      console.log(document.getElementById('topId').foo);
      console.log(document.getElementById('topId').href);
    </script>
    ```
* CSS стили в DOM
  * Зачем нужно свойство `style` у HTML-элемента? Как им пользоваться?
  * Какими способами можно задать стили элементу через JS?
  * Для чего используется `window.getComputedStyle`?
* Что такое `DocumentFragment`?
* Система координат
  * В чем отличие систем координат относительно окна/документа/экрана? В каких случаях применять ту или иную систему координат?
  * Как получить размеры окна/документа?
  * Как получить координаты определенного элемента относительно окна/документа?
  * Как программно прокрутить документ до определенного элемента?
* Что такое event bubbling и event capturing?
* Что такое делегирование DOM событий? Как и в каких случаях этим пользоваться?
* Для чего нужны свойства `outerHTML`/`innerHTML`/`outerText`/`innerText`/`textContent`? Как и в каких случаях их использовать? 
  * В чем отличия между `innerHTML`/`innerText`/`textContent`?

### Ресурсы

* [Курс на Learn Javascript](https://learn.javascript.ru/document)
* [Спецификация (W3C)](https://www.w3.org/TR/REC-DOM-Level-1/expanded-toc.html)
* [Спецификация (WHATWG)](https://dom.spec.whatwg.org)




* [Хороший курс на learn js](https://learn.javascript.ru/document)
* [W3C spec, first level DOM](https://www.w3.org/TR/REC-DOM-Level-1/expanded-toc.html)
* [WHATWG spec, dom living standard](https://dom.spec.whatwg.org)
* [Cвойства textContent, innerHTML, innerText](https://itchief.ru/lessons/javascript/javascript-dom-textcontent-properties-innerhtml)
