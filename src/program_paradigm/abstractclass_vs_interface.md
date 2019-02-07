## Чем `абстрактный` класс отличается от `интерфейса`

[**Вернутся к списку вопросов**](https://github.com/Torlopov-Andrey/hh_interview_ios/blob/master/readme.md)


`Абстрактный класс` - это класс, у которого не реализован один или больше методов (некоторые языки требуют такие методы помечать специальными ключевыми словами).

`Интерфейс` - это абстрактный класс, у которого все методы не реализованы, все публичные и нет переменных класса.

`Интерфейс` нужен обычно, когда описывается только интерфейс (тавтология). Например, один класс хочет дать другому возможность доступа к некоторым своим методам, но не хочет себя "раскрывать". Поэтому он просто реализует интерфейс.

`Абстрактный класс` нужен, когда нужно семейство классов, у которых есть много общего. Конечно, можно применить и интерфейс, но тогда нужно будет писать много идентичного кода.

В некоторых языках (С++) специального ключевого слова для обозначения интерфейсов нет.
Можно считать, что любой интерфейс - это уже абстрактный класс, но не наоборот.