# Soojusõpetus ja termodünaamika — Eksamiülesanded

> Riigieksamite stiilis ülesanded täislahenduste ja hindamisskeemidega.

---

## Soojusülekanne

### Ülesanne 1 (12 punkti)

**Püstitus:**

Metallist lipp (ala A = 0,5 m²) lähendatakse kuumale vett (T₁ = 80°C). Õhutemperatuur on T₂ = 20°C. Soojusülekande koefitsient h = 15 W/(m²⋅K).

a) Arvuta temperatuurivahe soojusülekannet.

b) Arvuta soojusvõimsus, mis ülekandub lääbile.

c) Kui palju soojusenergia ülekandub 10 minuti jooksul?

**Lahendus:**

**a)** Temperatuurivahe:
$$\Delta T = T_1 - T_2 = 80 - 20 = 60 \text{ K (või °C)}$$

**Vastus:** ΔT = 60 K

**b)** Soojusvõimsus konvektsiooni teel:
$$P = hA\Delta T = 15 \cdot 0,5 \cdot 60$$
$$P = 15 \cdot 30 = 450 \text{ W}$$

**Vastus:** P = 450 W

**c)** Energia 10 minuti jooksul (t = 10 × 60 = 600 s):
$$Q = Pt = 450 \cdot 600 = 270\,000 \text{ J} = 270 \text{ kJ}$$

Või kilokalorites: $Q = \frac{270\,000}{4200} \approx 64,3$ kcal

**Vastus:** Q = 270 kJ

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Temperatuurivahe | 2 |
| b) | Soojusvõimsuse valem konvektsioonile | 4 |
| b) | Õige arvutus | 2 |
| c) | Energia arvutamine | 2 |
| c) | Aeg sekundites | 1 |
| c) | Õige arvutus | 1 |

---

### Ülesanne 2 (12 punkti)

**Püstitus:**

Musta keha (ala A = 1 m², emissioonitegur ε = 1) kiirgatakse soojust Stefan-Boltzmanni seaduse järgi. Keha temperatuur T = 500 K, ympäristö temperatuur T₀ = 300 K. Konstant σ = 5,67 × 10⁻⁸ W/(m²⋅K⁴).

a) Arvuta musta keha kiirgavõimsus.

b) Arvuta keskkonna poolt keha poole kiirgavõimsus.

c) Arvuta netto soojuskadu.

**Lahendus:**

**a)** Musta keha kiirgavõimsus:
$$P = \varepsilon \sigma A T^4 = 1 \cdot 5,67 \times 10^{-8} \cdot 1 \cdot 500^4$$
$$P = 5,67 \times 10^{-8} \cdot 62,5 \times 10^8$$
$$P = 5,67 \times 62,5 \times 10^0 = 354,375 \text{ W}$$

**Vastus:** P ≈ 354 W

**b)** Keskkonna kiirgavõimsus (sama seadus):
$$P_0 = \varepsilon \sigma A T_0^4 = 1 \cdot 5,67 \times 10^{-8} \cdot 1 \cdot 300^4$$
$$P_0 = 5,67 \times 10^{-8} \cdot 8,1 \times 10^8$$
$$P_0 = 5,67 \times 8,1 = 45,927 \text{ W}$$

**Vastus:** P₀ ≈ 46 W

**c)** Netto soojuskadu:
$$P_{\text{netto}} = P - P_0 = 354 - 46 = 308 \text{ W}$$

**Vastus:** Pnetto ≈ 308 W

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Stefan-Boltzmanni valem | 3 |
| a) | Õige arvutus | 2 |
| b) | Keskkonna kiirgavõimsus | 3 |
| b) | Õige arvutus | 2 |
| c) | Netto soojuskadu | 2 |

---

## Agregaatolekute muutused

### Ülesanne 3 (12 punkti)

**Püstitus:**

Jää mass m = 2 kg algtemperatuuriga t₁ = -10°C kuumutatakse, kuni see muutub veeauruks. Jää erisoojus c₁ = 2100 J/(kg⋅K), vee erisoojus c₂ = 4200 J/(kg⋅K), sulamise latentne soojus L_f = 334 000 J/kg, aurustamise latentne soojus L_v = 2 260 000 J/kg.

a) Arvuta soojus, mis kulub jää kuumutamisele -10°C-st 0°C-ni.

b) Arvuta soojus, mis kulub jää sulamisele.

c) Arvuta kogu soojus jää muutumiseks veeauruks.

**Lahendus:**

**a)** Jää kuumutamine -10°C-st 0°C-ni (ΔT = 10 K):
$$Q_1 = mc_1 \Delta T = 2 \cdot 2100 \cdot 10 = 42\,000 \text{ J}$$

