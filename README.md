# Moderation Tool
Тулза для модерирования сервером в Minecraft.

Главная страница представляет собой пустую страницу, откуда, открыв всплывающее меню, можно перейти в интересующий и доступный вам раздел.

![image](https://i.imgur.com/PKpt9wu.png)

![image](https://i.imgur.com/7fgQWz2.png)

Перейдем к разделам движка. 

# Профиль (аватарка, резервный пароль)

![image](https://i.imgur.com/aHnkQ3F.png)


Изменение вашего аватара на сайте

![image](https://i.imgur.com/sXfwfwe.png)


Изменение резервного пароля на сайте

![image](https://i.imgur.com/4pRullI.png)

Так как авторизация на мод.тулзу происходит от базы данных сервера авторизации, то, в случае, если сервер авторизации будет неиспраен, вход будет возможен только по запасному паролю. Запасной вход: https://moderation-tool.factionsmc.ru/app/auth/backup

# Модерация

Модерация разбивается на 2 подраздела:

1. Логи
2. История наказаний

Логи дают возможность посмотреть, что происходило на сервер за конкретный промежуток времени и от какого игрока.
Страница логов выглядит так:

![image](https://i.imgur.com/sjImlow.png)

Поиск логов доступен в 4 областях:
  1. Чат
  2. Команды
  3. Убийства
  4. Вход/Выход

![image](https://i.imgur.com/Tla7Wtb.png)


Выбираем интересующий нас раздел и вбиваем данные в поля. Обязательно к указанию: Дата, Время от, Время до.

![image](https://i.imgur.com/HcoFV0Q.png)


История наказаний: будет позже.

# Управление сервером

Управление сервером разбивается на 2 подраздела:

1. Сервер
2. Промокоды

На странице сервера выводится список игроков с указанием их IP адресов и с возможность применить перечень действий к игроку.
Также на странице сервера есть кнопка для пробуждения помощников в беседе ВКонтакте ))

![image](https://i.imgur.com/eeMosGv.png)

Доступный перечень действий:
  1. Просмотр истории накзаний игрока
  2. Отправка сообщения игроку в личку на сервере
  3. Кик игрока с сервера
  4. Блокировка чата игрока на сервере
  5. Разблокировка чата игрока на сервере
 
К примеру, отправка сообщения игроку в личку на сервере:

![image](https://i.imgur.com/fKcccy0.png)




Промокоды.

![image](https://i.imgur.com/Uxmyyb0.png)


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

Управление сайтом разбивается на 3 подраздела:

1. Пользователи
2. Хост изображений
3. Настройки

Но уделим внимание только 1 пункту.

Управление пользователями. На главной странице предлагается выбрать пользователя и по нажатию на кнопку "Редактировать" перейти к нему. К созданию пользователей вернемся чуть позже.

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

Так как авторизация на мод.тулзу происходит от базы данных сервера авторизации, то, в случае, если сервер авторизации будет неиспраен, вход будет возможен только по запасному паролю. Запасной вход: https://moderation-tool.factionsmc.ru/app/auth/backup


