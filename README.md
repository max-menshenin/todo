Простое ToDo-приложение с REST API на Spring Boot и встроенным веб-интерфейсом на чистом HTML + JavaScript.
⚙️ Стек технологий

    Java 17+

    Spring Boot 3+

    Spring Web / Spring Data JPA

    H2 (встроенная база данных)

    Lombok

    HTML + Vanilla JS (в папке static/)

🚀 Как запустить

    Клонируй проект:

git clone https://github.com/твой-профиль/todo-app.git
cd todo-app

Убедись, что установлен JDK 17 (или выше)

Запусти проект:

./mvnw spring-boot:run

Перейди в браузере:

    http://localhost:8080/

📦 REST API
Метод	URL	Описание
GET	/todos	Получить список
POST	/todos	Добавить задачу
PUT	/todos/{id}	Обновить задачу
DELETE	/todos/{id}	Удалить задачу
