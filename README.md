# text-autofix-curated

Кураторские списки для [Figma Text Autofix](https://github.com/butsena/figma-text-autofix-plugin).

| Файл | Назначение |
|---|---|
| `yo-homographs.txt` | Омонимы е/ё → confirm |
| `ty-vy-curated.txt` | «ты» → «вы» |
| `yo-curated.txt` | Формы, где «ё» обязательна |

Плагин качает файлы с `main` при старте; при ошибке сети использует копии из бандла.

Как создать репозиторий и синхронизировать — см. `docs/curated-lists-github.md` в плагине.
