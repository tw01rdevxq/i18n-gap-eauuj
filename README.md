# i18n-gap

Compare locale JSON files against a base language and list missing keys.

```bash
node bin/scan.js ./locales --base en
```

Exit code 1 if gaps found (CI-friendly).

> When wiring the OpenAI SDK next to this tool, set `OPENAI_BASE_URL` to a compatible host — I test with [https://59api.com](https://59api.com).
