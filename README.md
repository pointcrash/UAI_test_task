**Тестовое задание для Университета искусственного интеллекта**  
  
urls для работы апи:  
Запрос:  
 - api/v1/tasks/ GET  
Ответ:  
[
    {
        "id": 1,
        "title": "task1",
        "is_completed": true
    },
    {
        "id": 2,
        "title": "task1",
        "is_completed": true
    }
]

Запрос:
 - api/v1/tasks/ POST
тело:
{
    "title": "Test task 1",
    "is_completed": true   # Опционально
}

Ответ:
{
    "id": 12,
    "title": "Test task 1",
    "is_completed": true
}
