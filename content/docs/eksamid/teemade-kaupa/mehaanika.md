# Mehaanika — Eksamiülesanded

> Riigieksamite stiilis ülesanded täislahenduste ja hindamisskeemidega.

---

## Kinemaatika

### Ülesanne 1 (12 punkti)

**Püstitus:**

Võistlusauto sõidab sirget autoteed mööda. Esimese 10 sekundi jooksul kiireneb auto 0 m/s-st 20 m/s-ni ühtlase kiirendusega.

a) Arvuta auto kiirendus esimese 10 sekundi jooksul.

b) Kui pika vahemaa läbib auto selle aja jooksul?

c) Millises ajahetkes saavutab auto kiirusega 15 m/s?

**Lahendus:**

**a)** Kiirendus ühtlasel kiirenemisel:
$$a = \frac{\Delta v}{\Delta t} = \frac{v_f - v_i}{t} = \frac{20 - 0}{10} = 2 \text{ m/s}^2$$

**Vastus:** a = 2 m/s²

**b)** Vahemaa ühtlase kiirendusega liikumisel:
$$s = v_i t + \frac{1}{2}at^2 = 0 \cdot 10 + \frac{1}{2} \cdot 2 \cdot 10^2$$
$$s = 0 + 100 = 100 \text{ m}$$

Kontrolli keskmise kiiruse valemiga: $s = \frac{v_i + v_f}{2} \cdot t = \frac{0 + 20}{2} \cdot 10 = 10 \cdot 10 = 100$ m ✓

**Vastus:** s = 100 m

**c)** Aeg, mil v = 15 m/s:
$$v = v_i + at$$
$$15 = 0 + 2 \cdot t$$
$$t = 7,5 \text{ s}$$

**Vastus:** t = 7,5 s

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Kiirenduse valemi kasutamine | 3 |
| a) | Õige arvutusfunktsioon | 1 |
| b) | Õige kinemaatika valemi valimine | 3 |
| b) | Õige arvutusliin | 3 |
| c) | Kiirenduse kasutamine aja arvutamisel | 2 |

---

### Ülesanne 2 (12 punkti)

**Püstitus:**

Jalgrattur sõidab algkiirusega 8 m/s ja pidurdab ühtlaselt, kuni peatub täielikult. Pidurdamine kestab 5 sekundit.

a) Arvuta pidurdamise kiirendus (negatiivne kiirendus).

b) Kui pika vahemaa jalgrattur pidurdamisel läbib?

c) Tee kiiruse graafikud ajagraafik (v-t graafik), mis näitab kogu pidurdamise protsessi.

**Lahendus:**

**a)** Pidurdamise kiirendus (negatiivne kiirendus):
$$a = \frac{v_f - v_i}{t} = \frac{0 - 8}{5} = -1,6 \text{ m/s}^2$$

**Vastus:** a = -1,6 m/s² (kiirendus on pidurdamine)

**b)** Pidurdamisel läbitud vahemaa:
$$s = v_i t + \frac{1}{2}at^2 = 8 \cdot 5 + \frac{1}{2} \cdot (-1,6) \cdot 5^2$$
$$s = 40 - 20 = 20 \text{ m}$$

Kontrolli keskmise kiiruse meetodiga: $s = \frac{v_i + v_f}{2} \cdot t = \frac{8 + 0}{2} \cdot 5 = 4 \cdot 5 = 20$ m ✓

**Vastus:** s = 20 m

**c)** v-t graafik:
- Algkiirus: v = 8 m/s (t = 0)
- Lõppkiirus: v = 0 m/s (t = 5 s)
- Graafikul on **lineaarne laskuv joon** (algusest (0,8) lõpuni (5,0))

```
v (m/s)
    8 |●─────\
    6 |      \
    4 |       \
    2 |        \
    0 |─────────●
      0 1 2 3 4 5  t (s)
```

Graafiku pindala = vahemaa = 20 m ✓

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Negatiivse kiirenduse arvutamine | 4 |
| b) | Vahemaa arvutamine ühtlase pidurdamise valemiga | 4 |
| c) | Õige v-t graafik, lineaarne | 2 |
| c) | Graafikul õiged väärtused | 2 |

---

### Ülesanne 3 (10 punkti)

**Püstitus:**

