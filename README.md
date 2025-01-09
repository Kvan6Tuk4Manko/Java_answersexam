## 1. Введение в Java. Основные характеристики языка, сферы применения, история создания. Экосистема языка JAVA. JDK, JRE, JVM. 
- Простой - построен на основе языка C++, но значительно упрощен
- Объектно-ориентированный - Java с самого начала проектировался как объектно-ориентированный
- Распределенный - разработан для упрощения распределенных вычислений
- Интерпретируемый - для запуска необходим интерпретатор
- Надежный - Java-компиляторы могут обнаружить множество проблем
- Безопасный - несколько механизмов безопасности
- Кросс-платформенный - «Один раз напишите, везде запустите»
- Высокопроизводительный - достаточная скорость для интерактивных приложений, где центральный процессор простаивает
- Многопоточный - многопоточное программирование плавно интегрировано в Java
- Динамичный - новые функциональные возможности Java могут прозрачно встраиваться
---
- Java — это мощный и универсальный язык программирования
для разработки программного обеспечения, работающего на
мобильных устройствах, встраиваемых системах, настольных
компьютерах, серверах и т.д.

- Важные системы: банковские терминалы, системы обработки
транзакций, сервисы координации перелетов и другие.
---
- Java Development Kit (JDK) – это программный комплект, который предоставляет всё необходимое для разработки и компиляции Java-приложений.
- Java Runtime Environment (JRE) – это окружение, необходимое для выполнения Java-программ.
- Java Virtual Machine (JVM) – это центральный компонент платформы Java, который обеспечивает независимость кода от конкретной операционной системы и аппаратной архитектуры. JVM является частью JRE.

## 2. Основные платформы Java. Java SE, Java EE, Java ME, их особенности и области применения. 
- Java Card - создание приложений для смарт-карт и других устройств с ограниченными вычислительными ресурсами.
- Java Standard Edition (Java SE)-разработка настольных и серверных приложений. Она предоставляет стандартные библиотеки и API для создания полнофункциональных приложений.
- Java Micro Edition (Java ME) - создание приложений, работающих на мобильных устройствах, встроенных системах и т.д.
- Java Enterprise Edition (Java EE) - создания масштабируемых, надёжных и управляемых корпоративных приложений

## 3. Виртуальные машины и их роль в JAVA. Архитектура JVM. Основные компоненты: Class Loader, Execution Engine, Garbage Collector.
## 4. Компиляция Java-программ. Различия между JIT (Just-in-Time) и AOT (Ahead-of-Time) компиляцией. Преимущества и недостатки. 
## 5. Модель памяти в Java. Основные области памяти JVM: куча (Heap) и стек (Stack), их назначение и различия. Как распределяются объекты и примитивные данные в этих областях? Что такое Young Generation, Old Generation и Metaspace? Как работа сборщика мусора влияет на управление памятью?
## 6. Основные парадигмы программирования в Java. Объектно-ориентированное, функциональное, многопоточное программирование.
## 7. Виртуальные машины и их роль в JAVA. Особенности стандартной HotSpot JVM. GraalVM и другие сторонние виртуальные машины для Java. Основные преимущества и возможности сторонних виртуальных машин.
## 8. Компиляция и запуск проекта на Java. Обеспечение переносимости кода на различные платформы. Понятие промежуточного байт-кода и его роль в переносимости программ. Чем отличаются методы компиляции JIT (Just-In-Time) и AOT (Ahead-of-Time), и как они влияют на производительность и переносимость?
## 9. Современный инструментарий разработчика Java. Популярные IDE и их возможностей для написания, отладки и сборки кода. Основные системы сборки и их роль в управлении проектами на JAVA. Контроль версий с использованием Git и интеграция с платформами хостинга ИТ-проектов. Использование Docker и Kubernetes для контейнеризации и оркестрации приложений. Инструменты CI/CD  для автоматизации сборки, тестирования и деплоя JAVA приложений.
## 10. Современные фреймворки для разработки на Java. Особенности Spring Framework. Основные возможности Hibernate. Основные причины использования данных фреймворков при разработке на JAVA.
## 11. Объектная модель Java. Основные принципы объектной модели в Java: классы, объекты, интерфейсы, наследование и инкапсуляция. Класс Object и методы, которые он предоставляет.
## 12. Пакеты в Java. Основное предназначение. Структура, организация, использование в программировании (импорт пакетов).
## 13. Синтаксис и лексика Java. Основные элементы лексики языка: ключевые слова, идентификаторы, литералы, комментарии, операторы и разделители. Правила именования идентификаторов. Соглашения по оформлению кода.
## 14. Типы данных в Java. Примитивные типы данных, объявление и присваивание переменных. Отличия примитивных типов данных от ссылочных.
## 15. Типы данных в Java. Ссылочные типы данных, объявление и присваивание переменных. Отличия ссылочных типов данных от примитивных. Роль классов-оберток (Wrapper Classes) для работы с примитивами.
## 16. Константы в Java. Понятие констант и их объявление с использованием ключевого слова final. Основные правила и соглашения по именованию констант. Примеры создания констант для примитивных типов данных и строк. Как константы помогают обеспечить неизменность данных и улучшают читаемость кода?
## 17. Ключевое слово var в Java. Особенности использования var для объявления локальных переменных. Как происходит неявное выведение типа переменной компилятором? Ограничения на использование var: недопустимость для полей класса, параметров методов и возвращаемых типов.
## 18. Соглашения по оформлению кода Java. Java Code Conventions и её значение для совместной работы.

