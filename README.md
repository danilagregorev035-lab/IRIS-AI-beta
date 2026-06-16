(RU/ENG) ENG:

🌌 IRIS AI — Smart Neural Network Without API Key
IRIS AI is a fully autonomous web interface for interacting with artificial intelligence that requires no registration, API keys, or paid subscriptions. Simply open the page in your browser — and start asking questions. Everything runs on a free LLM endpoint, while advanced modes (deep thinking, real-time search, theme switching, and even aggressive communication style) make this tool unique among similar solutions.

✨ Features
🧠 Deep Thinking
A special mode that forces the neural network to analyze the question step by step: first it generates an internal reasoning chain [Thinking], then outputs the final answer [Answer]. You can see the AI's thought process — this is especially useful for complex questions, learning, and debugging response logic.

🔍 Search for Answers
Before answering, IRIS can independently find information on the internet via the DuckDuckGo API. Search results are added to the neural network's context, improving accuracy and relevance of responses. Works without proxies or CORS errors thanks to JSONP callbacks.

🔥 Aggression Mode
A unique feature: toggle it on, and the neural network will start communicating rudely, with profanity and insults. A 4-second warning appears upon activation. The mode is fully reversible — you can turn it off at any time.

🎨 Switchable Visual Themes
Supports 7 visual themes that change the entire color palette and fonts:

🌙 Standard Dark (classic deep space)

☀️ Light (clean minimalism)

🌀 Cosmic Nebula (purple-pink gradients, Orbitron font)

⭐ Star Map (constellations, turquoise accents)

🛰️ Orbital Station (technical style, Press Start 2P)

🚀 Galactic Journey (neon panels, Share Tech Mono)

🕳️ Black Hole (aggressive red-black, accretion disk)

The theme is saved in localStorage and restored on the next launch.

💬 Chat History
All conversations are saved in the left sidebar. You can:

Create new chats

Switch between them

Delete unnecessary ones

Automatically name chats based on the first message

Data is stored locally in the browser and never transmitted to any server.

📱 Full Mobile Adaptation
The interface automatically adjusts to smartphone screens: the sidebar hides and opens via a burger button, controls are optimized for touch interaction, and font sizes and margins are adapted for narrow screens (down to 320px).

⚠️ System Warning
On first launch, a notification appears about possible slow neural network performance — you can close it, and it won't appear again.

🧩 Technical Details
How the Neural Network Works
IRIS AI uses the free text.pollinations.ai endpoint, which accepts a text prompt and returns a generated response. A simple HTTP request is all that's needed — no API key required.

Information Search
For the "Search Answer" mode, the DuckDuckGo Instant Answer API is used through dynamic JSONP script loading. This bypasses CORS restrictions and retrieves brief relevant information based on the query, which is then inserted into the neural network's prompt.

Data Storage
localStorage is used to save chats, active themes, toggle states (deep thinking, search, aggressive mode), and the warning dismissal flag.

No data is sent to external servers except in the body of requests to DuckDuckGo and Pollinations.

Code Structure
iris.html — interface markup

styles.css — styles including all 7 themes and media queries

iris.js — all logic: chat management, request handling, search, theme switching, UI interaction

🚀 How to Run
Download the repository or simply save the HTML file.

Open iris.html in any modern browser (Chrome, Edge, Firefox, Safari).

That's it! You can start asking questions immediately.

No dependencies, builders, servers, or keys required.

🖼️ Screenshots
Dark Theme	Light Theme	Mobile View
(Add your screenshots here)

🔧 Building a Browser Extension (Optional)
Although the main version is a standalone HTML page, the repository also contains files for packaging as a Chrome Extension:

manifest.json (Manifest V3)

background.js (opens popup or new tab)


The extension can be loaded in developer mode via chrome://extensions/.

📋 TODO / Development Roadmap
Export chats to PDF / TXT

Voice input (Web Speech API)

"Uncensored" mode with style selection (sarcasm, philosophical, childish)

Offline mode support (interface caching)

Integration with other free LLM endpoints

PWA version (install on phone as an app)

📜 License
MIT — do whatever you want, just provide attribution.

👤 Author
Developed with passion and love 
If you have questions or suggestions — create an Issue or Pull Request.
Enjoy using IRIS AI!

RU:

🌌 IRIS AI — Умная нейросеть без API-ключа
IRIS AI — это полностью автономный веб-интерфейс для взаимодействия с искусственным интеллектом.
Вам не нужна регистрация, API-ключи или платные подписки. Просто откройте страницу в браузере и задавайте вопросы.

В основе работы — бесплатный LLM-эндпоинт, а расширенные режимы делают IRIS уникальным инструментом:

🧠 глубокое мышление

🔍 поиск в реальном времени

🎨 смена тем оформления

🔥 агрессивный стиль общения

