# ahri

Курс лабораторных работ по дисциплине "Архитектуры систем искусственного интеллекта". Описание курса доступно на [github pages](https://manaslu8.github.io/ahri.github.io/).

## Local deployment

Для локального развертывания необходимы следующие компоненты:

```sh
node: v19.4.0
npm: 9.2.0
```

Перед развертыванием необходимо выгрузить все вспомогательные модули:

```sh
npm install
```

Также требуется выполнить дополнительные команды для конфигурации окружения:

```sh
export NODE_OPTIONS=--openssl-legacy-provider
```

Развертывание осуществляется следующей командой:

```sh
npm run docs:dev
```