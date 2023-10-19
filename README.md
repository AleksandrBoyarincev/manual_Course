# manual_Course# Вопросы для собеседования по тестированию веб-API

## 1. Что такое API?

  API расшифровывается как "Application Programming Interface" (интерфейс программирования приложений). Это набор правил и протоколов, которые позволяют разным программным компонентам взаимодействовать друг с другом. API определяет способы и форматы обмена информацией между различными программами или сервисами, обеспечивая возможность эффективного использования функциональности других приложений.

## 2. Что такое тестирование API?

Тестирование API (Application Programming Interface) - это процесс проверки и оценки функциональности, надежности, безопасности и производительности программного интерфейса, который позволяет взаимодействовать между различными программами или сервисами.

## 3.Назовите некоторые распространенные протоколы, используемые при тестировании API?

HTTP (Hypertext Transfer Protocol): Это основной протокол для передачи данных веб-серверами и клиентами. Он широко используется для API, работающих через REST и SOAP.

HTTPS (Hypertext Transfer Protocol Secure): Это защищенная версия протокола HTTP, которая обеспечивает шифрование данных для безопасной передачи.

REST (Representational State Transfer): Архитектурный стиль, который использует протокол HTTP для передачи данных между клиентами и серверами. API, работающие по стилю REST, называют RESTful API.

SOAP (Simple Object Access Protocol): Протокол, который обеспечивает структурированное взаимодействие между клиентом и сервером, используя XML для обмена сообщениями.


## 4.Каковы преимущества тестирования API?

Преимущества тестирования API включают:
Быструю обратную связь о качестве кода;
Обеспечение надежной интеграции между компонентами системы;
Раннее обнаружение ошибок и уязвимостей
Снижение стоимости исправления ошибок.


## 5. Что именно нужно проверить в API Testing?

Функциональность: Проверка, что API выполняет свои функции согласно спецификациям и ожидаемому поведению. Необходимо протестировать различные методы и операции, которые предоставляет API.

Валидация данных: Убедиться, что возвращаемые API данные соответствуют ожидаемому формату и структуре, а также что API корректно обрабатывает неверные или недопустимые данные.

Аутентификация и авторизация: Проверить, что API правильно обрабатывает процессы аутентификации пользователей и авторизации доступа к различным ресурсам.

Обработка ошибок: Убедиться, что API предоставляет адекватные и информативные сообщения об ошибках, когда что-то идет не так.

Сценарии с различными нагрузками: Протестировать API под различными уровнями нагрузки, чтобы оценить его производительность и устойчивость.

Совместимость: Убедиться, что API хорошо интегрируется с другими системами и соблюдает стандарты и спецификации.

Безопасность: Проверить уровень защиты API от несанкционированного доступа, атак и других угроз безопасности.

Документация: Проверить, что документация API ясна, полна и актуальна, чтобы разработчики могли легко использовать интерфейс.

Интеграционное тестирование: Тестирование взаимодействия между различными компонентами системы через API.

## 6.Назовите некоторые инструменты, используемые для тестирования API?

Postman: Postman - это один из самых популярных инструментов для тестирования API. Он предоставляет графический интерфейс, который позволяет создавать, отправлять, отлаживать и автоматизировать тесты для API.
Insomnia: Insomnia - это еще один мощный инструмент для тестирования API с поддержкой REST, GraphQL и других протоколов. Он предоставляет удобный интерфейс для работы с запросами и ответами API.
Swagger (или OpenAPI): Swagger - это инструмент для создания и документирования API, а также для автоматической генерации клиентского кода и тестовых сценариев.
SoapUI: SoapUI - это инструмент, который специализируется на тестировании SOAP и RESTful веб-сервисов.
Newman: Newman - это командная строковая утилита для выполнения коллекций тестов Postman из командной строки, что упрощает их автоматизацию.


## 7. Назовите несколько популярных примеров API.

Facebook Graph API: Этот API предоставляет доступ к данным и функциональности Facebook, позволяя разработчикам интегрировать функции Facebook в свои приложения, такие как получение информации о пользователях, их друзьях, постах и многое другое.

Twitter API: Twitter API предоставляет доступ к данным и функциональности Twitter, позволяя разработчикам получать твиты, профили пользователей, тенденции и многое другое.

Google Maps API: Этот API позволяет разработчикам интегрировать карты Google в свои приложения и получать информацию о местоположении, маршрутах, геокодировании и других географических данных.

