# F5 — Elektrostaatika. Alalisvoolu seadused

**Kursus:** F5
**Klass:** 11. klass
**Eeldus:** F2

---

## 1. Elektrilaeng ja Coulomb'i seadus

**Elektrilaeng** $q$ on füüsikaline suurus, mis iseloomustab aine omadust osaleda elektromagnetilises vastasmõjus.

Elektrilaengul on kaks liiki:
- **Positiivne laeng** (+) — näiteks prootonitel
- **Negatiivne laeng** (−) — näiteks elektronidel

Laengu ühik SI-süsteemis: **kulon** (C).

**Coulomb'i seadus** väidab, et kahe punktlaengu vaheline jõud on võrdeline nende laengute korrutisega ja pöördvõrdeline nendevahelise kauguse ruuduga:

$$F = k\frac{q_1 q_2}{r^2}$$

kus:
- $k$ — Coulomb'i konstant ($k = 8,99 \times 10^9$ N·m²/C² või ligikaudu $k = 9 \times 10^9$ N·m²/C²)
- $q_1$, $q_2$ — laengud (C)
- $r$ — laengute vaheline kaugus (m)

Jõud on tõmbejõud, kui laengud on vastassuunalised, ja tõukejõud, kui laengud on samasuunalised.

---

## 2. Elektriväli

**Elektriväli** on ruumi osa, kus elektrilaengule mõjub elektrijõud.

Elektrivälja tugevus $E$ iseloomustab elektrivälja intensiivsust. Määratlus: elektrivälja tugevus on jõu ja laengu suhe:

$$\vec{E} = \frac{\vec{F}}{q}$$

kus:
- $F$ — elektrijõud (N)
- $q$ — proovilaeng (C)
- $E$ — elektrivälja tugevus (N/C või V/m)

**Punktlaengu elektriväli:**

$$E = k\frac{q}{r^2}$$

Elektrivälja tugevus väheneb kauguse ruudu pöördvõrdeliselt.

**Elektrivälja jooned** on kujuteldavad jooned, mille puutuja igas punktis näitab elektrivälja suunda positiivse laengu korral.

---

## 3. Elektriline potentsiaal ja pinge

**Elektriline potentsiaal** $\varphi$ iseloomustab elektrivälja energia omadust. Potentsiaal määratleb elektrivälja võimet teha tööd laengu liigutamisel.

Elektrivälja potentsiaal:

$$\varphi = \frac{W}{q}$$

kus $W$ on elektrijõud tehtud töö ja $q$ on laeng.

**Pinge** $U$ kahe punkti vahel on potentsiaalide erinevus:

$$U = \varphi_1 - \varphi_2 = \frac{A}{q}$$

kus:
- $A$ — elektrijõud tehtud töö laengu liigutamisel (J)
- $q$ — laeng (C)
- $U$ — pinge (V)

Pinge SI-ühik: **volt** (V).

---

## 4. Kondensaator

**Kondensaator** on seade, mis koosnevad kahest elektrijuhtivast plaadist, mille vahel on dielektricum (isolaator).

Kondensaatori **mahtuvus** $C$ näitab, kui palju laengut saab kondensaator salvestada antud pingeuurise kohta:

$$C = \frac{q}{U}$$

kus:
- $q$ — kondensaatori laeng (C)
- $U$ — pinge kondensaatori plaatide vahel (V)
- $C$ — mahtuvus (F)

Mahtuvuse ühik SI-süsteemis: **farad** (F).

**Lamepindse kondensaatori mahtuvus:**

$$C = \varepsilon_0 \varepsilon_r \frac{S}{d}$$

kus:
- $\varepsilon_0$ — vaakumi dielektriline läbilaskvus ($\varepsilon_0 = 8,85 \times 10^{-12}$ F/m)
- $\varepsilon_r$ — suheline dielektriline läbilaskvus
- $S$ — plaatide pindala (m²)
- $d$ — plaatide vaheline kaugus (m)

Kondensaatori energia:

$$W = \frac{1}{2}CU^2 = \frac{1}{2}\frac{q^2}{C} = \frac{1}{2}qU$$

---

## 5. Ohmi seadus ja takistus

**Ohmi seadus** väidab, et voolutugevus on võrdeline pingega ja pöördvõrdeline takistusega:

$$I = \frac{U}{R}$$

kus:
- $I$ — voolutugevus (A)
- $U$ — pinge (V)
- $R$ — takistus (Ω)

Takistuse SI-ühik: **oom** (Ω).

**Eritakistus** $\rho$ iseloomustab materjali omadust takistada elektrilise voolu juhtimist:

$$R = \rho\frac{l}{S}$$

kus:
- $\rho$ — eritakistus (Ω·m)
- $l$ — juhi pikkus (m)
- $S$ — juhi ristlõike pindala (m²)

Takistus sõltub temperatuurist:

$$R(T) = R_0(1 + \alpha \Delta T)$$

kus $\alpha$ on takistuse temperatuuritegur.

