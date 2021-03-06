## Junior


### Общие

1. Какие методы HTTP-запросов вы знаете?

2. Какие версии HTTP-протокола вам известны?

3. Какие знаете коды ответа (состояния) HTTP?

4. Что такое Cross-Origin Resource Sharing? Как устранить проблемы с CORS?

5. Что такое cookie?

6. Какой максимальный размер cookie?

7. Что означает директива use strict?

8. Чем JS отличается при работе на front-end и back-end?

9. Что такое статическая и динамическая типизации?

10. Как клиент взаимодействует с сервером?

11. Что такое REST?

12. Объяснить понятие мутабельность/иммутабельность? Какие типы являются мутабельными и наоборот?

13. Как искать ошибки в коде? Используете ли вы дебаггер?

14. Каких известных людей из мира JS знаете?


### JS Core

15. Какие существуют типы данных в JS?

16. Как проверить, является ли объект массивом?

17. Как проверить, является ли число конечным?

18. Как проверить, что переменная равна NaN?

19. Чем отличается поведение isNaN() и Number.isNaN()?

20. Сравните ключевые слова var, let, const.

21. Что такое область видимости?

22. Что такое деструктуризация?

23. Для чего предназначены методы setTimeout и setInterval?

24. Сравните подходы работы с асинхронным кодом: callbacks vs promises vs async / await.

25. Можно ли записывать новые свойства / функции в прототипы стандартных классов (Array, Object и т. д.)? Почему нет? В каких случаях это делать можно? Как обезопасить себя, если нужно расширить прототип?

26. Назовите методы массивов, какие помните, и скажите, для чего они нужны.

27. Какие методы перебора массива знаете? В чем их отличие?

28. Как работают операторы присваивания / сравнения / строчные / арифметические / битовые и т. д.?

29. Опишите назначение и принципы работы с коллекциями Map и Set.

30. Что означает глубокая (deep) и поверхностная (shallow) копия объекта? Как сделать каждую из них?


### Функции

31. Какая разница между декларацией функции (function declaration) и функциональным выражением (function expression)?

32. Что такое анонимная функция?

33. Расскажите о стрелочных функциях (arrow function). В чем заключаются отличия стрелочных функций от обычных?

34. Что такое и для чего используют IIFE (Immediately Invoked Function Expression)?

35. Что такое hoisting, как он работает для переменных и функций?

36. Что такое замыкание (closure) и какие сценарии его использования?

37. Как вы понимаете замыкания? Что будет выведено в консоли в этом случае?

```
var f = function() {

  console.log(1);

}

var execute = function(f) {

  setTimeout(f, 1000);

}

execute(f); // что выведет в консоль и почему

f = function() {

  console.log(2);

}
```

38. Что такое рекурсия?

39. Что означает ключевое слово this?

40. Что такое потеря контекста, когда происходит и как ее предотвратить?

41. Методы функций bind / call / apply - зачем и в чем разница?


### Front-end

42. Что такое DOM?

43. Сравните атрибуты подключения скрипта async и defer в HTML-документе.

44. Какая разница между свойствами HTML-элементов innerHTML и innerText?

45. Опишите процесс всплытия (bubbling) событий в DOM.

46. Как остановить всплытие (bubbling) события?

47. Как остановить дефолтную обработку события?

48. Чему равен this в обработчике событий (event handler)?

49. Что такое LocalStorage и SessionStorage? Какой максимальный размер LocalStorage?

50. Как получить высоту блока? Его положение относительно границ документа?

51. Что такое webpack?

52. Чем отличается dev-сборник от prod?


### Верстка

53. Что такое блочная модель CSS?

54. Какие способы центрирования блочного контента по горизонтали и вертикали знаете?

55. Какие подходы в верстке вам известны (float, flex, grid, etc.)?

56. Как сделать приложение responsive?

57. Какие есть принципы семантической верстки?

58. Зачем нужны префиксы для некоторых CSS-свойств (-webkit-, -moz- и т. д.)?

59. Как упростить написание кросс-браузерных стилей?

60. Практические задачи: прокомментировать и исправить пример плохого CSS или HTML.

