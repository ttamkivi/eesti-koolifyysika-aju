# F5 Elektrostaatika ja alalisvool — Harjutusülesanded

> 10 ülesannet kasvava raskusega. Iga ülesanne sisaldab täislahendust ja hindamisskeemi.

---

## Ülesanne 1 ⭐ (kerge)

**Püstitus:** Kaks punktlaengut: q₁ = 2 μC ja q₂ = 3 μC asuvad üksteisest 20 cm kaugusel. Leida Coulombi jõud nende vahel. (k = 9 × 10⁹ N·m²/C²)

**Lahendus:**
Coulombi seadus:
$$F = k \frac{q_1 q_2}{r^2}$$

Ühikud: r = 0,2 m; q₁ = 2 × 10⁻⁶ C; q₂ = 3 × 10⁻⁶ C

$$F = 9 \times 10^9 \times \frac{2 \times 10^{-6} \times 3 \times 10^{-6}}{(0.2)^2}$$

$$F = 9 \times 10^9 \times \frac{6 \times 10^{-12}}{0.04}$$

$$F = 9 \times 10^9 \times 1.5 \times 10^{-10} = 1.35 \text{ N}$$

**Vastus:** 1,35 N

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Coulombi seaduse tunnus | 2p |
| Ühikute teisendamine | 2p |
| Arvutus etapiti | 4p |
| Lõppvastus | 2p |

---

## Ülesanne 2 ⭐ (kerge)

**Püstitus:** Elektrivälja tugevus 500 N/C. Leida jõud 5 μC laengule selles väljas.

**Lahendus:**
Elektriväljade jõud:
$$F = qE$$

$$F = 5 \times 10^{-6} \times 500 = 2.5 \times 10^{-3} = 0.0025 \text{ N}$$

**Vastus:** 0,0025 N (või 2,5 mN)

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Elektrivälja valemi tunnus | 3p |
| Ühikute teisendamine | 2p |
| Arvutus | 3p |
| Ühikud | 2p |

---

## Ülesanne 3 ⭐ (kerge)

**Püstitus:** Lamekondensaator plaatide vahel on 2 mm, plaatide pindala 100 cm². Leida kondensaatori mahtuvus. (ε₀ = 8,85 × 10⁻¹² F/m, dielektriku konstant ε = 1)

**Lahendus:**
Lamekondensaatori mahtuvus:
$$C = \varepsilon \varepsilon_0 \frac{S}{d}$$

Ühikud: S = 100 cm² = 0,01 m²; d = 2 mm = 0,002 m

$$C = 1 \times 8.85 \times 10^{-12} \times \frac{0.01}{0.002}$$

$$C = 8.85 \times 10^{-12} \times 5 = 4.425 \times 10^{-11} \text{ F}$$

$$C = 44.25 \text{ pF}$$

**Vastus:** 44,25 pF

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Mahtuvuse valemi tunnus | 2p |
| Ühikute teisendamine | 3p |
| Arvutus | 3p |
| Vastus pikofaradi ühikus | 2p |

---

## Ülesanne 4 ⭐⭐ (keskmine)

**Püstitus:** Vooluringis on takistused R₁ = 6 Ω, R₂ = 3 Ω ja R₃ = 2 Ω järjestikku ühendatud. Tegemist on 12 V pingeallika. Leida: (1) kogu takistus, (2) vool ringis, (3) pinged iga takistuse peal.

**Lahendus:**

**(1) Kogu takistus (järjestikku):**
$$R_{kogu} = R_1 + R_2 + R_3 = 6 + 3 + 2 = 11 \text{ Ω}$$

**(2) Vool (Ohmi seadus):**
$$I = \frac{U}{R_{kogu}} = \frac{12}{11} = 1.09 \text{ A}$$

**(3) Pinged:**
$$U_1 = IR_1 = 1.09 \times 6 = 6.54 \text{ V}$$
$$U_2 = IR_2 = 1.09 \times 3 = 3.27 \text{ V}$$
$$U_3 = IR_3 = 1.09 \times 2 = 2.18 \text{ V}$$

Kontrollimine: 6,54 + 3,27 + 2,18 = 11,99 ≈ 12 V ✓

