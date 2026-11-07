// Домашняя страница для Zalith Launcher 2 Plus (2.4.10)
// Строки, начинающиеся с //, лаунчер не показывает. Это мои подсказки.
// Что менять: тексты, ссылки (помечены ВАШ_...) и картинки.

# Добро пожаловать! 👋

// Баннер. Замени ссылку на свою картинку (прямая ссылка на .png или .jpg).
...image url="https://picsum.photos/800/300" width=100% shape=16dp

...card-start title="🎮 Быстрый старт" shape=large contentPadding=(16, 12)
Нажми **«Играть»**, чтобы запустить выбранную версию игры.
...card-end

...row-start horizontal=spacedBy(8)
...button text="▶ Играть" event="launch_game" weight=(1)
...button-outlined text="🔄 Обновления" event="check_update" weight=(1)
...row-end

...card-start title="💡 Совет" shape=large contentPadding=(16, 12)
...random-start
Не копай прямо под собой.
weight(2.0): Всегда носи с собой факелы и еду.
Построй кровать рядом с домом, чтобы сохранить точку возрождения.
Перед походом в Незер возьми запас блоков.
...random-end
...card-end

...card-start title="📰 Новости" shape=large contentPadding=(16, 12)
- Добавлена новая сборка модов
- Исправлены вылеты на старте
- Скоро: новый сервер

// Чтобы изменить новости, просто поправь текст выше и сохрани файл.
...card-end

...card-start title="🔗 Ссылки" shape=large contentPadding=(16, 12)
...column-start vertical=spacedBy(8)
...button-filled-tonal text="Discord" event="url{https://discord.gg/ВАШ_КОД}" width=100%
...button-filled-tonal text="YouTube" event="url{https://www.youtube.com/@ВАШ_КАНАЛ}" width=100%
...button-filled-tonal text="Скопировать IP сервера" event="copy{mc.example.com}" width=100%
...column-end
...card-end

...row-start horizontal=spacedBy(8)
...button-text text="🔁 Обновить страницу" event="refresh_page" weight=(1)
...button-text text="📋 Поделиться логом" event="share_game_log" weight=(1)
...row-end