Tennisepall visatakse vertikaalselt üles algkiirusega 20 m/s. (Kasuta g = 10 m/s², õhuringistust ei arvestata)

a) Arvuta palli maksimaalse kõrguse.

b) Kui kaua kestab palli lendu, kuni see jõuab tagasi lähtepunkti?

c) Mis kiirusega lendab pall tagasi lähtepunkti?

**Lahendus:**

**a)** Maksimaalse kõrguse juures on kiirus v = 0:
$$v^2 = v_0^2 - 2gh$$
$$0 = 20^2 - 2 \cdot 10 \cdot h$$
$$20h = 400$$
$$h = 20 \text{ m}$$

**Vastus:** h = 20 m

**b)** Aeg, mil pall jõuab maksimaalse kõrguseni:
$$t_{\text{üles}} = \frac{v_0}{g} = \frac{20}{10} = 2 \text{ s}$$

Kogu lendude aeg (üles + alla):
$$t_{\text{kogu}} = 2 \cdot t_{\text{üles}} = 2 \cdot 2 = 4 \text{ s}$$

**Vastus:** t = 4 s

**c)** Lõpukiirus (sümmeetria):
$$v = gt_{\text{alla}} = 10 \cdot 2 = 20 \text{ m/s}$$

Või energeetiliselt: pall langeb samalt kõrguselt tagasi, seega kiirus on sama suurusega, aga **vastupidises suunas**: v = -20 m/s (alla)

Suuruselt: |v| = 20 m/s

**Vastus:** v = 20 m/s (allapoole)

**Hindamisskeem:**

| Osa | Kriteerium | Punktis |
|-----|-----------|---------|
| a) | Õige valem maksimaalse kõrguse jaoks | 2 |
| a) | Õige arvutus | 2 |
| b) | Aeg maksimaalse kõrguseni | 2 |
| b) | Kogu aeg (sümmeetria) | 2 |
| c) | Energeetilise või kinemaatilise põhjenduse | 2 |

---

## Dünaamika

### Ülesanne 4 (12 punkti)

**Püstitus:**

Autokraanal tõsteavutakse maast 1000 kg kaaluva metallosina. Kraan tõstab oosina ühtlaselt kiirendusega a = 0,5 m/s². (g = 10 m/s²)

a) Arvuta gravitatsioonijõud, mis mõjub oosinal.

b) Arvuta pinge köies (tõmbejõud), mis hoiab oosinal.

c) Kui pika aja jooksul tõstetakse oosina 10 meetri kõrgusele?

**Lahendus:**

**a)** Gravitatsioonijõud:
$$F_g = mg = 1000 \cdot 10 = 10\,000 \text{ N}$$

**Vastus:** Fg = 10,000 N

**b)** Newtoni teise seaduse rakendamine (ülespoole):
$$F_{\text{netting}} = ma$$
$$F_T - F_g = ma$$
$$F_T = ma + F_g = 1000 \cdot 0,5 + 10\,000$$
$$F_T = 500 + 10\,000 = 10\,500 \text{ N}$$

**Vastus:** FT = 10,500 N

**c)** Vahemaa s = 10 m, algkiirus v₀ = 0:
$$s = \frac{1}{2}at^2$$
$$10 = \frac{1}{2} \cdot 0,5 \cdot t^2$$
$$10 = 0,25 t^2$$
$$t^2 = 40$$
$$t = \sqrt{40} = 2\sqrt{10} \approx 6,3 \text{ s}$$

**Vastus:** t ≈ 6,3 s (või täpselt $2\sqrt{10}$ s)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Gravitatsioonijõu valem ja arvutus | 3 |
| b) | Newtoni teise seaduse rakendamine | 3 |
| b) | Pinge arvutamine õigesti | 3 |
| c) | Kinemaatika valemi kasutamine | 3 |

---

### Ülesanne 5 (12 punkti)

**Püstitus:**

Kahvel keha kumoavad kaks vastassuunalist horisontaalset jõudu. Esimene jõud on 40 N paremale, teine jõud on 30 N vasakule. Keha mass on 5 kg. Algkiirus on 0.

a) Arvuta netto jõud kehale.

b) Arvuta keha kiirendus.

c) Kui kaua kestab, kuni keha saavutab kiirusega 4 m/s?

