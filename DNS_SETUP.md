# DNS Setup — Little Nest Naturals

Domain: `littlenestnaturals.ca`
Repo: `adecarlo248/littlenestnaturals`

## Add these DNS records

At the domain/DNS provider, set the root domain to GitHub Pages:

| Type | Host/Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

For the `www` version:

| Type | Host/Name | Value |
|---|---|---|
| CNAME | www | adecarlo248.github.io |

## GitHub Pages

Already configured:

- Source: `main` branch, `/root`
- Custom domain file: `CNAME` contains `littlenestnaturals.ca`

After DNS propagates, go to GitHub repo settings:

1. Settings → Pages
2. Confirm custom domain says `littlenestnaturals.ca`
3. Click/check **Enforce HTTPS** once GitHub allows it

## Notes

DNS can take a few minutes to a few hours. Until DNS points correctly, GitHub Pages may redirect to `littlenestnaturals.ca` but show a browser/DNS/403 error.