## 19. Класс и экземпляры класса. Что такое класс в Java и как происходит создание объектов (инстанцирование) с использованием ключевого слова new? Примеры создания и использования экземпляров класса.
## 20. Записи (Records) в Java. Какие возможности они предоставляют и в чем их отличие от обычных классов? Примеры использования записей.
## 21. Запечатанные (Sealed) классы. Как они ограничивают наследование и для чего используются?
## 22. Инкапсуляция в Java. Понятие инкапсуляции как механизма защиты данных и управления доступом к ним. Реализация инкапсуляции с использованием модификаторов доступа (private, protected, public, package-private). Роль геттеров и сеттеров в обеспечении контроля за изменением данных объекта. Примеры нарушения инкапсуляции и способы предотвращения этих ошибок.
## 23. Модификаторы доступа. Какие уровни доступа существуют в Java? Как модификаторы доступа используются для контроля видимости классов, полей и методов?
## 24. Модификатор final. Применение final к переменным, методам и классам. Как он предотвращает изменения данных, поведение методов и наследование? 
## 25. Конструкторы в Java. Понятие конструктора и его роль в создании объектов. Различия между конструктором и методом. Типы конструкторов. Как реализовать перегрузку конструкторов? 
## 26. Конструкторы в Java. Понятие конструктора и его роль в создании объектов. Использование ключевого слова this для вызова одного конструктора из другого. Особенности работы конструкторов в наследовании, вызов конструктора родительского класса через super.
## 27. Блоки инициализации. Виды блоков инициализации: статические и нестатические. Их роль в подготовке объектов и классов. Примеры использования блоков для сокращения повторяющегося кода.
## 28. Статические блоки инициализации. Примеры и использование статических блоков для выполнения кода при загрузке класса. Их роль в инициализации общих данных.
## 29. Модификатор static. Особенности использования static для полей, методов и блоков. Различия между статическими и нестатическими членами класса. Примеры применения для создания общих ресурсов.
## 30. Ключевое слово this. Использование this для доступа к полям и методам объекта, вызова других конструкторов и передачи текущего объекта. Примеры решения конфликтов имен с помощью this.
## 31. Концепция неизменяемых классов. Что делает класс неизменяемым? Использование final для предотвращения изменений. Примеры создания неизменяемых объектов.
## 32. Создание объектов. Отличие фабричных методов от стандартного создания объектов с использованием new. Примеры использования фабричных методов.
## 33. Рефлексия в Java. Возможности рефлексии для создания объектов и вызова методов во время выполнения. Примеры использования рефлексии для создания объектов.
## 34. Жизненный цикл объектов в JAVA. Роль сборщика мусора в управлении памятью. Примеры оптимизации работы объектов в Java.
## 35. Инициализация переменных в JAVA. Способы инициализации переменных: по умолчанию, в конструкторах, через блоки инициализации. Примеры применения.
## 36. Математические функции. Класс Math в Java и его методы для выполнения вычислений. Примеры использования тригонометрических и экспоненциальных функций в задачах. Нужно ли создавать объект класса Math для использования математических методов.

