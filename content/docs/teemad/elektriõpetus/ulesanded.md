# Elektriõpetus — Harjutusülesanded (9. klass)

> 10 ülesannet kasvava raskusega. Lihtne keel ja näited Eestist.

---

## Ülesanne 1 ⭐ (kerge)

**Püstitus:** Elektrilamp ühendatakse 230 V pingega. Lambi takistus on 1000 oomi. Arvuta voolutugevus lambi juures.

**Lahendus:**

Ohmi seadus:
$$I = \frac{U}{R}$$

Kus:
- U = 230 V (pinge)
- R = 1000 Ω (takistus)

$$I = \frac{230}{1000} = 0,23 \text{ A}$$

**Vastus:** Voolutugevus on 0,23 amprit.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Ohmi seaduse teadmine | 4p |
| Suuruste määramine | 2p |
| Arvutamine | 3p |
| Vastus õiges ühikus | 1p |

---

## Ülesanne 2 ⭐ (kerge)

**Püstitus:** Elektrijuhe on kupariväävast ja pikkusega 100 m. Juhe ristlõike pindala on 2,5 mm². Kupari eritakistus on ρ = 0,017 Ω·mm²/m. Arvuta juhe takistus.

**Lahendus:**

Takistuse valem:
$$R = \rho \times \frac{l}{S}$$

Kus:
- ρ = 0,017 Ω·mm²/m (eritakistus)
- l = 100 m (pikkus)
- S = 2,5 mm² (ristlõike pindala)

$$R = 0,017 \times \frac{100}{2,5} = 0,017 \times 40 = 0,68 \text{ Ω}$$

**Vastus:** Juhe takistus on 0,68 oomi.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Takistuse valemi teadmine | 3p |
| Suuruste määramine | 2p |
| Arvutamine | 3p |
| Vastus | 2p |

---

## Ülesanne 3 ⭐ (kerge)

**Püstitus:** Kaks takistit 10 Ω ja 20 Ω ühendatakse järjest. Ühenduse otste vahel on pinge 60 V. Arvuta voolutugevus.

**Lahendus:**

Jadaühendus: kogu takistus on summa

$$R_{\text{kogu}} = R_1 + R_2 = 10 + 20 = 30 \text{ Ω}$$

Ohmi seadus:
$$I = \frac{U}{R_{\text{kogu}}} = \frac{60}{30} = 2 \text{ A}$$

**Vastus:** Voolutugevus on 2 amprit.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Jadaühenduse reegli teadmine | 3p |
| Kogu takistuse arvutamine | 2p |
| Ohmi seaduse rakendamine | 3p |
| Vastus | 2p |

---

## Ülesanne 4 ⭐⭐ (keskmine)

**Püstitus:** Kaks takistit 10 Ω ja 20 Ω ühendatakse rööbiti. Ühenduse otste vahel on pinge 60 V. Arvuta kogu voolutugevus.

**Lahendus:**

Rööpühendus: vastastikune takistus

$$\frac{1}{R_{\text{kogu}}} = \frac{1}{R_1} + \frac{1}{R_2}$$

$$\frac{1}{R_{\text{kogu}}} = \frac{1}{10} + \frac{1}{20} = \frac{2}{20} + \frac{1}{20} = \frac{3}{20}$$

$$R_{\text{kogu}} = \frac{20}{3} \approx 6,67 \text{ Ω}$$

Kogu voolutugevus:
$$I_{\text{kogu}} = \frac{U}{R_{\text{kogu}}} = \frac{60}{6,67} = 9 \text{ A}$$

**Vastus:** Kogu voolutugevus on 9 amprit.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Rööpühenduse valemi teadmine | 3p |
| Kogu takistuse arvutamine | 3p |
| Ohmi seaduse rakendamine | 2p |
| Vastus | 2p |

---

## Ülesanne 5 ⭐⭐ (keskmine)

**Püstitus:** Elektrolamp käib 5 tundi ööpäevas. Lambi võimsus on 75 W. Tavahind on 0,15 eurot kWh-st. Arvuta kuue kuu elektrikulud.

**Lahendus:**

Päevane energiatarbimine:
$$E_{\text{päev}} = P \times t = 75 \text{ W} \times 5 \text{ h} = 375 \text{ Wh} = 0,375 \text{ kWh}$$

