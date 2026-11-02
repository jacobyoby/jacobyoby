# Jacobrakai Foundation

Free, public-interest software for court self-help, municipal public records, food safety, and internet security. Jacobrakai Foundation is an IRS 501(c)(3) public charity (EIN 33-3382083).

<img src="assets/workshop.webp" alt="Illustrated workbench: court papers and a red stamp, a terminal wired to a honey jar, a purple handheld console, and a sleeping black dog." width="1774" height="887" />

## Products

**[Forma Pauperis](https://formapauperis.com/)** — Find and complete New Jersey court forms. The fee-waiver application is free to complete, with no account.

**[Sic Semper Errata](https://sicsempererrata.com/)** — Records-request software for municipal clerks, from intake through review and release. Try the [Bellwether demo](https://demo.sicsempererrata.com/) with sample records. [Municipal deployment is in development](https://sicsempererrata.com/editions/).

**[Beanstalk](https://jacobrakaifoundation.github.io/beanstalk/)** — Search FDA and USDA food recall records by product, company, or hazard, with links to the original agency records. Free, no account. iPhone app in development.

## Security

**eMudhra CA compromise** — Eight eMudhra intermediate CA private keys were found to be trivially recoverable ([Mozilla Bug 2083449](https://bugzilla.mozilla.org/show_bug.cgi?id=2083449)). [emsign-g3-distrust](https://github.com/jacobyoby/emsign-g3-distrust) and [4thehardway](https://github.com/jacobrakaiFoundation/4thehardway) find the affected certificates and block them in trust stores and on the network. Our report that eMudhra's revocation servers blocked common HTTP clients such as curl and Wget is [Mozilla Bug 2085612](https://bugzilla.mozilla.org/show_bug.cgi?id=2085612).

**[honeypot-blocklist](https://github.com/jacobyoby/honeypot-blocklist)** — A honeypot-confirmed IP blocklist, published as a [free feed](https://jacobrakai.org/feed/) in formats ready for firewalls and threat-intel tools.

## Work with us

Municipalities, legal-aid organizations, and funders: email [jacob@jacobrakai.org](mailto:jacob@jacobrakai.org).

[jacobrakai.org](https://jacobrakai.org) · [Foundation on GitHub](https://github.com/jacobrakaiFoundation) · [Donate](https://donate.stripe.com/eVq4gy97DanS9h60phfrW00) · [All repositories](https://github.com/jacobyoby?tab=repositories)
