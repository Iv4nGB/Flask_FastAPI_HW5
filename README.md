# Урок 5. Знакомство с FastAPI

Задание

Необходимо создать API для управления списком задач. Каждая задача должна содержать заголовок и описание. 
Для каждой задачи должна быть возможность указать статус (выполнена/не выполнена).

API должен содержать следующие конечные точки:

  1) GET /tasks — возвращает список всех задач.
  2) GET /tasks/{id} — возвращает задачу с указанным идентификатором.
  3) POST /tasks — добавляет новую задачу.
  4) PUT /tasks/{id} — обновляет задачу с указанным идентификатором.
  5) DELETE /tasks/{id} — удаляет задачу с указанным идентификатором.

Для каждой конечной точки необходимо проводить валидацию данных запроса и ответа. Для этого использовать библиотеку Pydantic.