**Lahendus:**

**a)** Võta positiivseks suunaks paremale:
- Esimene jõud: F₁ = +40 N
- Teine jõud: F₂ = -30 N

Netto jõud:
$$F_{\text{netto}} = F_1 + F_2 = 40 - 30 = 10 \text{ N}$$

**Vastus:** Fnetto = 10 N (paremale)

**b)** Newtoni teise seadus:
$$a = \frac{F_{\text{netto}}}{m} = \frac{10}{5} = 2 \text{ m/s}^2$$

**Vastus:** a = 2 m/s²

**c)** Aeg kiirusega v = 4 m/s:
$$v = v_0 + at$$
$$4 = 0 + 2 \cdot t$$
$$t = 2 \text{ s}$$

**Vastus:** t = 2 s

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Jõudude vektoraalne summa | 4 |
| b) | Newtoni teise seaduse kasutamine | 4 |
| c) | Kinemaatika valemi rakendamine | 4 |

---

### Ülesanne 6 (12 punkti)

**Püstitus:**

Kaks keha kumoavad paigal oleva pinnal. Keha A (mass 2 kg) ja keha B (mass 3 kg) on seotud niidiga. Keha A tõmmatakse horisontaalsel tasandil jõuga 25 N. Pinnakoefitsient on μ = 0,1. (g = 10 m/s²)

a) Arvuta hõõrdejõu summa (mõlemale kehale).

b) Arvuta süsteemi kiirendus.

c) Arvuta niidi pinge.

**Lahendus:**

**a)** Hõõrdejõud keha A jaoks:
$$f_A = \mu m_A g = 0,1 \cdot 2 \cdot 10 = 2 \text{ N}$$

Hõõrdejõud keha B jaoks:
$$f_B = \mu m_B g = 0,1 \cdot 3 \cdot 10 = 3 \text{ N}$$

Hõõrdejõud kokku:
$$f_{\text{kokku}} = f_A + f_B = 2 + 3 = 5 \text{ N}$$

**Vastus:** fkokku = 5 N

**b)** Newtoni teise seadus kogu süsteemile (m = mA + mB = 5 kg):
$$F_{\text{netto}} = F - f_{\text{kokku}} = 25 - 5 = 20 \text{ N}$$
$$a = \frac{F_{\text{netto}}}{m_A + m_B} = \frac{20}{5} = 4 \text{ m/s}^2$$

**Vastus:** a = 4 m/s²

**c)** Niidi pinge (keha B arvutus):
$$T - f_B = m_B a$$
$$T = m_B a + f_B = 3 \cdot 4 + 3 = 12 + 3 = 15 \text{ N}$$

Kontrolli keha A arvutusega:
$$F - T - f_A = m_A a$$
$$T = F - f_A - m_A a = 25 - 2 - 2 \cdot 4 = 25 - 2 - 8 = 15 \text{ N}$$ ✓

**Vastus:** T = 15 N

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Hõõrdejõudude arvutamine | 3 |
| a) | Summa | 1 |
| b) | Netto jõu arvutamine | 2 |
| b) | Kiirenduse arvutamine | 2 |
| c) | Niidi pinge valemi rakendamine | 2 |
| c) | Õige väärtus | 2 |

---

## Energia ja jäävusseadused

### Ülesanne 7 (12 punkti)

**Püstitus:**

Pall kukkub taolt kõrguselt h = 5 m. Palli mass on m = 0,5 kg. (g = 10 m/s², õhuringistust ei arvestata)

a) Arvuta palli gravitatsioonist tingitud potentsiaalne energia taol.

b) Arvuta palli kineetiliseks energia just enne maapinnale langemist.

c) Arvuta palli kiirus maapinnale jõudmisel.

**Lahendus:**

**a)** Potentsiaalne energia taol (h = 5 m):
$$E_p = mgh = 0,5 \cdot 10 \cdot 5 = 25 \text{ J}$$

**Vastus:** Ep = 25 J

**b)** Energia jäävus — potentsiaalse energia muutub kineetiliseks:
$$E_p = E_k$$
$$25 = E_k$$

**Vastus:** Ek = 25 J