**Vastus:** Q₁ = 42,000 J = 42 kJ

**b)** Jää sulamine:
$$Q_2 = mL_f = 2 \cdot 334\,000 = 668\,000 \text{ J}$$

**Vastus:** Q₂ = 668,000 J = 668 kJ

**c)** Kogu soojus (jää -10°C → vee 0°C → vee 100°C → aur):

Jää kuumutamine: Q₁ = 42,000 J (ülal)

Jää sulamine: Q₂ = 668,000 J (ülal)

Vee kuumutamine 0°C-st 100°C-ni:
$$Q_3 = mc_2 \Delta T = 2 \cdot 4200 \cdot 100 = 840\,000 \text{ J}$$

Vee aurustamine:
$$Q_4 = mL_v = 2 \cdot 2\,260\,000 = 4\,520\,000 \text{ J}$$

Kogu soojus:
$$Q_{\text{kogu}} = Q_1 + Q_2 + Q_3 + Q_4$$
$$Q_{\text{kogu}} = 42\,000 + 668\,000 + 840\,000 + 4\,520\,000$$
$$Q_{\text{kogu}} = 6\,070\,000 \text{ J} = 6\,070 \text{ kJ} \approx 6,1 \text{ MJ}$$

**Vastus:** Qkogu = 6,070 kJ ≈ 6,1 MJ

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Jää kuumutamise soojus | 3 |
| a) | Õige arvutus | 1 |
| b) | Sulamise latentne soojus | 3 |
| b) | Õige arvutus | 1 |
| c) | Kõigi etappide arvestamine | 2 |
| c) | Õige summa | 2 |

---

### Ülesanne 4 (12 punkti)

**Püstitus:**

Vesi mass m = 1 kg algtemperatuuriga T₁ = 20°C kuumutatakse, kuni see algab keema (100°C). Vee erisoojus c = 4200 J/(kg⋅K).

a) Arvuta soojus, mis kulub vee kuumutamisele 20°C-st 100°C-ni.

b) Arvuta vee aurustumiseks vajalik soojus (L = 2 260 000 J/kg).

c) Kui teisenduse käigus kulu elektrienergia on W = 1000 W, arvuta aeg vee keemiseni.

**Lahendus:**

**a)** Vee kuumutamine (ΔT = 100 - 20 = 80 K):
$$Q_1 = mc\Delta T = 1 \cdot 4200 \cdot 80 = 336\,000 \text{ J}$$

**Vastus:** Q₁ = 336,000 J = 336 kJ

**b)** Vee aurustamine:
$$Q_2 = mL = 1 \cdot 2\,260\,000 = 2\,260\,000 \text{ J}$$

**Vastus:** Q₂ = 2,260,000 J = 2,260 kJ

**c)** Aeg vee kuumutamisel (ainult kuumutamine, mitte aurustamine):
$$t = \frac{Q_1}{P} = \frac{336\,000}{1000} = 336 \text{ s} = 5 \text{ min } 36 \text{ s}$$

**Vastus:** t = 336 s ≈ 5,6 min

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Kuumutamise soojus | 4 |
| b) | Aurustamise soojus | 4 |
| c) | Aeg võimsuse kaudu | 4 |

---

## Ideaalgaas

### Ülesanne 5 (12 punkti)

**Püstitus:**

Ideaalgaas ruumala V = 0,05 m³, rõhk p = 2 × 10⁵ Pa, temperatuur T = 300 K. Gaasi molaarmass M = 32 g/mol, gaasikonstan R = 8,314 J/(mol⋅K).

a) Arvuta gaasi moolide arv.

b) Arvuta gaasi mass.

c) Arvuta gaasi kineetilisest keskmise energia.

**Lahendus:**

**a)** Ideaalgaasi seadus:
$$pV = nRT$$
$$n = \frac{pV}{RT} = \frac{2 \times 10^5 \cdot 0,05}{8,314 \cdot 300}$$
$$n = \frac{10\,000}{2494,2} \approx 4,01 \text{ mol}$$

**Vastus:** n ≈ 4 mol

**b)** Gaasi mass:
$$m = nM = 4,01 \cdot 32 \times 10^{-3} = 0,128 \text{ kg} = 128 \text{ g}$$

**Vastus:** m ≈ 128 g

**c)** Keskmise kineetilisest energia:
$$E_k = \frac{3}{2}nRT = \frac{3}{2} \cdot 4 \cdot 8,314 \cdot 300$$
$$E_k = 1,5 \cdot 4 \cdot 2494,2 = 14\,965 \text{ J} \approx 15 \text{ kJ}$$

