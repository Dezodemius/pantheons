# Пантеоны — боги для D&D

Справочник богов трёх пантеонов для D&D: скандинавский (асы и ваны), славянский и греческий (олимпийцы). По каждому божеству — сфера, характер, символы, культ и готовая игровая раскладка: мировоззрение, домены жреца (Cleric Domains), священный символ, последователи и сюжетные зацепки. Используй этот скилл, когда пользователь просит «опиши бога / богов / пантеон», «скандинавские / славянские / греческие боги», «божество-покровитель для персонажа», «кому молится жрец / паладин», «какой домен жреца», «храм / культ / жречество бога», «божественный квестодатель / гнев / знамение», «придумай религию для региона на основе пантеона». Заточен под D&D: раскладка стыкуется с механикой скилла dnd-master, а мифы и сюжеты с этими богами берёт folklore-myth. Весь вывод на русском.

Скилл в формате [Agent Skills](https://agentskills.io): работает в Claude, Codex, Gemini CLI и других ИИ-агентах, а однофайловая версия — в любом чате.

## Примеры запросов

> Какому славянскому богу может служить жрец домена Бури? Дай обеты и зацепки.

> Придумай культ Гекаты для портового города: храм, жрецы, тайна.

> Божественный квестодатель из скандинавского пантеона для партии 5 уровня.

## Установка

Готовые файлы лежат в [релизах](https://github.com/Dezodemius/pantheons/releases/latest).

| Где пользуетесь | Как подключить |
| --- | --- |
| **claude.ai**, Claude Desktop | Скачать [`pantheons.zip`](https://github.com/Dezodemius/pantheons/releases/latest/download/pantheons.zip) → Настройки → Возможности → Skills → загрузить. В Desktop можно открыть [`pantheons.skill`](https://github.com/Dezodemius/pantheons/releases/latest/download/pantheons.skill) двойным кликом |
| **Claude Code** | `/plugin marketplace add Dezodemius/agent-skills`, затем `/plugin install pantheons@dezodemius-skills` |
| **Codex, Gemini CLI, Cursor, GitHub Copilot, OpenCode** и другие агенты | `npx skills add Dezodemius/pantheons` |
| **ChatGPT, Gemini, DeepSeek, Qwen, Grok, Алиса, GigaChat** и другие чаты | Скачать [`pantheons.prompt.md`](https://github.com/Dezodemius/pantheons/releases/latest/download/pantheons.prompt.md) и приложить в начале чата или вставить в инструкции проекта / GPT / Gem |

Подробно по каждой платформе — в [каталоге](https://github.com/Dezodemius/agent-skills#установка).

## Связка D&D-скиллов

Скиллы работают и по отдельности, и цепочкой: сюжет → механика → книга.

| Скилл | Роль |
| --- | --- |
| [folklore-myth](https://github.com/Dezodemius/folklore-myth) | сюжетная основа из мифов и фольклора |
| [writers-council](https://github.com/Dezodemius/writers-council) | консилиум писателей разворачивает тему в сюжет |
| [pantheons](https://github.com/Dezodemius/pantheons) | боги, культы, домены жрецов |
| [dnd-master](https://github.com/Dezodemius/dnd-master) | правила 5e, баланс, NPC, локации |
| [dnd-module](https://github.com/Dezodemius/dnd-module) | вёрстка в книгу-модуль, наполнение карты |

Полный каталог: [Dezodemius/agent-skills](https://github.com/Dezodemius/agent-skills).

## Выпуск релиза

Релиз собирается автоматически по тегу из четырёх чисел на коммите из `main`:

```bash
git tag 1.0.0.0 && git push origin 1.0.0.0
```

Общий CD и проверки живут в [Dezodemius/agent-skills](https://github.com/Dezodemius/agent-skills).

## Лицензия

Apache License 2.0 — см. [LICENSE](LICENSE) и [NOTICE](NOTICE).
