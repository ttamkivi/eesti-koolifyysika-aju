# Olümpiaadi näidisülesanded lahendusega

> Need näidisülesanded illustreerivad olümpiaadil esinevaid tüüpilisi ülesandeid ja nende lahendamise stiili. Iga ülesande juures on hindamisskeem.

---

## Ülesanne 1: Mehaanika (põhikool)

### Püstitus

Klots massiga $m = 2{,}0$ kg libiseb hõõrdevabalt kaldpinnalt alla. Kaldpinna kõrgus on $h = 1{,}5$ m ja pikkus $l = 3{,}0$ m. Kaldpinna lõpus põrkab klots vastu seina ja põrkab tagasi, kusjuures põrge on täiesti elastne.

a) Leia klotsi kiirus kaldpinna alumises otsas.
b) Kui kaugele kaldpinnast peale põrget klots jõuab, kui ta hakkab liikuma horisontaalsel hõõrdega pinnal ($\mu = 0{,}30$)?

### Lahendus

**a) Kiirus kaldpinna all:**

Kasutame energia jäävuse seadust (hõõrdevaba kaldpind):

$$mgh = \frac{1}{2}mv^2$$

$$v = \sqrt{2gh} = \sqrt{2 \cdot 9{,}81 \cdot 1{,}5} = \sqrt{29{,}43} = 5{,}4 \text{ m/s}$$

**b) Pidurdumistee horisontaalpinnal:**

Elastse põrke järel on kiirus sama suur: $v = 5{,}4$ m/s.

Hõõrdejõud:
$$F_{hõõrde} = \mu m g = 0{,}30 \cdot 2{,}0 \cdot 9{,}81 = 5{,}9 \text{ N}$$

Energia jäävusest:
$$\frac{1}{2}mv^2 = F_{hõõrde} \cdot s$$

$$s = \frac{mv^2}{2\mu mg} = \frac{v^2}{2\mu g} = \frac{5{,}4^2}{2 \cdot 0{,}30 \cdot 9{,}81} = \frac{29{,}2}{5{,}89} = 5{,}0 \text{ m}$$

**Vastus:** a) $v = 5{,}4$ m/s; b) $s = 5{,}0$ m

### Hindamisskeem (10 punkti)

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Energia jäävuse seaduse kirjapanemine | 2 |
| a) | Kiiruse valem $v = \sqrt{2gh}$ | 1 |
| a) | Arvutusvastus ühikutega | 1 |
| a) | Kontroll: ühikud, mõistlik suurus | 1 |
| b) | Elastse põrke tuvastamine (kiirus säilib) | 1 |
| b) | Hõõrdejõu valem | 1 |
| b) | Energia ja hõõrdetöö tasakaalustamine | 1 |
| b) | Arvutusvastus ühikutega | 1 |
| b) | Kontroll ja lõppvastus | 1 |

---

## Ülesanne 2: Elekter (põhikool)

### Püstitus

Vooluringis on aku (EMJ $\varepsilon = 12$ V, sisetakistus $r = 1{,}0$ $\Omega$), mille külge on ühendatud kaks takistit: $R_1 = 6{,}0$ $\Omega$ ja $R_2 = 3{,}0$ $\Omega$ rööbiti.

a) Leia takistite rööpühenduse kogutakistus.
b) Leia voolutugevus ahelas.
c) Leia pinge takistitel.

### Lahendus

**a) Rööpühenduse kogutakistus:**

$$\frac{1}{R_{kok}} = \frac{1}{R_1} + \frac{1}{R_2} = \frac{1}{6{,}0} + \frac{1}{3{,}0} = \frac{1 + 2}{6} = \frac{3}{6} = \frac{1}{2}$$

$$R_{kok} = 2{,}0 \text{ } \Omega$$

**b) Voolutugevus:**

Kogu ahela takistus: $R_{ahel} = R_{kok} + r = 2{,}0 + 1{,}0 = 3{,}0$ $\Omega$

$$I = \frac{\varepsilon}{R_{ahel}} = \frac{12}{3{,}0} = 4{,}0 \text{ A}$$

**c) Pinge takistitel:**

$$U = I \cdot R_{kok} = 4{,}0 \cdot 2{,}0 = 8{,}0 \text{ V}$$