61. Что такое CSS-препроцессоры? С какими работали? Что нового они приносят в стандартный CSS?


### Angular

62. Перечислите основные компоненты фреймворка (модуль, роут, директива и т .п.).

63. В чем разница между компонентом и директивой?

64. Расскажите о жизненном цикле компонента.

65. Перечислите часто используемые хуки жизненного цикла компонента и расскажите, для чего они нужны?

66. В чем разница между конструктором и ngOnInit-хуком?

67. Как защитить роут от несанкционированного доступа? Какие механизмы предоставляет для этого фреймворк?

68. Что такое Lazy loading, как и для чего используется?

69. Какое назначение RouterOutlet?

70. Как компоненты могут взаимодействовать друг с другом?

71. Как создать two-way binding свойство для компонента?

72. Какие типы форм у фреймворка? В каких случаях и что лучше использовать?

73. Какие состояния у формы и как это можно применить?

74. Зачем нужны сервисы? Как с ними работать?

75. Что такое singleton-сервисы? Каково их назначение? Способ создания?

76. Какие есть способы объявления сервисов?

77. Для чего нужны модули? Сколько их должно быть в проекте?

78. Зачем нужны общие модули (shared)?

79. Какие преимущества типизации в TypeScript?

80. Какие возможности TypeScript можно использовать для типизации (здесь имеются в виду интерфейсы, типы, enum и т. д.)?

81. Какая разница между интерфейсом и классом?

82. В чем разница между интерфейсом и абстрактным классом?

83. Какая разница между интерфейсом и типом?

84. Что такое RxJS? Как он используется во фреймворке? Какие компоненты фреймворка тесно связаны с ним?

85. Чем отличаются Observable и Promise?

86. Для чего нужны Subjects? Какие типы Subjects существуют?

87. Как сделать несколько последовательных запросов к API с помощью HTTP-сервиса и RxJS?

88. Какая разница между switchMap, concatMap, mergeMap?

89. Как можно конфигурировать Angular-приложение?

90. Зачем нужны environment-файлы? Когда их лучше не использовать?

91. В чем разница между «умным» (smart) и «глупым» (dumb) компонентами? В каких случаях применяется каждый из них?

92. В чем разница между NgForm, FormGroup и FormControl и как их применяют для построения форм?

93. Зачем нужен и как работает async pipe?

94. Как следить за развитием фреймворка? Каких известных людей, связанных с Angular, знаете / читаете?


### React

95. Работали ли вы с классовыми компонентами? В чем их особенность?

96. Какие данные лучше хранить в состоянии компонента, а какие передавать через пропсы? Приведите пример.

97. Ознакомлены ли вы с хуками? В чем их преимущества? Приходилось ли делать свои и с какой целью?

98. Знакомы ли вы с фрагментами и порталами? Зачем они нужны?

99. Когда и для чего используют рефы?

100. Какие вы знаете методы жизненного цикла компонента?

101. В каком методе жизненного цикла компонента лучше делать запросы на сервер? Почему?

102. В каком методе жизненного цикла компонента лучше делать подписку и отписку от листенера? Почему? Зачем отписываться?

103. Был ли опыт работы с контекстом? Когда его стоит использовать?

104. В чем особенность PureComponent?

105. Работали ли вы с мемоизоваными селекторами (memoized selectors)? Для чего их используют и какой принцип работы?

106. В чем видите преимущества библиотеки React?

107. Почему библиотека React быстрая? Что такое Virtual DOM и Shadow DOM?

108. Зачем в списках ключи? Можно ли делать ключами индексы элементов массива? Когда это оправдано?

109. В чем основная идея Redux?

110. Работа со стилями в React.

111. React - это библиотека или фреймворк? Какая разница между этими двумя понятиями.

112. Можно ли использовать jQuery вместе с React? Почему да / нет?

113. Что такое codemod?

114. Приходилось ли вам настраивать проект React с нуля? С помощью каких инструментов вы это делали?

115. Перечислите все библиотеки, которые использовали в связке с React.

116. Что самое сложное вам приходилось реализовывать с помощью React?