---

## 6. Jada- ja rööpühendus

**Jadaühendus:** Takistused ühendatakse järjest. Sama vool voolab läbi kõigi takistuste.

Kogutakistus:
$$R_{kogu} = R_1 + R_2 + R_3 + ...$$

Pinge jaguneb takistuste vahel:
$$U = U_1 + U_2 + U_3 + ...$$

**Rööpühendus:** Takistused ühendatakse paralleelselt. Kõikidel takistustel on sama pinge.

Kogutakistuse pöördväärtus:
$$\frac{1}{R_{kogu}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + ...$$

Vool jaguneb takistuste vahel:
$$I = I_1 + I_2 + I_3 + ...$$

| Ühendus | Kogutakistus | Pinge | Vool |
|---|---|---|---|
| Jadaühendus | Summa | Jaguneb | Sama |
| Rööpühendus | Pöördväärtuste summa | Sama | Jaguneb |

---

## 7. Elektromotoorjõud ja sisemakistus

**Elektromotoorjõud** (EMJ) $\varepsilon$ on väline allikas (nt aku), mis tekitab pinge elektriahelass.

Kui vooluringi kuulub allikas sisemakistusega $r$, on Ohmi seadus kogu ringi jaoks:

$$I = \frac{\varepsilon}{R+r}$$

kus:
- $\varepsilon$ — elektromotoorjõud (V)
- $R$ — välisähela takistus (Ω)
- $r$ — allikas sisemakistus (Ω)

Väline pinge (pinge välisähelas):

$$U = \varepsilon - Ir$$

---

## 8. Elektrienergia ja võimsus

**Elektri poolt tehtud töö** vooluringis:

$$A = UIt$$

kus:
- $U$ — pinge (V)
- $I$ — voolutugevus (A)
- $t$ — aeg (s)

**Elektrilise võimsus** näitab elektri poolt tehtud tööd ajaühiku kohta:

$$N = UI$$

kus $N$ on võimsus (W).

**Joule'i seadus** — soojushulk, mis eraldub takistuse läbivoolust:

$$Q = I^2Rt$$

Võimsus takistusel:

$$N = I^2R = \frac{U^2}{R}$$

---

## Levinud väärarusaamad

| Väärarusaam | Õige seletaming |
|---|---|
| Voolu "kulus" välja kasvõi | Vool jääb ringis konserveerunud. Muutub energia elektrilisest energia. |
| Elektron liigub väga kiiresti | Elektronide triivikirus on tegelikult väga aeglane (mm/s), energia levib seevastu valguse kiirusel. |
| Jadaühenduses on pinged ühesuurused | Jadaühenduses jaguneb pinge takistuste vahel; rööpühenduses on pinged samad. |
| Takistus "tarbib" elektrit | Takistus ei tarbida elektrit, vaid muudab elektrienergia soojusenergiaks. |
| Kondensaator "blokeerib" alalisvoolu täielikult | Alalisvoolu režiimis kondensaator on laetud ja voolu ei teki, kuid üleminekuperioodil tekib vool. |

---

## Näidisülesanne

**Ülesanne:** Elektrivõrk koosneb kolmest takistist: $R_1 = 10$ Ω (jadaühendus), $R_2 = 20$ Ω ja $R_3 = 20$ Ω (rööpühendus). Allikas on elektromotoorjõud $\varepsilon = 12$ V ja sisemakistus $r = 2$ Ω.

Arvuta:
1. Välisähela kogutakistus
2. Voolutugevus ringis
3. Pinge välisahelas
4. Võimsus välisahelas

**Lahendus:**

**1. samm — Rööpühenduse takistus:**

$$\frac{1}{R_{23}} = \frac{1}{20} + \frac{1}{20} = \frac{2}{20} = \frac{1}{10}$$

$$R_{23} = 10 \text{ Ω}$$

**2. samm — Kogu välisähela takistus:**

$$R = R_1 + R_{23} = 10 + 10 = 20 \text{ Ω}$$

**3. samm — Voolutugevus ringis:**

$$I = \frac{\varepsilon}{R+r} = \frac{12}{20+2} = \frac{12}{22} = 0,545 \text{ A}$$

**4. samm — Pinge välisahelas:**

$$U = \varepsilon - Ir = 12 - 0,545 \times 2 = 12 - 1,09 = 10,91 \text{ V}$$

Või: $U = IR = 0,545 \times 20 = 10,9$ V

**5. samm — Võimsus välisahelas:**

$$N = UI = 10,91 \times 0,545 = 5,95 \text{ W}$$

Või: $N = \frac{U^2}{R} = \frac{10,91^2}{20} = 5,95$ W

**Vastus:** Kogutakistus on 20 Ω, voolutugevus 0,545 A, pinge välisahelas 10,91 V, võimsus 5,95 W.

---

## Seotud materjalid

- [Kursuse kaart F5](../../oppekava/gymnaasium-F5-elektrostaatika.md)
