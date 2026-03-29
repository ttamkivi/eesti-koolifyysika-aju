# F4 Termodünaamika — Harjutusülesanded

> 10 ülesannet kasvava raskusega. Iga ülesanne sisaldab täislahendust ja hindamisskeemi.

---

## Ülesanne 1 ⭐ (kerge)

**Püstitus:** Ideaalse gaasi mooli arv on 2, rõhk 100 kPa ja ruumala 50 L. Leida gaasikonstandiga temperatuur. Gaasikonstand R = 8,314 J/(mol·K).

**Lahendus:**
Ideaalse gaasi võrrand:
$$pV = nRT$$

Temperatuur:
$$T = \frac{pV}{nR}$$

Ühikute teisendamine: V = 50 L = 0,05 m³, p = 100 kPa = 100000 Pa

$$T = \frac{100000 \cdot 0.05}{2 \cdot 8.314} = \frac{5000}{16.628} \approx 301 \text{ K}$$

**Vastus:** T ≈ 301 K (≈ 28°C)

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Ideaalse gaasi võrrandi tunnus | 2p |
| Ühikute teisendamine | 2p |
| Valemi teisendamine | 2p |
| Arvutus | 3p |
| Lõppvastus Kelvinites | 1p |

---

## Ülesanne 2 ⭐ (kerge)

**Püstitus:** Gaas osaline isotermilises protsessis (T = const). Algseisundis rõhk 2 atm ja ruumala 10 L. Lõppseisundis ruumala 20 L. Leida lõpprõhk.

**Lahendus:**
Isotermilises protsessis (T = const):
$$p_1 V_1 = p_2 V_2$$

$$p_2 = p_1 \frac{V_1}{V_2} = 2 \cdot \frac{10}{20} = 1 \text{ atm}$$

**Vastus:** 1 atm

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Isotermilise protsessi tunnus | 3p |
| Boyle'i seaduse rakendamine | 2p |
| Arvutus | 3p |
| Ühikud | 2p |

---

## Ülesanne 3 ⭐ (kerge)

**Püstitus:** Isobaarne protsess (p = const). Algolukorras T₁ = 300 K ja V₁ = 5 m³. Temperatuur muutub 400 K-ni. Leida lõplik ruumala.

**Lahendus:**
Isobaarses protsessis (p = const):
$$\frac{V_1}{T_1} = \frac{V_2}{T_2}$$

$$V_2 = V_1 \frac{T_2}{T_1} = 5 \cdot \frac{400}{300} = 5 \cdot 1.333 = 6.67 \text{ m}^3$$

**Vastus:** 6,67 m³

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Isobaarse protsessi tunnus | 3p |
| Charlesʼi seaduse rakendamine | 2p |
| Arvutus | 3p |
| Ühikud | 2p |

---

## Ülesanne 4 ⭐⭐ (keskmine)

**Püstitus:** Gaas teeb tööd 1000 J ja sisest energia suureneb 500 J võrra. Leida gaasile antud soojuse hulk. (Esimene termodünaamika seadus)

**Lahendus:**
Termodünaamika I seadus:
$$Q = \Delta U + A$$

Kus:
- Q = soojuse hulk
- ΔU = sisest energia muutus = 500 J
- A = tehtud töö = 1000 J

$$Q = 500 + 1000 = 1500 \text{ J}$$

**Vastus:** 1500 J

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Termodünaamika I seaduse tunnus | 3p |
| Suuruste õige märkamine | 2p |
| Arvutus | 3p |
| Ühikud | 2p |

---

## Ülesanne 5 ⭐⭐ (keskmine)

**Püstitus:** Soojusmasin saab soojust 3000 J ja andab külmavesi 1200 J. Leida masina kasutegur.

**Lahendus:**
Soojusmahina kasutegur:
$$\eta = 1 - \frac{Q_c}{Q_h} = \frac{Q_h - Q_c}{Q_h}$$

Kus:
- Q_h = kuumast allikast saadud soojus = 3000 J
- Q_c = külmale allikale antud soojus = 1200 J

$$\eta = \frac{3000 - 1200}{3000} = \frac{1800}{3000} = 0.6 = 60\%$$

**Vastus:** 60% (või 0,6)

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Kasuteguri valemi tunnus | 3p |
| Soojushulkade õige märkamine | 2p |
| Arvutus | 3p |
| Vastus protsendina | 2p |

