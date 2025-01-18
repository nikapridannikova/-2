# ProjectManager

## Описание

Данный проект представляет собой систему управления задачами и проектами. Он включает два класса: `Task` и `Project`.

### Класс Task

- **Свойства**:
  - `title`: Название задачи.
  - `description`: Описание задачи.
  - `status`: Статус задачи (по умолчанию "Не выполнено").

- **Методы**:
  - Конструктор принимает название и описание задачи.
  - Деструктор выводит сообщение о том, что задача была удалена.
  - Магический метод `__call` обрабатывает вызовы несуществующих методов для установки и получения свойств.
  - Магический метод `__toString` возвращает строковое представление задачи.

### Класс Project

- **Свойства**:
  - `name`: Название проекта.
  - `tasks`: Массив задач в проекте.

- **Методы**:
  - Конструктор принимает название проекта.
  - Деструктор выводит сообщение о завершении проекта.
  - Метод `addTask` добавляет задачу в проект.
  - Магический метод `__toString` возвращает строковое представление проекта.