**Vastus:** Ek ≈ 15 kJ

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Ideaalgaasi seaduse rakendamine | 3 |
| a) | Õige arvutus | 1 |
| b) | Massi arvutamine molide kaudu | 3 |
| b) | Õige arvutus | 1 |
| c) | Kineetilise energia valem | 2 |
| c) | Õige arvutus | 2 |

---

### Ülesanne 6 (12 punkti)

**Püstitus:**

Ideaalgaas isobaarisel protsessil (p = const): algne ruumala V₁ = 0,01 m³, temperatuur T₁ = 300 K. Gaasigas kuumutatakse T₂ = 450 K-ni.

a) Arvuta lõplik ruumala (Gay-Lussaci seadus).

b) Arvuta rõhk (isobaarne seadus).

c) Arvuta gaasi tehtud töö (isobaarne protsess).

**Lahendus:**

**a)** Gay-Lussaci seadus (isobaarne):
$$\frac{V_1}{T_1} = \frac{V_2}{T_2}$$
$$V_2 = V_1 \frac{T_2}{T_1} = 0,01 \cdot \frac{450}{300} = 0,01 \cdot 1,5 = 0,015 \text{ m}^3$$

**Vastus:** V₂ = 0,015 m³

**b)** Isobaarse protsessi korral rõhk ei muutu: p = const

Rõhu arvutamiseks võib kasutada ideaalgaasi seadust:
$$p = \frac{nRT_1}{V_1}$$

Kuid rõhu konkreetne väärtus sõltub moolide arvust, mis ei ole antud.

**Vastus:** p = const (antud andmetest ei saa konkreetset väärtust)

**c)** Isobaarses protsessis tehtud töö:
$$A = p\Delta V = p(V_2 - V_1)$$

Ideaalgaasi seadusest:
$$A = nR(T_2 - T_1)$$

Konkretset arvutust ei saa ilma p või n andmata.

Kui teadsime p = 1 × 10⁵ Pa:
$$A = 1 \times 10^5 \cdot (0,015 - 0,01) = 1 \times 10^5 \cdot 0,005 = 500 \text{ J}$$

**Vastus:** A = p(V₂ - V₁) või A = nR(T₂ - T₁)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Gay-Lussaci seadus | 4 |
| a) | Õige arvutus | 2 |
| b) | Isobaarne protsess — rõhk jääb samaks | 3 |
| c) | Töö isobaarses protsessis | 3 |

---

### Ülesanne 7 (12 punkti)

**Püstitus:**

Ideaalgaas isotermaalses protsessis (T = const): algne rõhk p₁ = 2 × 10⁵ Pa, ruumala V₁ = 0,02 m³. Gaasi surutakse, kuni ruumala V₂ = 0,01 m³.

a) Arvuta lõplik rõhk (isotermaalne seadus).

b) Arvuta gaasi tehtud töö isotermaalses protsessis.

c) Kas sisemise energia muutub? Põhjenda.

**Lahendus:**

**a)** Boyle'i seadus (isotermaalne):
$$p_1 V_1 = p_2 V_2$$
$$p_2 = p_1 \frac{V_1}{V_2} = 2 \times 10^5 \cdot \frac{0,02}{0,01}$$
$$p_2 = 2 \times 10^5 \cdot 2 = 4 \times 10^5 \text{ Pa}$$

**Vastus:** p₂ = 4 × 10⁵ Pa

**b)** Isotermaalses protsessis tehtud töö:
$$A = nRT \ln\frac{V_1}{V_2} = p_1 V_1 \ln\frac{V_1}{V_2}$$
$$A = 2 \times 10^5 \cdot 0,02 \cdot \ln\frac{0,02}{0,01}$$
$$A = 4000 \cdot \ln(2) = 4000 \cdot 0,693$$
$$A \approx 2772 \text{ J}$$

**Vastus:** A ≈ 2,77 kJ

**c)** Sisemise energia muutus:

Ideaalgaasi sisemise energia sõltub ainult temperatuurist. Isotermaalses protsessis T = const, seega ΔU = 0.

**Vastus:** Sisemise energia ei muutu (ΔU = 0), sest temperatuur on konstantne.

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Boyle'i seadus | 3 |
| a) | Õige arvutus | 1 |
| b) | Isotermaalse töö valem | 3 |
| b) | Õige arvutus (naturaallogi kasutamine) | 2 |
| c) | Sisemise energia ja temperatuuri seos | 3 |

---

## Termodünaamika seadused

### Ülesanne 8 (12 punkti)

**Püstitus:**

Gaas teeb isobaarses protsessis (p = 1 × 10⁵ Pa) tööd A = 500 J, saavutades soojust Q = 1250 J.

a) Arvuta gaasi sisemise energia muutus (esimene termodünaamika seadus).

b) Mis tüüpi protsess see on (soojenemine vai jahtumine)?

