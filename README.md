# 📅 Интерактивная диаграмма Ганта · Interactive Gantt Chart

[🇷🇺 Русский](#русский) · [🇬🇧 English](#english)

---

## Русский

Интерактивная диаграмма Ганта — полностью автономный инструмент для планирования проектов на временной шкале. Реализован в виде одного HTML-файла: не требует установки, сервера или подключения к интернету (кроме экспорта в PDF).

### Возможности

- **Задачи** — добавление, редактирование, удаление; перетаскивание по шкале, изменение длительности за правый край блока
- **Разделы** — цветные группы задач; произвольное количество, 10 цветов на выбор
- **Зависимости** — визуальные стрелки между задачами с каскадным сдвигом при перемещении
- **Шкала времени** — настройка количества недель, масштаба, даты начала с автоматическим расчётом дат всех недель
- **Сортировка строк** — перетаскивание задач вверх/вниз
- **Темы** — тёмная и светлая цветовые схемы
- **Экспорт в PDF** — скриншот диаграммы со стрелками и датами
- **Сохранение** — выгрузка в HTML с сохранением всех данных; файл можно передать любому пользователю

### Как использовать

1. Скачайте файл `timeline.html`
2. Откройте в браузере (Chrome, Edge или Firefox версии 90+)
3. Начните планировать

### Стек

Чистый HTML + CSS + JavaScript, без фреймворков.  
Экспорт в PDF: [html2canvas](https://html2canvas.hertzen.com/) + [jsPDF](https://github.com/parallax/jsPDF) (загружаются с CDN при экспорте).

### Подробная информация по эксплуатации находится в руководстве

---

## English

An interactive Gantt chart tool built as a single self-contained HTML file. No installation, no server, no backend — just open in a browser and start planning.

### Features

- **Tasks** — add, edit, delete; drag to reposition, resize by pulling the right edge
- **Sections** — color-coded task groups; unlimited count, 10 colors available
- **Dependencies** — visual arrows between tasks with automatic cascade shifting
- **Timeline** — configurable week count, zoom level, start date with auto-calculated week ranges
- **Row reordering** — drag rows up and down
- **Themes** — dark and light color schemes
- **PDF export** — full screenshot including arrows and dates
- **Portable saves** — export as HTML with all data embedded; share with anyone, no setup needed

### How to use

1. Download `timeline.html`
2. Open in a browser (Chrome, Edge or Firefox 90+)
3. Start planning

### Stack

Plain HTML + CSS + JavaScript. No frameworks.  
PDF export via [html2canvas](https://html2canvas.hertzen.com/) + [jsPDF](https://github.com/parallax/jsPDF) (loaded from CDN on export).

---

*Разработано RikaNV совместно с [Claude AI](https://claude.ai) (Anthropic) · Developed by RikaNV with [Claude AI](https://claude.ai) (Anthropic)*
