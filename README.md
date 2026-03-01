# Русификатор Wizardry Variants Daphne | Russian Translation

[![Latest Release](https://img.shields.io/github/v/release/daniilcathey/WVD_RUS_Releases?label=Версия&color=blue)](https://github.com/daniilcathey/WVD_RUS_Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/daniilcathey/WVD_RUS_Releases/total?label=Скачиваний&color=green)](https://github.com/daniilcathey/WVD_RUS_Releases/releases/latest)

Полный русский перевод для **Wizardry Variants Daphne** (Steam). Диалоги, интерфейс, предметы, навыки, квесты — всё на русском языке с кириллическими шрифтами.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/daniilcathey/WVD_RUS_Releases/main/screenshots/city_ui.jpg" width="48%" alt="Город — Таверна, Храм, Гильдия, Руины">
  <img src="https://raw.githubusercontent.com/daniilcathey/WVD_RUS_Releases/main/screenshots/npc_dialogue.jpg" width="48%" alt="Диалог NPC — Сестра Кристель">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/daniilcathey/WVD_RUS_Releases/main/screenshots/battle_ui.jpg" width="48%" alt="Бой — Атака, Навыки, Заклинания, Защита, Бегство">
  <img src="https://raw.githubusercontent.com/daniilcathey/WVD_RUS_Releases/main/screenshots/skill_description.jpg" width="48%" alt="Описание навыка — Точный удар">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/daniilcathey/WVD_RUS_Releases/main/screenshots/blacksmith_items.jpg" width="48%" alt="Кузнец — предметы, статы, улучшения">
</p>

---

## Что переведено

| Категория | Объём |
|---|---|
| Диалоги NPC | ~26 000 строк (33+ бандла) |
| Мастер-данные (предметы, навыки, квесты, достижения) | 14 300 записей |
| Интерфейс (меню, кнопки, подсказки) | 2 274 строки |
| Шрифты | Кириллические глифы встроены в игровые шрифты |
| Гендерное согласование | Женские NPC говорят в женском роде |

## Установка

### Первая установка

1. **Скачайте** из [последнего релиза](https://github.com/daniilcathey/WVD_RUS_Releases/releases/latest):
   - `WVD_Russifier.exe` — лаунчер русификатора
   - `WVD_translations_v*.zip` — файлы переводов
2. **Создайте папку** `russifier_pack` в директории игры:
   ```
   Steam/steamapps/common/Wizardry Variants Daphne/russifier_pack/
   ```
3. **Поместите** оба файла в эту папку
4. **Запустите** `WVD_Russifier.exe`
5. Нажмите **«Применить переводы»** и дождитесь завершения

> Путь к игре можно найти в Steam: ПКМ по игре → Управление → Просмотреть локальные файлы

### Обновление

Лаунчер проверяет обновления автоматически при каждом запуске. Если доступна новая версия — появится баннер с предложением обновиться.

Для ручного обновления: скачайте новый `WVD_translations_v*.zip` из [релизов](https://github.com/daniilcathey/WVD_RUS_Releases/releases/latest), поместите в `russifier_pack/` и нажмите «Применить переводы».

### После обновления/проверки файлов Steam

Если Steam обновил игру или вы запускали «Проверить целостность файлов» — **переводы будут сброшены**. Просто запустите `WVD_Russifier.exe` и нажмите «Применить переводы» заново.

## Требования

- Windows 10/11
- Steam-версия Wizardry Variants Daphne
- ~100 МБ свободного места
- Игра должна быть запущена хотя бы один раз (для скачивания игровых данных)

## FAQ

<details>
<summary><b>Чёрный экран после установки</b></summary>

Скорее всего, кэш мастер-данных повреждён. Решение:
1. Закройте игру
2. Запустите `WVD_Russifier.exe`
3. Нажмите «Удалить переводы»
4. Запустите игру (она скачает свежие данные)
5. Закройте игру и снова примените переводы

</details>

<details>
<summary><b>Часть текста на английском</b></summary>

Некоторый контент переводится только после того, как игра скачает его в кэш. Пройдите нужный контент в игре, затем переприменте переводы.

</details>

<details>
<summary><b>Как удалить русификатор</b></summary>

Запустите `WVD_Russifier.exe` → «Удалить переводы». Это удалит все патчи и вернёт игру к оригинальному состоянию.

Альтернативно: Steam → ПКМ по игре → Свойства → Установленные файлы → Проверить целостность файлов.

</details>

<details>
<summary><b>Совместимость с обновлениями игры</b></summary>

После обновления игры переводы нужно переприменить. Запустите лаунчер — он автоматически определит, что переводы сброшены, и предложит применить заново.

</details>

<details>
<summary><b>Где хранятся файлы русификатора</b></summary>

- Лаунчер и переводы: `Steam/.../Wizardry Variants Daphne/russifier_pack/`
- Настройки лаунчера: `%APPDATA%/WVD_Russifier/config.json`

</details>

## Контакты

- Telegram: [@catheyco](https://t.me/catheyco) — новости, обсуждение, баг-репорты
- [Issues](https://github.com/daniilcathey/WVD_RUS_Releases/issues) — баг-репорты и предложения

---

<sub>Wizardry Variants Daphne Russian translation, русификатор, локализация, перевод на русский, JRPG, Steam, drecom, Wizardry Daphne, russifier</sub>
