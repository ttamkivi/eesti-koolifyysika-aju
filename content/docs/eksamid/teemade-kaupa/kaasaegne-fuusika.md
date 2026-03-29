# Kaasaegne füüsika — Eksamiülesanded

> Riigieksamite stiilis ülesanded täislahenduste ja hindamisskeemidega.

---

## Fotoefekt

### Ülesanne 1 (12 punkti)

**Püstitus:**

Fotoelektriliselt meetodiga uuritakse metalle. Metall omab tööfunktsiooni A = 3,2 eV. Valgusel lainepikkus λ = 200 nm. Plancki konstant h = 6,63 × 10⁻³⁴ J⋅s, valgusel kiirus c = 3 × 10⁸ m/s, 1 eV = 1,6 × 10⁻¹⁹ J.

a) Arvuta fotoni energia.

b) Kas fotoni energia on piisav elektronide väljastamiseks metallilt?

c) Arvuta maksimaalse kineetilisest energia elektronidel.

**Lahendus:**

**a)** Fotoni energia:
$$E = h\nu = h \frac{c}{\lambda} = 6,63 \times 10^{-34} \cdot \frac{3 \times 10^8}{200 \times 10^{-9}}$$
$$E = 6,63 \times 10^{-34} \cdot 1,5 \times 10^{15} = 9,95 \times 10^{-19} \text{ J}$$

Teisenda elektronvoltidesse:
$$E = \frac{9,95 \times 10^{-19}}{1,6 \times 10^{-19}} \approx 6,22 \text{ eV}$$

**Vastus:** E ≈ 6,2 eV

**b)** Võrdlus tööfunktsiooniga:

E = 6,2 eV > A = 3,2 eV

**Jah, fotoni energia on piisav elektronide väljastamiseks.**

**c)** Maksimaalse kineetilisest energia (Einsteini fotovõrrand):
$$E_k = E - A = 6,2 - 3,2 = 3,0 \text{ eV}$$

SI ühikutes:
$$E_k = 3,0 \text{ eV} = 3,0 \cdot 1,6 \times 10^{-19} = 4,8 \times 10^{-19} \text{ J}$$

**Vastus:** Ek = 3,0 eV = 4,8 × 10⁻¹⁹ J

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Fotoni energia valem | 3 |
| a) | Õige arvutus ja teisendus eV-desse | 2 |
| b) | Energia ja tööfunktsiooni võrdlemine | 3 |
| c) | Einsteini fotovõrrandi rakendamine | 2 |
| c) | Õige arvutus | 2 |

---

### Ülesanne 2 (12 punkti)

**Püstitus:**

Fotoelektri uuringul kirjalikult varieerida valgusel lainepikkust ja mõõta peatuspingega U_s.

Andmed:
- λ₁ = 400 nm, U_s1 = 1,2 V
- λ₂ = 600 nm, U_s2 = 0,2 V

a) Arvuta tööfunktsioon metallist.

b) Arvuta Plancki konstant (kontroll).

c) Arvuta künnelainepikkus (lühem lainepikkus, mille korral fotoefekt algab).

**Lahendus:**

**a)** Peatospinge seotud kineetilisest energiaga:
$$E_k = eU_s$$

Einsteini fotovõrrand:
$$h\nu = A + eU_s$$

Kahest mõõtmisest:
$$h\nu_1 = A + eU_{s1}$$
$$h\nu_2 = A + eU_{s2}$$

Lahutada:
$$h(\nu_1 - \nu_2) = e(U_{s1} - U_{s2})$$
$$h\left(\frac{c}{\lambda_1} - \frac{c}{\lambda_2}\right) = e(U_{s1} - U_{s2})$$

h väärtuse korral kasutame h = 6,63 × 10⁻³⁴ J⋅s ja c = 3 × 10⁸ m/s:

$$A = h\nu_1 - eU_{s1} = h\frac{c}{\lambda_1} - eU_{s1}$$
$$A = 6,63 \times 10^{-34} \cdot \frac{3 \times 10^8}{400 \times 10^{-9}} - 1,6 \times 10^{-19} \cdot 1,2$$
$$A = 6,63 \times 10^{-34} \cdot 7,5 \times 10^{14} - 1,92 \times 10^{-19}$$
$$A = 4,97 \times 10^{-19} - 1,92 \times 10^{-19} = 3,05 \times 10^{-19} \text{ J}$$

Elektronvoltidesse:
$$A = \frac{3,05 \times 10^{-19}}{1,6 \times 10^{-19}} \approx 1,91 \text{ eV}$$

**Vastus:** A ≈ 1,9 eV

**b)** Plancki konstandi kontroll:

