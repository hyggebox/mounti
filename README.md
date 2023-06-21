# mounti

![HTML5](https://img.shields.io/badge/-HTML5-18191b?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS3-18191b?style=flat-square&logo=css3)
![CSS3](https://img.shields.io/badge/-SASS-18191b?style=flat-square&logo=sass)

Главная страница сервиса для туристов на HTML + SASS. Страница сделана на HTML + CSS с использованием препроцессора SASS.

Для страницы применена адаптивная верстка для различных размеров экрана — контрольные точки (брейкпоинты): 1200px, 1100px, 900px, 600px, 460px.

Посмотреть страницу > [hyggebox.github.io/mounti/](https://hyggebox.github.io/mounti/)

![mouti](https://github.com/hyggebox/mounti/assets/80201470/429fc6f7-f500-4a68-9296-424e531b3332)



## Запуск и установка 

Чтобы открыть страницу на локальной машине, необходимо:
- скачать файлы из репозитория
- в терминате перейти в папку с проектом и запустить на локальном сервере, например с помощью утилиты livereload: `livereload .`


## Формирование css-файла

- установите зависимости с помощью команды `npm install`
  
- Стили прописаны в `.scss` файлах в папке `sass/`. `.css` файл компилируется командой `node-sass sass/main.scss css/style.css`.
Также (вместо этого) финальный сжатый `.css` файл можно сформировать с помощью команды `npm run build:css` в терминале. 

- Для отслеживания изменений в процессе разработки используется команда `npm run start`

## Цели проекта
Проект написан в образовательных целях


