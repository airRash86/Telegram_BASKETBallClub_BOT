# ☑️Telegram Бот любительского Б.Больного клуба🏀 
Включает в себя мини комплекс из двух ботов: 

### 📡Главный бот:  
-Найти работающую в продакшне версию бота по ТГ поиску: @Dorogomil-BASKET_BOT\
-Через адресную строку: https://t.me/rash_test_bot \
-GITHUB: https://github.com/airRash86/Telegram_B.BallClub_BOT/blob/main/TG_BOT.py  
Мне (до недавнего времени тренеру по баскетболу) пришла в голову мысль:  автоматизировать информирование занимающихся в моем клубе ребят, в случае появления каких-то ивентов (например турнир или отмена тренировки или иное). К такому выводу я пришел, т.к. понял, что, по моим наблюдением, Телеграм стал популярнее ВК и, если у кого-то из моих занимающихся есть ТГ  и он зареган в данном боте, то, скорее всего, инфо о событиях в басетбольном клубе он не пропустит.  
После установления связи с ботом юзеру предлагается пройти регистрацию;   после завершения регистрации мне, как админу, приходит уведомелние о том, что такой-то добавился в бот,  добавить ли его в число получающих рассылку? И также с сообщением мне прилетает возможность по клику перейти в его воцап (глянуть его аватар итд), т.е. через данную меру я, как админ, понимаю что за новый человек.  
Для новичков же в боте предусмотрена возмжность ознакомится с фотографиями спортивного зала и инфрастуктуры (мячи, душевая, раздевалки) и также написать в саппорт (а именно, опять же, - мне): по одному клику юзер может попасть из диалога с обсуждаемым ботом  на мою стр в ВК или в мой диалог в ТГ или в Воцап.  


### 📡Вспомогательный бот:  
-Найти работающую в продакшне версию бота по ТГ поиску: @your_BOT_FOR_BOT  
-Через адресную строку: https://t.me/your_BOT_FOR_BOT  
-GITHUB: https://github.com/airRash86/Telegram_B.BallClub_BOT/blob/main/QueryVK.py  
Функционал в том, чтобы по нажатию на команду /check (админом) запускалась логика проверки стены группы в ВК, которая 
является главным инфо ресурсом моего клуба Дорогомилово-БАСКЕТ (https://vk.com/its_my_basket).  
При наличии нового поста админ уведомляется об этом и ему предлагается дать разрешение произвести  рассылку-уведомление в адрес
прошедших регистрацию в главном боте посльзователей о пояление нового поста в ВК. Также в автоматическисформерованном сообщении от главного бота
в адрес юзеров-подписчиков имеется ссылка, перейдя по которой можно попасть на последний (самый "свежи") пост на стене в группе в ВК.


### 📸Ниже скрин структуры таблицы БД SQLITE, применяемой в данном проекте:
![Структура таблицы SQLITE3](https://user-images.githubusercontent.com/107410620/204576410-040c1267-49d4-4e36-8fa3-dfffdcd244a6.png)