**Vastus:** R_kogu = 11 Ω; I ≈ 1,09 A; U₁ ≈ 6,54 V; U₂ ≈ 3,27 V; U₃ ≈ 2,18 V

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Järjestikku takistuse liitmise tunnus | 2p |
| Kogu takistuse arvutus | 1p |
| Ohmi seaduse rakendamine | 2p |
| Voolu arvutus | 1p |
| Pingete arvutus | 2p |
| Kontrollimine | 1p |
| Lõppvastused | 1p |

---

## Ülesanne 5 ⭐⭐ (keskmine)

**Püstitus:** Vooluringis R₁ = 4 Ω ja R₂ = 6 Ω on paralleelselt ühendatud 12 V allikale. Leida: (1) kogu takistus, (2) koguvool, (3) voolu iga haru peal.

**Lahendus:**

**(1) Kogu takistus (paralleelselt):**
$$\frac{1}{R_{kogu}} = \frac{1}{R_1} + \frac{1}{R_2} = \frac{1}{4} + \frac{1}{6} = \frac{3 + 2}{12} = \frac{5}{12}$$

$$R_{kogu} = \frac{12}{5} = 2.4 \text{ Ω}$$

**(2) Koguvool (Ohmi seadus):**
$$I = \frac{U}{R_{kogu}} = \frac{12}{2.4} = 5 \text{ A}$$

**(3) Voolu iga haru peal:**
$$I_1 = \frac{U}{R_1} = \frac{12}{4} = 3 \text{ A}$$
$$I_2 = \frac{U}{R_2} = \frac{12}{6} = 2 \text{ A}$$

Kontrollimine: I₁ + I₂ = 3 + 2 = 5 A = I ✓

**Vastus:** R_kogu = 2,4 Ω; I = 5 A; I₁ = 3 A; I₂ = 2 A

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Paralleelse takistuse liitmise tunnus | 2p |
| Kogu takistuse arvutus | 2p |
| Kogevoolu arvutus | 2p |
| Harude voolu arvutus | 2p |
| Kontrollimine | 1p |
| Vastused | 1p |

---

## Ülesanne 6 ⭐⭐ (keskmine)

**Püstitus:** Elektrikütuse takistus 10 Ω, pingeallika emj ε = 220 V ja sisetakistus r = 2 Ω. Leida: (1) vool ringis, (2) pinge kutsuse otstel, (3) võimsus välisringis.

**Lahendus:**

**(1) Vool (Ohmi seadus kogu ringi kohta):**
$$I = \frac{\varepsilon}{R + r} = \frac{220}{10 + 2} = \frac{220}{12} = 18.33 \text{ A}$$

**(2) Pinge kutsuse otstel (väline pinge):**
$$U = \varepsilon - Ir = 220 - 18.33 \times 2 = 220 - 36.67 = 183.33 \text{ V}$$

Või: $$U = IR = 18.33 \times 10 = 183.3 \text{ V}$$ ✓

**(3) Võimsus välisringis:**
$$P = UI = 183.33 \times 18.33 = 3360 \text{ W}$$

Või: $$P = I^2 R = (18.33)^2 \times 10 = 335.98 \times 10 = 3360 \text{ W}$$

**Vastus:** I ≈ 18,33 A; U ≈ 183,33 V; P ≈ 3360 W

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Kogu takistuse arvestamine | 2p |
| Voolu arvutus | 2p |
| Välist pinget arvutus | 2p |
| Võimsuse arvutus | 2p |
| Alternatiivne kontroll | 1p |
| Vastused | 1p |

---

## Ülesanne 7 ⭐⭐⭐ (raske)

**Püstitus:** Kombineeritud ahel: R₁ = 2 Ω ja R₂ = 3 Ω paralleelselt, seejärel R₃ = 5 Ω järjestikku. Allikas 20 V. Leida: (1) kogu takistus, (2) vool ringis, (3) pinge paralleelse osa peal, (4) voolu iga paralleelse haru peal.

**Lahendus:**

