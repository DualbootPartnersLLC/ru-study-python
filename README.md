# Python exercises

![Testing](https://github.com/DualbootPartnersLLC/ru-study-python/actions/workflows/main.yml/badge.svg?branch=feature/error-branch)

## Запуск проекта

```sh
docker-compose build
docker-compose run --rm python-course
```

## Запуск тестов

```sh
docker-compose run --rm python-course pytest
```

## Запуск линтеров

```sh
docker-compose run --rm python-course make check
```

## Задача

1. Сделать форк проекта к себе в аккаунт.

2. В дирректории exercises есть задачи.

  Нужно выбрать задачу, создать ветку и работать в ней.

  По умолчанию все тесты во всех задачах пропускаются. Чтобы начать работу, нужно удалить `pass_` из имени файла соответствующего теста.

  Далее для каждой из задач реализовать недостающие методы так, чтобы все тесты проходили. Дополнительную информацию можно найти в комментарии к тесту.

  Проверять можно запуская `docker-compose run --rm python-course coverage run -m pytest`

3. После того как все тесты проходят, нужно создать pull request в своем репозитори в `main` и отправить на ревью.