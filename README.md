# [kanye.rest](https://kanye.rest)

Аналог сервиса Kanye.rest, написанный на Express.
Используется в уроке по докеризации веб-приложения на курсе "Веб-разработчик плюс" Яндекс.Практикум.

Докеризированная версия приложения доступна в ветке [feature/dockerize](https://github.com/yandex-praktikum/kanye.rest/tree/feature/dockerize)

## Примеры использования API

### How to start after clone

```code
1- docker build . -t kanye-rest-docker
2- docker run -p 8081:3000 -d kanye-rest-docker
```

### `GET` [https://localhost:3000](https://localhost:3000)

```json
{
  "quote": "I feel like I'm too busy writing history to read it."
}
```

или

### `GET` [https://localhost:3000/text](https://localhost:3000/text)

```text
The world is our office
```

## Лицензия

MIT
