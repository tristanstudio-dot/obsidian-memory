# Telegram Bot для Obsidian - Синхронизация в реальном времени

**Дата:** 20 апреля 2026

## 🤖 ЧТО ДЕЛАЕТ БОТ

Получает твои сообщения → Обновляет Obsidian автоматически

---

## 📝 КАК ИСПОЛЬЗОВАТЬ

### Пример 1: Новая идея
\\\
Ты: HomeGarden - озеленение дома, обсудил с Фирузой
Бот: Создаёт THOUGHTS/Family_Ideas/HomeGarden.md
      Добавляет ссылку в PEOPLE/Family/Фироза.md
\\\

### Пример 2: Идея → Проект
\\\
Ты: HomeGarden запускаем! Фироза согласна
Бот: Создаёт PROJECTS/Active/HomeGarden.md
      Ссылает Фирозу как соучредителя
\\\

### Пример 3: Подпроекты
\\\
Ты: HomeGarden подпроекты: дизайн, выбор растений (Фироза), полив
Бот: Создаёт SUBPROJECTS/HomeGarden/Design.md
      SUBPROJECTS/HomeGarden/Plant_Selection.md (Фироза)
      SUBPROJECTS/HomeGarden/Care_Schedule.md
\\\

### Пример 4: Новый человек
\\\
Ты: HomeGarden - старшая дочь будет дизайном
Бот: Обновляет PROJECTS/Active/HomeGarden.md
      Ссылает старшую дочь в PEOPLE и в подпроект Design
\\\

---

## 🎙️ ГОЛОС ТОЖЕ РАБОТАЕТ

Просто отправляешь голосовую заметку - бот транскрибирует и создаёт файлы.

---

## 📱 БЫСТРЫЕ КОМАНДЫ (ОПЦИОНАЛЬНО)

\\\
[IDEA] HomeGarden - озеленение
[PROJECT] HomeGarden запускаем!
[UPDATE] HomeGarden - новая инфа
[SUBPROJECT] HomeGarden/Design - дизайн
[PERSON] Фироза - роль в HomeGarden
\\\

Но можешь просто писать естественно - бот поймёт!

---

## ✅ ПРИМЕР РОСТА (HomeGarden)

День 1: Идея
`
Фироза ← HomeGarden
`

День 2: Проект
`
Фироза ↔ HomeGarden
`

День 3: Подпроекты
`
Фироза ↔ HomeGarden ← [Design, Plants, Care]
`

День 4: Команда
`
      Старшая дочь (Design)
           ↓
Фироза ↔ HomeGarden ← [Plants, Care]
           ↑
        (Фироза)
`

**ОРГАНИЧЕСКИЙ РОСТ В РЕАЛЬНОМ ВРЕМЕНИ!** 🌱

---

**Last Updated:** 20 апреля 2026