GitHub API: GitHub API предоставляет доступ к данным и функциональности GitHub, позволяя разработчикам взаимодействовать с репозиториями, коммитами, запросами на слияние и многими другими функциями платформы GitHub.


YouTube API: Этот API предоставляет доступ к данным и функциональности YouTube, позволяя разработчикам взаимодействовать с видео, каналами, комментариями и другими элементами YouTube.


## 8.Какие основные проблемы возникают при тестировании API?

Недоступность API: API может быть временно недоступным или отвечать с ошибками, что затрудняет его тестирование и может повлиять на работу приложений, использующих его.

Некорректные данные: Некорректные входные данные или неправильная обработка данных API может привести к некорректным результатам и ошибкам в работе системы.

Неправильное форматирование ответов: Некорректное форматирование ответов API может затруднить парсинг данных и использование API клиентами.

Несоответствие документации: Если документация API не соответствует его реальной функциональности, разработчики могут столкнуться с неожиданными проблемами при использовании API.

Низкая производительность: Некорректная оптимизация или неэффективное использование ресурсов может привести к низкой производительности API при больших нагрузках.

Проблемы с авторизацией и аутентификацией: Некорректная реализация механизмов аутентификации и авторизации может создать риски для безопасности и привести к возможности несанкционированного доступа.


## 9. Назовите некоторые наиболее часто используемые методы HTTP?

GET: Метод GET используется для получения данных с сервера. Клиент отправляет запрос на сервер для получения информации и сервер возвращает запрошенные данные в ответ.

POST: Метод POST используется для отправки данных на сервер для обработки. Клиент отправляет запрос с данными на сервер, который обрабатывает эти данные и может создавать новые ресурсы.

PUT: Метод PUT используется для обновления существующего ресурса на сервере. Клиент отправляет запрос с обновленными данными, и сервер обновляет ресурс в соответствии с этими данными.

DELETE: Метод DELETE используется для удаления ресурса с сервера. Клиент отправляет запрос на удаление определенного ресурса, и сервер удаляет его, если ресурс существует.


## 10. Можно ли использовать запрос GET вместо PUT для создания ресурса?

Нет, запрос GET предназначен для получения информации о ресурсе без изменения его состояния, тогда как PUT используется для создания или обновления ресурса. Использование GET для создания ресурса может привести к неправильной обработке запроса и нарушению принципов RESTful архитектуры.


## 11. В чем разница между методами PUT и POST?

Метод PUT используется для обновления существующего ресурса на сервере или для создания нового ресурса с определенным идентификатором. Если ресурс с указанным идентификатором уже существует, то он будет обновлен данными из запроса. Если ресурса с таким идентификатором нет, он будет создан.

Метод POST используется для создания нового ресурса на сервере. Когда клиент отправляет запрос с методом POST, сервер создает новый ресурс с уникальным идентификатором и сохраняет предоставленные данные.
Метод PUT является идемпотентным. Метод POST не является идемпотентным, что означает, что множественные запросы POST к одному ресурсу могут создавать дубликаты ресурсов или иметь другие побочные эффекты.


## 12. Перечислите ключевые элементы HTTP-запроса?

Метод: Это указывает тип операции, которую клиент хочет выполнить на сервере. 

URI (Uniform Resource Identifier): Это путь к ресурсу на сервере, с которым клиент хочет взаимодействовать. 

Заголовки (Headers): Заголовки содержат метаинформацию о запросе, такую как тип контента, язык, аутентификационные данные, куки, кэширование, пользовательские данные и другие параметры.

Тело запроса (Request Body): Некоторые HTTP-методы, такие как POST и PUT, могут содержать данные, которые клиент отправляет на сервер. Тело запроса содержит эти данные, как правило, в формате JSON, XML или форм-данных.

Параметры запроса (Query Parameters): Это дополнительные данные, которые можно передать с запросом через URL в виде параметров. Они часто используются для фильтрации, поиска или передачи дополнительных параметров запроса.

Версия протокола: Указывает версию HTTP-протокола, который используется для запроса. 

## 13. Хорошо. А какие бывают ключевые элементы HTTP-ответа?

Статус-код (Status Code): Статус-код - это трехзначный числовой код, который указывает на результат выполнения запроса. Он предоставляет информацию о том, успешно ли выполнен запрос или возникли какие-либо ошибки. 

