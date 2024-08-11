## Dev

### Pre-requisites

1. Create a Supabase account

2. Set up Discord OAuth

https://discord.com/developers/applications

Make sure to:

    - Set AUTH_DISCORD_ID and AUTH_DISCORD_SECRET in .env file
    - Add `http://localhost:3000/api/auth/callback/discord` to the OAuth2 redirects in Discord

3. [NVM (Node Version Manager)](https://github.com/nvm-sh/nvm)

```
nvm use
pnpm store prune
pnpm install
pnpm lint
pnpm build
```

## Connecting directly to DB

```
psql -h aws-0-ap-southeast-2.pooler.supabase.com -U USERNAME -d postgres -p 5432
```

## Troubleshooting

# error: todo: handle www-authenticate challenges as needed

Cause:
Fix:
