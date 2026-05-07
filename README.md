# Little Nest Naturals

Premium landing page for Little Nest Naturals — natural mom and baby care products.

## Live Domain

- Primary domain: `littlenestnaturals.ca`
- GitHub Pages repo: `adecarlo248/littlenestnaturals`

## Links

- Order form: https://docs.google.com/forms/d/e/1FAIpQLSctdXZSxY2DPIWMLJX3ANXUCUsZQQMwKCbKN-7fo7uGNbxyfA/viewform?usp=sharing&ouid=110825510580070357305
- Review form: https://docs.google.com/forms/d/e/1FAIpQLSd_B7pQP1IS-LvNlzsoHUNELaQV_y2HYIU-2xKqGPuRFKsprA/viewform?usp=dialog

## DNS Setup for GitHub Pages

At the DNS provider for `littlenestnaturals.ca`, add these records:

### Apex/root domain

Create four `A` records:

| Type | Name/Host | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

### www subdomain

Create one `CNAME` record:

| Type | Name/Host | Value |
|---|---|---|
| CNAME | www | adecarlo248.github.io |

## GitHub Pages Settings

In GitHub:

1. Open repo: `adecarlo248/littlenestnaturals`
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: **main**
5. Folder: **/ root**
6. Custom domain: `littlenestnaturals.ca`
7. Enable **Enforce HTTPS** once DNS verifies

The `CNAME` file is already included in this repo.
