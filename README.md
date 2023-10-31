# Adwin
Test assignment for Adwin

Необходимо сделать дневник используя предоставленный макет. 
Записи должны храниться в базе данных. Для фронта можно использовать любой js и css фреймворк. Или не использовать 🤔
  [Макет](https://www.figma.com/file/Jl0fTIgR0oWVaVhLLbI5or/)
  Запись состоит из заголовка, даты(datetime) и текста.
  При добавлении записи - все поля обязательные
  Максимальный размер заголовка - 200 символов
  Максимальный размер текста - 2000 сиволов

Напишите простую инструкцию для запуска.

Опционально:
  Пагинация записей
  Сортировка записей
  Рабочая кнопка "Показать ещё"
  Серверная валидация при добавлении записи
    Заголовок не более 200 символов, не пустой
    Корректная дата
    Текст записи - не более 2000 симолов
  Rest api, формат ответа - json
    Получить список записей
      С сортировкой по дате
      С постраничной выборкой
    Получить одну запись по id
    Добавить новую запись
  Докеризировать проект , чтобы можно было использовать docker compose up для запуска.
  Любые другие фишки которые хочется показать 😁