Kuue kuu energiatarbimine (180 päeva):
$$E_{\text{6 kuu}} = 0,375 \times 180 = 67,5 \text{ kWh}$$

Kulud:
$$\text{Kulu} = 67,5 \times 0,15 = 10,125 \text{ eurot} \approx 10,13 \text{ eurot}$$

**Vastus:** Kuue kuu elektrikulud on ligikaudu 10,13 eurot.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Energiavõimsuse valemi teadmine | 2p |
| Päevase energiatarbe arvutamine | 2p |
| Kuue kuu tarbimine | 2p |
| Kulude arvutamine | 2p |
| Vastus | 2p |

---

## Ülesanne 6 ⭐⭐ (keskmine)

**Püstitus:** Elektrimootoris on toitepinge 380 V ja voolutugevus 15 A. Mootoris tekkiv soojus on 2 kW. Arvuta motori mehhaaniline võimsus.

**Lahendus:**

Elektriline võimsus:
$$P_{\text{el}} = U \times I = 380 \times 15 = 5700 \text{ W} = 5,7 \text{ kW}$$

Soojuse kaomine: 2 kW

Mehhaaniline võimsus (kasulik võimsus):
$$P_{\text{meh}} = P_{\text{el}} - P_{\text{kadu}} = 5,7 - 2 = 3,7 \text{ kW}$$

Kasutegur:
$$\eta = \frac{P_{\text{meh}}}{P_{\text{el}}} = \frac{3,7}{5,7} \approx 65\%$$

**Vastus:** Mehhaaniline võimsus on 3,7 kW, kasutegur 65%.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Elektrivoolu võimsuse valem | 2p |
| Arvutamine | 2p |
| Kasulikule võimsuse arvutamine | 2p |
| Kasuteguri valemi teadmine | 2p |
| Vastused | 2p |

---

## Ülesanne 7 ⭐⭐⭐ (raske)

**Püstitus:** Kolm takistit 4 Ω, 6 Ω ja 12 Ω ühendatakse rööbiti. Ühenduse otste vahel on pinge 24 V. Arvuta: a) kogu takistus, b) kogu voolutugevus, c) voolutugevus igas takistis.

**Lahendus:**

**a) Kogu takistus:**

$$\frac{1}{R_{\text{kogu}}} = \frac{1}{4} + \frac{1}{6} + \frac{1}{12}$$

Ühendage nimetajad (LCD = 12):
$$\frac{1}{R_{\text{kogu}}} = \frac{3}{12} + \frac{2}{12} + \frac{1}{12} = \frac{6}{12} = \frac{1}{2}$$

$$R_{\text{kogu}} = 2 \text{ Ω}$$

**b) Kogu voolutugevus:**

$$I_{\text{kogu}} = \frac{U}{R_{\text{kogu}}} = \frac{24}{2} = 12 \text{ A}$$

**c) Voolutugevus igas takistis:**

Rööpühenduses on pinge sama:

$$I_1 = \frac{U}{R_1} = \frac{24}{4} = 6 \text{ A}$$

$$I_2 = \frac{U}{R_2} = \frac{24}{6} = 4 \text{ A}$$

$$I_3 = \frac{U}{R_3} = \frac{24}{12} = 2 \text{ A}$$

Kontroll: I₁ + I₂ + I₃ = 6 + 4 + 2 = 12 A = I_kogu ✓

**Vastus:** a) Kogu takistus 2 Ω, b) Kogu voolutugevus 12 A, c) Voolutugevused: 6 A, 4 A ja 2 A.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Rööpühenduse valemi rakendamine | 2p |
| Kogu takistuse arvutamine | 2p |
| Kogu voolutugevuse arvutamine | 2p |
| Voolutugevuste arvutamine igas takistis | 2p |
| Kontroll ja vastused | 2p |

---

## Ülesanne 8 ⭐⭐⭐ (raske)

**Püstitus:** Elektromagnetisse käitavad takistid: jadaühenduses 20 Ω ja 30 Ω. Jadaühendus ühendatakse 10 Ω takistiga rööbiti. Ühenduse otste vahel on pinge 100 V. Arvuta kogu voolutugevus.

**Lahendus:**

**Osa 1: Jadaühendus**

Jadaühendus: R₁ + R₂ = 20 + 30 = 50 Ω

