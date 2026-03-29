# F2 — Ringliikumine. Dünaamika

**Kursus:** F2
**Klass:** 10. klass
**Eeldused:** F1

## 1. Ringliikumise omadused

Ringliikumine on liikumine ringikujulises trajektooril jäävast keskpunktist võrdsel kaugusel. Ringliikumise kirjeldamiseks kasutatakse järgmisi suurusi:

**Periood** ($T$) – aeg, mille jooksul keha teeb ühe täisringi. Ühik: sekund (s).

**Sagedus** ($f$) – täisringide arv ajaühikus. Ühik: herts (Hz = 1/s).

Periood ja sagedus on seotud seosega:

$$T = \frac{1}{f}$$

**Nurkkiirus** ($\omega$) – näitab, kui kiiresti muutub keha asendinurk. Ühik: rad/s.

$$\omega = \frac{\varphi}{t} = \frac{2\pi}{T} = 2\pi f$$

kus $\varphi$ on poordumisnurk radiaanides.

**Joonkiirus** ($v$) – keha liikumiskiirus ringjoone puutuja suunas. Ühik: m/s.

$$v = \omega r$$

kus $r$ on ringjoone raadius.

## 2. Kesktõmbekiirendus ja kesktõmbejõud

Ringliikumisel on kehal jäigi kiirus, kuid kiirus muudab pidevalt suunda. Seega on kehal kiirendus, mis on suunatud ringjoone keskpunkti poole.

**Kesktõmbekiirendus** ($a_n$) arvutatakse valemitega:

$$a_n = \omega^2 r = \frac{v^2}{r}$$

## 3. Newtoni seadused

**Newtoni I seadus (inertsi seadus):** Keha jääb paigal või liigub ühtlaselt sirgjooneliselt, kui temale mõjuvate jõudude resultant on null.

$$\sum \vec{F} = 0$$

**Newtoni II seadus:** Keha kiirendus on võrdeline talle mõjuva jõuga ja pöördvõrdeline massiga.

$$\vec{a} = \frac{\vec{F}}{m} \quad \text{ehk} \quad \vec{F} = m\vec{a}$$

**Newtoni III seadus:** Kui keha A mõjub jõuga keha B-le, mõjub keha B võrdse, kuid vastassuunalise jõuga keha A-le.

$$\vec{F}_{AB} = -\vec{F}_{BA}$$

## 4. Jõud looduses

### 4.1 Gravitatsioonijõud

Kaks massiivse keha tõmbuvad teineteise poole jõuga, mis on võrdeline nende masside korrutisega ja pöördvõrdeline kauguse ruuduga:

$$F = G\frac{m_1 m_2}{R^2}$$

kus $G = 6{,}67 \times 10^{-11}$ N·m²/kg² on gravitatsioonikonstant.

### 4.2 Kaal

Kaal on jõud, millega keha rõhub toele või tõmbab pealekinnitusjõu. Vertikaalselt liikuva keha kaal:

$$P = m(g \pm a)$$

kus $+$ märk kasutatakse ülespoole kiirendusel ja $-$ märk allapoole kiirendusel.

### 4.3 Hõõrdejõud

Hõõrdejõud on jõud, mis takistab keha liikumist pöördel. Kuivhõõrde korral:

$$F_h = \mu N$$

kus $\mu$ on hõõrdetegur ja $N$ on normaaljõud.

### 4.4 Hooke'i seadus

Elastse keha deformeerimisel tekkiv jõud on võrdeline deformatsiooni suurusega:

$$F_{ex} = -kx$$

kus $k$ on jäikustegur ja $x$ on deformatsioon.

## 5. Ringliikumise jõudude analüüs

| Situatsioon | Kesktõmbejõu allikas | Valem |
|---|---|---|
| Auto kurvis | Hõõrdejõud | $F_h = \frac{mv^2}{r}$ |
| Pall nööril | Pinge jõud | $T = \frac{mv^2}{r} + mg$ |
| Satelliit orbiidil | Gravitatsioon | $\frac{GMm}{r^2} = \frac{mv^2}{r}$ |
| Vertikaalne ring | Normaaljõud + kaal | $N + mg = \frac{mv^2}{r}$ |

## Levinud väärarusaamad

| Väärarusaam | Õige seletus |
|---|---|
| Ringliikumises pole kiirendust, sest kiirus on konstantne | Kiirus (suurus) on konstantne, kuid kiirendus on olemas, kuna suund muutub. Kiirendus on kesktõmbekiirendus. |
| Kesktõmbejõud on keha sees, mitte väljast | Kesktõmbejõud on alati välisjõud (pinge, gravitatsioon, normaaljõud jne), mille resultant on suunatud ringjoone keskpunkti poole. |
| Kaal on alati $mg$ | Kaal muutub, kui kehal on vertikaalne kiirendus. Kaal = näited, mida näitab kaalud. |
| Hõõrdejõud on alati liikumisele vastu | Hõõrdejõud on liikumisele vastu, kuid ringliikumises osutub see kesktõmbejõuks, mis pöördiab keha trajektoori. |

## Näidisülesanne

**Ülesanne:** Auto massiga 1200 kg liigub horisontaalselt kõveras teel raadiusega 50 m. Suurim hõõrdetegur asfalti ja rehvi vahel on 0,8. Milline on suurim kiirus, millega auto saab seda kõverat ohutult läbida?

**Lahendus:**

Ringliikumises peab kesktõmbejõud olema hõõrdejõud:

$$F_h = \frac{mv^2}{r}$$

Maksimaalne hõõrdejõud:

$$F_{h,max} = \mu mg$$

Seega:

$$\mu mg = \frac{mv^2}{r}$$

Taandades massi:

$$\mu g = \frac{v^2}{r}$$

Avaldame kiirust:

$$v = \sqrt{\mu g r} = \sqrt{0{,}8 \times 10 \times 50} = \sqrt{400} = 20 \text{ m/s}$$

**Vastus:** Auto suurim ohutus kiirus on 20 m/s (72 km/h).

---

## Seotud materjalid

- [Kursuse kaart F2](../../oppekava/gymnaasium-F2-dunaamika.md)
