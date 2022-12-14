
# Программа «Фильм на вечер»

Программа на RUBY, демонстрация работы с файлами и сетью.

## Описание работы программы:

Программа рекомендует к просмотру один из фильмов любимого режиссёра. Список фильмов состоит из ТОП 250 лучших по версии [IMDB](https://ru.wikipedia.org/wiki/250_лучших_фильмов_по_версии_IMDb)
При отсутствии интернета, либо недоступности `URL` программа порекомендует фильм из своей собственной коллекции, которая расположена в папке `data` в файлах `txt`.

Установите `Bundler`:

```
gem install bundler
```

Склонируйте репозиторий:

```
git clone https://github.com/goodquietly/film_for_the_evening.git
````

Находясь в папке с игрой `cd film_for_the_evening`, установите библиотеки:

```
bundle install
```

Запустите программу:

```
bundle exec ruby main.rb
```


## Изменение набора фильмов в локальной коллекции:

*Добавление или удаление фильмов производится путем изменения набора файлов `txt` в папке `data` с аналогичным содержимым:*

```
Зеленая миля
Фрэнк Дарабонт
1999
```

