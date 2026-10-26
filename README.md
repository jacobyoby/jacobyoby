# jacobrakai

I'm Jacob. I do security research and build public-interest software.

When the private keys of eight eMudhra intermediate CAs turned out to be trivially recoverable in October 2026, I published tools to find and block those certificates, and my report on eMudhra's revocation servers became [its own Mozilla incident bug](https://bugzilla.mozilla.org/show_bug.cgi?id=2085612). I also build free tools for people doing their own court paperwork, for clerks handling public-records requests, and for anyone checking a food recall.

**Open to new roles.** Email [jacob@jacobrakai.org](mailto:jacob@jacobrakai.org) or message me on [LinkedIn](https://linkedin.com/in/jacobjacobdurham). I write Python, TypeScript, Go, Swift, Kotlin, and PowerShell.

<img src="assets/workshop.webp" alt="Illustrated workbench: court papers and a red stamp, a terminal wired to a honey jar, a purple handheld console, and a sleeping black dog." width="1774" height="887" />

## Security research

**eMudhra CA compromise** — Eight eMudhra intermediate CA private keys turned out to be trivially recoverable ([Mozilla Bug 2083449](https://bugzilla.mozilla.org/show_bug.cgi?id=2083449)). [emsign-g3-distrust](https://github.com/jacobyoby/emsign-g3-distrust) and [4thehardway](https://github.com/jacobrakaiFoundation/4thehardway) find the affected certificates on a machine and block them in trust stores and on the network. I also found that eMudhra's revocation servers blocked common HTTP clients such as curl and Wget; that finding is now [Mozilla Bug 2085612](https://bugzilla.mozilla.org/show_bug.cgi?id=2085612).

**[honeypot-blocklist](https://github.com/jacobyoby/honeypot-blocklist)** — I run a honeypot and publish a [blocklist feed](https://jacobrakai.org/feed/) from the attack traffic it records. The repository includes the data formats and validation tools.

## Court forms and public records

**[Forma Pauperis](https://formapauperis.com/)** — I build tools for finding and working through New Jersey court forms. The fee-waiver application is free to complete without an account.

**[Sic Semper Errata](https://sicsempererrata.com/)** — I'm developing software for municipal clerks to handle records requests from intake through review and release. The [Bellwether demo](https://demo.sicsempererrata.com/) uses sample records. [Municipal deployment is still in development](https://sicsempererrata.com/editions/).

## Food recalls

**[Beanstalk](https://jacobrakaifoundation.github.io/beanstalk/)** — I build a free web app for searching FDA and USDA food recall records by product, company, or hazard, with links to the original agency records. No account required. The iPhone app is in development.

## Other work

**[mewtoo](https://github.com/jacobyoby/mewtoo)** — I connect a language model to a Game Boy emulator so it can play Pokémon Red. The code handles game state, controls, and model calls.

[jacobrakai.org](https://jacobrakai.org) · [Jacobrakai Foundation](https://github.com/jacobrakaiFoundation) (IRS 501(c)(3) public charity, EIN 33-3382083, effective Feb 11, 2025) · [Donate](https://donate.stripe.com/eVq4gy97DanS9h60phfrW00) · [More repositories](https://github.com/jacobyoby?tab=repositories)
