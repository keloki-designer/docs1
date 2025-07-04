Для работы с OData достаточно установить флажок «Публиковать стандартный интерфейс OData» при публикации конфигурации на web-сервер. Если в конфигурации установлен режим совместимости 8.3.4 или ниже, то возможна публикация только всех метаданных сразу.

Доступ к данным осуществляется соответственно роли пользователя, т.е. если пользователь под которым вы авторизуетесь не имеет доступ к документам РКО, то при запросе метаданных вы увидите описание, но при запросе документов ничего не получите.

Если же у вас в конфигурации отключен режим совместимости, то вы можете воспользоваться методом УстановитьСоставСтандартногоИнтерфейсаOData, который позволяет установить список публикуемых объектов.  
Данная обработка реализует простой интерфейс для этого метода.  
![](https://samarasoft.com/wp-content/uploads/2017/11/%D0%A0%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5OData.png)

Скачать файл обработки можно по этой [ссылке](http://ftp.samarasoft.ru/_Connector/%D0%A0%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%D0%A1%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B0%D0%A1%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D0%BE%D0%B3%D0%BE%D0%98%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81%D0%B0OData.epf):

Для загрузки файла обработки перейдите в пункт меню [Файл] — [Открыть] (!не в конфигураторе).

Выбрать все данные и выбрать [Сохранить].

![](https://samarasoft.com/wp-content/uploads/2017/11/12.png)

![](https://samarasoft.com/wp-content/uploads/2017/11/123.png)

Состав данных можно отредактировать и через интерфейс тонкого клиента.![](https://samarasoft.com/wp-content/uploads/2017/11/Odata.png)

![](https://samarasoft.com/wp-content/uploads/2017/11/Odata2-1024x719.png)