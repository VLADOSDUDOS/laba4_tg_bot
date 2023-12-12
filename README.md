# laba4_tg_bot
Мой телеграм-бот представляет из себя определённый фильтр, который применяется к сайту Market Dota2. Он способен найти самые дешёвые лоты всех тринадцати предметов, имеющих редкость Arcana, которые выставлены на продажу на этом сайте. Код бота состоит из трёх файлов:

В файле dota2market_bot.py находиться скелет телеграм-бота. Ниже представленны все элементы работы телеграм-бота:
![image](https://github.com/VLADOSDUDOS/laba4_tg_bot/assets/146865995/97475532-aaa8-43d8-af87-1ad7fcdcc5c7)
![image](https://github.com/VLADOSDUDOS/laba4_tg_bot/assets/146865995/3d4bdd12-f244-4b6b-bb33-c61519d1c3c1)
![image](https://github.com/VLADOSDUDOS/laba4_tg_bot/assets/146865995/7a877219-bf77-43fa-bbc3-0a916fa78224)
![image](https://github.com/VLADOSDUDOS/laba4_tg_bot/assets/146865995/1dbfd6bc-4395-4202-a949-7482b6bb7969)
В файле main.py происходит сортировка объектов, которые мы получаем по ссылке "https://market.dota2.net/ajax/price/Arcana/Обычная/all/{page}/56/0;500000/all/all?sd=asc".
В файле result.json записаны названия, цены, изображения объектов и ссылки на них.