Kontroll: pingelang sisetakistusel $U_r = I \cdot r = 4{,}0 \cdot 1{,}0 = 4{,}0$ V.
Summa: $8{,}0 + 4{,}0 = 12$ V = $\varepsilon$ ✓

**Vastus:** a) $R_{kok} = 2{,}0$ $\Omega$; b) $I = 4{,}0$ A; c) $U = 8{,}0$ V

### Hindamisskeem (10 punkti)

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Rööpühenduse valemi kirjapanemine | 2 |
| a) | Õige arvutus $R_{kok} = 2{,}0$ $\Omega$ | 1 |
| b) | Kogu ahela takistuse leidmine (sh sisetakistus) | 2 |
| b) | Ohmi seadus EMJ jaoks ja arvutus | 2 |
| c) | Pinge leidmine $U = IR$ | 2 |
| c) | Kontroll Kirchhoffi seadusega | 1 |

---

## Ülesanne 3: Termodünaamika (gümnaasium)

### Püstitus

Suletud silindris viibiga on ideaalne gaas. Algolekus: rõhk $p_1 = 1{,}0 \times 10^5$ Pa, ruumala $V_1 = 2{,}0$ L, temperatuur $T_1 = 300$ K.

a) Gaasi kuumutatakse konstantsel rõhul temperatuurini $T_2 = 600$ K. Leia uus ruumala.
b) Seejärel surutakse gaas isotermiliselt kokku algsele ruumalale $V_1$. Leia lõpprõhk.
c) Joonista protsess $p$-$V$ diagrammile.

### Lahendus

**a) Isobaariline paisumine ($p = \text{const}$):**

$$\frac{V_1}{T_1} = \frac{V_2}{T_2}$$

$$V_2 = V_1 \cdot \frac{T_2}{T_1} = 2{,}0 \cdot \frac{600}{300} = 4{,}0 \text{ L}$$

**b) Isotermiline kokkusurumine ($T = \text{const} = 600$ K):**

$$p_2 V_2 = p_3 V_3$$

kus $V_3 = V_1 = 2{,}0$ L:

$$p_3 = p_2 \cdot \frac{V_2}{V_3} = 1{,}0 \times 10^5 \cdot \frac{4{,}0}{2{,}0} = 2{,}0 \times 10^5 \text{ Pa}$$

**c) Diagramm:**

```
p (Pa)
  ↑
  |         C (2,0; 2,0×10⁵)
  |        /
  |       / isoterm (T₂=600K)
  |      /
  A----B
  |  isobaar (p₁)
  |
  +----------→ V (L)
     2,0  4,0
```

- A→B: isobaariline paisumine (horisontaalne sirge paremale)
- B→C: isotermiline kokkusurumine (hüperbool vasakule üles)

**Vastus:** a) $V_2 = 4{,}0$ L; b) $p_3 = 2{,}0 \times 10^5$ Pa

### Hindamisskeem (10 punkti)

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Isobaarse protsessi tuvastamine | 1 |
| a) | Gaasi olekuvõrrandi rakendamine | 2 |
| a) | Arvutusvastus | 1 |
| b) | Isotermilise protsessi tuvastamine | 1 |
| b) | Boyle'i seaduse rakendamine | 2 |
| b) | Arvutusvastus | 1 |
| c) | p-V diagramm õigete telgedega | 1 |
| c) | Mõlema protsessi korrektne kujutamine | 1 |

---

## Ülesanne 4: Optika (gümnaasium)

### Püstitus

Kumerläätse fookuskaugus on $f = 10$ cm. Ese asub $a = 15$ cm kaugusel läätsest.

a) Leia kujutise kaugus läätsest.
b) Kas kujutis on päri- või pöördkujutis? Kas tõeline või näiv?
c) Leia joonsuurendus.
d) Ese nihkub läätsele 3 cm lähemale. Kuidas muutub kujutis?

### Lahendus

**a) Kujutise kaugus:**

$$\frac{1}{f} = \frac{1}{a} + \frac{1}{k}}$$

$$\frac{1}{k} = \frac{1}{f} - \frac{1}{a} = \frac{1}{10} - \frac{1}{15} = \frac{3 - 2}{30} = \frac{1}{30}$$

$$k = 30 \text{ cm}$$

**b) Kujutise omadused:**

- $k > 0$ → kujutis on **tõeline** (tekib teisele poole läätse)
- Kuna $a > f$ (ese on kaugemal kui fookus) → kujutis on **pöördkujutis** (ümberpööratud)

