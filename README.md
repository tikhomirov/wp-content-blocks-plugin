# WordPress Content Blocks (`wp-content-blocks-plugin`)

![WordPress Plugin](https://img.shields.io/badge/WordPress-5.0%2B-blue.svg)
![PHP Support](https://img.shields.io/badge/PHP-7.4%20%7C%208.0%20%7C%208.1%20%7C%208.2%20%7C%208.3-777BB4.svg)
![License](https://img.shields.io/badge/License-GPLv2-green.svg)

Легкий WordPress плагин для создания многократных контентных блоков (Repeatable Content Blocks) и их вывода через шорткоды или виджеты.

---

## 🚀 Возможности

- 🧩 **Пользовательский тип записей:** Создание и удобное хранение блоков текста, HTML или медиа в админ-панели.
- 📌 **Шорткод `[content_block id="..."]`:** Быстрая вставка блока в любую запись, страницу или конструктор.
- 🧱 **Встроенный виджет:** Отображение сохраненных блоков в любых областях виджетов темы.
- 🌐 **Локализация:** Полная поддержка русского языка (`.mo`, `.po`, `.l10n.php`).

---

## 📥 Установка

### Через Composer (рекомендуется)
```bash
composer require tikhomirov/wp-content-blocks-plugin
```

### Вручную
1. Скачайте ZIP-архив репозитория.
2. Распакуйте в директорию `/wp-content/plugins/wp-content-blocks-plugin/`.
3. Активируйте плагин в админ-панели **Плагины → Установленные**.

---

## 💻 Использование

### Использование через шорткод
```html
[content_block id="123"]
[content_block slug="header-banner"]
```

### Вывод в PHP шаблоне темы
```php
<?php echo do_shortcode('[content_block id="123"]'); ?>
```

---

## 🛠️ Требования

- **WordPress:** 5.0 или выше
- **PHP:** 7.4, 8.0, 8.1, 8.2, 8.3