### Back-end

117. Что такое REPL?

118. Что такое streams в Node.js?

119. Что такое middleware?

120. Для чего используют функцию setImmediate?

121. Зачем нужен app.param() в express?

122. Что такое token based authentication?


### Базы данных

123. Напишите простой запрос для вычисления трех авторов, у которых больше всего книг.

124. Напишите запрос, который выбирает последние три комментарии для конкретного пользователя для двух таблиц: комментарии и пользователи.

125. Спроектируйте простую схему базы данных для библиотеки.

126. Для чего используют SQL-оператор HAVING?

127. Зачем используют SQL-оператор LEFT JOIN?

128. Чем отличается embed- от reference-связи в MongoDB?

129. В одном проекте программисты сохраняют данные в MongoDB-коллекции комментариев, используя такие типы данных (смотрите ниже). Что плохого в этом решении?

```
id: ObjectID

text: string

author_id: string

created_at: Date
```

130. В проекте понадобилось внести изменения в структуру таблиц, добавить несколько полей и индексы. Как программисты будут делать это на продакшене?


### Инструменты

131. Каждый раз, когда вы делаете pull, почему-то случается конфликт в последней строке во всех файлах, которые вы редактировали. Что происходит?

132. Что делает команда git fetch?

133. Какой git hygiene подходы вы знаете?

134. Что такое CI / CD? Для чего это нужно?


### Практические задания

135. Расскажите, какие есть способы копирования простого объекта типа obj = {a 1, b 2, c 3}

136. Напишите deep clone для объекта.

137. Назовите различные способы, как поменять местами значения двух переменных.

138. Менеджер попросил в задаче поменять статусы из «active, inactive» на «active, removed», но в коде фигурируют только цифры и непонятно, какой статус соответствует какой цифре. Как помочь будущим программистам не лезть в документацию по коду? Вопрос ставят на конкретном примере с кодом.

139. Необходимо сделать мини проект - список пользователей с формой создания / редактирования пользователя:

Для хранения пользователей используйте Firebase (это бесплатно).
Для стилизации используйте Bootstrap.
Минимальный набор полей пользователя:
имя;
фамилия;
электронная почта;
телефон (в формате +380 (XX) XXX-XX-XX)
дата рождения;
будет плюсом - добавление аватара и возможность crop-картинки.
Пользователи должны иметь возможность фильтрации и пагинацию.
Проект должен содержать README-файл с шагами для запуска.



## Middle


### Общие

1. Расскажите о пирамиде тестирования.

2. Какие типы автоматизированных тестов выпадала возможность писать? Какие библиотеки при этом использовали? Каким инструментам отдаете предпочтение и почему?

3. Что такое unit-тесты? Какое место в пирамиде тестирования занимают unit-тесты?

4. Что такое code coverage? Обязательно 100% покрытие тестами кода?

5. Как запретить браузеру отдавать кэш на HTTP-запрос?

6. Что такое XSS (Cross-Site Scripting)?

7. Расскажите о паттернах Observer, Pub / Sub. Какая между ними разница? Приведите примеры реализации этих паттернов в известных фреймворках / библиотеках / браузерных API.

8. С какой целью может быть использован event listener события fetch self.addEventListener ( 'fetch', event => {})?

9. Что такое Event loop и как он работает? Расскажите о микрозадачах и макрозадачах.


### JS Core

10. Какие типы данных бывают в JavaScript? Какой будет результат выполнения кода?

```
let firstObj = { name: 'Hello' };

let secondObj = firstObj;

firstObj = { name: 'Bye' };

console.log(secondObj.name);
```

11. Что такое temporal dead zone?

12. Как работает boxing / unboxing в JavaScript?

13. В чем разница между оператором in и методом hasOwnProperty?

14. Опишите, с помощью чего в JS реализуются такие ООП-парадигмы, как инкапсуляция, полиморфизм, абстракция?

15. Что такое прототип? Как работает прототипное наследование в JS? Объясните работу кода.

```
function Main () {}

Main.prototype = { protected: true };

const obj = new Main();

Main.prototype = { protected: false };

console.log('Object protection: ', obj.protected);
```

