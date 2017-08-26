# Общая информация:

## Для работы вам понадобится `консоль`

На `Mac` вы можете пользоваться встроенным терминалом, а на `Windows` рекомендую установить программу [cmder](http://cmder.net/)

## Node.js
Перед началом работы установите node.js последней версии с [официального сайта](https://nodejs.org/en/) 

После установки вы можете проверить версию node.js в консоли с помощью команды 
```bash
node -v
```
Также проверьте версию npm 
```bash
npm -v
```

## Grunt
Затем глобально установите Grunt через консоль с помощью команды 

```bash
npm install -g grunt
```
## Переход в папку
Перейдите в папку проекта в консоли с помощью команды 
```bash
cd путь_до_папки
```



# SVG-спрайты

Для запуска сборки нужно поставить необходимые пакеты. Из папки проекта запустить:

```bash
npm i
```

Для сборки спрайта, запуска демки и автообновления:

```bash
grunt
```



## Что где

`/img/sprite_svg/` —  папка для мелких файлов, из которых собирается спрайт.

`/img/sprite.svg` — собираемый спрайт.



## Прочее

Требуется [nodeJS](https://nodejs.org/en/).

Если ранее не работали с консолью, [вот статья](http://nicothin.ru/page/console-windows) для  пользователей windows.
