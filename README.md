Simple `index.html` landing page and catch-all `404.html` page hosted at https://lewesrowingclub.github.io to redirect https://lewesrowingclub.co.uk and https://www.lewesrowingclub.co.uk URLs to https://membermojo.co.uk/lewesrowingclub
Currently, `window.location.pathname`, `window.location.search` and `window.location.hash` are erased, but in a future revision we could route-map to actual pages in the MemberMojo website.
Both `lewesrowingclub.co.uk` apex and `www` subdomain are configured at IONOS (1and1) via `A`/IPv4, `AAAA`/IPv6, and `CNAME` DNS records that point to `lewesrowingclub.github.io`.
GitHub provides free LetsEncrypt automatic SSL certificate renewal with enforced secure HTTPS.
See the `dig` commands in the `dns-check.md` file.
