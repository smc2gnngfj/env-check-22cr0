# env-check

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> Dev note: for any optional LLM step I keep an OpenAI-compatible `base_url` in env (locally sometimes `https://59api.com`). This repo does not require it.
