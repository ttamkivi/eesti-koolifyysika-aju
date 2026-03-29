# Kinemaatika — Teooria

> **Kursus:** F1 | **Klass:** 10 | **Eeldused:** —

---

## 1. Mida kinemaatika uurib?

Kinemaatika kirjeldab keha liikumist ilma liikumise põhjuseid uurimata. Me kirjeldame **kus** keha on ja **kuidas** ta liigub — mitte **miks**.

**Mehaanika põhiülesanne:** määrata keha koordinaadid igal ajahetkel, kui on teada algtingimused.

---

## 2. Põhimõisted

### Punktmass
Mudel, kus kehale omistatakse ainult mass, mitte mõõtmed. Kasutatakse siis, kui keha mõõtmed on liikumise ulatusega võrreldes tühised.

*Näide: auto teel Tallinnast Tartusse — auto on punktmass. Auto parkimisel — ei ole.*

### Taustsüsteem
Koordinaatsüsteem + taustkeha + kell. Liikumine on alati suhteline — kirjeldatakse kindla taustsüsteemi suhtes.

### Teepikkus vs nihe

| | Teepikkus $s$ | Nihe $\vec{s}$ |
|---|---|---|
| **Tüüp** | Skalaarne suurus | Vektorialne suurus |
| **Tähendus** | Läbitud tee kogupikkus | Sirgjoon algpunktist lõpp-punkti |
| **Alati** | $s \geq 0$ | Võib olla negatiivne |

*Näide: lähed kooli (500 m) ja tuled tagasi. Teepikkus = 1000 m. Nihe = 0 m.*

---

## 3. Kiirus

### Keskmine kiirus

$$\bar{v} = \frac{s}{t}$$

Kirjeldab keskmist liikumiskiirust kogu teekonna jooksul.

### Hetkkiirus

$$v_x = \frac{\Delta x}{\Delta t} \quad \text{(kui } \Delta t \to 0\text{)}$$

Kiirus konkreetsel ajahetkel. Kiiruse suund on alati **liikumissuunas** (puutuja trajektoorile).

### Ühik
$$[v] = \frac{\text{m}}{\text{s}} = \text{m/s}$$

Teisendus: $1 \frac{\text{m}}{\text{s}} = 3{,}6 \frac{\text{km}}{\text{h}}$

---

## 4. Ühtlane sirgjooneline liikumine

Kiirus on **konstantne**: $v = \text{const}$, kiirendus $a = 0$.

### Liikumisvõrrand

$$x = x_0 + v_x \cdot t$$

### Graafikud

**$x$-$t$ graafik** (asukoht ajast): sirgjoon, kalle = kiirus

**$v$-$t$ graafik** (kiirus ajast): horisontaalne sirgjoon

> 💡 **Oluline:** Teepikkus = $v$-$t$ graafiku alune pindala

---

## 5. Kiirendus

Kiirendus kirjeldab kiiruse muutumist ajas.

$$\vec{a} = \frac{\vec{v} - \vec{v_0}}{\Delta t} = \frac{\Delta \vec{v}}{\Delta t}$$

### Ühik
$$[a] = \frac{\text{m}}{\text{s}^2}$$

**Kiirenev liikumine:** $a$ ja $v$ on sama suunaga  
**Aeglustuv liikumine:** $a$ ja $v$ on vastassuunalised

---

## 6. Ühtlaselt muutuv sirgjooneline liikumine

Kiirendus on **konstantne**: $a = \text{const} \neq 0$.

### Põhiseosed

$$v_x = v_{0x} + a_x t$$

$$x = x_0 + v_{0x}t + \frac{a_x t^2}{2}$$

$$s_x = v_{0x}t + \frac{a_x t^2}{2}$$

$$a_x = \frac{v_x^2 - v_{0x}^2}{2s_x}$$

### $v$-$t$ graafik
Sirgjoon, mille:
- **kalle** = kiirendus $a$
- **alune pindala** = läbitud teepikkus $s$

---

## 7. Vaba langemine

Erijuht ühtlaselt muutuvast liikumisest, kus $a = g = 9{,}8 \approx 10 \text{ m/s}^2$ (suunaga alla).

$$v = g \cdot t$$

$$h = \frac{g \cdot t^2}{2}$$

$$v^2 = 2gh$$

---

## 8. Kiiruste liitmine (klassikaline)

Kui keha liigub liikuva aluse peal:

$$\vec{v} = \vec{v_1} + \vec{v_2}$$

*Näide: inimene kõnnib laeval. Inimese kiirus mere suhtes = inimese kiirus laeva suhtes + laeva kiirus mere suhtes.*

---

## Levinud väärarusaamad

| Väärarusaam | Tegelikkus |
|---|---|
| "Suurem kiirus = suurem kiirendus" | Ei. Kiirendus sõltub kiiruse **muutusest**, mitte kiiruse suurusest |
| "Aeglustumisel on kiirendus null" | Ei. Aeglustumisel on kiirendus nullist erinev, kuid vastassuunaline liikumisega |
| "Nihe = teepikkus" | Ainult siis, kui liigutakse ühes suunas sirgjooneliselt |
| "Vaba langemise kiirendus sõltub massist" | Ei. Galileo näitas, et $g$ on kõigile kehadele sama (õhutakistuseta) |

---

## Näidisülesanne

**Ülesanne:** Auto kiireneb puhkeolekust kiirendusega $a = 3 \text{ m/s}^2$. Kui suur on kiirus 5 sekundi pärast ja kui pikk tee on läbitud?

**Lahendus:**

Antud: $v_0 = 0$, $a = 3 \text{ m/s}^2$, $t = 5 \text{ s}$

$$v = v_0 + at = 0 + 3 \cdot 5 = 15 \text{ m/s}$$

$$s = v_0 t + \frac{at^2}{2} = 0 + \frac{3 \cdot 25}{2} = 37{,}5 \text{ m}$$

---

## Seotud materjalid

- [Harjutusülesanded](kinemaatika-ulesanded.md)
- [Levinud väärarusaamad](kinemaatika-vaararusaamad.md)
- [Praktilised tööd](kinemaatika-praktilised.md)
- [Kursuse kaart F1](../../oppekava/gymnaasium-F1-kinemaatika.md)
