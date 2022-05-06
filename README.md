# Moderation Tool
Инструкция по использованию тулзы для модерирования сервером в Minecraft.

На главной странице отображается статистика по заработанным коинам и отработанным часам на сервере. В верхнем левом углу кликнув на иконку можно открыть вспывающее меню, где можно перейти в интересующий и доступный вам раздел.

![image](https://i.imgur.com/hKsexed.png)

![image](https://i.imgur.com/Q4f0X35.png)

Перейдем к разделам движка. 

# Профиль (аватарка, резервный пароль)

![image](https://i.imgur.com/aHnkQ3F.png)


Изменение вашего аватара на сайте

![image](https://i.imgur.com/sXfwfwe.png)


Изменение резервного пароля на сайте

![image](https://i.imgur.com/4pRullI.png)

Так как авторизация на мод.тулзу происходит от базы данных сервера авторизации, то, в случае, если сервер авторизации будет неиспраен, вход будет возможен только по запасному паролю. Запасной вход: https://moderation-tool.forcezone.ru/app/auth/backup

# Модерация

Модерация разбивается на 4 подраздела:

1. Логи
2. Сервер
3. Рабочие аккаунты
4. История наказаний

**Логи** дают возможность посмотреть, что происходило на сервере за конкретный промежуток времени и от какого игрока.
Страница логов выглядит так:

![image](https://i.imgur.com/sjImlow.png)

Поиск логов доступен в 4 областях:
  1. Чат
  2. Команды
  3. Убийства
  4. Вход/Выход

![image](https://i.imgur.com/Tla7Wtb.png)


Выбираем интересующий нас раздел и вбиваем данные в поля. Обязательно к указанию: Дата, Время от, Время до. После нажатия кнопки выпадает таблица, в которой будет вся интересующая вас информация. Также, нажав на ник, вы попадете на страницу истории наказаний этого игрока.

![image](https://i.imgur.com/HcoFV0Q.png)




**Сервер.** На странице сервера выводится список игроков с указанием их IP адресов и с возможность применить перечень действий к игроку.
Также на странице сервера есть кнопка для пробуждения помощников в беседе ВКонтакте ))

![image](https://i.imgur.com/eeMosGv.png)

Доступный перечень действий:
  1. Просмотр истории накзаний игрока
  2. Отправка сообщения игроку в личку на сервере
  3. Кик игрока с сервера
  4. Блокировка чата игрока на сервере
  5. Разблокировка чата игрока на сервере
 
К примеру, отправка сообщения игроку в личку на сервере:

![image](https://i.imgur.com/SFkA782.png)

![image](https://i.imgur.com/iI4AN3q.png)

**Рабочие аккаунты.** В этом разделе вы видите список ваших рабочих аккаунтов, которые к вам привязаны. В таблице отображен ник аккаунта, ваш ник (ник владельца), группа аккаунта и активность аккаунта (активен или заблокирован/не активен)

![image](https://i.imgur.com/RkfrtyR.png)

Перейдя на страницу аккаунта у нас появляется инфорамция об аккаунте: ник и пароль. Пароль на экране скрыт в целях безопасности, но его можно скопировать.

![image](https://i.imgur.com/IDujI7Y.png)

При попытке перейти не на свой аккаунт или на заблокированный/не актированный аккаунт выпадает типичная страница *403 Forbidden*

![image](https://i.imgur.com/ZlGNJ5J.png)


**История наказаний**. Сайт истории наказаний, где вы можете посмотреть информацию о любом выданном наказании на сервере.

![image](https://i.imgur.com/6IAyv5L.png)

![image](https://i.imgur.com/2QQFzE1.png)

![image](https://i.imgur.com/1p7pHYX.png)

![image](https://i.imgur.com/E31oq18.png)

# Адмнинистрирование

Администрирование разбивается на 5 подразделов:

1. Пользователи
2. Коины
3. ONLINE-таблица
4. Рабочие аккаунты
5. Промокоды


**Управление пользователями.** На главной странице предлагается выбрать пользователя и по нажатию на кнопку "Редактировать" перейти к нему. К созданию пользователей вернемся чуть позже.

![image](https://i.imgur.com/uMAZWkX.png)

![image](https://i.imgur.com/BTSXNVV.png)

Рядом с ником пользователя выводится и его соответствующая роль. 

![image](https://i.imgur.com/T4N8pLP.png)

Здесь мы можем изменить запасной пароль пользователя, а также поменять роль, удалить пользователя.

![image](https://i.imgur.com/c5reyE2.png)


Но если обратить внимание на правый блок страницы, то можно заметить еще кое-что. Отдельные права пользователя.

![image](https://i.imgur.com/15T6m3c.png)


Для пользователя можно устанавливать отдельные права, независимо от роли. Администратор, который занимается управлением пользователем, может выдавать пользователю только те права, которые есть и у самого администратора.

![image](https://i.imgur.com/uvKsOyq.png)

Серые чекбоксы говорят о том, что у человека уже есть это право от его роли и выдать это право отдельно не получится. 
Синие - о том, что у человека это право установлено отдельно.
Белые - у него вообще нет права на это действие.

Вернемся к созданию пользователя и затронем здесь запасной пароль.

![image](https://i.imgur.com/Bn5lMQD.png)

Для того, чтобы создать пользователя, нужно указать ник помощника, запасной пароль, который будет установлен и роль.

Так как авторизация на мод.тулзу происходит от базы данных сервера авторизации, то, в случае, если сервер авторизации будет неиспраен, вход будет возможен только по запасному паролю. Запасной вход: https://moderation-tool.forcezone.ru/app/auth/backup



**Коины**. В данном разделе идет управление внутренней валютой помощников. За нее в будущем планируется сделать магазин, где помощники смогут накопленные коины на что-то обменять.

![image](https://i.imgur.com/6FaUyNw.png)

![image](https://i.imgur.com/GZE1JL4.png)

**Онлайн-таблица**. В этом разделе можно отследить количество наигранного времени на сервере помощниками. Можно как за текущую неделю, так и за любую другую. В настройках движка устанавливается первая неделя отсчета.

![image](https://i.imgur.com/95DIPkP.png)

![image](https://i.imgur.com/m0SfwRf.png)

**Рабочие аккаунты**. Отсюда происходит управление рабочими аккаунтами помощниками.

![image](https://i.imgur.com/AWqHDU0.png)

На странице аккаунта можно посмотреть информацию о дате и IP последней авторизации. Доступны следующие действия:

1. Смена ответственного
2. Смена пароля
3. Блокировка/разблокировка аккаунта

![image](https://i.imgur.com/MSSQYZc.png)

Нажав на *Сменить ответственного* выпадает список пользователей, которым можно передать доступ к аккаунту. После выбора прошлый пользователь теряет доступ к аккаунту, а выбранный наоборот приобретает. В момент смены ответственного пользователя от аккаунта автоматически сменяется пароль.

![image](https://i.imgur.com/E01t8DQ.png)

Нажав на *Сменить пароль* выпадает панелька, в которой вы можете либо подтвердить действие, либо отменить. После смены пароля, текущий пользователь, привязанный к аккаунту, может сразу же его узнать. Пароль генерируется рандомным методом. Администраторы, сменившие пароль, не узнают этот пароль.

![image](https://i.imgur.com/4tdE8HE.png)

Нажав на *Заблокировать/Разблокировать аккаунт* выпдает панелька, предлагающие либо заблокировать, либо соответственно разблокировкать рабочий аккаунт. В момент блокировки пароль от рабочего аккаунта меняется и также применяется блокировка аккаунта в некоторых местах. В таблице рабочих аккаунтов появляется отметка о блокировке аккаунта как у администратора, так и у пользователя, привязанного к аккаунту.

![image](https://i.imgur.com/nRCDIRi.png)

![image](https://i.imgur.com/CYm7ztx.png)

![image](https://i.imgur.com/y1eOftE.png)

![image](https://i.imgur.com/q13dy39.png)

**Промокоды.**

![image](https://i.imgur.com/8NBu2n2.png)


Промокоды можно разыгрывать между игроками, прятать и всякое такое. Активировать промокод на сервере можно командой /promo <промокод>.
На странице промокодов можно:
  1. Создавать промокоды 
  2. Редактировать промокоды
  3. Удалять промокоды
 
Редактировать можно только неактивированные промокоды.
Все действия, описанные о промокодах могут выполнять только администраторы, имеющие полные права на сервере.

Создание промокодов:

![image](https://user-images.githubusercontent.com/34684142/139945366-5a16d870-be2d-4b10-bda9-ad6badbadd9b.png)

В первом поле вводится команда, которая будет выполняться на сервере. Если мы хотим указать в аргументе ник игрока, который активировал промокод, используем переменную %player%. Вводим срок действия промокода и нажимаем кнопку "Создать".
Получившийся промокод будет в правом верхнем углу, как уведомление. Его можно будет скопировать.

![image](https://i.imgur.com/zalehnG.png)


Активация промокода на сервере:

![image](https://i.imgur.com/6z9HjzA.png)

Если промокод уже был активирован или срок активации истёк:

![image](https://i.imgur.com/J6eHnKU.png)


# Управление сайтом

Управление сайтом разбивается на 2 подраздела:

1. Хост изображений
2. Настройки