## 37. Абстракция и инкапсуляция класса. Понятие абстракции как отделения реализации класса от его использования. Как эти принципы улучшают структурирование кода и его модульность? 
## 38. Отношения между классами. Основные виды отношений между классами: ассоциация, агрегация, композиция, наследование.
## 39. Ассоциация. Понятие ассоциации как бинарного отношения между классами. Примеры реализации ассоциации в Java. Как ассоциация помогает моделировать взаимодействие объектов?
## 40. Агрегация и композиция. Понятия агрегации и композиции, их различия. Как они отражают отношения «has-a» между объектами? Примеры реализации агрегации и композиции в проектировании классов.
## 41. Обработка примитивных типов как объектных. Использование классов-оберток для работы с примитивными типами как с объектами. Примеры преобразования примитивных типов в объекты и обратно. 
## 42. Классы-обертки. Основные возможности классов-оберток: Integer, Double, Boolean и других. Методы для преобразования значений и сравнения объектов. Примеры использования методов parseInt, valueOf и compareTo.
## 43. Автоматическое преобразование. Что такое автоупаковка (autoboxing) и автораспаковка (unboxing) в Java? Как они автоматически преобразуют значения примитивных типов в объекты и обратно? Примеры использования.
## 44. Класс String. Понятие неизменяемости(иммутабельности) строк в Java. Как создаются объекты типа String? Примеры работы с методами создания, сравнения и модификации строк.
## 45. Строки в JAVA. Замена и разделение строк. Методы класса String для замены символов и разделения строк. Примеры работы с методами replace и split.
## 46. Строки в JAVA. Преобразования между строками и массивами. Как преобразовать строку в массив символов и наоборот? Примеры использования методов toCharArray и valueOf.
## 47. Строки в JAVA. Класс StringBuilder и StringBuffer. Понятие изменяемых строк. Основные отличия между StringBuilder и StringBuffer. Примеры их использования. Влияние классов StringBuilder и StringBuffer на типобезопасность.
## 48. Строки в JAVA. Преобразование символов и чисел в строки. Какие методы используются для преобразования чисел, символов и объектов в строки? Примеры работы с методами String.valueOf() и toString().
## 49. Строки в JAVA. Интернированные строки. Что такое интернированные строки? Как JVM оптимизирует работу с повторяющимися строками? Примеры их использования.
## 50. Наследование в JAVA. Основные принципы наследования в Java. Что такое суперклассы(родительские) и подклассы(дочерние)? Как наследование помогает переиспользовать код? Примеры реализации наследования.
## 51. Перегрузка метода в Java (overload). Переопределение метода в Java (override). В чем разница между перегрузкой и переопределением методов.
## 52. Наследование и отношение is-a. Как наследование реализует отношение «is-a»? Когда использование наследования может быть нецелесообразным? Примеры решений.
## 53. Ключевое слово super. Роль ключевого слова super в Java. Использование для вызова методов и конструкторов суперкласса. Примеры реализации.
## 54. Цепочка конструкторов. Понятие цепочки конструкторов. Как вызвать один конструктор из другого с использованием this() и super()? Примеры реализации.
## 55. Класс Object и его основные методы. Роль класса Object как суперкласса для всех классов в Java. Как метод toString() используется для представления объекта в виде строки? Примеры переопределения метода.
## 56. Полиморфизм. Понятие полиморфизма в Java. Как переменная супертипа может ссылаться на объект подтипа? Примеры применения полиморфизма для создания гибкого кода.

## 57. Интерфейсы в Java. Понятие интерфейсов как конструкций для определения общих операций. Основные элементы интерфейсов: константы и абстрактные методы. Примеры использования интерфейсов для создания обобщенных решений.
## 58. Интерфейсы в Java. Понятие интерфейсов как конструкций для определения общих операций. Особенности интерфейсов, добавленные в JAVA 8 версии. Дефолтные методы в интерфейсах.
## 59. Интерфейсы в Java. Особенности интерфейсов. Чем интерфейсы отличаются от классов? Как используются ключевые слова interface и implements? Примеры объявления и реализации интерфейсов.
## 60. Интерфейсы в Java 8 и 9. Новые возможности интерфейсов, такие как default и static методы (Java 8), а также private и private static методы (Java 9). Примеры реализации и применения.
## 61. Интерфейс Comparable. Как интерфейс Comparable используется для сравнения объектов? Реализация метода compareTo() и его роль в сортировке. Примеры работы с интерфейсом.
## 62. Интерфейс Comparable для классов стандартной библиотеки JAVA. Как реализован интерфейс Comparable в классах String, Integer и Date? Примеры сравнения объектов с помощью метода compareTo().
## 63. Интерфейс Comparable для пользовательских классов. Как реализовать интерфейс Comparable для пользовательских классов? Примеры сравнения объектов на основе пользовательских критериев.
## 64. Интерфейс Cloneable. Понятие клонирования объектов. Как интерфейс Cloneable позволяет клонировать объекты? Ограничения и примеры использования.
## 65. Метод clone(). Как метод clone(), определенный в классе Object, используется совместно с интерфейсом Cloneable? Примеры работы с клонируемыми объектами.
## 66. Интерфейсы и абстрактные классы. Основные различия между интерфейсами и абстрактными классами. 
## 67. Понятие абстрактных классов в Java. Что такое абстрактный класс, и как он используется для создания общего базового поведения? Чем отличается абстрактный класс от интерфейса? Примеры объявления и реализации абстрактного класса с абстрактными и конкретными методами.
## 68. Понятие абстрактных классов в Java. Объявление абстрактных методов. Что такое абстрактный метод, и какие правила нужно соблюдать при его объявлении? Как абстрактные методы помогают подклассам реализовать специфическое поведение? Примеры реализации абстрактных методов в наследуемых классах.
## 69. Понятие абстрактных классов в Java. Особенности работы с абстрактными классами. Почему абстрактные классы нельзя инстанцировать? Как использовать абстрактный класс как основу для других классов? Примеры создания иерархии классов с базовым абстрактным классом.
## 70. Ограничение множественного наследования в JAVA. Множественное наследование интерфейсов. Как классы наследуют методы от нескольких интерфейсов.
## 71. Интерфейсы в Java. Особенности интерфейсов. Интерфейсы и полиморфизм. Как интерфейсы способствуют реализации полиморфизма?

