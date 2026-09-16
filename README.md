<div align="center">

# 🎡 PAPICH WHEEL — КОЛЕСО ПАПИЧА 🎡

### not a wheel, a pure sigma content generator for your stream 🗿💯🔥

<img src="https://img.shields.io/badge/aura-%2B9000-blueviolet?style=for-the-badge" />
<img src="https://img.shields.io/badge/kek-100%25-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/based-confirmed-brightgreen?style=for-the-badge" />
<img src="https://img.shields.io/badge/internet-not%20required-black?style=for-the-badge" />
<img src="https://img.shields.io/badge/framework-none%2C%20pure%20js-orange?style=for-the-badge" />

### 🔗 [LIVE DEMO — open right in your browser](https://karaseklobys.github.io/papich-wheel/)

**[🇬🇧 English](#-english)** · **[🇷🇺 Русский](#-русский)**

</div>

---

## 🇬🇧 English

### 🤔 What is this

One(!) HTML file. Open it and you're already running a wheel like Папич
(a huge RU streamer) does on stream. No websites, no sign-ups, no
"log in with VK ID". Download `wheel.html` → double-click → aura go up 📈

It's a **lot auction** format: viewers pledge points for whatever they
want to see (a game, a challenge, anything) — points become the lot's
weight on the wheel. Spin it, and it fairly eliminates lots one by one
(the lower the weight, the higher the odds of getting knocked out),
until one lot remains — the winner, i.e. what the streamer plays or
does next 🏆

### ⚡ Features (they actually work, no cap)

- 🎯 **Weighted lots** — bigger weight, bigger slice on the wheel
- 🌀 **Spin = elimination** — spin it, someone gets knocked out, repeat until a winner remains
- 🧮 **Fair formula** — genuinely fair random, no rigged pointer for your friends
- 🔍 Search, sort by weight, hide eliminated lots
- 💾 **Export / import** the list as JSON — don't lose your lots between streams
- ⏱️ Built-in timer (for counting down anything)
- 🎨 Sliders for wheel size / UI scale / font — fits any OBS overlay
- 🖼️ Center-image gallery: trollface, pepe, wojak, doge, gigachad, among us, meme man — pick today's vibe
- 🔊 **Epic fanfare while it spins** — stops the moment it lands, with a big mute button right up front
- 🔌 **Works offline.** Everything's baked into one file, no CDNs, no trackers

### 🚀 How to download and run

1. Open [**Releases**](../../releases/latest) and grab `wheel.html` —
   always the latest stable build, no extra junk
2. Open the file in your browser (double-click) — or drop it into OBS
   as a **Browser Source**
3. Add lots, type auction points as the weight, hit **"Spin"**
4. ??? — you're already streaming at Папич tier

> Alternative: just clone the repo and open `wheel.html` — works fine
> without Releases too.

The file saves everything to `localStorage` — close the tab, reopen it,
your lots are still there.

### 📊 Aura rating of features

| Feature | Aura |
|---|---|
| Wheel spins smoothly | +500 |
| Gigachad in the center of the wheel | +1000 |
| Works with no internet | +2000 |
| Fair formula (no cheating) | +9000 |
| Viewers think you coded this yourself | +∞ |

### 🛠️ For the nerds who want to know how it's built

Pure HTML + CSS + JS, no frameworks, no dependencies. The wheel is
drawn on a `<canvas>`, the spin animation runs on
`requestAnimationFrame` with easing, and the winner is picked with
genuinely fair weighted-random selection. All state lives in this
file's `localStorage`.

### 🤝 Contributing

PRs, ideas, new gallery images — welcome. Got an idea to make the
wheel even more sigma? Open an issue.

### ⚠️ Disclaimer

The meme images in the gallery come from open sources (pngimg,
StickPNG, KnowYourMeme, Imgflip) and are used for personal,
non-commercial use — as befits any self-respecting streamer tool.

The spin fanfare ("Brass Fanfare with Timpani and Winchimes,
Reverberated") is by a Pixabay contributor, used under the
[Pixabay Content License](https://pixabay.com/service/license-summary/)
(free for this kind of use, no attribution required).

---

## 🇷🇺 Русский

### 🤔 ЧТО ЭТО

Один(!) HTML файл. Открыл — и уже гоняешь колесо как Папич на стриме.
Никаких сайтов, никаких регистраций, никакого "войдите через VK ID".
Скачал `wheel.html` → дважды кликнул → аура пошла вверх 📈

Формат — **аукцион лотов**: зрители задонатили баллы за то, что хотят
увидеть (игру, челлендж, что угодно) — баллы становятся весом лота на
колесе. Дальше крутишь колесо, оно честно выбывает лоты один за другим
(чем меньше вес — тем выше шанс вылететь), пока не останется один
лот-победитель — то, что стример играет/делает дальше 🏆

### ⚡ ФИЧИ (реально работают, не кринж)

- 🎯 **Лоты с весами** — чем больше вес, тем жирнее сектор на колесе
- 🌀 **Крутить = выбывание** — крутанул, кто-то выбыл, повторить до победителя
- 🧮 **Честная формула** — рандом реально честный, без "наводки стрелки" для своих
- 🔍 Поиск, сортировка по весу, скрытие выбывших
- 💾 **Экспорт / импорт** списка в JSON — не теряешь лоты между стримами
- ⏱️ Встроенный таймер (для обратного отсчёта чего угодно)
- 🎨 Ползунки размера колеса / масштаба / шрифта — под любой оверлей в OBS
- 🖼️ Галерея картинок в центр колеса: тролфейс, пепе, вояк, доге, гигачад,
  амогус, мем-мэн — выбирай вайб дня
- 🔊 **Эпичная фанфара во время спина** — обрывается ровно в момент остановки, кнопка мьюта прямо на виду
- 🔌 **Работает офлайн.** Всё зашито в один файл, никаких CDN и трекеров

### 🚀 КАК СКАЧАТЬ И ЗАПУСТИТЬ

1. Открой [**Releases**](../../releases/latest) и скачай `wheel.html` —
   это всегда последняя стабильная версия, без лишнего мусора
2. Открой файл в браузере (двойной клик) — или закинь в OBS как
   **Browser Source**
3. Добавляй лоты, вписывай баллы аукциона как вес, жми **«Крутить»**
4. ??? — ты уже стример уровня Папича

> Альтернатива: просто клонируй репозиторий и открой `wheel.html` —
> без Releases тоже работает.

Файл всё сохраняет в `localStorage` — закрыл вкладку, открыл заново,
лоты на месте.

### 📊 АУРА-РЕЙТИНГ ФИЧЕЙ

| Фича | Аура |
|---|---|
| Колесо крутится плавно | +500 |
| Гигачад в центре колеса | +1000 |
| Работает без интернета | +2000 |
| Честная формула (без читов) | +9000 |
| Зрители думают что ты кодил это сам | +∞ |

### 🛠️ ДЛЯ ТЕХ КОМУ ИНТЕРЕСНО КАК ЭТО СДЕЛАНО

Чистый HTML + CSS + JS, без фреймворков и зависимостей. Колесо
рисуется на `<canvas>`, анимация спина — `requestAnimationFrame` с
easing, выбор победителя — честный weighted-random. Всё состояние
живёт в `localStorage` этого файла.

### 🤝 КОНТРИБЬЮТИТЬ

Пул-реквесты, идеи, новые картинки в галерею — велком. Если знаешь как
сделать колесо ещё более сигма — открывай issue.

### ⚠️ ДИСКЛЕЙМЕР

Мемные картинки в галерее взяты из открытых источников (pngimg,
StickPNG, KnowYourMeme, Imgflip) и используются для личного
некоммерческого использования — как и положено уважающему себя
стримерскому тулу.

Фанфара при спине ("Brass Fanfare with Timpani and Winchimes,
Reverberated") взята с Pixabay и используется по
[Pixabay Content License](https://pixabay.com/service/license-summary/)
(бесплатно для такого использования, атрибуция не требуется).

---

<div align="center">

**made on pure vibes, zero frameworks / сделано на чистом вайбе, без единого фреймворка** ✨

</div>
