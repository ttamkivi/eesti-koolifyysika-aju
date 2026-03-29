# Kuidas panustada — Eesti Füüsika Aju

Tere tulemast! See repositoorium on **Eesti koolide füüsikaõppe ühine teadmistebaas**. Iga õpetaja, kes lisab siia materjali, aitab kõigi Eesti füüsikaõpilaste ja -õpetajate tööd paremaks muuta.

---

## Mida saab panustada?

- **Teooria selgitused** — teema selgitus oma sõnadega, näidetega
- **Harjutusülesanded** — eriti lahendatud näited koos kommentaaridega
- **Väärarusaamad** — levinud vead, mida oled klassis näinud
- **Praktiliste tööde juhendid** — katse kirjeldused, tulemuste analüüs
- **Parandused** — vead, ebatäpsused, aegunud info

---

## Repositooriumi struktuur

```
eesti-fuusika-aju/
├── oppekava/          ← Ametlikud kursuse kaardid (F1–F15, põhikool)
├── teemad/            ← Sisuline materjal teemade kaupa
│   ├── kinemaatika/
│   │   ├── teooria.md
│   │   ├── ulesanded.md
│   │   ├── vaararusaamad.md
│   │   └── praktilised.md
│   ├── dunaamika/
│   └── ...
├── opetajate-arhiiv/  ← Õpetajate isiklikud materjalid
│   └── [sinu-nimi]/
└── eksamid/           ← Varasemad eksamiküsimused ja näidisvastused
```

---

## Kuidas materjali lisada?

### Variant A — Lihtsaim (GitHub veebis)

1. Mine repositooriumis õigesse kausta
2. Kliki failil ja seejärel pliiatsiikooni (✏️ Edit)
3. Tee muudatused
4. Kirjelda muudatus väljal "Commit changes"
5. Kliki "Propose changes"

See loob automaatselt **pull request**, mida admin vaatab üle.

### Variant B — Uus fail (GitHub veebis)

1. Mine õigesse kausta
2. Kliki "Add file" → "Create new file"
3. Nimeta fail (nt `kinemaatika-vaararusaamad.md`)
4. Kirjuta sisu
5. Kliki "Propose new file"

### Variant C — Git (edasijõudnutele)

```bash
git clone https://github.com/[repo-aadress]
git checkout -b minu-lisandus
# tee muudatused
git add .
git commit -m "Lisa: kinemaatika näidisülesanded"
git push origin minu-lisandus
# ava pull request GitHubis
```

---

## Failide vorming

Kõik failid on **Markdown** (`.md`) formaadis. Markdown on lihtne tekstivormindus.

### Põhivõtted

```markdown
# Suur pealkiri
## Väiksem pealkiri

**Paks tekst**
*Kaldkiri*

- Loendi punkt
- Teine punkt

1. Numbered list
2. Teine punkt
```

### LaTeX valemid

Valemid kirjutatakse LaTeX süntaksis:

```markdown
Rida sees: $F = ma$

Eraldi real:
$$v = v_0 + at$$
```

Renderdub kujul: $v = v_0 + at$

### Tabelid

```markdown
| Suurus | Sümbol | Ühik |
|--------|--------|------|
| Kiirus | $v$    | m/s  |
| Mass   | $m$    | kg   |
```

---

## Faili struktuur — soovituslik mall

Uue teema teoreetilise faili jaoks:

```markdown
# Teema nimi — Teooria

> **Kursus:** F1 | **Klass:** 10 | **Eeldused:** —

## 1. Mida see teema uurib?
[Lühike sissejuhatus]

## 2. Põhimõisted
[Definitsioonid koos näidetega]

## 3. Põhiseosed
[Valemid LaTeX-is]

## 4. Näidisülesanne
[Lahendatud näide koos kommentaaridega]

## Levinud väärarusaamad
[Mida õpilased sageli valesti mõistavad]

## Seotud materjalid
[Lingid seotud failidele]
```

---

## Kvaliteedipõhimõtted

✅ **Hea panustus:**
- Kirjutatud õpilasele arusaadavas eesti keeles
- Sisaldab konkreetseid näiteid
- Valemid on LaTeX-is
- Viitab, millisele kursusele (F1–F15) materjal kuulub

❌ **Väldi:**
- Kopeeri-kleebi ilma allikale viitamata
- Liiga akadeemiline keel põhikooli materjalides
- Valemid pildina (kasuta alati LaTeX-i)

---

## Õpetajate arhiiv

Kui soovid jagada oma isiklikke materjale (tunnikonspektid, ülesannete kogumikud, selgitused), lisa need kausta:

```
opetajate-arhiiv/[sinu-nimi]/
```

Näiteks: `opetajate-arhiiv/jaan-tamm/elektriahelate-selgitus.md`

Siin pole rangeid formaadi nõudeid — jaga seda, mis sinu klassis toimib.

---

## Küsimused?

Ava **Issue** GitHubis (sakk "Issues" → "New issue") ja kirjelda oma küsimust või ettepanekut.

---

*Aitäh, et panustad Eesti füüsikaõppe paremaks muutmisse!*
