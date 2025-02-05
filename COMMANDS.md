# 🤖 Команды Telegram-бота Помощника 🤖

---

## 📜 Модерация (доступно администраторам группы Telegram)

### 🔇 Мут

**Описание:** Запрещает пользователю отправлять сообщения в чат на указанное время.

**Использование:** `мут [время] [причина]`

**Как указать цель (кого мутить):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `мут [время] [причина]`
*   **@username:** Напишите: `мут @username [время] [причина]`
*   **ID пользователя:** Напишите: `мут [user ID] [время] [причина]`

**Параметры:**

*   `[время]`:  Продолжительность мута.  Можно указывать в формате: `[число] минут`, `[число] мин`, `[число] час`, `[число] ч`, `[число] день`, `[число] д`.  Например: `1 минута`, `30 мин`, `6 часов`, `1 день`.
*   `[причина]`: (Необязательно) Причина мута.  Текст причины будет виден в сообщении о муте.

**Примеры:**

*   *Ответ на сообщение:* `мут 1 час`
*   `@username`: `мут @user_example 30 мин флуд`
*   `ID`: `мут 987654321 5 минут`
*   `мут @username 1 день нарушение правил`

### 🗣️ Размут

**Описание:** Снимает мут с пользователя, позволяя ему снова отправлять сообщения.

**Использование:** `размут`

**Как указать цель (кого размутить):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `размут`
*   **@username:** Напишите: `размут @username`
*   **ID пользователя:** Напишите: `размут [user ID]`

**Примеры:**

*   *Ответ на сообщение:* `размут`
*   `@username`: `размут @user_example`
*   `ID`: `размут 987654321`

### 🔨 Бан

**Описание:** Полностью блокирует пользователя в группе. Забаненый пользователь не может вернуться в группу, пока его не разбанят.

**Использование:** `бан [причина]`

**Как указать цель (кого банить):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `бан [причина]`
*   **@username:** Напишите: `бан @username [причина]`
*   **ID пользователя:** Напишите: `бан [user ID] [причина]`

**Параметры:**

*   `[причина]`: (Необязательно) Причина бана.  Текст причины будет виден в сообщении о бане.

**Примеры:**

*   *Ответ на сообщение:* `бан спам`
*   `@username`: `бан @user_example оскорбление`
*   `ID`: `бан 987654321`
*   `бан @username` (без причины)

### 🚪 Кик

**Описание:** Исключает пользователя из группы. Кикнутый пользователь может вернуться в группу по пригласительной ссылке.

**Использование:** `кик [причина]`

**Как указать цель (кого кикать):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `кик [причина]`
*   **@username:** Напишите: `кик @username [причина]`
*   **ID пользователя:** Напишите: `кик [user ID] [причина]`

**Параметры:**

*   `[причина]`: (Необязательно) Причина исключения. Текст причины будет виден в сообщении о кике.

**Примеры:**

*   *Ответ на сообщение:* `кик флуд`
*   `@username`: `кик @user_example нарушение`
*   `ID`: `кик 987654321`
*   `кик @username` (без причины)

### ⚠️ Пред / Варн

**Описание:** Выдает пользователю предупреждение. Система предупреждений может быть настроена на автоматический бан после достижения определенного количества предупреждений (функция не реализована в текущей версии).

**Использование:** `пред [причина]` или `варн [причина]`

**Как указать цель (кому выдать пред/варн):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `пред [причина]` или `варн [причина]`
*   **@username:** Напишите: `пред @username [причина]` или `варн @username [причина]`
*   **ID пользователя:** Напишите: `пред [user ID] [причина]` или `варн [user ID] [причина]`

**Параметры:**

*   `[причина]`: (Необязательно) Причина предупреждения. Текст причины будет виден в сообщении о предупреждении.

**Примеры:**

*   *Ответ на сообщение:* `пред флуд`
*   `@username`: `пред @user_example спам`
*   `ID`: `варн 987654321`
*   `пред @username` (без причины)
*   `варн` (без причины, в ответ на сообщение)

### 📊 Варны / Преды (посмотреть)

**Описание:** Показывает количество предупреждений, выданных пользователю.

**Использование:** `варны` или `преды`