Заголовки ответа (Response Headers): Заголовки ответа содержат метаинформацию о ответе, такую как тип контента, дата истечения срока действия, кэширование, кодировка и другие параметры.

Тело ответа (Response Body): Тело ответа содержит данные, возвращенные сервером в ответ на запрос. Ответ может содержать данные в различных форматах, таких как JSON, XML, HTML, текст и другие.

Куки (Cookies): Куки - это данные, которые сервер отправляет в браузер клиента для хранения на стороне клиента. Куки могут использоваться для отслеживания состояния сеанса или хранения пользовательских предпочтений.

Кэширование (Caching): Элементы ответа также могут содержать информацию о кэшировании, что позволяет клиентам или прокси-серверам сохранять ответы и использовать их для будущих запросов.

Редиректы (Redirects): Если запрос был перенаправлен на другой ресурс, ответ может содержать информацию о редиректе, чтобы клиент знал, куда перейти для получения данных.

Версия протокола: Указывает версию HTTP-протокола, которая использовалась для ответа. 


## 14. Что такое «окружение» (environment) в Postman?
Окружение в Postman - это набор переменных, которые могут быть использованы в различных запросах API и скриптах тестирования. Окружение позволяет хранить и управлять информацией, которая может изменяться в зависимости от среды, в которой выполняются запросы (например, разработка, тестирование, продакшн).


## 15.Что такое коллекция? (Postman Collection)

Коллекция в Postman - это группа запросов, которые объединены для упрощения организации и совместного использования. Коллекции позволяют сохранять и структурировать запросы, связанные с определенным проектом или функциональностью, а также делиться ими с другими участниками команды. Коллекции также могут содержать предустановленные тесты и скрипты для автоматизации процесса тестирования API.


## 16. Где передаются параметры в GET-запросе?

Параметры в GET-запросе передаются непосредственно в URL-адресе (Uniform Resource Locator). Они добавляются после вопросительного знака ("?") и разделяются символом амперсанда ("&"). Параметры состоят из ключей и значений, и каждый параметр имеет следующий формат: ключ=значение.

## 17. Какой будет код ответа HTTP на POST-запрос с некорректными параметрами?

Код состояния 400 Bad Request: Этот код указывает, что сервер не может обработать запрос из-за некорректного синтаксиса или неверных параметров запроса. Код 400 Bad Request часто используется, когда клиент отправляет запрос с неправильными или отсутствующими параметрами.

Код состояния 404 Not Found: Код 404 Not Found указывает, что запрашиваемый ресурс не найден на сервере. Если некорректные параметры указывают на несуществующий ресурс, сервер может вернуть код 404.

## 18. Чем отличается HTTP от HTTPS?

HTTP передает данные в открытом текстовом формате, что делает их уязвимыми для перехвата и прослушивания злоумышленниками.

HTTPS предоставляет безопасное соединение с помощью шифрования данных, используя SSL (Secure Socket Layer) или его современный эквивалент TLS (Transport Layer Security). Это позволяет защитить данные от несанкционированного доступа и прослушивания. HTTPS также предоставляет аутентификацию сервера, что позволяет клиентам проверить, что они подключены к правильному серверу, а не к злоумышленнику.

## 19. Из чего состоит HTTP запрос?

См. Перечислите ключевые элементы HTTP-запроса

## 20. А на каком языке программирования пишутся тесты в Postman?

Тесты в Postman пишутся на языке JavaScript. Postman предоставляет возможность написания автоматизированных тестов для проверки ответов от API (Application Programming Interface). JavaScript используется в Postman для создания тестовых сценариев и проверки данных, возвращаемых сервером после отправки запросов.

## 21. Какие вы знаете  HTTP запросы?

GET: Используется для получения данных с сервера. Запросы GET должны быть идемпотентными, что означает, что они не должны менять состояние сервера. GET-запросы обычно используются для чтения данных, таких как получение информации о продукте, статье или других ресурсах. 


POST: Используется для отправки данных на сервер для обработки. POST-запросы могут изменять состояние сервера и часто используются для создания новых ресурсов на сервере. Не является идемпотентным.


PUT: Используется для замены существующих данных на сервере новыми данными. PUT-запросы обновляют или создают ресурс с указанным идентификатором. Является идемпотентным.


DELETE: Используется для удаления данных с сервера. DELETE-запросы удаляют ресурс с указанным идентификатором. Является идемпотентным.

