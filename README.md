# American Wireless Website

Website for American Wireless, a phone repair shop in Columbia, TN.

**Live Site:** https://americanwirelesstn.com

---

## Services & Logins Reference

| Service | Purpose | URL | What It Does |
|---------|---------|-----|--------------|
| **Cloudflare** | Hosting & DNS | https://dash.cloudflare.com | Hosts the website, manages domain DNS, provides SSL/HTTPS |
| **GitHub** | Code Repository | https://github.com/American-Wireless/american-wireless-website | Stores all website code; push changes here to trigger redeployment |
| **Formspree** | Contact Form | https://formspree.io | Receives contact form submissions and emails them to wirelessdimention@hotmail.com |
| **Namecheap** | Domain Registrar | https://www.namecheap.com | Where the domain americanwirelesstn.com was purchased (nameservers point to Cloudflare) |

---

## How to Make Updates

### Edit Website Content

1. Edit files in this repository (locally or on GitHub)
2. Commit and push changes to the `main` branch
3. Cloudflare automatically redeploys within 1-2 minutes

### Key Files

| File | What It Controls |
|------|------------------|
| `index.html` | All website content (text, sections, links) |
| `styles.css` | Colors, fonts, layout, responsive design |
| `script.js` | Mobile menu, animations, form behavior |
| `images/storefront.png` | Storefront photo |

---

## Common Tasks

### Change Business Hours or Phone Number
Edit `index.html` - search for the current hours/phone and replace

### Update Contact Form Email
1. Log in to https://formspree.io
2. Go to your form settings
3. Change the email address

### Add Facebook Link
In `index.html`, find the footer section and replace `href="#"` in the Facebook link with your Facebook page URL. Also remove the `disabled` class.

### Check Contact Form Submissions
Log in to https://formspree.io to see all form submissions

---

## DNS Configuration

The domain uses Cloudflare nameservers:
- `fred.ns.cloudflare.com`
- `mary.ns.cloudflare.com`

Custom domains configured:
- `americanwirelesstn.com` (root)
- `www.americanwirelesstn.com`

---

## Support

- **Cloudflare Issues:** https://dash.cloudflare.com → Support
- **Formspree Issues:** https://formspree.io/help
- **Domain Issues:** https://www.namecheap.com → Support

---

## Created

November 2024