---

## Ülesanne 6 ⭐⭐ (keskmine)

**Püstitus:** Isohoorses protsessis (V = const) gaasi rõhk kasvab 50 kPa-lt 200 kPa-le, temperatuur aga 300 K-lt 800 K-le. Kontrolli Gay-Lussac' seadust.

**Lahendus:**
Isohoorses protsessis (V = const):
$$\frac{p_1}{T_1} = \frac{p_2}{T_2}$$

Vasak pool:
$$\frac{p_1}{T_1} = \frac{50}{300} = 0.1667 \text{ kPa/K}$$

Parem pool:
$$\frac{p_2}{T_2} = \frac{200}{800} = 0.25 \text{ kPa/K}$$

Ei võrdu! Kontroll näitab ebakõla.

Korrektne andmed näitaksid: $\frac{50}{300} = \frac{p_2}{800}$ → $p_2 = \frac{50 \cdot 800}{300} = 133.3$ kPa

**Vastus:** Seadus ei ole täidetud antud andmete puhul; peaks olema p₂ ≈ 133,3 kPa

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Gay-Lussac' seaduse tunnus | 2p |
| Vasaku poole arvutus | 2p |
| Parema poole arvutus | 2p |
| Võrdluse tegemine | 2p |
| Järeldus ja seletus | 2p |

---

## Ülesanne 7 ⭐⭐⭐ (raske)

**Püstitus:** Ideaalse gaasi pooles moolis osaline tsükliline protsess. Algseis: p₁ = 100 kPa, V₁ = 10 L, T₁ = 300 K. Isotermiline paisumine: V₂ = 20 L. Isohoornesurumine algolukorrani. Leida: (1) temperatuur pärast isohoorilist protsessi, (2) tehtud töö, (3) sisest energia muutus.

**Lahendus:**

**(1) Tsükli sammud:**

**Samm 1: Isotermiline paisumine (T = const = 300 K)**
$$p_1 V_1 = p_2 V_2$$
$$p_2 = p_1 \frac{V_1}{V_2} = 100 \cdot \frac{10}{20} = 50 \text{ kPa}$$

T₂ = T₁ = 300 K

**Samm 2: Isohoornesurumine (V = const = V₂ = 20 L)**
Lõppseisund: V₃ = V₁ = 10 L

Aga see ei ole isohoornesurumine, sest ruumala muutub. Kirjeldus tähendab isohooriset käiku V = V₂ = 20 L-ga, naastes algse rõhu juurde.

Korrektimine: Isohoornes käik: V = const = 20 L, p muutub 50 kPa-lt p₃-le, et naasta algse temperatuurini.

$$\frac{p_2}{T_2} = \frac{p_3}{T_3}$$

Kui naastakse V₁-ni isohoorsel teel: see on võimatu, sest isohoorses ei saa V muutuda.

Interpreteerime: Isohoornesurumine tähistab p ja T muutust V = 20 L juures, siis isobaarne või teine protsess V₁-ni.

Lihtsam: Tsükli lõpus naastakse algolukorrani (p₁, V₁, T₁).

**(2) Tehtud töö:**

Isotermilise paisumise töö:
$$A_1 = p_1 V_1 \ln \frac{V_2}{V_1} = 100 \times 10 \times \ln(2) = 1000 \times 0.693 = 693 \text{ J}$$

Isohoorses ei tööd ei tee (V = const).

Isobaarne kokkasurumises V₂-st V₁-ni (p = p₂ = 50 kPa):
$$A_3 = p_2(V_1 - V_2) = 50 \times (10 - 20) = 50 \times (-10) = -500 \text{ J}$$

Kogu töö:
$$A = A_1 + A_3 = 693 - 500 = 193 \text{ J}$$

**(3) Sisest energia muutus:**

Kuna tsükkel naastab algolukorrani: ΔU = 0 J

**Vastus:** T₃ = 300 K (algule); A ≈ 193 J; ΔU = 0 J

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Isotermilise paisumise rõhu arvutus | 1p |
| Isotermilise paisumise töö arvutus | 2p |
| Isohoorses protsessis töö | 1p |
| Isobaarse kokkasurumise töö | 2p |
| Kogu töö | 1p |
| Sisest energia muutus | 1p |
| Vastuste korrektsus | 1p |

---

## Ülesanne 8 ⭐⭐⭐ (raske)

