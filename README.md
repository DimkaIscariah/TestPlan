# План по автоматизации

 # 1. Перечень автоматизируемых сценариев

 # Тест-кейс №1. Переход на страницу формы заявки на курс "Тестировщик ПО" через каталог курсов.
   1. Найти кнопку "Каталог курсов" на форме страницы и нажать на неё.
   2. Найти "Направление обучения" - "Программирование", нажать на элемент.
   3. Найти элемент "Тестировщик ПО", нажать на элемент.
   4. Найти кнопку "Записаться", нажать на неё.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".
     

 # Тест-кейс №2. Переход на страницу формы заявки на курс "Тестировщик ПО" через поиск в каталоге курсов.
   1. Найти кнопку "Каталог курсов" на форме страницы и нажать на неё.
   2. Ввести в строке поиска с наименованием "Какой курс вам нужен?" текст "Тестировщик".
   3. Перейти в появивщийся курс "Тестировщик ПО".
   4. Найти кнопку "Записаться", нажать на неё.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".  
  

 # Тест-кейс №3. Переход на страницу формы заявки на курс "Тестировщик ПО" через панель "Направление обучения".
   1. Найти на панели "Направление обучения" элемент "Программирование", нажать на него.
   2. Найти курс с наименованием "Тестировщик ПО", нажать на него.
   3. Найти кнопку "Записаться", нажать на неё.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".

 # Тест-кейс №4. Переход на страницу формы заявки на курс "Тестировщик ПО" через элемент главной страницы, раздел "Каталог курсов".
   1. Найти на главной странице элемент "Каталог курсов", нажать на него.
   2. Ввести в строку поиска с наименованием "Какой курс вам нужен?" текст "Тестировщик".
   3. Найти кнопку "Записаться", нажать на кнопку.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".

 # Тест-кейс №5. Переход на страницу формы заявки на курс "Тестировщик ПО" через элемент главной страницы, раздел "Программирование".
   1. Найти на главной странице элемент "Программирование", нажать на него.
   2. Ввести в строку поиска с наименованием "Какой курс вам нужен?" текст "Тестировщик".
   3. Найти кнопку "Записаться", нажать на кнопку.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".

 # Тест-кейс №6. Переход на страницу формы заявки на курс "Тестировщик ПО" через поиск в разделе "Программирование".
   1. Найти кнопку "Каталог курсов" на форме страницы и нажать на неё.
   2. Найти элемент "Программирование", нажать на элемент.
   3. Ввести в строку поиска с наименованием "Какой курс вам нужен?" текст "Тестировщик".
   4. Найти кнопку "Записаться", нажать на неё.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".

 # Тест-кейс №7. Переход на страницу формы заявки на курс "Тестировщик ПО" через панель "Направления обучения".
   1. Найти кнопку "Каталог курсов" на форме страницы и нажать на неё.
   2. Найти "Курсы для новичков", нажать на элемент.
   3. Ввести в строку поиска с наименованием "Какой курс вам нужен?" текст "Тестировщик".
   4. Найти кнопку "Записаться", нажать на кнопку.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".

 # Тест-кейс №8. Переход на страницу формы заявки на курс "Тестировщик ПО" через поиск в полном каталоге.
   1. Найти элемент "Полный каталог" на панели "Направления обучения", нажать на элемент.
   2. Ввести в строку поиска с наименованием "Какой курс вам нужен?" текст "Тестировщик".
   3. Найти кнопку "Записаться", нажать на кнопку.
  
   Ожидаемый результат: Открывается форма для записи на курс. Отображаются поля: "Имя", "Телефон", "Электронная почта".

# Тестирование формы записи на курс "Тестировщик ПО".

# Тест-кейс №1. Отправляем валидную заявку.
1. Нажимаем на кнопку "Записаться".
2. В поле "Имя" вводим "Дмитрий".
3. В поле "Телефон" вводим "+79209234724".
4. В поле "Электронная почта" вводим "iscariah2008@yandex.ru".
5. Нажимаем на кнопку "Записаться".

Ожидаемый результат: Открывается форма для оплаты обучения.

# Тест-кейс №2. Заявка с невалидными данными в поле "Имя" не отправляется.
1. Нажимаем на кнопку "Записаться"
2. В поле "Имя" вводим "81452"
3. В поле "Телефон" вводим "+79056173272"
4. В поле "Электронная почта" вводим "iscariah2008@yandex.ru"
5. Нажимаем на кнопку "Записаться".