HEAD: Похож на GET-запрос, но возвращает только заголовки ответа без тела ответа. Он используется для получения метаинформации о ресурсе, такой как размер файла или тип содержимого, без необходимости загружать всё содержимое. Является идемпотентным.


PATCH: Используется для частичного обновления ресурса на сервере. Похож на PUT, но обновляет только те поля, которые были указаны в запросе. Является идемпотентным.



## 22. Что такое Rest API?

REST API (Representational State Transfer API) - это стиль архитектуры веб-сервисов, который определяет набор ограничений и рекомендаций для создания и организации взаимодействия между клиентами и серверами. REST API использует протокол HTTP для передачи данных и поддерживает различные методы запросов (GET, POST, PUT, DELETE) для выполнения операций с ресурсами.

Основные принципы REST API:


Ресурсы (Resources): Ресурсы представляют собой сущности или объекты, с которыми взаимодействуют клиенты. Каждый ресурс имеет уникальный идентификатор (URI), по которому можно получить доступ к нему.


Единый интерфейс (Uniform Interface): REST API определяет единый и простой интерфейс для взаимодействия с ресурсами. Это включает использование методов HTTP для выполнения различных операций с ресурсами и правильное использование статусных кодов HTTP для обозначения состояния операций.


Сервер не хранит информацию о клиенте (Stateless): Каждый запрос к REST API должен содержать всю необходимую информацию для его обработки. Сервер не должен хранить информацию о состоянии клиента между запросами. Это делает REST API более масштабируемым и уменьшает нагрузку на сервер.


Клиент и сервер независимы друг от друга: REST API следует принципу разделения ответственности между клиентами и серверами. Клиенты отвечают за пользовательский интерфейс и взаимодействие с пользователем, а серверы обеспечивают обработку запросов и хранение данных.


Кеширование (Caching): REST API поддерживает возможность кеширования данных для улучшения производительности и снижения нагрузки на сервер.


## 23.Чем отличается  Rest от SOAP?

REST (Representational State Transfer) и SOAP (Simple Object Access Protocol) - это два различных подхода к созданию веб-сервисов и обмену данными между клиентами и серверами. Они имеют различные характеристики и принципы работы:

Архитектурный стиль: REST - это стиль архитектуры веб-сервисов, который опирается на протокол HTTP и использует его методы (GET, POST, PUT, DELETE) для взаимодействия с ресурсами. SOAP использует протоколы, такие как HTTP, SMTP, TCP и другие, для обмена сообщениями.


Формат данных: Обычно использует форматы данных, такие как JSON или XML, для передачи данных между клиентом и сервером. 
SOAP использует XML для формата сообщений и описания веб-сервисов с помощью WSDL (Web Services Description Language).


Унифицированный интерфейс: REST API предоставляет единый интерфейс для взаимодействия с ресурсами, используя стандартные методы HTTP. SOAP предоставляет гарантии доставки сообщений и контроль за надежностью, что делает его более надежным, но также более сложным.


Состояние: REST API является без состояния (stateless), что означает, что каждый запрос содержит всю необходимую информацию, и сервер не хранит информацию о состоянии клиента между запросами. SOAP может быть без состояния или состояние включено, в зависимости от спецификации и реализации.


Простота и легковесность: REST API обычно более простой и легковесный в реализации, что облегчает его использование и понимание. SOAP-сообщения могут быть гораздо более сложными и тяжеловесными из-за использования XML, что делает его менее простым в использовании и отладке.


Масштабируемость: REST API обычно масштабируется лучше, так как его без состояния уменьшает нагрузку на сервер. SOAP обладает богатыми возможностями расширения и поддерживает различные протоколы и стандарты.


## 24. Что такое JSON/XML?

JSON (JavaScript Object Notation) - это легкий формат обмена данными, основанный на тексте и легко читаемый человеком. JSON используется для представления структурированных данных и является популярным форматом для обмена данными в REST API.

XML (eXtensible Markup Language), который является языком разметки для представления структурированных данных. XML также может использоваться в REST API и является основой для протокола SOAP.



## 25.  Что такое HTML?

HTML (HyperText Markup Language) - это стандартный язык разметки для создания веб-страниц и веб-приложений. HTML используется для структурирования и представления контента на веб-страницах с помощью различных тегов, атрибутов и элементов. HTML является одним из основных компонентов веб-технологий, наряду с CSS (Cascading Style Sheets) для стилизации и JavaScript для интерактивности.