16. Какая разница между композицией и наследованием?

17. Почему не стоит использовать конструкторы типа new String?

18. Расскажите о базовом устройстве и механизме работы Event loop.

19. Что такое записи (records) и кортежи (tuples)? Чем они отличаются от обычных объектов?

20. Какие различия в поведении ES5 функции-конструктора и ES2015 класса?

21. Как реализовать паттерн «Модуль»?

22. Почему typeof null возвращает object?

23. Что такое приведение (преобразование) типов в JS?

24. Что такое явное и неявное приведение (преобразование) типов данных в JS? Как происходит преобразование типов в следующих примерах:

```
{}+[]+{}+[1]

!!"false" == !!"true"

['x'] == 'x'
```

25. Что такое Garbage Collector?

26. Опишите основные принципы работы «сборщика мусора» в JS-движках (engines).

27. Опишите назначение и принципы работы с коллекциями WeakMap и WeakSet? Чем они отличаются от коллекций Map и Set соответственно?

28. Чем отличается Observable от Promise?

29. Что такое Promise? Назовите порядок выполнения then и catch в цепочке.

```
Promise.resolve(10)

  .then(e => console.log(e)) // ??

  .then(e => Promise.resolve(e))

  .then(console.log) // ??

  .then(e => {

    if (!e) {

      throw 'Error caught';

    }

  })

  .catch(e => {

    console.log(e); // ??

    return new Error('New error');

  })

  .then(e => {

    console.log(e.message); // ??

  })

  .catch(e => {

    console.log(e.message); // ??

  });
```

30. Расскажите о последовательном и параллельном выполнении асинхронных функций. В чем разница между Promise.all() и Promise.allSettled()?

31. Что такое дескрипторы свойств объектов? Расскажите об их практическом применение.

32. Назовите несколько способов создания постоянного (неизменного) объекта в JavaScript.

33. Как создать свойство у объекта, которое нельзя будет изменить?

34. Зачем нужен конструктор Proxy? Приведите пример использования.

35. Что такое ArrayBuffer? В чем разница между Uint32Array и Float32Array? Каков результат выполнения кода?

```
const uint32Array = new Uint32Array();

Array.isArray(uint32Array);
```

36. Каким будет результат сравнения?

```
const url = “HTTPs://xyz.com/path<to>page.html”;

encodeURI(url) == encodeURIComponent(url);
```

37. Расскажите о генераторах и итераторах.

38. Объясните, что делает приведенный ниже код:

```
function * fn(num) {

  for (let i = 0; i < num; i += 1) {

    yield console.log(i);

  }

}

const loop = fn(5);

loop.next();

loop.next();
```

39. Расскажите о типе данных Symbol и его практическом применении. Как перевести число с 10-разрядной системы в 16 (2,8) разрядную систему счисления?


### Функции

40. Объясните, что означает currying. Приведите пример использования на практике.

41. Приведите пример функции с мемоизацией. Когда следует применять эту технику?

42. Что такое чейнинг функций? Напишите пример с использованием этого подхода.

43. В чем разница между function и arrow function? Каким будет результат выполнения кода?

```
const pluckDeep = key => obj => key.split('.').reduce((accum, key) => accum[key], obj)

const compose = (...fns) => res => fns.reduce((accum, next) => next(accum), res)

const unfold = (f, seed) => {

  const go = (f, seed, acc) => {

    const res = f(seed)

    return res ? go(f, res[1], acc.concat([res[0]])) : acc

  }

  return go(f, seed, [])

}
```

### Front-end

44. В чем принципиальная разница между событиями mouseleave и mouseout?

45. В каком порядке обрабатываются пользовательские события в DOM (click, mouseover и т .д.)? FIFO или LIFO?

46. Что такое Event bubbling и Event capturing?

47. Сравните методы объекта event stopPropagation и stopImmediateProparation.

48. Какие есть подходы оптимизации производительности веб-страницы?

49. Как реализован механизм same-origin policy в браузере? На какие браузерные API он распространяется?

50. Назовите способы хранения данных в браузере. Сравните их.

