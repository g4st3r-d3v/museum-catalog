# Museum Catalog

Веб-приложение на Django для ведения каталога музея. Хранит и отображает информацию об участниках, местах, воинских званиях, фото и видеоматериалах.

## Стек

- **Django** + SQLite
- Модели: `Combatants`, `Ranks`, `Places`, `Pictures`, `Videos`
- Шаблоны, статика, медиафайлы

## Запуск

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