**(1) Paralleelse osa takistus:**
$$\frac{1}{R_{parallel}} = \frac{1}{2} + \frac{1}{3} = \frac{5}{6}$$
$$R_{parallel} = 1.2 \text{ Ω}$$

Kogu takistus:
$$R_{kogu} = R_{parallel} + R_3 = 1.2 + 5 = 6.2 \text{ Ω}$$

**(2) Vool ringis:**
$$I = \frac{U}{R_{kogu}} = \frac{20}{6.2} = 3.23 \text{ A}$$

**(3) Pinge paralleelse osa peal:**
$$U_{parallel} = I \times R_{parallel} = 3.23 \times 1.2 = 3.87 \text{ V}$$

**(4) Voolu paralleelsetes harudes:**
$$I_1 = \frac{U_{parallel}}{R_1} = \frac{3.87}{2} = 1.94 \text{ A}$$
$$I_2 = \frac{U_{parallel}}{R_2} = \frac{3.87}{3} = 1.29 \text{ A}$$

Kontrollimine: I₁ + I₂ = 1,94 + 1,29 = 3,23 A = I ✓

**Vastus:** R_kogu = 6,2 Ω; I = 3,23 A; U_parallel ≈ 3,87 V; I₁ ≈ 1,94 A; I₂ ≈ 1,29 A

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Paralleelse takistuse arvutus | 1p |
| Järjestikku takistuste liitmine | 1p |
| Kogu takistus | 1p |
| Voolu arvutus | 1p |
| Paralleelse osa pinge | 1p |
| Harude voolu arvutus | 2p |
| Kontrollimine | 1p |
| Vastused | 1p |

---

## Ülesanne 8 ⭐⭐⭐ (raske)

**Püstitus:** Elektrostaatika: ühtlases elektriväljas E = 1000 N/C, otsekul 50 cm pikkus. Laeng liigub välja suunas. Leida: (1) jõud 2 μC laengule, (2) tehtud töö, (3) välja potentsiaali erinevus, (4) laengu potentsiaalne energia muutus.

**Lahendus:**

**(1) Jõud:**
$$F = qE = 2 \times 10^{-6} \times 1000 = 0.002 \text{ N} = 2 \text{ mN}$$

**(2) Tehtud töö:**
$$A = F \times d = 0.002 \times 0.5 = 0.001 \text{ J} = 1 \text{ mJ}$$

**(3) Potentsiaali erinevus:**
$$U = E \times d = 1000 \times 0.5 = 500 \text{ V}$$

**(4) Potentsiaalse energia muutus:**
$$\Delta E_p = q \times U = 2 \times 10^{-6} \times 500 = 0.001 \text{ J} = 1 \text{ mJ}$$

Või: ΔE_p = -A (energia väheneb, kuna laeng liigub jõu suunas)

**Vastus:** F = 0,002 N; A = 0,001 J; U = 500 V; ΔE_p = -0,001 J

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Jõu arvutus | 1p |
| Töö arvutus | 2p |
| Potentsiaali erinevuse arvutus | 2p |
| Potentsiaalse energia muutus | 2p |
| Seosed töö ja energiaga | 1p |
| Vastused | 1p |

---

## Ülesanne 9 ⭐⭐⭐ (raske)

**Püstitus:** RC-ringi laadimine: kondensaator C = 10 μF, takistus R = 1000 Ω, allikas U = 100 V. Leida: (1) maksimaalne laeng kondensaatoril, (2) ajakonstant, (3) laeng 5 ms pärast sisselülitamist.

**Lahendus:**

**(1) Maksimaalne laeng:**
$$Q_{max} = C \times U = 10 \times 10^{-6} \times 100 = 10^{-3} \text{ C} = 1 \text{ mC}$$

**(2) Ajakonstant:**
$$\tau = R \times C = 1000 \times 10 \times 10^{-6} = 0.01 \text{ s} = 10 \text{ ms}$$

**(3) Laeng 5 ms pärast:**

Laadimise ajal:
$$Q(t) = Q_{max}(1 - e^{-t/\tau})$$

