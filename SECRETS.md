## Secrets

```bash

# For uploading dev secrets
npx wrangler secret bulk --env "" .dev.vars
# For uploading prod secrets
npx wrangler secret bulk --env "production" .dev.vars.production

```