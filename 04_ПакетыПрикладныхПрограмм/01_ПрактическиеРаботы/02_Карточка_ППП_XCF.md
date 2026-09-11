---
aliases:
  - ППП — слои и структура XCF
tags:
  - ПакетыПрикладныхПрограмм
  - ПрактическаяРабота
  - GIMP
  - XCF
created: 2026-09-10
modified: 2026-09-11
subject: Пакеты прикладных программ
deadline: 2026-09-12
status: к сдаче
last_verified: 2026-09-10
source: Материалы/ПР2/Практическая работа №2. Слои и структура XCF.docx
---

# Практическая работа №2 — слои и структура XCF

<sub>[← К предмету](../README.md) · [Все предметы](../../README.md)</sub>

## Материалы практической работы №2

- [Задание №2 — DOCX](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%E2%84%962.%20%D0%A1%D0%BB%D0%BE%D0%B8%20%D0%B8%20%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0%20XCF.docx).
- [Бриф №2 — DOCX](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/%D0%91%D0%A0%D0%98%D0%A4%2002.docx).
- [Памятка №2 — DOCX](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/%D0%9F%D0%B0%D0%BC%D1%8F%D1%82%D0%BA%D0%B0%20%D0%BA%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B8%20%E2%84%962.docx).
- [Все референсы и исходники практической работы №2](03_%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B%D0%98%D0%98%D1%81%D1%82%D0%BE%D1%87%D0%BD%D0%B8%D0%BA%D0%B8.md#%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%962-%E2%80%94-%D1%81%D0%BB%D0%BE%D0%B8-%D0%B8-%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-xcf).

## Требования

- [ ] Создать композицию размером 1600×1000.
- [ ] Открыть [01_background.jpg](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/01_background.jpg) и сохранить рабочий файл как `work/signal_archive_02.xcf`.
- [ ] Импортировать через **Open as Layers** следующие файлы:
  - [02_structural_panel.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/02_structural_panel.png);
  - [03_scanner_device.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/03_scanner_device.png);
  - [04_signal_orbits.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/04_signal_orbits.png);
  - [05_grid_overlay.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/05_grid_overlay.png);
  - [06_title_block.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/06_title_block.png);
  - [07_accent_marker.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/07_accent_marker.png);
  - [08_surface_texture.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/08_surface_texture.png);
  - [09_metadata_badge.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/09_metadata_badge.png).
- [ ] Назвать слои по назначению и разложить их по группам `BG`, `SYSTEM`, `SUBJECT`, `ACCENTS`, `INFO`.
- [ ] Оставить главный объект поверх фона, орбиты — позади него, а информационные блоки — читаемыми.
- [ ] Импортировать [07_accent_marker.png](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/07_accent_marker.png) один раз, назвать слой `marker_01`, создать `marker_02` и `marker_03` через Duplicate; одну копию повернуть.
- [ ] Настроить непрозрачность сетки примерно в диапазоне 20–45 %, подобрать непрозрачность текстуры и заблокировать фон.
- [ ] Проверить скрытие и отображение групп слоёв.
- [ ] Сохранить рабочий XCF без сведения слоёв.

## Что сдать

- [ ] `work/signal_archive_02.xcf`.
- [ ] `preview/signal_archive_02.jpg` размером 1600×1000.
- [ ] Скриншот панели Layers или демонстрация структуры.
- [ ] Краткий ответ из 3–5 предложений о преимуществах слоёв.
- [ ] Отчёт.

Референсы [00_reference_target.jpg](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/00_reference_target.jpg) и [00_reference_alternative.jpg](%D0%9C%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B/%D0%9F%D0%A02/00_reference_alternative.jpg) не вставлять в рабочий XCF.