Kahe mõõtmise allusel:
$$h = \frac{e(U_{s1} - U_{s2})}{c\left(\frac{1}{\lambda_1} - \frac{1}{\lambda_2}\right)}$$
$$h = \frac{1,6 \times 10^{-19} \cdot (1,2 - 0,2)}{3 \times 10^8 \left(\frac{1}{400 \times 10^{-9}} - \frac{1}{600 \times 10^{-9}}\right)}$$
$$h = \frac{1,6 \times 10^{-19} \cdot 1,0}{3 \times 10^8 \cdot (2,5 \times 10^6 - 1,667 \times 10^6)}$$
$$h = \frac{1,6 \times 10^{-19}}{3 \times 10^8 \cdot 0,833 \times 10^6}$$
$$h = \frac{1,6 \times 10^{-19}}{2,5 \times 10^{14}} = 6,4 \times 10^{-34} \text{ J⋅s}$$

**Vastus:** h ≈ 6,4 × 10⁻³⁴ J⋅s (teoreetiliselt 6,63 × 10⁻³⁴, hästi samakäik)

**c)** Künnelainepikkus (U_s = 0):
$$h\nu_0 = A$$
$$h\frac{c}{\lambda_0} = A$$
$$\lambda_0 = \frac{hc}{A} = \frac{6,63 \times 10^{-34} \cdot 3 \times 10^8}{3,05 \times 10^{-19}}$$
$$\lambda_0 = \frac{19,89 \times 10^{-26}}{3,05 \times 10^{-19}} = 6,52 \times 10^{-7} \text{ m} = 652 \text{ nm}$$

**Vastus:** λ₀ ≈ 650 nm

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Tööfunktsiooni arvutamine ja teisendamine | 4 |
| b) | Plancki konstandi arvutamine tabelist | 3 |
| b) | Kontroll ja võrdlus | 1 |
| c) | Künnelainepikkuse valem | 2 |
| c) | Õige arvutus | 2 |

---

## Aatomi ehitus

### Ülesanne 3 (12 punkti)

**Püstitus:**

Vesiniku aatomi Bohri mudel. Elektroni raadius esimesel orbiidil (Bohri raadius) a₀ = 0,53 × 10⁻¹⁰ m.

a) Arvuta elektroni kiirus esimesel orbiidil.

b) Arvuta elektroni kineetilisest energia esimesel orbiidil.

c) Arvuta ionisatsiooni energia vesiniku aatomille (põhiseisundist).

**Lahendus:**

**a)** Elektron teeb ringliikumist Coulombi jõu all:

Bohri teooria:
$$v_n = \frac{e^2}{2\varepsilon_0 h n}$$

Esimesel orbiidil (n = 1):
$$v_1 = \frac{c}{137} \approx 2,19 \times 10^6 \text{ m/s}$$

(Klassikalisest konstandi: v₁ = c/137 ≈ 0,73% c)

**Vastus:** v₁ ≈ 2,19 × 10⁶ m/s

**b)** Elektroni kineetilisest energia:
$$E_k = \frac{1}{2}m_e v_1^2 = \frac{1}{2} \cdot 9,11 \times 10^{-31} \cdot (2,19 \times 10^6)^2$$
$$E_k = \frac{1}{2} \cdot 9,11 \times 10^{-31} \cdot 4,8 \times 10^{12}$$
$$E_k = 2,19 \times 10^{-18} \text{ J}$$

Elektronvoltidesse:
$$E_k = \frac{2,19 \times 10^{-18}}{1,6 \times 10^{-19}} \approx 13,7 \text{ eV}$$

**Vastus:** Ek ≈ 13,7 eV

**c)** Ionisatsiooni energia (Rydbergi energia):
$$E_{\text{ionisatsioon}} = 13,6 \text{ eV}$$

(Vesiniku aatomi ionisatsiooni energia põhiseisundist on standardne 13,6 eV)

**Vastus:** E_ionisatsioon = 13,6 eV

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Bohri orbiitide kiirus | 4 |
| a) | Õige väärtus | 1 |
| b) | Kineetilisest energia valem | 3 |
| b) | Õige arvutus ja teisendus | 2 |
| c) | Ionisatsiooni energia | 2 |

---

### Ülesanne 4 (12 punkti)

**Püstitus:**

Vesiniku aatomi energiatasemed: E_n = -13,6/n² eV.

a) Arvuta energia untersched üleminek n = 2 → n = 1 tase.

b) Arvuta valgusel lainepikkus, mis vastab sellele üleminnekule.

c) Millele spektri piirkonnale see vastab?

**Lahendus:**

