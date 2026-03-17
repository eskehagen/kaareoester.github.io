# 📝 Sådan tilføjer du et nyt indlæg — trin for trin

Denne guide er skrevet til dig, der ikke er vant til at arbejde med kode.
Det eneste du skal bruge er en computer med internetadgang og en gratis GitHub-konto.

---

## Hvad er GitHub?

GitHub er et website, hvor din hjemmesides filer er gemt. Når du gemmer en ny fil dér,
opdateres din hjemmeside automatisk inden for et par minutter.

Du behøver **ikke** forstå kode. Du skriver bare din tekst i et simpelt format.

---

## Trin 1 — Log ind på GitHub

1. Gå til **https://github.com** i din browser
2. Log ind med din bruger og adgangskode
3. Gå til dit hjemmeside-repository (f.eks. `github.com/kaareoester/kaareoester.github.io`)

---

## Trin 2 — Gå til mappen `_posts`

1. Klik på mappen **`_posts`** i listen over filer
2. Her kan du se alle eksisterende indlæg som filer

---

## Trin 3 — Opret en ny fil

1. Klik på knappen **"Add file"** (øverst til højre)
2. Vælg **"Create new file"**

---

## Trin 4 — Navngiv filen korrekt

Filnavnet skal følge dette mønster:

```
ÅÅÅÅ-MM-DD-titel-paa-indlaeg.md
```

**Eksempler:**
- `2026-04-15-rejse-til-marokko.md`
- `2026-05-01-ny-bog-udgivet.md`
- `2026-03-10-projekt-om-klimaet.md`

> ⚠️ Vigtigt: Brug kun bogstaver, tal og bindestreger. Ingen æ, ø, å i filnavnet.

---

## Trin 5 — Skriv indlæggets indhold

Kopier denne skabelon ind i tekstfeltet og udfyld den:

```
---
layout: post
title: "Her skriver du overskriften på dit indlæg"
date: 2026-04-15
categories:
  - "Rejser"
---

Her begynder din tekst. Du kan bare skrive almindelig tekst.

Du kan lave et nyt afsnit ved at hoppe en linje over.

## En underoverskrift

Du kan bruge ## til at lave underoverskrifter.

**Fed tekst** laves med to stjerner på hver side.

*Kursiv tekst* laves med en stjerne på hver side.

- Punkt 1 i en liste
- Punkt 2 i en liste
- Punkt 3 i en liste
```

---

## Kategorier du kan vælge

Brug én eller flere af disse kategorier:

| Kategori | Bruges til |
|----------|-----------|
| `Rejser` | Rejsebeskrivelser og oplevelser |
| `Projekter` | Faglige projekter og samarbejder |
| `Udgivelser` | Nye bøger og materialer |
| `Bøger` | Specifikke bøger (brug sammen med Udgivelser) |
| `Danmark` | Steder og rejser i Danmark |
| `Verden` | Rejser udenfor Danmark |
| `Arktis` | Alt om Arktis, Grønland, Svalbard |

Vil du bruge **flere kategorier**, skriver du dem sådan:

```
categories:
  - "Rejser"
  - "Verden"
```

---

## Tilføj et billede til indlægget

**Metode 1 — Et billede fra internettet:**

```
![Billedtekst](https://www.eksempel.dk/sti/til/billede.jpg)
```

**Metode 2 — Upload dit eget billede:**

1. Klik på **"Code"** (tilbage til forsiden af dit repository)
2. Gå til mappen `assets` → `images`
3. Klik **"Add file"** → **"Upload files"**
4. Træk dit billede ind eller klik for at vælge det
5. Klik **"Commit changes"**

Derefter bruger du billedet i din tekst sådan:

```
![Billedbeskrivelse](/assets/images/mit-billede.jpg)
```

Du kan også tilføje et **forsidebillede** til indlægget (vises på forsiden og øverst i indlægget).
Det gør du ved at tilføje en linje i toppen af filen (i den del der er mellem `---`):

```
---
layout: post
title: "Min rejse"
date: 2026-04-15
categories:
  - "Rejser"
image: "/assets/images/mit-forsidebillede.jpg"
---
```

---

## Trin 6 — Gem indlægget

1. Rul ned til bunden af siden
2. Du ser en boks med teksten **"Commit new file"**
3. I det første felt kan du skrive en kort beskrivelse, f.eks. `Nyt indlæg om Marokko`
   (eller bare lade det stå som det er)
4. Klik på den grønne knap **"Commit new file"**

✅ **Færdig!** Din hjemmeside opdateres automatisk inden for 1-3 minutter.

---

## Ret i et eksisterende indlæg

1. Gå til mappen `_posts`
2. Klik på filen du vil rette
3. Klik på **blyantsikonet** (✏️) øverst til højre
4. Foretag dine rettelser
5. Klik **"Commit changes"** og derefter **"Commit changes"** igen

---

## Slet et indlæg

1. Gå til mappen `_posts`
2. Klik på filen du vil slette
3. Klik på **skraldespandsikonet** (🗑️) øverst til højre
4. Bekræft ved at klikke **"Commit changes"**

---

## Problemer?

Hvis noget ikke virker, eller hjemmesiden ikke opdateres:

1. Gå til fanen **"Actions"** i dit repository
2. Her kan du se om der er fejl i byggeprocessen (der vises en rød kryds hvis noget gik galt)
3. Tjek at dit filnavn følger mønsteret `ÅÅÅÅ-MM-DD-titel.md`
4. Tjek at du har `---` linjer øverst og nederst i frontmatter-blokken

Kontakt din søn/datter for hjælp — de kender opsætningen 😊