c) Arvuta gaasi erisoojus isobaarses protsessis (Cp - Cv suhe).

**Lahendus:**

**a)** Esimene termodünaamika seadus:
$$Q = \Delta U + A$$
$$\Delta U = Q - A = 1250 - 500 = 750 \text{ J}$$

**Vastus:** ΔU = 750 J

**b)** Kuna Q > 0 ja ΔU > 0, siis gaas **soojeneb** ja selle temperatuur tõuseb.

**Vastus:** Soojenemine — gaasi temperatuur tõuseb

**c)** Erisoojus isobaarses protsessis:

Isobaarne erisoojus:
$$C_p = \frac{Q}{n \Delta T}$$

Teeme seose nR(T₂ - T₁) = A:
$$500 = nR \Delta T$$
$$n \Delta T = \frac{500}{R} \approx \frac{500}{8,314} \approx 60,1 \text{ mol⋅K}$$

Siis:
$$C_p = \frac{Q}{n \Delta T} = \frac{1250}{60,1} \approx 20,8 \text{ J/(mol⋅K)}$$

**Vastus:** Cp ≈ 20,8 J/(mol⋅K)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Esimene termodünaamika seadus | 4 |
| a) | Õige arvutus | 2 |
| b) | Soojus ja energia muutuse analüüs | 3 |
| c) | Erisoojuse arvutamine | 3 |

---

### Ülesanne 9 (12 punkti)

**Püstitus:**

Kuum keha (temp T₁ = 400 K) suhtleb külmaga keskkonnaga (temp T₂ = 300 K). Entroopia muutus kehas: ΔS₁ = -10 J/K. Entroopia muutus keskkonna: ΔS₂ = +12 J/K.

a) Arvuta kogu entroopia muutus (teise termodünaamika seaduse kontroll).

b) Kas protsess on spontaanne?

c) Arvuta soojus, mida keha kaotas.

**Lahendus:**

**a)** Kogu entroopia muutus:
$$\Delta S_{\text{kogu}} = \Delta S_1 + \Delta S_2 = -10 + 12 = 2 \text{ J/K}$$

**Vastus:** ΔSkogu = 2 J/K

**b)** Kuna ΔSkogu > 0, siis **protsess on spontaanne** (vastab teisele termodünaamika seadusele).

**Vastus:** Jah, protsess on spontaanne

**c)** Keha entroopia muutus:
$$\Delta S_1 = -\frac{Q}{T_1}$$
$$Q = -T_1 \Delta S_1 = -400 \cdot (-10) = 4000 \text{ J}$$

**Vastus:** Q = 4000 J = 4 kJ (keha kaotas 4 kJ soojust)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Kogu entroopia summa | 3 |
| b) | Teise termodünaamika seaduse rakendamine | 4 |
| c) | Soojuse arvutamine entroopia muutusest | 4 |
| c) | Õige märk (kadu) | 1 |

---

### Ülesanne 10 (12 punkti)

**Püstitus:**

Ideaalse soojusmasin kasutab kumerusi allikast T₁ = 600 K ja eraldab kuumust mahajääma T₂ = 300 K. Soojusmasin saab soojust Q₁ = 3000 J.

a) Arvuta Carnot'i masina teoreetiline kasutegur.

b) Arvuta teoreetiline töö, mida masin teeb.

c) Arvuta soojus, mis mahajääb.

**Lahendus:**

**a)** Carnot'i masina kasutegur:
$$\eta = 1 - \frac{T_2}{T_1} = 1 - \frac{300}{600} = 1 - 0,5 = 0,5 = 50\%$$

**Vastus:** η = 50% = 0,5

**b)** Teoreetiline töö:
$$A = \eta Q_1 = 0,5 \cdot 3000 = 1500 \text{ J}$$

**Vastus:** A = 1500 J = 1,5 kJ

**c)** Mahajäänud soojus:
$$Q_2 = Q_1 - A = 3000 - 1500 = 1500 \text{ J}$$

Kontrolli: $Q_2 = Q_1 \frac{T_2}{T_1} = 3000 \cdot \frac{300}{600} = 1500$ J ✓

**Vastus:** Q₂ = 1500 J = 1,5 kJ

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Carnot'i kasuteguri valem | 3 |
| a) | Õige arvutus | 2 |
| b) | Töö arvutamine kasutegurist | 2 |
| b) | Õige arvutus | 1 |
| c) | Mahajäänud soojuse arvutamine | 2 |
| c) | Kontroll | 2 |

---

**Kokku:** 10 ülesannet × 12 punkti = 120 punkti soojusõpetuse ja termodünaamika kohta

Nende ülesannete harjutamine aitab sul mõista soojusnähtusi ja termodünaamika seadusi!