**Как указать цель (чьи варны смотреть):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `варны` или `преды`
*   **@username:** Напишите: `варны @username` или `преды @username`
*   **ID пользователя:** Напишите: `варны [user ID]` или `преды [user ID]`

**Примеры:**

*   *Ответ на сообщение:* `варны`
*   `@username`: `преды @user_example`
*   `ID`: `варны 987654321`

### ✅ Снять Варны / Снять Преды

**Описание:** Снимает все предупреждения с пользователя.

**Использование:** `снять варны` или `снять преды`

**Как указать цель (у кого снять варны):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `снять варны` или `снять преды`
*   **@username:** Напишите: `снять варны @username` или `снять преды @username`
*   **ID пользователя:** Напишите: `снять варны [user ID]` или `снять преды [user ID]`

**Примеры:**

*   *Ответ на сообщение:* `снять варны`
*   `@username`: `снять преды @user_example`
*   `ID`: `снять варны 987654321`

### 🧹 Очистить

**Описание:** Удаляет последние сообщения в чате.

**Использование:** `очистить [количество сообщений]`

**Параметры:**

*   `[количество сообщений]`: (Необязательно) Количество сообщений для удаления. По умолчанию удаляет 100 последних сообщений. Максимальное количество для удаления за один раз - 500.

**Примеры:**

*   `очистить 50` (очистит последние 50 сообщений)
*   `очистить` (очистит последние 100 сообщений)

### 🛡️ Антифлуд Вкл / Выкл

**Описание:** Включает или выключает автоматическую защиту от флуда (количество сообщений в единицу времени). Логика антифлуда в текущей версии простая и требует доработки.

**Использование:** `антифлуд вкл` или `антифлуд выкл`

**Примеры:**

*   `антифлуд вкл`
*   `антифлуд выкл`

### 🔗 Антилинк Вкл / Выкл

**Описание:** Включает или выключает автоматическое удаление сообщений, содержащих ссылки (от пользователей, не являющихся администраторами).

**Использование:** `антилинк вкл` или `антилинк выкл`

**Примеры:**

*   `антилинк вкл`
*   `антилинк выкл`

### 🤬 Антимат Вкл / Выкл

**Описание:** Включает или выключает фильтр нецензурной лексики (мат-фильтр).  Словарь мата в текущей версии не настроен и требует добавления.

**Использование:** `антимат вкл` или `антимат выкл`

**Примеры:**

*   `антимат вкл`
*   `антимат выкл`

### 📜 Правила (установить / просмотреть)

**Описание:** Позволяет установить правила группы или просмотреть текущие правила.

**Использование:**

*   **Установить правила:** `правила [текст правил]`
*   **Просмотреть правила:** `правила` (без параметров)

**Примеры:**

*   `правила Добро пожаловать в нашу группу! Пожалуйста, соблюдайте правила поведения... (текст правил)` (установка правил)
*   `правила` (просмотр правил)

### 👋 Приветствие (установить / просмотреть)

**Описание:** Позволяет установить приветственное сообщение для новых участников группы или просмотреть текущее приветствие. Используйте `{user}`, чтобы вставить имя нового участника в приветствие.

**Использование:**

*   **Установить приветствие:** `приветствие [текст приветствия]`
*   **Просмотреть приветствие:** `приветствие` (без параметров)

**Примеры:**

*   `приветствие Добро пожаловать, {user}, в нашу дружную компанию! ... (текст приветствия)` (установка приветствия)
*   `приветствие` (просмотр приветствия)

### 🤖 Капча Вкл / Выкл

**Описание:** Включает или выключает капчу для новых участников группы. **Внимание:** Реализация капчи в текущей версии является заглушкой и требует доработки.

**Использование:** `капча вкл` или `капча выкл`

**Примеры:**

*   `капча вкл`
*   `капча выкл`

### 👑 Модераторы

**Описание:** Показывает список модераторов бота (не администраторов группы Telegram, а внутренних админов бота, назначенных создателем группы).

**Использование:** `модераторы`

**Пример:**

*   `модераторы`

### 🐌 Медленный Режим

**Описание:** Включает медленный режим в группе, ограничивая частоту отправки сообщений пользователями.

**Использование:** `медленный режим [время в секундах]`

**Параметры:**

*   `[время в секундах]`:  Время в секундах, через которое пользователи смогут отправлять сообщения.

**Примеры:**

*   `медленный режим 5` (включит медленный режим 5 секунд)
*   `медленный режим 10` (включит медленный режим 10 секунд)

### 🔒 Запретить Контент

**Описание:** Запрещает отправку определенного типа контента в группе (медиа, стикеры, гифки и т.д.). **Внимание:** Реализация запрета контента в текущей версии является заглушкой и требует доработки.

**Использование:** `запретить [тип контента]`

**Параметры:**

*   `[тип контента]`:  Тип контента для запрета. Доступные типы: `все`, `медиа`, `стикеры`, `гифки`, `голосовые`, `видео`, `файлы`, `опросы`.

**Примеры:**

*   `запретить стикеры`
*   `запретить медиа`
*   `запретить все`

### 🔓 Разрешить Контент

**Описание:** Разрешает отправку ранее запрещенного типа контента в группе. **Внимание:** Работает в связке с командой "Запретить контент" и также является заглушкой в текущей версии.

**Использование:** `разрешить [тип контента]`

**Параметры:**

*   `[тип контента]`:  Тип контента для разрешения. Доступные типы: `все`, `медиа`, `стикеры`, `гифки`, `голосовые`, `видео`, `файлы`, `опросы`.

**Примеры:**

*   `разрешить стикеры`
*   `разрешить медиа`
*   `разрешить все`

### 📌 Закрепить Сообщение

**Описание:** Закрепляет сообщение вверху чата.

**Использование:** `закрепить` (ответить на сообщение, которое нужно закрепить)

**Как использовать:**

*   **Ответить на сообщение:** Ответьте на сообщение, которое хотите закрепить, и напишите: `закрепить`

**Пример:**

*   *Ответ на сообщение:* `закрепить`

### unpin Открепить Сообщение

**Описание:** Открепляет закрепленное сообщение вверху чата.

**Использование:** `открепить`

**Пример:**

*   `открепить`

### 📢 Репорт

**Описание:** Отправляет репорт на сообщение администраторам бота. **Внимание:**  Функция отправки репортов администраторам бота в текущей версии является заглушкой и требует доработки.

**Использование:** `репорт [причина]` (ответить на сообщение, которое нужно зарепортить)

**Как использовать:**

*   **Ответить на сообщение:** Ответьте на сообщение, которое хотите зарепортить, и напишите: `репорт [причина]`

**Параметры:**

*   `[причина]`: (Необязательно) Причина репорта.

**Примеры:**

*   *Ответ на сообщение:* `репорт спам`
*   *Ответ на сообщение:* `репорт` (без причины)

### 👤 Игнор

**Описание:** Добавляет пользователя в игнор-лист бота. Бот перестанет реагировать на команды этого пользователя. **Внимание:**  Функция игнор-листа в текущей версии является заглушкой и требует доработки.

**Использование:** `игнор [цель]`

**Как указать цель (кого игнорировать):**

*   **@username:** Напишите: `игнор @username`
*   **ID пользователя:** Напишите: `игнор [user ID]`

**Примеры:**

*   `игнор @user_example`
*   `игнор 987654321`

### 👤 Убрать Игнор

**Описание:** Удаляет пользователя из игнор-листа бота. Бот снова начнет реагировать на команды этого пользователя. **Внимание:**  Работает в связке с командой "Игнор" и также является заглушкой в текущей версии.

**Использование:** `убрать игнор [цель]`

**Как указать цель (у кого снять игнор):**

*   **@username:** Напишите: `убрать игнор @username`
*   **ID пользователя:** Напишите: `убрать игнор [user ID]`

**Примеры:**

*   `убрать игнор @user_example`
*   `убрать игнор 987654321`

---

## 🎲 Игры

### 🎲 Кости

**Описание:** Бросает игральные кости (виртуальные).

**Использование:** `кости`

**Пример:**

*   `кости`

### 🪙 Монетка

**Описание:** Подбрасывает монетку, определяя "орел" или "решка".

**Использование:** `монетка`

**Пример:**

*   `монетка`

### 🔮 Шар 8

