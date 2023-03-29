## Использование демо-версии продукта

### Сервер

### Клиент

- **Ссылка на веб-версию** - 

## Визуальное описание бизнес-процесса, сервисов, сущности БД 



## Схематическое описание архитектуры

1. Клиент (Фронтенд) отправляет запрос с параметрами.
2. Сервер (Бэкенд) получает запрос.
3. Бэкенд осуществляет запрос к базе данных. <br/>
    └── Таблица базы данных: VideoPath ↔ VideoID
4. База данных возвращает путь к видео.
5. Бэкенд получает видеофайл, используя путь.
6. Бэкенд декодирует и обрабатывает видео с учетом параметров запроса.
7. Бэкенд кодирует обработанное видео.
8. Бэкенд создает блок данных размером 2 МБ из закодированного видео.
9. Бэкенд отправляет блок данных размером 2 МБ на фронтенд.
10. Фронтенд получает и отображает видеофрагмент.

## Скриншоты сервиса
<img width="1706" alt="2" src="https://user-images.githubusercontent.com/111357634/228554358-174ab8d4-ec31-4c76-82a5-5f193a78c074.png">
<img width="1706" alt="3" src="https://user-images.githubusercontent.com/111357634/228554374-24992be8-4f91-454b-9614-e307172955c3.png">
<img width="1706" alt="4" src="https://user-images.githubusercontent.com/111357634/228554381-f0a6d59d-36ef-4f8d-8ce0-c9ce265e57b8.png">
<img width="1706" alt="5" src="https://user-images.githubusercontent.com/111357634/228554386-c4775e06-23e7-4e22-96c6-f899ebe6a9d3.png">
<img width="1706" alt="6" src="https://user-images.githubusercontent.com/111357634/228554391-8e7856a9-13c8-4956-befb-8c5b4f77f257.png">
<img width="1706" alt="7" src="https://user-images.githubusercontent.com/111357634/228554395-cbd38305-1da7-46a8-a468-8309e34e11f9.png">

## Предложения по масштабированию

