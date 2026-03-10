# friendbar site (buddybar.app)

## Deployment

This site is hosted on **Cloudflare Pages** but is NOT connected to Git auto-deploy.
After pushing to `main`, you must also manually deploy:

```
npx wrangler pages deploy . --project-name=friendbar-site
```

Always do both: `git push` then `wrangler pages deploy`.