**Описание:** Магический шар 8 отвечает на вопросы "Да/Нет". Задайте вопрос после команды.

**Использование:** `шар [вопрос]` или `8ball [вопрос]`

**Параметры:**

*   `[вопрос]`:  Вопрос, на который хотите получить ответ "Да/Нет".

**Примеры:**

*   `шар Будет ли сегодня хорошая погода?`
*   `8ball Повезет ли мне сегодня?`

### 🎮 Викторина

**Описание:** Запускает викторину (в разработке, пока заглушка).

**Использование:** `викторина`

**Пример:**

*   `викторина`

### 🔢 Угадай Число

**Описание:** Запускает игру "Угадай число" (в разработке, пока заглушка). Бот загадывает число, пользователи пытаются угадать.

**Использование:** `угадай число`

**Пример:**

*   `угадай число`

### 🪨 Ножницы 📃 Бумага / КНБ

**Описание:** Игра "Камень, ножницы, бумага" против бота.

**Использование:** `камень ножницы бумага [выбор]` или `кнб [выбор]`

**Параметры:**

*   `[выбор]`:  Ваш выбор: `камень`, `ножницы` или `бумага`.

**Примеры:**

*   `камень ножницы бумага камень`
*   `кнб ножницы`

### 🔢 Рандомное Число

**Описание:** Возвращает случайное число в заданном диапазоне (в разработке, пока заглушка).

**Использование:** `рандомное число [от] [до]`

**Параметры:**

*   `[от]`:  Начало диапазона (целое число).
*   `[до]`:  Конец диапазона (целое число).

**Примеры:**

*   `рандомное число 1 100` (случайное число от 1 до 100)

### 👤 Кто

**Описание:** Случайным образом выбирает одного пользователя из группы (в разработке, пока заглушка).

**Использование:** `кто`

**Пример:**

*   `кто`

### 🎭 Правда Или Действие

**Описание:** Запускает игру "Правда или действие" (в разработке, пока заглушка).

**Использование:** `правда или действие`

**Пример:**

*   `правда или действие`

---

## ℹ️ Информация

### 🌦️ Погода

**Описание:** Показывает погоду в указанном городе. **Внимание:** Интеграция с API погоды в текущей версии является заглушкой и требует доработки.

**Использование:** `погода [город]`

**Параметры:**

*   `[город]`:  Название города, погоду в котором хотите узнать.

**Примеры:**

*   `погода Москва`
*   `погода Лондон`

### 💰 Курс Валюты

**Описание:** Показывает курс указанной валюты (относительно рубля или другой валюты - нужно настроить). **Внимание:** Интеграция с API курсов валют в текущей версии является заглушкой и требует доработки.

**Использование:** `курс [код валюты]`

**Параметры:**

*   `[код валюты]`:  Код валюты (например, `USD`, `EUR`, `RUB`, `BTC`).

**Примеры:**

*   `курс USD`
*   `курс EUR`
*   `курс BTC`

### 📚 Вики / Wikipedia

**Описание:** Ищет информацию в Википедии по запросу. **Внимание:** Интеграция с API Википедии в текущей версии является заглушкой и требует доработки.

**Использование:** `вики [запрос]` или `wikipedia [запрос]`

**Параметры:**

*   `[запрос]`:  Поисковый запрос для Википедии.

**Примеры:**

*   `вики Python`
*   `wikipedia Telegram bot`

### 💡 Факт

**Описание:** Возвращает случайный интересный факт (в разработке, пока заглушка).

**Использование:** `факт`

**Пример:**

*   `факт`

### 😂 Анекдот

**Описание:** Возвращает случайный анекдот (в разработке, пока заглушка).

**Использование:** `анекдот`

**Пример:**

*   `анекдот`

### 📜 Цитата

**Описание:** Возвращает случайную цитату (в разработке, пока заглушка).

**Использование:** `цитата`

**Пример:**

*   `цитата`

### ⏰ Время

**Описание:** Показывает текущее время (время сервера, на котором запущен бот).

**Использование:** `время`

**Пример:**

*   `время`

---

## 💬 Социальные

### 👋 Привет Всем

**Описание:** Отправляет приветствие всем участникам группы от имени пользователя, вызвавшего команду.