**a)** Energiatasemete erinevus:
$$\Delta E = E_2 - E_1 = -13,6 \cdot \frac{1}{4} - (-13,6 \cdot 1)$$
$$\Delta E = -3,4 + 13,6 = 10,2 \text{ eV}$$

(Negatiivne: energia eraldub)

**Vastus:** ΔE = 10,2 eV

**b)** Valgusel lainepikkus:
$$E = h\nu = h\frac{c}{\lambda}$$
$$\lambda = \frac{hc}{E}$$

Teisenda: 10,2 eV = 10,2 × 1,6 × 10⁻¹⁹ J = 1,632 × 10⁻¹⁸ J

$$\lambda = \frac{6,63 \times 10^{-34} \cdot 3 \times 10^8}{1,632 \times 10^{-18}}$$
$$\lambda = \frac{19,89 \times 10^{-26}}{1,632 \times 10^{-18}} = 1,22 \times 10^{-7} \text{ m} = 122 \text{ nm}$$

**Vastus:** λ ≈ 122 nm

**c)** Spektri piirkond:

122 nm on **ultraviolett piirkond** (UV-B, 280-315 nm piirkonna lähisele).

Täpsemalt: 122 nm on kõrge energiaga UV.

**Vastus:** Ultraviolett (UV) spektri piirkond

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Energiatasemete arvutus Bohri mudeli järgi | 3 |
| a) | Õige erinevus | 2 |
| b) | Lainepikkuse valem | 2 |
| b) | Õige arvutus | 2 |
| c) | Spektri piirkonna määramine | 3 |

---

## Tuumafüüsika

### Ülesanne 5 (12 punkti)

**Püstitus:**

Radioaktiivne süsinik ¹⁴C laguneb beeta-miinuse kaudu. Poolväärtusaeg T = 5730 aastat. Algal isotoobi arv N₀ = 1000.

a) Arvuta lagunemisjadak (λ).

b) Arvuta isotoobi arv pärast 11 460 aastat.

c) Arvuta murdosa järelejäänud isotoopidest.

**Lahendus:**

**a)** Lagunemisjadak:
$$\lambda = \frac{\ln 2}{T} = \frac{0,693}{5730} \approx 1,21 \times 10^{-4} \text{ a}^{-1}$$

(aastate pöördväärtustes)

**Vastus:** λ ≈ 1,21 × 10⁻⁴ a⁻¹

**b)** Isotoobi arv pärast t = 11 460 aastat:

Markeerida: 11 460 = 2 × 5730, seega 2 poolväärtusperioodi.

$$N(t) = N_0 \left(\frac{1}{2}\right)^{t/T}$$
$$N(11460) = 1000 \cdot \left(\frac{1}{2}\right)^{11460/5730}$$
$$N(11460) = 1000 \cdot \left(\frac{1}{2}\right)^2 = 1000 \cdot 0,25 = 250$$

**Vastus:** N = 250

**c)** Murdosa järelejäänud:
$$\frac{N}{N_0} = \frac{250}{1000} = 0,25 = 25\%$$

**Vastus:** 25% (või 1/4)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Lagunemisjadagi arvutamise valem | 3 |
| a) | Õige arvutus | 1 |
| b) | Eksponentsiaalse lagumise valem | 3 |
| b) | Õige arvutus | 2 |
| c) | Murdosa arvutamine | 3 |

---

### Ülesanne 6 (12 punkti)

**Püstitus:**

Tuumareaaktsioon: deuteeriumist ja triitiumist fuusioon heliumiks.
$$^2_1H + ^3_1H \to ^4_2He + ^1_0n + E$$

Vastava masside: m(D) = 2,014 u, m(T) = 3,016 u, m(He) = 4,003 u, m(n) = 1,009 u. 1 u = 931,5 MeV/c².

a) Arvuta mass vahe (defekt).

b) Arvuta väljastatud energia (Q-väärtus).

c) Kas see reaktsioon on eksotermilisest eller endotermilisest?

**Lahendus:**

**a)** Massisüssevus:
$$\Delta m = (m_D + m_T) - (m_{He} + m_n)$$
$$\Delta m = (2,014 + 3,016) - (4,003 + 1,009)$$
$$\Delta m = 5,030 - 5,012 = 0,018 \text{ u}$$

**Vastus:** Δm = 0,018 u

**b)** Väljastatud energia (Einsteini seos):
$$Q = \Delta m \cdot c^2 = 0,018 \cdot 931,5 \text{ MeV}$$
$$Q = 16,77 \text{ MeV}$$

**Vastus:** Q ≈ 17 MeV

**c)** Kuna Q > 0, on väljastatud energiat.

**Reaktsioon on eksotermilisest** — energia vabaneb.

