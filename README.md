# photo-platform
Проект позволяющий публиковать фотографии, оценивать их. 
Будет возможность регистрироваться, публиковать фотограции, управлять профилем, оценивать фотограции дргуих пользователей и смотреть рейтинги.  
Проект будет разработан с применением архитектуры SOA, на первоначальном этапе планируются три сервиса: шлюз, сервис авторизации и основной сервис(монолит, который будет писаться по Мартину Фаулеру, с сохранением возможности разделения его на микро сервсисы. В ходе выполнения возможно будут добавляться новые сервисы. 
В качестве бд буду использовать postgres, в качестве системы messaging буду использовать kafka.  
Стек проекта: java 11, spring, kafka, postgres, html+javascript. Остановился на данном стеке, т.к. имею опыт программирования на языке java и опыт работы со spring-ом, вообщем то удобный фреймворк предоставляющий инструменты, как раз по моим потребностям, также он позволит настроить и авторизацию. Опыта с кафкой нет, есть опыт с раббитом, но хочется получить этот опыт.  
Для фронотов остановился пока на html+javascript, предполагая использовать какой-нибудь универсальный фреймворк. В случае если возникнут сложности преключусь на использование jsf или jsp.  
Сообщение между сервером и клиентом будут в формате json.  
Для обработки событий планирую применять AJAX подход.  