✨ Возможности
🧠 Глубокое мышление
Специальный режим, при котором нейросеть сначала генерирует внутреннюю цепочку рассуждений [Thinking], а затем выдаёт финальный ответ [Answer].
Вы видите ход мыслей ИИ — это особенно полезно для сложных вопросов, обучения и отладки логики.

🔍 Поиск ответа
IRIS может самостоятельно находить информацию в интернете через DuckDuckGo API.
Результаты поиска добавляются в контекст нейросети, что повышает точность и актуальность ответов.
Работает без прокси и CORS-ошибок благодаря JSONP-коллбэкам.

🔥 Режим агрессии
Уникальная функция: включите тумблер — и нейросеть начнёт общаться грубо, с матом и оскорблениями.
При активации появляется 4-секундное предупреждение. Режим полностью обратим — можно выключить в любой момент.

🎨 Сменные темы оформления
Доступно 7 визуальных тем, меняющих цветовую палитру и шрифты:

Тема	Описание
🌙 Стандартная тёмная	Классический deep space
☀️ Светлая	Чистый минимализм
🌀 Космическая туманность	Фиолетово-розовые переливы, шрифт Orbitron
⭐ Звёздная карта	Созвездия, бирюзовые акценты
🛰️ Орбитальная станция	Технический стиль, Press Start 2P
🚀 Путешествие сквозь галактику	Неоновые панели, Share Tech Mono
🕳️ Чёрная дыра	Агрессивный красно-чёрный, аккреционный диск
Тема сохраняется в localStorage и восстанавливается при следующем запуске.

💬 История чатов
Все диалоги сохраняются в левой боковой панели. Вы можете:

создавать новые чаты,

переключаться между ними,

удалять ненужные.

Название чата автоматически присваивается по первому сообщению.
Данные хранятся локально в браузере и не передаются на сервер.

📱 Полная мобильная адаптация
Интерфейс автоматически подстраивается под экраны смартфонов:

боковая панель скрывается и открывается по кнопке-бургеру,

элементы управления оптимизированы для тач-взаимодействия,

шрифты и отступы адаптированы под узкие экраны (вплоть до 320px).

⚠️ Системное предупреждение
При первом запуске отображается уведомление о возможной медленной работе нейросети.
Его можно закрыть — и оно больше не появится.

🧩 Технические детали
Как работает нейросеть
IRIS AI использует бесплатный эндпоинт text.pollinations.ai, который принимает текстовый промпт и возвращает сгенерированный ответ.
Для этого достаточно обычного HTTP-запроса — API-ключ не требуется.

Поиск информации
Для режима «Поиск ответа» используется DuckDuckGo Instant Answer API через динамическую подгрузку JSONP-скриптов.
Это позволяет обойти ограничения CORS и получать краткую релевантную информацию по запросу, которая затем подставляется в промпт нейросети.

Хранение данных
localStorage используется для сохранения:

чатов,

активной темы,

состояния переключателей (глубокое мышление, поиск, агрессивный режим),

флага о закрытии предупреждения.

Никакие данные не отправляются на внешние серверы, кроме запросов к DuckDuckGo и Pollinations.

Структура кода
iris.html — разметка интерфейса

styles.css — стили, включая все 7 тем и медиа-запросы

iris.js — вся логика: управление чатами, отправка запросов, поиск, переключение тем, UI-взаимодействие

🚀 Как запустить
Скачайте репозиторий или просто сохраните HTML-файл.

Откройте iris.html в любом современном браузере (Chrome, Edge, Firefox, Safari).

Всё! Можно сразу задавать вопросы.

Никаких зависимостей, сборщиков, серверов или ключей.

🖼️ Скриншоты
Тёмная тема	Светлая тема	Мобильный вид
(добавьте скриншот)	(добавьте скриншот)	(добавьте скриншот)
🔧 Сборка расширения для браузера (опционально)
Хотя основная версия — это самостоятельная HTML-страница, репозиторий также содержит файлы для упаковки в Chrome Extension:

manifest.json (Manifest V3)

background.js (открытие popup или новой вкладки)

icons/ (иконки 16×16, 48×48, 128×128)

Расширение можно загрузить в режиме разработчика через chrome://extensions/.

📋 Планы по развитию
Экспорт чатов в PDF / TXT

Голосовой ввод (Web Speech API)

Режим «без цензуры» с выбором стиля (сарказм, философский, детский)

Поддержка офлайн-режима (кэширование интерфейса)

Интеграция с другими бесплатными LLM-эндпоинтами

PWA-версия (установка на телефон как приложение)

📜 Лицензия
MIT — делайте что угодно, только указывайте авторство.

👤 Автор
Ghost Dev
Разработано с душой и любовью
По вопросам и предложениям — создавайте Issue или Pull Request.

Приятного использования IRIS AI! 🚀

