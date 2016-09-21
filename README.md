# Разгневанные головы

## Назначение

Проект призван помочь толковым соискателям выбирать хорошие места работы на основании *рейтинга работодателей*.

Рейтинг вычисляется на основании оценок, которые ставят сотрудники, в том числе и бывшие. Чтобы избежать спама,
мы собираем отзывы только тех людей, кто действительно работал в компании.

Мы проверяем этот факт с помощью [HeadHunter API](https://dev.hh.ru/). Для того, чтобы оставить отзыв, сотрудник
должен быть зарегистрирован на сайте [HeadHunter](https://hh.ru) и иметь заполненное резюме. Он может ставить
оценки только тем компаниям, в которых работал.

## Фан

Проект делается не для пользы, а для фана. [Клуб программистов города Москвы](http://www.meetup.com/progmsk/)
решил замутить webdev на Haskell.

## Инструкции

1. Клонируем проект к себе, например, в папку `angry-heads`.

2. Устанавливаем на свой компьютер [`stack`](https://docs.haskellstack.org/en/stable/README/), то есть
   *кросс-платформенный инструмент для разработки на Хаскелле*.

3. Читаем статью про [WAI](http://ruhaskell.org/posts/web/2015/09/01/wai-rpc.html) (рус.).

4. В папке `angry-heads` выполняем команды:

```    
stack setup
stack build
stack exec angry-heads
```

