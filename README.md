ПРИМЕР ИНТЕГРАЦИОННОГО ТЕСТА

1)  -тест на отправку письма:
создать пользователя в приложении электронной почты
- отправка письма от нового пользователя на другой адрес элетронной почты
- проверить,что письмо успешно отправлено и находится в папке "отправленные"
- проверка,что письмо доставлено адресату
 ТЕСТ НА ПОЛУЧЕНИЕ ПИСЬМА
- создание пользователя в приложении элетронной почты
- отправка тестового письма на адрес этого пользователя
- проверить,что письмо получено и находится во входящих письмах получателя
- проверка содержимого письма и соответствие ожидаемым данным

  - проверка отправки сообщения на другой домен элетронной почты
  - проверка,что письмо доставленно на другой домен почты
  - проверка получения письма с другого домена элетронной почты

 SMOKE-тест электронной почты
 - проверка авторизации:приложение должно предоставить возможность поля ввода логина и пароля для входа в почтовый ящик.
   тест включает в себя ввод правильных данных и проверку успешного входа в аккаунт.
- проверка отправки электронной почты: тест включает в себя нажатие на кнопку "Написать" и проверку ,что открывается новое окно для создания и отправки письма.
так же можно включить проверку полей "кому", "тема" и "текст" письма,а затем нажатие кнопки "отправить"
Результат- успешная отправка письма без ошибок
- Работа в офф-лайн режиме: проверить, что система позволяет пользоваться электронной почтой и просматривать уже скаченные сообщения без подключения к интернету
- удаление и архивирование сообщений : проверить, что система предоставляет возможность удаления и архивирования почтовых сообщений , а также возможность восстановления удаленных сообщений
- Возможность создания папок и меток : проверить ,что пользователи могут создавать свои папки и метки для более удобной организации почтовых сообщений
6) Проверить, что система правильно автоматически сортирует входящие сообщения по разделам : "Входящие", "Отправленные", "Черновик"
- Проверка ,что система правильно предоставляет возможность установки фильтров и правил для автоматической сортировки писем
- Проверка удаления писем. Включает выбор одного или несколько писем и выполнения удаления писем. Результат должен быть успешное удаление писем без ошибок

РЕ-ТЕСТ 
- планирование тестов: включает в себя разработку плана тестирования , выбор тестовых случаев , определение приоритета исправленных ошибок
- проведение тестов включающие фиксированные ошибки , чтобы убедиться в работоспособности системы в целом.
- приложение должно корректно отправлять и получать письма.
- приложение должно правильно работать с различными типами вложений. Включает проверку прикрепления вложений к письмам.

НЕФУНКЦИОНАЛЬНОЕ ТЕСТИРОВАНИЕ

- тестирование производительности : проверяется как быстро приложение обрабатывает большое количество писем и вложений, отправленных и полученных пользователями
- тестирование безопастности: направлен на проверку уровня защиты личных данных пользователей и безопастности переписки. В ходе проверки проводится анализ системы на уязвимости и попытки получить доступ к почтовым ящикам без авторизвции
- тестирование совместимости: проверяется насколько хорошо работает приложение с различными операционными системами, браузерами, мобильными версиями браузеров и операционных сиситем
- тестирование удобство пользования: проверяется насколько удобно и интуитивно понятно использовать приложение электронной почты
- оценивается навигация по интерфейсу , доступность основных функций и возможности настройки(фильтрация папок)
- тестирование надежности: проверяется надежность приложения и его способность сохранять почту и данные пользователя в течении длительного времени. Также проводится тест на восстановление данных после сбоев и потери связи с сетью.

2). РАЗДЕЛ СПАМ
Проведение регриссионного тестирования при добавлении раздела "Спам" , является необходимым.
это процесс проверки работоспособности системы после внесения изменений в уже существующую функциональность.
Регриссонное тестирование позволяет убедиться, что вновь внесенные изменения не привели к появлению ошибок и не влияют на работу всей системы в целом. В данном случае следует проверить , что добавление раздела "Спам" работает корректно, а остальные функции не нарушены.

ПЕРЕИМЕНОВАНИЕ РАЗДЕЛА

- Изменение раздела может повлечь за собой изменение функционала приложения. Возможно в раздел "Корзина" появится новая функция работы с удаленными письмами. Такие измения могут привести к ошибкам и неправильной работе функционала. Регриссионное тестирование позволит выявить такие проблемы и убедиться , что после переименования раздела все функции приложения работают корректно. Изменения могут повлиять на пользовательский интерфейс приложения. Возможно , кнопки и ссылки , связанные с разделом "Удаленные", теперь будут отображаться как кнопки и ссылки , связанные с разделом "Корзина". Регриссионное тестиование позволит убедиться, что новый интерфейс легко понятен и не вызывает проблему у пользователей.
  «СТРАНИЦА ВХОДА»
-  Регриссионное тестирование необходимо провести в случае , когда на "Странице входа" устранен обнаруженные дефект. Возможно после исправления данного дефекта , в приложении электронной почты произошли изменения, которые могут повлиять других функий и модулей сисмтемы. Регрессионное тестиование позволяет проверить , не появились ли новые дефекты или не возникли ли проблемы в других частях приложения.

3).
Необходимо провести Smoke тестирование , на начальном этапе( нового билда) и в первую очередь направленного на проверку готовности разработанного продукта к проведению более расширенного тестирования, определения общего состояния качества продукта.

4).
- Для обнаружения данного дефекта можно провести функциональное тестироание. Функциональное тестирование направлено на проверку соответствия функциональности системы заявленным требованиям и определению наличия дефекта. В данном случае мы можем протестировать работу кнопки "Удалить письмо" в разделе "Черновик" и проверить, выполняется ли функция удаления письма корректно. 