$$Q(0.005) = 10^{-3}(1 - e^{-0.005/0.01})$$
$$Q(0.005) = 10^{-3}(1 - e^{-0.5})$$
$$Q(0.005) = 10^{-3}(1 - 0.606)$$
$$Q(0.005) = 10^{-3} \times 0.394 = 0.394 \text{ mC}$$

**Vastus:** Q_max = 1 mC; τ = 10 ms; Q(5ms) ≈ 0,394 mC

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Maksimaalse laengu valemi tunnus | 2p |
| Laengu arvutus | 1p |
| Ajakonstandi valemi tunnus | 2p |
| Ajakonstandi arvutus | 1p |
| Eksponentsiaalse funktsioon rakendamine | 2p |
| Laengu arvutus 5 ms pärast | 1p |
| Vastused | 1p |

---

## Ülesanne 10 ⭐⭐⭐⭐ (olimpiaad)

**Püstitus:** Keerulinen kombineeritud ringis: R₁ = 6 Ω, R₂ = 3 Ω paralleelselt; seejärel R₃ = 2 Ω järjestikku; siis R₄ = 4 Ω ja R₅ = 12 Ω paralleelselt. Allikas: ε = 24 V, r = 1 Ω. Leida: (1) kogu takistus, (2) vool ringis, (3) pinge R₄ ja R₅ paralleelsel osal, (4) voolu iga paralleelse haru peal (R₁, R₂ ja R₄, R₅).

**Lahendus:**

**(1) Kogu takistus:**

Esimene paralleelse osa (R₁, R₂):
$$\frac{1}{R_{12}} = \frac{1}{6} + \frac{1}{3} = \frac{1 + 2}{6} = \frac{1}{2}$$
$$R_{12} = 2 \text{ Ω}$$

Teine paralleelse osa (R₄, R₅):
$$\frac{1}{R_{45}} = \frac{1}{4} + \frac{1}{12} = \frac{3 + 1}{12} = \frac{1}{3}$$
$$R_{45} = 3 \text{ Ω}$$

Kogu väline takistus:
$$R_{väline} = R_{12} + R_3 + R_{45} = 2 + 2 + 3 = 7 \text{ Ω}$$

Kogu takistus koos sisetakistusega:
$$R_{kogu} = R_{väline} + r = 7 + 1 = 8 \text{ Ω}$$

**(2) Vool ringis (kogu vool):**
$$I = \frac{\varepsilon}{R_{kogu}} = \frac{24}{8} = 3 \text{ A}$$

**(3) Pinge R₄ ja R₅ paralleelsel osal:**

$$U_{45} = I \times R_{45} = 3 \times 3 = 9 \text{ V}$$

**(4) Voolu paralleelsetes harudes:**

Esimene paralleelse osa (pingestandarte R₁, R₂):
$$U_{12} = I \times R_{12} = 3 \times 2 = 6 \text{ V}$$

$$I_1 = \frac{U_{12}}{R_1} = \frac{6}{6} = 1 \text{ A}$$
$$I_2 = \frac{U_{12}}{R_2} = \frac{6}{3} = 2 \text{ A}$$

Kontroll: I₁ + I₂ = 1 + 2 = 3 A = I ✓

Teine paralleelse osa:
$$I_4 = \frac{U_{45}}{R_4} = \frac{9}{4} = 2.25 \text{ A}$$
$$I_5 = \frac{U_{45}}{R_5} = \frac{9}{12} = 0.75 \text{ A}$$

Kontroll: I₄ + I₅ = 2,25 + 0,75 = 3 A = I ✓

**Vastus:** R_kogu = 8 Ω; I = 3 A; U_{45} = 9 V; I₁ = 1 A; I₂ = 2 A; I₄ = 2,25 A; I₅ = 0,75 A

**Hindamisskeem (10p):**
| Samm | Punktid |
|------|---------|
| Esimene paralleelse arvutus | 1p |
| Teine paralleelse arvutus | 1p |
| Järjestikku summeerimine | 1p |
| Sisetakistuse arvestamine | 1p |
| Voolu arvutus | 1p |
| Esimese paralleelse osa pinge | 1p |
| Teise paralleelse osa pinge | 1p |
| Harude voolu arvutus | 2p |
| Kontrollimine | 1p |