**Vastus:** Eksotermilisest

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Massidefekti arvutamine | 3 |
| a) | Õige arvutus | 1 |
| b) | Energia arvutamine E = Δmc² | 3 |
| b) | Õige arvutus ja ühik | 2 |
| c) | Eksotermilisuse määramine | 3 |

---

## Relatiivsusteooria alused

### Ülesanne 7 (12 punkti)

**Püstitus:**

Osake liigub kiirusega v = 0,6c (60% valgusel kiirusest). Osake puhkemassi m₀ = 1 kg.

a) Arvuta relativistlik mass.

b) Arvuta kineetilisest energia.

c) Arvuta kogu energia.

**Lahendus:**

**a)** Relativistlik mass:
$$m = \frac{m_0}{\sqrt{1 - v^2/c^2}} = \frac{1}{\sqrt{1 - 0,36}} = \frac{1}{\sqrt{0,64}} = \frac{1}{0,8} = 1,25 \text{ kg}$$

**Vastus:** m = 1,25 kg

**b)** Kineetilisest energia:
$$E_k = (\gamma - 1)m_0 c^2 = (1,25 - 1) \cdot 1 \cdot (3 \times 10^8)^2$$
$$E_k = 0,25 \cdot 9 \times 10^{16} = 2,25 \times 10^{16} \text{ J}$$

**Vastus:** Ek = 2,25 × 10¹⁶ J = 22,5 PJ

**c)** Kogu energia:
$$E_{\text{kogu}} = \gamma m_0 c^2 = 1,25 \cdot 1 \cdot 9 \times 10^{16}$$
$$E_{\text{kogu}} = 1,125 \times 10^{17} \text{ J}$$

Kontrolli: $E_{\text{kogu}} = E_k + m_0 c^2 = 2,25 \times 10^{16} + 9 \times 10^{16} = 1,125 \times 10^{17}$ J ✓

**Vastus:** Ekogu = 1,125 × 10¹⁷ J = 112,5 PJ

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Relativistlik tegur γ | 3 |
| a) | Relativistlike massi arvutamine | 1 |
| b) | Kineetilisest energia valem | 3 |
| b) | Õige arvutus | 2 |
| c) | Kogu energia ja kontrolli | 3 |

---

### Ülesanne 8 (12 punkti)

**Püstitus:**

Energia-mass ekvivalents: E = mc². Kaalida, kui palju energiat saab vabaneda, kui muundatakse 1 kg materjali täielikult energiaks.

a) Arvuta väljastatud energia 1 kg materjali täielik muundamisel.

b) Võrdle seda energiat tuumapommi (1 megatoon TNT ≈ 4,2 × 10¹⁵ J).

c) Arvuta ekvivalentsel aja (tunni kohta), mille jooksul inimese keha saab väljastada sellise energiaga.

**Lahendus:**

**a)** Energia 1 kg materjali täielikul muundamisel:
$$E = mc^2 = 1 \cdot (3 \times 10^8)^2 = 9 \times 10^{16} \text{ J}$$

**Vastus:** E = 9 × 10¹⁶ J

**b)** Võrdlus tuumapommiga:

Tuumapommi energia: 1 MT = 4,2 × 10¹⁵ J

$$\frac{E}{1 \text{ MT}} = \frac{9 \times 10^{16}}{4,2 \times 10^{15}} \approx 21,4$$

**Energia on umbes 21 megatooni TNT energiaga samaväärsed.**

**Vastus:** 21,4 megatooni

**c)** Inimese keha tavapärane võimsus ~100 W (1 inimene puhkeolekus):

Aeg sama energiaga:
$$t = \frac{E}{P} = \frac{9 \times 10^{16}}{100} = 9 \times 10^{14} \text{ s}$$

Teisenda aastatesse:
$$t = \frac{9 \times 10^{14}}{365,25 \cdot 24 \cdot 3600} = \frac{9 \times 10^{14}}{3,156 \times 10^7} \approx 2,85 \times 10^7 \text{ aastat}$$

**Vastus:** ~28,5 miljonit aastat (või 9 × 10¹⁴ sekundit)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Energia-mass ekvivalentsi rakendamine | 3 |
| a) | Õige arvutus | 1 |
| b) | Võrdlus tuumapommiga | 4 |
| c) | Ajaarvutus võimsuse kaudu | 3 |
| c) | Teisendus aastatesse | 1 |

---

**Kokku:** 8 ülesannet × 12 punkti = 96 punkti kaasaegse füüsika kohta

Nende ülesannete harjutamine aitab sul mõista kaasaegse füüsika (kvantmehaanika, tuuma- ja relatiivsusteooria) aluste!