**Использование:** `привет всем`

**Пример:**

*   `привет всем`

### 🌃 Спокойной Ночи

**Описание:** Желает всем участникам группы спокойной ночи.

**Использование:** `спокойной ночи`

**Пример:**

*   `спокойной ночи`

### 🤔 Выбор

**Описание:** Бот случайным образом выбирает один вариант из перечисленных вами.

**Использование:** `выбор [вариант1], [вариант2], [вариант3], ...`

**Параметры:**

*   `[вариант1], [вариант2], [вариант3], ...`:  Варианты выбора, перечисленные через запятую.

**Примеры:**

*   `выбор чай, кофе, какао`
*   `выбор пойти в кино, остаться дома, пойти гулять`

### 😊 Комплимент

**Описание:** Бот делает комплимент пользователю.

**Использование:** `комплимент`

**Как указать цель (кому сделать комплимент):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `комплимент`
*   **@username:** Напишите: `комплимент @username`
*   **ID пользователя:** Напишите: `комплимент [user ID]`

**Примеры:**

*   *Ответ на сообщение:* `комплимент`
*   `@username`: `комплимент @user_example`
*   `ID`: `комплимент 987654321`

### 😈 Оскорбление (Шуточное)

**Описание:** Бот шуточно оскорбляет пользователя. **Внимание:**  Использовать с осторожностью и только в группах, где это уместно и не обидит участников.

**Использование:** `оскорбление`

**Как указать цель (кого оскорбить):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `оскорбление`
*   **@username:** Напишите: `оскорбление @username`
*   **ID пользователя:** Напишите: `оскорбление [user ID]`

**Примеры:**

*   *Ответ на сообщение:* `оскорбление`
*   `@username`: `оскорбление @user_example`
*   `ID`: `оскорбление 987654321`

### 🏅 Звание

**Описание:** Присваивает пользователю случайное звание (в разработке, пока заглушка).

**Использование:** `звание`

**Пример:**

*   `звание`

### ⭐ Статус

**Описание:** Присваивает пользователю случайный статус (в разработке, пока заглушка).

**Использование:** `статус`

**Пример:**

*   `статус`

---

## 👑 Администрирование Бота (доступно создателю группы Telegram)

### 👑 Назначить Админом Бота

**Описание:** Назначает пользователя администратором бота с определенным уровнем доступа.  Админы бота получают доступ к расширенным функциям бота (в зависимости от уровня доступа).  Назначать админов бота может только создатель группы Telegram.

**Использование:** `назначить админом [уровень]`

**Как указать цель (кого назначить админом):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `назначить админом [уровень]`
*   **@username:** Напишите: `назначить админом @username [уровень]`
*   **ID пользователя:** Напишите: `назначить админом [user ID] [уровень]`

**Параметры:**

*   `[уровень]`:  Уровень доступа назначаемого админа бота. Доступные уровни: `младший`, `средний`, `старший`, `создатель`.

**Примеры:**

*   *Ответ на сообщение:* `назначить админом старший`
*   `@username`: `назначить админом @user_example младший`
*   `ID`: `назначить админом 987654321 средний`

### 👑 Снять Админа Бота

**Описание:** Снимает пользователя с должности администратора бота. Снять админа бота может только создатель группы Telegram.

**Использование:** `снять админа`

**Как указать цель (кого снять с админки бота):**

*   **Ответить на сообщение:** Ответьте на сообщение пользователя и напишите: `снять админа`
*   **@username:** Напишите: `снять админа @username`
*   **ID пользователя:** Напишите: `снять админа [user ID]`

**Примеры:**

*   *Ответ на сообщение:* `снять админа`
*   `@username`: `снять админа @user_example`
*   `ID`: `снять админа 987654321`

### 👑 Кто Админ

**Описание:** Показывает список текущих админов бота в этом чате.

**Использование:** `кто админ`

**Пример:**

*   `кто админ`

---

## ❓ Помощь

### ❓ /help

**Описание:** Показывает ссылку на полный список команд бота и это руководство.  **Внимание:** Это единственная команда бота, которая используется со слэшем `/`.

**Использование:** `/help`

**Пример:**

*   `/help`

---
