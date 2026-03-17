# kaareoester.github.io

Hjemmeside for **Kaare Øster**, fagforfatter.

Bygget med [Jekyll](https://jekyllrb.com/) og hostet gratis via [GitHub Pages](https://pages.github.com/).

## 🌐 Live hjemmeside

→ **https://kaareoester.github.io** (eller dit eget domæne når det er opsat)

## 📝 Tilføj et nyt indlæg

Se den detaljerede guide: [VEJLEDNING-NYT-INDLAEG.md](VEJLEDNING-NYT-INDLAEG.md)

**Kort version:**
1. Gå til mappen `_posts/`
2. Klik "Add file" → "Create new file"
3. Navngiv filen `ÅÅÅÅ-MM-DD-titel.md` (f.eks. `2026-04-15-rejse-til-marokko.md`)
4. Brug skabelonen nedenfor
5. Klik "Commit new file" — hjemmesiden opdateres automatisk!

**Skabelon til nyt indlæg:**
```
---
layout: post
title: "Din overskrift her"
date: 2026-04-15
categories:
  - "Rejser"
---

Din tekst her...
```

## 🗂️ Kategorier

- `Rejser` — Rejsebeskrivelser
- `Projekter` — Faglige projekter  
- `Udgivelser` — Bøger og materialer
- `Bøger` — Specifikke bøger
- `Danmark` — Rejser i Danmark
- `Verden` — Udenlandske rejser
- `Arktis` — Arktiske emner

## 🖼️ Tilføj billeder

Upload billeder til `assets/images/` og brug dem i teksten:
```
![Billedtekst](/assets/images/dit-billede.jpg)
```

## 🏗️ Teknisk

- **Generator:** Jekyll (statisk hjemmeside)
- **Hosting:** GitHub Pages (gratis)
- **Deployment:** Automatisk via GitHub Actions når du pusher til `main`
- **Domæne:** Konfigurér dit eget domæne i `_config.yml` og GitHub Pages indstillinger