**c) Joonsuurendus:**

$$\Gamma = \frac{k}{a} = \frac{30}{15} = 2{,}0$$

Kujutis on 2 korda suurem kui ese.

**d) Ese kaugusel $a' = 12$ cm:**

$$\frac{1}{k'} = \frac{1}{10} - \frac{1}{12} = \frac{6 - 5}{60} = \frac{1}{60}$$

$k' = 60$ cm, $\Gamma' = 60/12 = 5{,}0$

Kujutis nihkub kaugemale (30 → 60 cm) ja muutub suuremaks (2× → 5×).

**Vastus:** a) $k = 30$ cm; b) tõeline pöördkujutis; c) $\Gamma = 2{,}0$; d) kujutis nihkub kaugemale ja suureneb

### Hindamisskeem (10 punkti)

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Läätse valemi kirjapanemine | 2 |
| a) | Arvutus ja vastus | 1 |
| b) | Tõeline/näiv korrektne tuvastamine | 1 |
| b) | Päri-/pöördkujutise tuvastamine | 1 |
| c) | Suurenduse valem ja arvutus | 2 |
| d) | Uue olukorra lahendamine | 2 |
| d) | Kvalitatiivne järeldus | 1 |

---

## Ülesanne 5: Hindamisülesanne (Fermi ülesanne)

### Püstitus

Hinda, kui palju soojusenergiat kulub kõigi Eesti kodude kütmiseks ühe talvekuu jooksul. Esita oma eeldused ja hinnangud selgelt.

### Näidislahendus

**Eeldused:**

| Suurus | Hinnang | Põhjendus |
|--------|---------|-----------|
| Eesti elanike arv | ~1 300 000 | |
| Keskmine leibkond | 2,3 inimest | ~565 000 leibkonda |
| Elamuid | ~550 000 | osad mitmekorruselised |
| Keskmine eluruumi pindala | ~70 m² | |
| Lae kõrgus | ~2,7 m | ruumala ~190 m³ |
| Talvekuu kesk. välitemp. | –5 °C | jaanuar |
| Soovitud sisetemp. | +21 °C | $\Delta T = 26$ K |
| Soojuskadu läbi seinte | ~50 W korteri kohta kuni ~200 W maja kohta | $\approx$ 100 W keskmine |

**Arvutus:**

Keskmine soojuskadu korteri/maja kohta: ~100 W (hästi soojustatud) kuni ~300 W (vana maja). Võtame keskmiseks ~150 W temperatuurierinevuse 26 K korral.

Tegelikult paremini: soojuskadu sõltub seinte, akende ja katuse soojusläbivusest. Lihtsa hinnangu jaoks:

Soojusvajadus ühe eluruumi kohta: ~5–10 kW (arvestades kõiki kadusid — seinad, aknad, ventilatsioon).

Võtame keskmiseks $P \approx 5$ kW = 5000 W ühe eluruumi kohta.

Kuu jooksul (30 päeva × 24 h = 720 h):

$$Q_{üks} = P \cdot t = 5000 \cdot 720 \cdot 3600 = 1{,}3 \times 10^{10} \text{ J} \approx 13 \text{ GJ}$$

Kogu Eesti:

$$Q_{kokku} = 550\,000 \times 13 \text{ GJ} = 7{,}2 \times 10^6 \text{ GJ} \approx 7 \text{ PJ}$$

**Vastus:** Suurusjärgus $\sim 10$ PJ ($10^{16}$ J) ühe talvekuu kohta.

### Hindamisskeem (10 punkti)

| Kriteerium | Punktid |
|-----------|---------|
| Mõistlikud eeldused selgelt esitatud | 3 |
| Loogiline lähenemine ja arvutusskeem | 3 |
| Arvutuse korrektne läbiviimine | 2 |
| Lõppvastus õiges suurusjärgus | 1 |
| Tulemuse kriitiline hindamine | 1 |

---

## Seotud materjalid

- [Olümpiaadi juhend](juhend.md)
- [Ettevalmistusnõuanded](ettevalmistus.md)
- [EFO ülesannete arhiiv](http://efo.fyysika.ee/ulesannete-arhiiv/)
- [200 EFO ülesannet](https://www.digar.ee/arhiiv/et/raamatud/126061)
