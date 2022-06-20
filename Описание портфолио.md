# DummyAPI
Здесь представлено описание тестирования **DummyAPI**

## Оглавление

## Описание проекта
Сайт https://dummyapi.io является сервис, для тестирования API. 

### POST

#### GET /post (Get List)
Возвращает список публикаций отсортированных по дате создания.
 - доступен  query params для вывода определенной страницы
 
 **Response body** 
 
 **list**
```
 {
data: Array(Model)
total: number(total items in DB)
page: number(current page)
limit: number(number of items on page)
}
```
___
### POST /pist/create (Create Post)
Создает новую публицакию от пользователя, возвращает информацию 
___
