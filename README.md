# react-default-template

<p>Универсальная сборка react с предустановленными в package.json пакетами:</p>

# Что выходит в сборку:
<ul>
  <li>Обработка файлов стилей - css, scss, sass</li>
  <li>Обработка изображений - jpg, jpeg, png, gif, svg</li>
  <li>Обработка шрифтов - woff2, woff, eot, ttf, otf</li>
  <li>Обработка html файлов</li>
  <li>Имена файлов при сборке формируются при помощи hash и являются уникальными при обновлении</li>
</ul>

# 4 варианта запуска сборки:
<ul>
  <li>start - сборка development билда с запуском сервера webpack-dev-server + hot reload</li>
  <li>dev - сборка development билда без запуска сервера</li>
  <li>build - сборка production билда</li>
  <li>clear - очистка папки dist</li>
</ul>

<p>Для работы с приложением:</p>

## Запуск production сборки:
### `npm run build`

- сборка и оптимизация приложения в папке dist для деплоя.

## Запуск dev-сборки с запуском сервера:
### `npm run start`

## Запуск dev-сборки без запуска сервера:
### `npm run build`

## Очистка папки dist:
### `npm run clear`