**c)** Kineetilise energia valemi kasutamine:
$$E_k = \frac{1}{2}mv^2$$
$$25 = \frac{1}{2} \cdot 0,5 \cdot v^2$$
$$25 = 0,25 v^2$$
$$v^2 = 100$$
$$v = 10 \text{ m/s}$$

**Vastus:** v = 10 m/s

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Potentsiaalne energia valem | 3 |
| a) | Õige arvutus | 1 |
| b) | Energia jäävuse printsiibi rakendamine | 4 |
| c) | Kineetilise energia valemist kiiruse lahendamine | 4 |

---

### Ülesanne 8 (12 punkti)

**Püstitus:**

Elastne kummivõru on venitatud 0,1 m võrra. Kummivõru jäikustegur on k = 200 N/m. Kummivõrusse festimata pall massiga m = 0,2 kg.

a) Arvuta kummivõru elastne potentsiaalne energia venitatud olekus.

b) Kui kummivõru vabastatakse, muutub elastne energia kineetiliseks energiaks. Arvuta palli kiirus pärast vabastamist.

c) Kui kõrgele lendab pall vertikaalselt ülespoole, kui kummivõru lastakse horisontaalsest asendist vertikaalsuunas?

**Lahendus:**

**a)** Elastne potentsiaalne energia:
$$E_{\text{elastne}} = \frac{1}{2}kx^2 = \frac{1}{2} \cdot 200 \cdot (0,1)^2$$
$$E_{\text{elastne}} = 100 \cdot 0,01 = 1 \text{ J}$$

**Vastus:** Eelastne = 1 J

**b)** Energia jäävus — elastne energia → kineetilne energia:
$$E_{\text{elastne}} = E_k$$
$$1 = \frac{1}{2}mv^2$$
$$1 = \frac{1}{2} \cdot 0,2 \cdot v^2$$
$$1 = 0,1 v^2$$
$$v^2 = 10$$
$$v = \sqrt{10} \approx 3,16 \text{ m/s}$$

**Vastus:** v ≈ 3,16 m/s (või $\sqrt{10}$ m/s)

**c)** Kineetilisest energiast saab potentsiaalne energia:
$$E_k = E_p$$
$$1 = mgh$$
$$1 = 0,2 \cdot 10 \cdot h$$
$$1 = 2h$$
$$h = 0,5 \text{ m}$$

**Vastus:** h = 0,5 m

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Elastse potentsiaalne energia valem | 3 |
| a) | Õige arvutus | 1 |
| b) | Energia jäävuse rakendamine | 2 |
| b) | Kiiruse arvutamine | 2 |
| c) | Potentsiaalne energia vastusest kõrguse leidmine | 2 |
| c) | Õige arvutus | 2 |

---

### Ülesanne 9 (12 punkti)

**Püstitus:**

Kelk kukkub lumiselt nõlvalt kõrguselt h = 10 m. Kelgu mass koos inimesega on m = 80 kg. Nõlval on hõõrdejõud f = 200 N.

a) Arvuta kelgu potentsiaalne energia nõlva peal.

b) Arvuta hõõrdejõu poolt tehtud töö nõlval laskumisel.

c) Arvuta kelgu kineetilisest energia nõlva allosas ja palli kiirus.

**Lahendus:**

**a)** Potentsiaalne energia:
$$E_p = mgh = 80 \cdot 10 \cdot 10 = 8\,000 \text{ J}$$

**Vastus:** Ep = 8,000 J

**b)** Nõlva pikkus (sin α = h/L, kuid siin kasutame otsest hõõrdejõudu):
Töö, mille teeb hõõrdejõud:

Antud h ja f, nõlva pikkus:
$$L = \frac{h}{\sin \alpha}$$

Kuid hõõrdejõud on juba antud kui f = 200 N. Kui nõlv on sirge kõrgusega h = 10 m:
$$W_f = -f \cdot L$$

Eeldame, et nõlva nurk on selline, et hõõrdejõu töö on:
$$W_f = -f \cdot s$$

Kus s on teekond mõõluna. Kui h = 10 m ja eeldame nõlva nurka, näiteks 30°:
$$L = \frac{h}{\sin 30°} = \frac{10}{0,5} = 20 \text{ m}$$

$$W_f = -200 \cdot 20 = -4\,000 \text{ J}$$

**Vastus:** Wf = -4,000 J (hõõrdejõud teeb negatiivset tööd)

