Написано REST API бэкенд со следующим функционалом:
	Сохранение в БД Новостей и их Типов.
Новость  имеет структуру:
•	Имя;
•	Краткое описание;
•	Полное описание;
•	Тип новости;
Тип новостей  имеет структуру:
•	Имя типа;
•	Цвет типа;
	 функционал
•	CRUD (Create, Read, Update, Delete) типов новостей;
•	CRUD новостей;
•	Возможность получить список всех новостей (имя, краткое описание, тип новости – имя типа, цвет типа);
•	Возможность получить список новостей определенного типа;
•	Возможность получить список всех типов новостей.
Для написания программы использован Spring boot framework.
Для работы с БД использована спецификация spring-data-jpa. 
Реализована с помощью Hibernate.

A REST API backend has been written with the following functionality:  Saving News and their Types in the database. The news has the following structure: • Name; • Short description; • Full description; • Type of news; A news type has the following structure: • Type name; • Color type;  functionality • CRUD (Create, Read, Update, Delete) news types; • CRUD news; • Ability to get a list of all news (name, brief description, type of news - type name, type color); • Ability to get a list of news of a certain type; • Possibility to get a list of all types of news. The Spring boot framework was used to write the program. To work with the database, the spring-data-jpa specification is used. Implemented using Hibernate.