51. Web worker'ы. Опишите особенности передачи данных между worker'ами и основным потоком, между разделенными worker'ами.

51. Что такое Transferable-объекты?

52. Расскажите о способах оптимизации выполнения ресурсоёмких операций JS для улучшения производительности рендеринга контента на странице.

53. Почему ResizeObserver вызывает события изменения размера до воспроизведения элемента, а не после?

54. Расскажите, как вы понимаете Web Accessibility?

55. Опишите алгоритм создания функционала, который обеспечивает чтение содержимого .txt файла при перетаскивании его из файловой системы в окно браузера.

56. Что такое Virtual DOM?


### Верстка

57. Объясните разницу между единицами измерения px, em, rem.

58. Для чего нужны CSS-переменные? Приведите несколько примеров использования.

59. Что произойдет при добавлении следующего селектора?

```
* {Box-sizing: border-box; }
```

60. Как адаптировать страницу для печати?

61. Опишите особенности кастомизации стилей стандартных элементов форм.

62. Что такое progressive рендеринг? Какие подходы используются?

63. Назовите несколько способов реализации lazy-loading медиаресурсов на странице.

64. Назовите популярные шаблонизаторы для фронтенд-разработки. Опишите особенности их использования.

65. Назовите популярные CSS-методологии и их различия.

66. Как работает CSS Grid?

67. Какие форматы изображений поддерживают анимацию?

68. Как отследить прогресс / окончание CSS @keyframes анимаций или плавных переходов, реализованных с помощью transition, в JS?

69. Какие CSS-свойства могут быть обработаны непосредственно через GPU? Что такое композитные слои и почему большое их количество может привести к аварийному завершению работы браузера на мобильных устройствах?

70. Как переиспользовать инлайн SVG-элементы на странице?

71. Опишите способы оптимизации SVG-файлов.

72. Как реализовать иконочный шрифт из определенного набора SVG-файлов?

73. Что такое ложное жирное или ложное курсивное (Faux) начертание шрифтов?

74. Что такое #shadow-root в инспекторе HTML-страницы?

75. Зачем нужны Custom Elements?

76. Почему удаление лишних символов пробелов / символов переноса в HTML не отражается на конечной производительности загрузки страницы?

77. Что такое контекст отображения canvas? Какие существуют типы контекста для рендеринга двумерной и трехмерной графики?

### Angular

78. Как работает Dependency injection? Зачем это нужно? Расскажите об использовании кастомных инжекторов.

79. Что такое zone.js? Для чего Angular использует зоны? С какой целью можно использовать NgZone-сервис?

80. Как работает Change detection? Как можно оптимизировать компонент с помощью схем Change detection? Какие еще есть приемы для оптимизации рендеринга (связанные с Change detection)?

81. Как выполнить конфигурацию HTTP-сервиса? Зачем она нужна? Обработка HTTP-ошибок?

82. Какие есть подходы к организации работы с данными?

83. Как подготовить сборник к деплою?

84. Что такое NgRx? Когда стоит использовать?

85. В каких случаях лучше использовать Renderer-сервис вместо нативных методов? И наоборот?

86. Как работают и для чего нужны резолверы? Как получить данные, загруженные резолверами?

87. Как работают и зачем нужны динамические компоненты? Приведите примеры их целесообразного использования.

88. Какая разница между @ViewChild и @ContentChild?

89. Что делает код и как иначе можно связать класс компонента с переменной?

```
@HostBinding ( 'class.valid') isValid;
```

90. Как можно кэшировать данные, используя сервисы или RxJS?

91. Что такое асинхронная валидация форм? Когда применяется и как реализуется?

92. Зачем нужна forRoot-функция модуля?

93. Какая разница между декларированием и экспортом компонента из модуля?

94. Почему плохо «провайдить» сервис с shared-модуля в lazy-loaded модуль? (Вопрос о scope модулей.)

95. Что такое :: ng-deep и для чего используется?

96. Какие тесты можно запустить для Angular-программы? Какие инструменты используют для тестирования Angular-программы?

97. Как протестировать API-сервис?