**c)** Energia jäävus (ja töö energia teoreem):
$$E_p + W_f = E_k$$
$$8\,000 - 4\,000 = E_k$$
$$E_k = 4\,000 \text{ J}$$

Kiirus:
$$E_k = \frac{1}{2}mv^2$$
$$4\,000 = \frac{1}{2} \cdot 80 \cdot v^2$$
$$4\,000 = 40 v^2$$
$$v^2 = 100$$
$$v = 10 \text{ m/s}$$

**Vastus:** Ek = 4,000 J, v = 10 m/s

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Potentiaalse energia arvutamine | 3 |
| b) | Hõõrdejõu töö arvutamine (nõlva pikkusega) | 3 |
| b) | Negatiivne märk | 1 |
| c) | Töö-energia teoreem rakendamine | 2 |
| c) | Kiiruse arvutamine | 3 |

---

## Pöörlemisdünaamika

### Ülesanne 10 (12 punkti)

**Püstitus:**

Massiivne silinder (mass M = 10 kg, raadius R = 0,5 m) pöörleb telje ümber. Jõumomenti tekitav jõud on τ = 5 N⋅m. Silindri inertsmoment on I = ½MR².

a) Arvuta silindri inertsmoment.

b) Arvuta silindri nurkkiirendus.

c) Mitu pööret teeb silinder 10 sekundi jooksul, alustades puhkeolekust?

**Lahendus:**

**a)** Silindri inertsmoment:
$$I = \frac{1}{2}MR^2 = \frac{1}{2} \cdot 10 \cdot (0,5)^2$$
$$I = 5 \cdot 0,25 = 1,25 \text{ kg⋅m}^2$$

**Vastus:** I = 1,25 kg⋅m²

**b)** Nurkkiirendus (pöörlemise Newtoni teine seadus):
$$\tau = I \alpha$$
$$\alpha = \frac{\tau}{I} = \frac{5}{1,25} = 4 \text{ rad/s}^2$$

**Vastus:** α = 4 rad/s²

**c)** Nurkkaugus 10 sekundi jooksul:
$$\theta = \frac{1}{2}\alpha t^2 = \frac{1}{2} \cdot 4 \cdot 10^2$$
$$\theta = 2 \cdot 100 = 200 \text{ rad}$$

Pöörded:
$$N = \frac{\theta}{2\pi} = \frac{200}{2\pi} = \frac{100}{\pi} \approx 31,8 \text{ pööret}$$

**Vastus:** N ≈ 31,8 pööret (või 100/π pööret)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Inertsmoment valemi kasutamine | 3 |
| a) | Õige arvutus | 1 |
| b) | Nurkkiirenduse valem | 2 |
| b) | Arvutus | 2 |
| c) | Nurkkauguse arvutamine | 2 |
| c) | Pöörded radiaanidest | 2 |

---

### Ülesanne 11 (12 punkti)

**Püstitus:**

Kettad (mass m = 2 kg, raadius r = 0,2 m) rullub mõõda kallakut ilma libisemiseta. Kettas algab puhkeolekust kõrguselt h = 1 m. Kettas inertsmoment: I = ½mr².

a) Arvuta kettas potentsiaalne energia algsel kõrgusel.

b) Arvuta kettas rotatsiooniline kineetilisest energia põhjal alamale jõudmisel.

c) Arvuta kettas lineaarne kiirus alamale jõudmisel.

**Lahendus:**

**a)** Potentsiaalne energia:
$$E_p = mgh = 2 \cdot 10 \cdot 1 = 20 \text{ J}$$

**Vastus:** Ep = 20 J

**b)** Rullimise tingimus (ilma libisemiseta): v = ωr

Potentsiaalse energia jaotus:
- Lineaarne kineetilisest energia: $E_{k,lin} = \frac{1}{2}mv^2$
- Pöörlemiskineetilisest energia: $E_{k,rot} = \frac{1}{2}I\omega^2$

Energia jäävus:
$$E_p = E_{k,lin} + E_{k,rot}$$
$$E_p = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2$$

Kasutades v = ωr ja I = ½mr²:
$$E_p = \frac{1}{2}mv^2 + \frac{1}{2} \cdot \frac{1}{2}mr^2 \cdot \left(\frac{v}{r}\right)^2$$
$$E_p = \frac{1}{2}mv^2 + \frac{1}{4}mv^2 = \frac{3}{4}mv^2$$