Ожидаемый результат: Поле "Имя" выделено красным. Появляется сообщение "Данное поле должно содержать только буквы".

# Тест-кейс №3. Заявка без заполненного поля "Имя" не отправляется.
1. Нажимаем на кнопку "Записаться".
2. Поле "Имя" оставляем незаполненным.
3. В поле "Телефон" вводим "+79056173272".
4. В поле "Электронная почта" вводим "iscariah2008@yandex.ru".
5. Нажимаем на кнопку "Записаться".

Ожидаемый результат: Поле "Имя" выделено красным. Появляется сообщение "Данное поле обязательно для заполнения".

# Тест-кейс №4. Заявка с невалидными данными в поле "Телефон" не отправляется.
1. Нажимаем на кнопку "Записаться".
2. В поле "Имя" вводим "Дмитрий".
3. В поле "Телефон" вводим "Здравствуйте".
4. В поле "Электронная почта" вводим "iscariah2008@yandex.ru".
5. Нажимаем на кнопку "Записаться".

Ожидаемый результат: Поле "Телефон" выделено красным. Появляется сообщение "Номер телефона должен быть указан  в формате +7 (999) 999-99-99".

# Тест-кейс №5. Заявка без заполненного поля "Телефон" не отправляется.
1. Нажимаем на кнопку "Записаться".
2. В поле "Имя" вводим "Дмитрий"
3. Поле "Телефон" оставляем незаполненным.
4. В поле "Электронная почта" вводим "iscariah2008@yandex.ru".
5. Нажимаем на кнопку "Записаться".

Ожидаемый результат: Поле "Телефон" выделено красным. Появляется сообщение "Данное поле обязательно для заполнения".

# Тест-кейс №6. Заявка с невалидными данными в поле "Электронная почта" не отправляется.
1. Нажимаем на "Записаться".
2. В поле "Имя" вводим "Дмитрий".
3. В поле "Телефон" вводим "+79056173272".
4. В поле "Электронная почта" вводим "tpo242@gmail.cccom".
5. Нажимаем на кнопку "Записаться".

Ожидаемый результат: Поле "Электронная почта" выделено красным. Появляется сообщение "Неверный email".

# Тест-кейс №7. Заявка без заполненного поля "Электронная почта" не отправляется.
1. Нажимаем на кнопку "Записаться".
2. В поле "Имя" вводим "Дмитрий".
3. В поле "Телефон" вводим "+79056173272".
4. Поле "Электронная почта" оставляем незаполненным.
5. Нажимаем на кнопку кнопку "Записаться".

Ожидаемый результат: Поле "Электронная почта" выделено красным. Появляется сообщение "Данное поле обязательно для заполнения".



# Инструменты
  1. IntelliJ IDEA - среда разработки в которой будет написан код.
  2. Gradle - система сборки проектов внутри IntelliJ IDEA.
  3. Junit - фреймворк для написания и запуска автотестов.
  4. Selenide - фреймворк, необходимый для тестирования веб-интерфейсов.
  5. Lombok - библиотека, позволающая оптимизировать код.
  6. Faker - генератор пользовательских данных.
  7. Allure - система генератора отчётов, позволяющая просмотреть хронологию тестирования и отчёты о выполненной работе.
  8. Github - система контроля версия, сервис для хранения проектов.



# Необходимые данные/доступы/разрешения
  1. Разрешение на проведение тестирования сайта https://netology.ru
  2. Разрешение на предоставление тестовых данных для проверки возможности записаться на курс.
  3. Доступ к API сайта.
  4. Доступ к базе данных.



# Возможные риски при автоматизации
  1. Отсутствие разрешения на проведение тестирования.
  2. Недоступность сайта.
  3. Возможная смена кода страницы.
  4. Высокая стоимость автоматизации.



# Необходимые специалисты для проведения автоматизации
  Инженер по автоматизированному тестированию



#  Интервальная оценка в часах с учётом рисков
   1. Подготовка инструментов и написание кода автотестов - 20 часов.
   2. Подготовка необходимой отчётной документации 4 часа.
   3. Запас времени с учётом возможных рисков и непредвиденных ситуаций - 10 часов.
