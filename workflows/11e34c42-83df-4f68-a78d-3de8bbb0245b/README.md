# cc-11e34c42-83df-4f68-a78d-3de8bbb0245b — exported from N2C

This is a standalone Wrangler project. N2C is not involved from here on — the
compiled script in `src/index.ts` is exactly what N2C would deploy for this workflow.

## Deploy

1. `npx wrangler login` (if you haven't already).
2. Create each KV namespace referenced in `wrangler.jsonc` and replace its `id` placeholder: `npx wrangler kv namespace create <binding>`.
3. `npx wrangler deploy`.

## Required secrets

- none