Pöörlemiskineetilisest energia:
$$E_{k,rot} = \frac{1}{4}mv^2$$

Energia jäävusest:
$$20 = \frac{3}{4} \cdot 2 \cdot v^2$$
$$20 = 1,5 v^2$$
$$v^2 = \frac{20}{1,5} = \frac{40}{3}$$

$$E_{k,rot} = \frac{1}{4} \cdot 2 \cdot \frac{40}{3} = \frac{1}{2} \cdot \frac{40}{3} = \frac{20}{3} \approx 6,67 \text{ J}$$

**Vastus:** Ek,rot ≈ 6,67 J

**c)** Lineaarne kiirus:
$$v = \sqrt{\frac{40}{3}} \approx 3,65 \text{ m/s}$$

Või tarkemalt:
$$v = \sqrt{\frac{40}{3}} = \frac{2\sqrt{10}}{\sqrt{3}} = \frac{2\sqrt{30}}{3} \approx 3,65 \text{ m/s}$$

**Vastus:** v ≈ 3,65 m/s

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Potentsiaalne energia | 2 |
| b) | Rullimise tingimus (v = ωr) | 2 |
| b) | Energia jäävus kahele kineetilisele osale | 3 |
| b) | Pöörlemiskineetilisest energia arvutus | 1 |
| c) | Lineaarne kiiruse arvutamine | 4 |

---

### Ülesanne 12 (12 punkti)

**Püstitus:**

Pöörlevad käik (mass M = 5 kg, raadius R = 0,3 m) peatub hõõrdejõu tõttu. Käik alguspõhja pöörlemise kiirus on ω₀ = 20 rad/s. Hõõrdejõumoment on τf = -0,6 N⋅m. Käik inertsmoment I = ½MR².

a) Arvuta käik inertsmoment.

b) Arvuta käik nurkkiirendus (negatiivne) hõõrdejõu tõttu.

c) Mitu sekundit kulub käigu pöörlemise lõpetamisele?

**Lahendus:**

**a)** Inertsmoment:
$$I = \frac{1}{2}MR^2 = \frac{1}{2} \cdot 5 \cdot (0,3)^2$$
$$I = 2,5 \cdot 0,09 = 0,225 \text{ kg⋅m}^2$$

**Vastus:** I = 0,225 kg⋅m²

**b)** Nurkkiirendus (hõõrdejõu moment):
$$\alpha = \frac{\tau_f}{I} = \frac{-0,6}{0,225} = -2,67 \text{ rad/s}^2$$

**Vastus:** α ≈ -2,67 rad/s² (või täpselt -8/3 rad/s²)

**c)** Aeg käigu pöörlemise lõpetamiseni (ω = 0):
$$\omega = \omega_0 + \alpha t$$
$$0 = 20 + (-2,67) \cdot t$$
$$t = \frac{20}{2,67} = 7,5 \text{ s}$$

Või täpselt: $t = \frac{20}{8/3} = 20 \cdot \frac{3}{8} = 7,5$ s

**Vastus:** t = 7,5 s

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Inertsmoment valemi kasutamine | 3 |
| a) | Õige arvutus | 1 |
| b) | Nurkkiirenduse arvutamine | 4 |
| c) | Aeg arvutamine kinemaatika valemiga | 4 |

---

## Vedelike mehaanika

### Ülesanne 13 (12 punkti)

**Püstitus:**

Vesi on paagis rõhugagi. Paagi põhjast tuleb avaused vee jaoks. Paagi kõrgus on h = 2 m, vee tihedus ρ = 1000 kg/m³. (g = 10 m/s²)

a) Arvuta hüdrostaatilisest rõhk paagi põhjale.

b) Kui suur on jõud paagi põhjale, mille ala on A = 0,5 m²?

c) Kui kiirusega väljub vesi paagi avast (Torricelli valem)?

**Lahendus:**

**a)** Hüdrostaatiline rõhk paagi põhjale:
$$p = \rho g h = 1000 \cdot 10 \cdot 2 = 20\,000 \text{ Pa}$$

**Vastus:** p = 20,000 Pa