**Püstitus:** Carnot' tsükkel töötab kuuma allikaaga T_h = 500 K ja külma allikaaga T_c = 300 K. Leida maksimaalse kasuteguri ja võrrelda see reaalse soojusmahina kasuteguriga 40%.

**Lahendus:**
Carnot' tsükli maksimaalsel kasuteguril:
$$\eta_{Carnot} = 1 - \frac{T_c}{T_h} = 1 - \frac{300}{500} = 1 - 0.6 = 0.4 = 40\%$$

Reaalse soojusmahina kasutegur: 40%

Võrdlus: Reaalse masina kasutegur = Carnot' maksimumne kasutegur. See on ideaalse juhul.

Tegelikkuses η_real < η_Carnot alati.

**Vastus:** η_Carnot = 40%; teoreetiline maksimum võrdub reaalse väärtusega antud näites

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Carnot' kasuteguri valemi tunnus | 3p |
| Temperatuuride õige kasutamine | 2p |
| Arvutus | 2p |
| Võrdlus reaalse kasuteguriga | 2p |
| Järeldus | 1p |

---

## Ülesanne 9 ⭐⭐⭐ (raske)

**Püstitus:** Termodünaamilises protsessis gaasile lisatakse soojust 2500 J, sisemine energia suureneb 1500 J. Leida: (1) gaasi poolt tehtud töö, (2) kui protsess on isobaarne ja gaasi on 1 mool, leida temperatuuride erinevus.

**Lahendus:**

**(1) Tehtud töö (I termodünaamika seadus):**
$$Q = \Delta U + A$$
$$2500 = 1500 + A$$
$$A = 1000 \text{ J}$$

**(2) Temperatuuride erinevus isobaarses protsessis:**

Isobaarses:
$$Q = nC_p \Delta T$$

Ideaalse gaasi jaoks: $C_p = \frac{7}{2}R$ (kahe-aatomne gaas)

$$2500 = 1 \times \frac{7}{2} \times 8.314 \times \Delta T$$
$$2500 = 29.1 \Delta T$$
$$\Delta T = \frac{2500}{29.1} = 85.9 \text{ K} \approx 86 \text{ K}$$

**Vastus:** A = 1000 J; ΔT ≈ 86 K

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| I termodünaamika seaduse rakendamine | 2p |
| Töö arvutus | 2p |
| Isobaarse protsessi tunnus | 1p |
| Soojusmahtuvuse valemi tunnus | 2p |
| Temperatuuride erinevuse arvutus | 2p |
| Vastused | 1p |

---

## Ülesanne 10 ⭐⭐⭐⭐ (olimpiaad)

**Püstitus:** Soojusmasin, mis töötatakse vaheldumisi kuumale (T_h = 600 K) ja külmale (T_c = 300 K) allikale. Masin kasutab 5000 J soojust kuumast allikast iga tsükli kohta. Arvutada: (1) maksimaalsel teoreetilisel kasuteguril töötav tegeliku kasutegur, (2) külmale allikale antud soojus, (3) tehtud töö, (4) kui masin töötab 10 sekundi, leida võimsus.

**Lahendus:**

**(1) Maksimaalsel kasuteguril (Carnot):**
$$\eta_{max} = 1 - \frac{T_c}{T_h} = 1 - \frac{300}{600} = 0.5 = 50\%$$

**(2) Külmale allikale antud soojus:**

Kasutegur:
$$\eta = \frac{A}{Q_h}$$

$$0.5 = \frac{A}{5000}$$
$$A = 2500 \text{ J}$$

Külmale antud soojus:
$$Q_c = Q_h - A = 5000 - 2500 = 2500 \text{ J}$$

**(3) Tehtud töö:**
$$A = 2500 \text{ J}$$

**(4) Võimsus 10 sekundis:**
$$P = \frac{A}{t} = \frac{2500}{10} = 250 \text{ W}$$

**Vastus:** η = 50%; Q_c = 2500 J; A = 2500 J; P = 250 W

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Carnot' kasuteguri arvutus | 1p |
| Kasuteguri rakendamine | 1p |
| Tehtud töö arvutus | 1p |
| Külmale antud soojuse arvutus | 1p |
| Energiajäävuse kontroll | 1p |
| Võimsuse valemi tunnus | 1p |
| Võimsuse arvutus | 1p |
| Vastuste korrektsus | 2p |