## 72. Обработка исключительных ситуаций в JAVA. Основные способы и подходы к обработке исключительных ситуаций в JAVA. Иерархия классов исключений в Java. Понятие и структура иерархии исключений. Чем отличаются классы Error, Exception и RuntimeException?
## 73. Создание и генерация исключений. Как создавать и генерировать исключения с помощью ключевого слова throw? Различия между throw и throws. Примеры создания пользовательских исключений.
## 74. Обработка исключений. Структура блока try-catch. Как обрабатывать исключения с использованием блоков try-catch? Примеры обработки нескольких исключений и упорядочения блоков catch. Роль объекта исключения (Exception e) в блоке catch.
## 75. Обработка исключений. Структура блока try-catch. Блок finally и его использование. Основные причины использования. Примеры использования.
## 76. Обработка исключений. Пропагирование исключений. Как исключения передаются вверх по стеку вызовов? Примеры использования ключевого слова throws в сигнатуре методов.
## 77. Обработка исключений. Проверяемые и непроверяемые исключения. Какие исключения считаются проверяемыми (checked), а какие - непроверяемыми (unchecked)? Примеры работы с ними. Исключения в популярных фреймворках. Почему большинство исключений в современных фреймворках являются непроверяемыми?
## 78. Обработка исключений. Использование try-with-resources. Как она упрощает управление ресурсами? Примеры работы.
## 79. Обработка исключитеьных ситуаций в JAVA. Роль JVM в обработке исключений. Как JVM управляет исключениями, если они не были обработаны? Примеры поведения при неперехваченных исключениях.
## 80. Перечисления (enums) в Java. Что такое перечисления и как они используются для создания фиксированных наборов значений? Характеристики перечислений. Перечисления и типобезопасность. Примеры их применения.
## 81. GUI в Java. Что такое GUI (графический пользовательский интерфейс)? Основные пакеты для работы с GUI в Java: AWT и Swing.
## 82. GUI в Java. Структура GUI в JAVA при реализации через Swing и AWT. Компоненты GUI. Какие элементы составляют графический интерфейс? Примеры кнопок, текстовых полей и других компонентов.
## 83. AWT (Abstract Window Toolkit). Что такое AWT и как он используется для создания GUI? Примеры простых интерфейсов с использованием AWT.
## 84. Swing в Java. Как Swing расширяет возможности AWT? Примеры создания интерфейсов с использованием Swing. Паттерн MVC в Swing. Как Swing реализует модель MVC (Model-View-Controller)? Примеры разделения логики, представления и управления в интерфейсе.
## 85. Структура GUI в Java. Основные компоненты GUI в Swing: контейнеры (JFrame, JPanel, JDialog), компоненты (JButton, JLabel, JTextField) и менеджеры компоновки. 
## 86. Класс JFrame. Что такое окно JFrame, и как использовать его для создания графического интерфейса? Примеры добавления элементов через метод getContentPane().
## 87. Класс JPanel. Как панель JPanel используется для группировки и управления компонентами? Примеры изменения менеджера компоновки с помощью метода setLayout().
## 88. Менеджеры компоновки в Java. Роль менеджеров компоновки в управлении размещением компонентов. Примеры использования менеджеров FlowLayout, BorderLayout, GridLayout.
## 89. Менеджер FlowLayout. Как работает FlowLayout? Примеры настройки выравнивания и промежутков между компонентами.
## 90. Менеджеры компоновки в Java. Роль менеджеров компоновки в управлении размещением компонентов. Примеры использования менеджеров FlowLayout, BorderLayout, GridLayout.
## 91. Менеджер FlowLayout. Как работает FlowLayout? Примеры настройки выравнивания и промежутков между компонентами.
## 92. Менеджер BorderLayout. Как BorderLayout делит контейнер на регионы (NORTH, SOUTH, EAST, WEST, CENTER)? Примеры создания интерфейсов с четкой организацией областей.
## 93. Менеджер GridLayout. Как компоненты размещаются в сетке с использованием GridLayout? Примеры создания таблиц или форм.
## 94. Менеджер BoxLayout. Как компоненты размещаются по горизонтали или вертикали с помощью BoxLayout? Примеры последовательного расположения элементов.
## 95. Границы в Swing. Как использовать границы для улучшения внешнего вида интерфейса? Примеры применения границ.
## 96. GUI и сбытийная модель в Java. Что такое событийная модель, и как она используется для взаимодействия компонентов через события? Основные элементы событийной модели.
## 97. Обработка событий в Java. Как источник события, слушатель и обработчик взаимодействуют в событийной модели? Примеры добавления слушателей событий. Модель делегирования событий. Как работает модель делегирования событий? 
## 98. Обработка событий при реализации GUI в JAVA. Классы событий пакета java.awt.event. Какие классы событий предоставляет пакет java.awt.event? Примеры обработки событий мыши и клавиатуры.
## 99. Обработка событий мыши в JAVA. Как использовать интерфейсы MouseListener и MouseMotionListener для обработки событий мыши? Примеры обработки нажатий и перемещений.
## 100. Обработка событий клавиатуры в JAVA. Как обрабатывать события клавиатуры с использованием KeyListener? Примеры регистрации слушателей клавиатурных событий.
## 101. Обобщённое программирование в Java. Понятие обобщённого программирования и его роль в упрощении создания алгоритмов для работы с различными типами данных. История разваития в JAVA. Примеры проектирования универсальных структур данных и алгоритмов.
## 102. Generics в Java. Реализация обобщенного программирования через Generics. Основные синтаксические конструкции: параметры типов, обобщенные классы и методы. Примеры работы с параметризованными классами и методами. Примущества и недостатки Generics.
## 103. Коллекции и Generics в Java. Как использование Generics повысило типобезопасность коллекций, таких как ArrayList, HashMap и HashSet? Примеры создания и обработки коллекций с обобщениями.
## 104. Параметризованные методы. Понятие параметризованных методов в Java. Как они позволяют работать с любыми типами данных? Примеры реализации методов с обобщенными параметрами и их вызова.
## 105. Generics в Java. Типовые ограничения в Generics. Как задать ограничения на параметры типов с помощью ключевых слов extends и super? Примеры их использования для обеспечения гибкости и безопасности обобщений.
## 106. Обобщенные интерфейсы. Использование Generics для создания универсальных интерфейсов. Примеры реализации обобщенных интерфейсов и их применения в реальных задачах.
## 107. Generics в Java. Подстановочные знаки (Wildcards). Как использовать ?, <? extends T> и <? super T> для работы с коллекциями? Примеры их применения.
## 108. Generics в Java. Стирание типов (Type Erasure). Как информация о Generics удаляется во время компиляции? Примеры преобразования Generics в сырой тип.
## 109. Коллекции в Java. Понятие коллекций как структур данных для хранения объектов. Основные интерфейсы и классы в Java Collections Framework (JCF). Примеры использования коллекций для хранения и обработки данных.
## 110. Иерархия коллекций. Структура иерархии коллекций в Java. Основные интерфейсы (Collection, List, Set, Map) и их ключевые особенности. Примеры реализации различных типов коллекций.
## 111. LinkedList в Java. Особенности класса LinkedList как реализации интерфейса List. Преимущества использования. 
## 112. Коллекции в Java. Понятие коллекций как структур данных для хранения объектов. Основные цели использования коллекций. Роль Iterable в Java Collections Framework. 
## 113. Коллекции в Java. Реализации List - ArrayList. Особенности функционирования ArrayList. Пример использования ArrayList.
## 114. Коллекции в Java. Создание Generic Collection в Java. Преимущства данного подхода. Примеры. 
## 115. Коллекции и Generics. Использование Generics для типобезопасности в коллекциях. Примеры создания типизированных списков и множеств.
## 116. ArrayList в Java. Понятие ArrayList как реализации интерфейса List. Основные методы (add, get, remove) для работы со списками. Примеры добавления, удаления и доступа к элементам.
## 117. Задача на выполнение


