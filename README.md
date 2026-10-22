# vurbag.com

Countdown to the World of Warcraft: Forever launch (4 November 2026, 15:00 PST = 23:00 UTC = 00:00 CET on 5 November), with Blizzard's WoW lofi mix playing. Home of Vurbag Smaldorn, Dwarf Warrior.

It's a single static page (`index.html`) with no build step. Hosted on GitHub Pages; the `CNAME` file points it at vurbag.com.

## Going live

1. **Repo visibility:** GitHub Pages on a private repo needs a paid plan. Either make this repo public or use GitHub Pro.
2. **Enable Pages:** Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. **GoDaddy DNS for vurbag.com:**
   - `A` `@` → `185.199.108.153`
   - `A` `@` → `185.199.109.153`
   - `A` `@` → `185.199.110.153`
   - `A` `@` → `185.199.111.153`
   - `CNAME` `www` → `burcturkoglu.github.io`
   - Delete GoDaddy's default "Parked" `A` record and any domain forwarding.
4. Back in Settings → Pages, set the custom domain to `vurbag.com` and tick **Enforce HTTPS** once the certificate is issued (can take up to an hour after DNS resolves).