### React

98. Что такое JSX? Что лежит в его основе?

99. Как работает алгоритм Virtual DOM?

100. Для чего нужно свойство key во время рендеринга списков?

101. В чем разница между функциональными и классовыми компонентами?

102. Зачем и когда нужно передавать props в super() при использовании классовых компонентов?

103. Почему нужно использовать setState() для обновления внутреннего состояния компонента?

104. В чем заключается принцип «подъема состояния»?

105. Какие библиотеки менеджмента состояния React-приложения вы знаете? Зачем они нужны?

106. Когда следует использовать Redux? Какие есть альтернативы?

107. Redux vs Mobx?

108. Расскажите о базовом принципе работы React Hooks.

109. В чем разница между createRef и useRef?

110. Когда следует использовать React refs? Когда не стоит?

111. Какие недостатки библиотеки React видите?

112. Какие паттерны используете вместе с React?

113. Как относитесь к типизации вместе с React?

114. Как построить хорошую архитектуру React-проекта?

115. Оптимизация React-приложений? Как измерить производительность программы?

116. Можно ли приложение на React встроить в другое приложение на React?


### Back-end

117. Почему Node.js однопоточный, а не многопоточный?

118. Что такое event driven development?

119. Сравните fork() и spawn() методы.

120. Расскажите о Node.js фреймворках, которые использовали. Какая между ними разница?

121. Опишите словам код ендпоинта, который должен сохранить с клиента файл размером 4 гигабайта и положить его на S3 или другой CDN.

122. Что такое микросервисы, зачем их используют?

123. В каких случаях вы бы выбрали монолит, а в каких - микросервисы?

124. Как понять, что приложение в определенный момент работает исправно?

125. Как понять, что приложение за последние три дня работал исправно?

126. Как происходит проверка правильности пароля при использовании bcrypt?

127. Что такое JWT?

128. Джуниор прислал код на ревью. Что здесь не так? Как исправить?

```
router.post ( '/ users', async (req, res, next) => {

  const user = await db.createUser (req);

  if (user) {

    return res.json (users);

  }

  res.json ({error: "can not create user"})

})
```

### Базы данных

129. Что такое Redis и для чего его используют?

130. Какие базы данных использовали? Какая разница между SQL и NoSQL?

131. Для двух таблиц - комментарии и пользователи - напишите запрос, который выбирает последние три комментария для каждого пользователя.

132. Я как заказчик прошу выбрать вас базу данных для нового проекта. Ваши действия?


### Инструменты и другое

133. Для чего нужен package-lock.json?

134. В чем разница между npm install и npm ci?

135. Для чего нужны бандлеры?

136. Расскажите о модульном подключении скриптов. Приведите пример использования загрузчиков / бандлеров модулей.

137. Чем различаются git merge и git rebase?

138. Что такое staging area в git?

139. Опишите процесс code review. Назовите основные правила, способы разрешения конфликтов и споров во время его проведения.


### Практические задания

140. Напишите функцию Sleep (ms), которая останавливает выполнение async-функции на заданный промежуток времени.

141. Реализуйте один из методов массива (например, splice).

142. Напишите функцию с RegExp для нахождения всех HTML-ссылок в строке.

143. Реализуйте функцию, которая исполнит callback для всех элементов определенной ветви DOM-дерева.

144. Реализуйте таблицу с виртуальным скролом.

145. Реализуйте функцию преобразования URL query строки в JSON.

```
const inData = "user.name.firstname=Bob&user.name.lastname=Smith&user.favoritecolor=Light%20Blue";

function queryObjectify(arg) {

// ??

}

queryObjectify(inData)

/* Результатом выполнения для входящего ряда, должен быть следующий объект

{

  'user': {

    'name': {

      'firstname': 'Bob',

      'lastname': 'Smith'

    },

    'favoritecolor': 'Light Blue'

  }

};

*/
```

146. Реализуйте функцию нахождения пересечения двух массивов.

```
const first = [1, 2, 3, 4];

const second = [3, 4, 5, 6];

function intersection (a, b) {

// ??

}

intersection(first, second) // -> [3, 4]
```

