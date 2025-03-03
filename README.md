# Проект MUI

Это проект на Next.js, который использует Material-UI (MUI) для создания пользовательских интерфейсов. Проект настроен с необходимыми зависимостями и скриптами для облегчения разработки, сборки и линтинга.

## Содержание

- [Установка](#установка)
- [Скрипты](#скрипты)
- [Зависимости](#зависимости)
- [Разработка](#разработка)

## Установка

Чтобы начать работу с этим проектом, клонируйте репозиторий и установите зависимости:
```bash
  git clone https://github.com/denizho/web_app_frontend.git
  cd mui
  npm install
```

## Скрипты

Этот проект включает несколько npm-скриптов для помощи в разработке:

- **dev**: Запускает сервер разработки.
```bash
  npm run dev
```
- **build**: Собирает приложение для продакшена.
```bash
  npm run build
```
- **start**: Запускает сервер в режиме продакшена.
```bash
  npm run start
```
- **lint**: Запускает линтер для проверки качества кода.
```bash
  npm run lint
```
## Зависимости

Этот проект использует следующие зависимости:

- @emotion/react: Библиотека для написания CSS-стилей с помощью JavaScript.
- @emotion/styled: Библиотека для создания стилизованных компонентов.
- @fontsource/roboto: Пакет для включения шрифта Roboto.
- @mui/material: Основная библиотека Material-UI для React.
- axios: HTTP-клиент на основе промисов для выполнения запросов.
- next: Фреймворк React для серверного рендеринга и генерации статических сайтов.
- react: Библиотека JavaScript для создания пользовательских интерфейсов.
- react-dom: Пакет, который служит точкой входа в DOM и рендереры сервера для React.

## Зависимости для разработки

- nodemon: Утилита, которая отслеживает изменения в вашем исходном коде и автоматически перезапускает сервер.

## Разработка

Чтобы начать разработку, выполните следующую команду для запуска сервера разработки:
```bash
  npm run dev
```
Затем вы можете открыть браузер и перейти по адресу [http://localhost:3000](http://localhost:3000), чтобы увидеть приложение в действии.

## Ссылка на Backend

[Перейти к Backend](https://github.com/denizho/web_app_backend)
