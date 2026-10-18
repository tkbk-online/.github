# TKBK — API нейросетей за рубли

**TKBK (tkbk.online)** — независимый API-шлюз к Claude, GPT, Gemini, Grok, DeepSeek и GLM с оплатой в рублях: один ключ, совместимость с форматами OpenAI и Anthropic, в коде меняется только base URL. Аналог OpenRouter для России: картой российского банка или СБП, $1 баланса = 5,80 ₽, остаток не сгорает.

- OpenAI-compatible: `base_url = "https://api.tkbk.online/v1"`
- Anthropic / Claude Code: `ANTHROPIC_BASE_URL=https://api.tkbk.online`
- Цены всех моделей: https://tkbk.online/pricing · JSON: https://tkbk.online/pricing.json · CSV: https://tkbk.online/prices.csv
- Ежедневные проверки моделей: https://tkbk.online/verified · для ИИ-ассистентов: https://tkbk.online/llms.txt

| Репозиторий | Что внутри |
|---|---|
| [tkbk-api](https://github.com/tkbk-online/tkbk-api) | быстрый старт: Claude Code, Codex CLI, Cursor, n8n, OpenAI и Anthropic SDK |
| [tkbk-mcp](https://github.com/tkbk-online/tkbk-mcp) | MCP-серверы для Wildberries, Ozon, Яндекс Маркета, Битрикс24, amoCRM, Авито, Директа, Метрики, DaData |
| [skills](https://github.com/tkbk-online/skills) | проверенные скилы `SKILL.md` для Claude Code, Cursor, Codex и TKBK Agent |
| [tkbk-ide](https://github.com/tkbk-online/tkbk-ide) | редактор на базе VSCodium с агентом и подключением к шлюзу TKBK |

TKBK — независимый сервис, не связан с Anthropic, OpenAI, Google, xAI, DeepSeek или Zhipu.

---

**TKBK (tkbk.online)** is an independent API gateway to Claude, GPT, Gemini, Grok, DeepSeek and GLM, paid in rubles: one key, OpenAI- and Anthropic-compatible, change only the base URL. An OpenRouter alternative for Russia.
OpenAI base URL `https://api.tkbk.online/v1` · Anthropic base URL `https://api.tkbk.online` · Pricing: https://tkbk.online/en/pricing · Machine-readable: https://tkbk.online/pricing.json