147. Реализуйте функцию / класс для генерации HTML.

```
const HTMLConstruct = {};

HTMLConstruct.span('foo'); // -> <span>foo</span>

HTMLConstruct.div.span('bar'); // -> <div><span>bar</span></div>

HTMLConstruct.div.p(

HTMLConstruct.span('bar'),

HTMLConstruct.div.span('baz')

); // -> <div><p><span>bar</span><span>baz</span></p></div>
```

148. Если есть проект с ограниченными сроками и некритичной производительностью, чем будете руководствоваться при выборе библиотек, подходов? Или все же будете обращать внимание на производительность? Или наоборот: сроки нелимитированные, производительность важна. Ваши действия?



## Senior

### Общие

1. Расскажите о функциональном программировании.

2. Что такое TDD (Test Driven Development) / BDD (Behaver Driven Development)?

3. Расскажите подробно о работе HTTPS.

4. Какой стек технологий можно выбрать для реализации клона какого-нибудь известного проекту и почему?

5. Имеется проект на старых технологиях, необходимо в него вносить изменения. Как это сделать лучше всего?

6. Если у кандидата есть опыт работы с несколькими фреймворками: какой будете использовать для следующего проекта? Какие факторы будут влиять на выбор?

7. Что такое V8 Engine?


### JS Core

8. Реализация паттерна Class Free OOP (HTTPs://observablehq.com/@bratter/class-free-oop).

9. Паттерн async disposer (HTTPs://advancedweb.hu/what-is-the-async-disposer-pattern-in-javascript).

10. использование регулярных выражений. Когда приемлемо / неприемлемо? Как они работают? Как можно сделать читабельный код?


### Front-end

11. Как браузер определяет, можем ли мы общаться между вкладками?

12. Что такое Content Security Policy?

13. Как избежать загрузки кэшированных файлов скриптов и стилей?

14. Что такое requestAnimationFrame?

15. Расскажите о микросервисной архитектуре Front-end App.

16. Что такое Shadow DOM?

17. Сравните nextElementSibling и nextSibling.

18. Какие знаете метрики веб-сайта?


### Angular

19. Как проводится конфигурация NgZone-модуля? Когда это необходимо?

20. Что раздражает в фреймворке? Что бы вы изменили?

21. Если бы вы решали, что добавить в следующем релизе фреймворка, какая фича это была бы?

22. Писали ли вы кастомные декораторы? Если да, то зачем?

23. Сделать ревью кода и дать замечания по архитектуре.

24. Расскажите, как бы вы делали такие фичи. Опишите архитектуру фичи в приложении.


### Back-end

25. Сравните Common.js с AMD Modules и ES6 Imports.

26. Какой фреймворк выбрали бы для бэкенда, почему?

27. Опишите своими словами, как работает OAuth v2.

28. Есть проект с источниками памяти, как их обнаружить, устранить и предотвратить это в будущем?

29. Есть проект с performance issues, как их обнаружить, устранить и предотвратить в будущем?


### Базы данных

30. Какие альтернативные виды баз данных используете?

31. Что такое RDS и почему он иногда не подходит?

32. Что такое SQL Injections и как их избежать?

33. Почему для запросов в БД надо использовать плейсхолдеры?

34. Как спроектировать кластер на MongoDB?

35. Для чего используют MongoDB Aggregation framework?

36. Расскажите о GraphQL.


### Инструменты

37. Можете ли вы описать суть методологии git flow в двух словах?

38. Что означает требование делать squash commits во время rebase?

39. Каково ваше мнение об альтернативных системы контроля версий (Version Control System)?

40. Какие конвенции знаете и используете для git?

41. Расскажите о своем опыте использования / внедрения CI / CD.

42. Необходимо настроить деплой проекту на несколько сред. Расскажите, как бы вы построили процесс? Какие инструменты использовали бы?


### Практические задания

43. Реализуйте асинхронный метод filter для Array (должны работать await).

44. Реализуйте функцию reduce при помощи рекурсии.

45. Как можно было бы сделать toggle-компонент, как в iPhone, без использования JS?