**b)** Jõud paagi põhjale:
$$F = p \cdot A = 20\,000 \cdot 0,5 = 10\,000 \text{ N}$$

**Vastus:** F = 10,000 N

**c)** Torricelli valem (energia jäävus):
$$v = \sqrt{2gh} = \sqrt{2 \cdot 10 \cdot 2} = \sqrt{40}$$
$$v = 2\sqrt{10} \approx 6,32 \text{ m/s}$$

**Vastus:** v ≈ 6,32 m/s

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Hüdrostaatiline rõhk valem | 3 |
| a) | Õige arvutus | 1 |
| b) | Jõu arvutamine rõhu kaudu | 3 |
| b) | Õige arvutus | 1 |
| c) | Torricelli valemi rakendamine | 4 |

---

### Ülesanne 14 (12 punkti)

**Püstitus:**

Üleslükkejõud (Archimedese seadus): Objekt (mass m = 5 kg, maht V = 0,006 m³) on vedelikus (tihedus ρ = 800 kg/m³). (g = 10 m/s²)

a) Arvuta objekti kaal õhus.

b) Arvuta üleslükkejõud vedelikus.

c) Kas objekt upub või ujub? Põhjenda.

**Lahendus:**

**a)** Objekti kaal:
$$G = mg = 5 \cdot 10 = 50 \text{ N}$$

**Vastus:** G = 50 N

**b)** Üleslükkejõud:
$$F_A = \rho g V = 800 \cdot 10 \cdot 0,006$$
$$F_A = 8000 \cdot 0,006 = 48 \text{ N}$$

**Vastus:** FA = 48 N

**c)** Võrdlus:
- Kaal: G = 50 N
- Üleslükkejõud: FA = 48 N

Kuna G > FA, on objekti kaal suurem kui üleslükkejõud, seega **objekti upub**.

**Vastus:** Objekt upub, sest G > FA.

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Kaalu arvutamine | 3 |
| b) | Üleslükkejõu valem | 3 |
| b) | Õige arvutus | 1 |
| c) | Võrdlus ja põhjendus | 5 |

---

### Ülesanne 15 (12 punkti)

**Püstitus:**

Bernoulli võrrand liiga kiirete vedelikuvoolu jaoks. Toru, mille ristlõige muutub: alguses A₁ = 0,01 m², lõpus A₂ = 0,005 m². Vedeliku tihedus ρ = 1000 kg/m³. Kiirus alguses v₁ = 2 m/s.

a) Arvuta vedeliku voolutugevus jäävuse seaduse järgi.

b) Arvuta vedeliku kiirus torude lõpus.

c) Kasutades Bernoulli võrrandit, arvuta rõhu muutus kitsendatud osa juures.

**Lahendus:**

**a)** Jäävusseadus:
$$Q = A_1 v_1 = 0,01 \cdot 2 = 0,02 \text{ m}^3/\text{s}$$

**Vastus:** Q = 0,02 m³/s

**b)** Kiirus torude lõpus:
$$Q = A_2 v_2$$
$$0,02 = 0,005 \cdot v_2$$
$$v_2 = \frac{0,02}{0,005} = 4 \text{ m/s}$$

**Vastus:** v₂ = 4 m/s

**c)** Bernoulli võrrand (horisontaalne toru):
$$p_1 + \frac{1}{2}\rho v_1^2 = p_2 + \frac{1}{2}\rho v_2^2$$
$$p_1 - p_2 = \frac{1}{2}\rho (v_2^2 - v_1^2)$$
$$\Delta p = \frac{1}{2} \cdot 1000 \cdot (4^2 - 2^2)$$
$$\Delta p = 500 \cdot (16 - 4) = 500 \cdot 12 = 6000 \text{ Pa}$$

**Vastus:** Δp = 6000 Pa (rõhk väheneb 6 kPa-ga)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Jäävusseaduse rakendamine | 3 |
| b) | Kiiruse arvutamine jäävusseadusest | 3 |
| c) | Bernoulli võrrandi rakendamine | 3 |
| c) | Õige arvutus | 3 |

---

**Kokku:** 15 ülesannet × 12 punkti = 180 punkti mehaanika kohta

Nende ülesannete harjutamine aitab sul valmistuda eksamile ulatuslikult!