Voolutugevus jadaühenduses:
$$I_1 = \frac{U}{R_{\text{jada}}} = \frac{100}{50} = 2 \text{ A}$$

**Osa 2: Rööpühenduses teine haru**

Voolutugevus 10 Ω takistis:
$$I_2 = \frac{U}{R_3} = \frac{100}{10} = 10 \text{ A}$$

**Kogu voolutugevus:**

$$I_{\text{kogu}} = I_1 + I_2 = 2 + 10 = 12 \text{ A}$$

**Vastus:** Kogu voolutugevus on 12 amprit.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Jadaühenduse mõistmine | 2p |
| Jadaühenduse voolutugevuse arvutamine | 2p |
| Rööpühenduse teise haru voolutugevus | 2p |
| Kogu voolutugevuse arvutamine | 2p |
| Vastus | 2p |

---

## Ülesanne 9 ⭐⭐⭐ (raske)

**Püstitus:** Elektrisöetava takistus on 48 Ω ja see ühendatakse 240 V pingega. Arvuta: a) voolutugevus, b) võimsus, c) energia, mida tarbib 30 minutit, d) soojus, mis vabaneb.

**Lahendus:**

**a) Voolutugevus:**

$$I = \frac{U}{R} = \frac{240}{48} = 5 \text{ A}$$

**b) Võimsus:**

$$P = U \times I = 240 \times 5 = 1200 \text{ W} = 1,2 \text{ kW}$$

Või:
$$P = \frac{U^2}{R} = \frac{240^2}{48} = \frac{57 600}{48} = 1200 \text{ W}$$

**c) Energia 30 minutit:**

30 min = 0,5 h

$$E = P \times t = 1,2 \text{ kW} \times 0,5 \text{ h} = 0,6 \text{ kWh} = 2 160 000 \text{ J} = 2,16 \text{ MJ}$$

**d) Soojus:**

Elektrisöetavas muutub kõik energia soojuseks:

$$Q = E = 2160 000 \text{ J}$$

**Vastus:** a) Voolutugevus 5 A, b) Võimsus 1,2 kW, c) Energia 2,16 MJ, d) Soojus 2,16 MJ.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Ohmi seaduse rakendamine | 1p |
| Võimsuse arvutamine | 2p |
| Energia arvutamine | 2p |
| Soojuse arvutamine | 2p |
| Ühikute teisendamine | 1p |
| Vastused | 2p |

---

## Ülesanne 10 ⭐⭐⭐⭐ (olümpiaad)

**Püstitus:** Elektrivõrgu pinges on 230 V ja tavahind on 0,15 eurot kWh-st. Kodust kasutavad käivad: elektrijahutik (võimsus 150 W, käivitus 6 tundi ööpäevas), elektrilamp (100 W, 8 h), elektrimootoriga pesmasin (1500 W, 2 h nädal) ja elektrilamp (40 W, 4 h). Arvuta kuukonna (30 päeva) elektrikulud.

**Lahendus:**

**1. Jahutik:**
- Energiatarbimine päevas: 150 W × 6 h = 900 Wh = 0,9 kWh
- Kuus: 0,9 × 30 = 27 kWh

**2. Elektrilamp (100 W):**
- Päev: 100 W × 8 h = 800 Wh = 0,8 kWh
- Kuus: 0,8 × 30 = 24 kWh

**3. Pesmasin (nädal):**
- Nädal: 1500 W × 2 h = 3000 Wh = 3 kWh
- Kuus (4 nädalat): 3 × 4 = 12 kWh

**4. Elektrilamp (40 W):**
- Päev: 40 W × 4 h = 160 Wh = 0,16 kWh
- Kuus: 0,16 × 30 = 4,8 kWh

**Kogu energiatarbimine kuus:**

E_kogu = 27 + 24 + 12 + 4,8 = 67,8 kWh

**Kuude kulud:**

Kulu = 67,8 × 0,15 = 10,17 eurot

**Vastus:** Kuululine elektrikulu on ligikaudu 10,17 eurot.

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Jahutiku energiatarbe arvutamine | 2p |
| Lambi energiatarbe arvutamine | 2p |
| Pesumasina energiatarbe arvutamine | 2p |
| Teise lambi energiatarbe arvutamine | 1p |
| Kogu energiatarbe summeerimine | 1p |
| Kuude kulude arvutamine | 1p |
| Vastus | 1p |

---