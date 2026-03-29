# Optika ja lained — Eksamiülesanded

> Riigieksamite stiilis ülesanded täislahenduste ja hindamisskeemidega.

---

## Geomeetriline optika

### Ülesanne 1 (12 punkti)

**Püstitus:**

Valgusvihk langeb peeglis nurga θ₁ = 30° alla. Peegel on tasane.

a) Arvuta peegeldusünurk.

b) Tee joonis, mis näitab langemisnurka ja peegeldusisnurka.

c) Kirjuta peegeldusseadus ja häira see ülesandes rakendada.

**Lahendus:**

**a)** Peegeldusseaduse järgi on peegeldusünurk võrdne langemisnurgaga:
$$\theta_r = \theta_i = 30°$$

**Vastus:** θᵣ = 30°

**b)** Joonis:
```
        Langev kiir
        ↘
    ────────────────  Peegel
        ↙
     Peegeldunud kiir

    Normal (⊥)
         ↑
         |
    ──30°|30°──
         |
```

**c)** Peegeldusseadus: **Langemisnurk võrdub peegeldusisnurgaga, ja langenud kiir, peegeldunud kiir ning pinnanormaali asuvad samas tasandis.**

Rakendamine: Kuna langemisnurk on 30°, on peegeldusünurk samuti 30°.

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Peegeldusseaduse rakendamine | 3 |
| a) | Õige arvutus | 1 |
| b) | Õige joonis langujaga ja peegeldunud kiirega | 4 |
| c) | Peegeldusseaduse sõnastamine | 2 |
| c) | Rakendamine ülesandes | 2 |

---

### Ülesanne 2 (12 punkti)

**Püstitus:**

Valgusvihk langeb klaasest õhusse piirile. Langemisnurk on θ₁ = 45°, murdumisnurk θ₂ = 60°.

a) Arvuta murdumisnäitaja, kasutades Snelli seadust.

b) Kas see on füüsikaliselt võimalik? Kontrolli.

c) Arvuta kriitilisest nurk täielikule sisepeeglutusele.

**Lahendus:**

**a)** Snelli seadus:
$$n_1 \sin \theta_1 = n_2 \sin \theta_2$$

Kus n₁ = n(klaas) ja n₂ = n(õhk) = 1.

$$n_1 \sin 45° = 1 \cdot \sin 60°$$
$$n_1 \cdot 0,707 = 0,866$$
$$n_1 = \frac{0,866}{0,707} \approx 1,22$$

**Vastus:** n ≈ 1,22

**b)** Kontroll füüsikalisusele:

Tavaklaasi murdumisnäitaja on umbes 1,5, mitte 1,22. **See pole füüsikaliselt võimalik** — murdumisnäitaja on liiga väike.

Tegelikkuses: kui klaasi murdumisnäitaja oleks 1,22, oleks murdumisnurk:
$$\sin \theta_2 = n_1 \sin \theta_1 = 1,22 \cdot 0,707 \approx 0,863$$
$$\theta_2 \approx 59,6° \approx 60°$$ ✓

**Vastus:** Matemaatiliselt õige, aga antud murdumisnäitaja (1,22) ei vasta reaalse klaasi omale.

**c)** Kriitiliselt nurk täielikule sisepeeglutusele:
$$\sin \theta_c = \frac{n_2}{n_1} = \frac{1}{1,22} \approx 0,820$$
$$\theta_c = \arcsin(0,820) \approx 55°$$

**Vastus:** θc ≈ 55°

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Snelli seaduse rakendamine | 3 |
| a) | Õige arvutus | 1 |
| b) | Kriitilisuse analüüs | 4 |
| c) | Kriitiliselt nurga valem | 2 |
| c) | Õige arvutus | 2 |

---

### Ülesanne 3 (12 punkti)

**Püstitus:**

Koonduva läätse poltus f = 0,2 m, objekti kaugus õõ esil on u = 0,6 m.

a) Arvuta kujutise kaugus läätse taga, kasutades läätsevõrrandit.

b) Milleline on kujutis — real või virtuaalne?

c) Arvuta suurendus.

**Lahendus:**

**a)** Läätsevõrrand:
$$\frac{1}{f} = \frac{1}{u} + \frac{1}{v}$$
$$\frac{1}{0,2} = \frac{1}{0,6} + \frac{1}{v}$$
$$5 = \frac{1}{0,6} + \frac{1}{v}$$
$$5 = 1,667 + \frac{1}{v}$$
$$\frac{1}{v} = 5 - 1,667 = 3,333$$
$$v = \frac{1}{3,333} = 0,3 \text{ m}$$

**Vastus:** v = 0,3 m

**b)** Kuna v > 0, on kujutis **realne** ja läätse taga.

**Vastus:** Reaaljaotus

**c)** Suurendus:
$$M = -\frac{v}{u} = -\frac{0,3}{0,6} = -0,5$$

Negatiivne märk näitab ümberpööratud kujutist. Suurenduse suurus |M| = 0,5.

**Vastus:** M = -0,5 (ümberpööratud, 0,5 korda väiksem)

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Läätsevõrrandi rakendamine | 3 |
| a) | Õige arvutus | 2 |
| b) | Kujutise tüübi määramine | 3 |
| c) | Suurenduse valem | 2 |
| c) | Õige arvutus ja märk | 2 |

---

## Laineoptika

### Ülesanne 4 (12 punkti)

**Püstitus:**

Valge valgus langeb kahe paralleelse pilu peale, pilu vahekaugus d = 1 × 10⁻⁶ m. Ekraani kaugus piltidest on L = 1 m. Valguse lainepikkus λ = 600 nm.

a) Arvuta võre kaugus kahe kõigeks maksimumi vahel.

b) Arvuta kahe kõigeks miinimumi vahe.

c) Kas see on vaatav?

**Lahendus:**

**a)** Kahe järjestikku maksimumi vaheline kaugus (kaksispilu interferents):
$$\Delta y = \frac{\lambda L}{d} = \frac{600 \times 10^{-9} \cdot 1}{1 \times 10^{-6}}$$
$$\Delta y = \frac{600 \times 10^{-9}}{1 \times 10^{-6}} = 600 \times 10^{-3} = 0,6 \text{ m} = 60 \text{ cm}$$

**Vastus:** Δy = 0,6 m = 60 cm

**b)** Miinimumid on maksimumite vahel, seega kahe järjestikuse miinimumi vahe on sama:
$$\Delta y_{\text{min}} = 0,6 \text{ m}$$

**Vastus:** 0,6 m

**c)** 60 cm on suurepärane vaatava suurusega. **Jah, see on vaatav.**

**Vastus:** Jah, käes nähtavale sobib

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Kaksispilu interferentsi valem | 4 |
| a) | Õige arvutus | 2 |
| b) | Miinimumi asukoht | 2 |
| c) | Vaatavuse hindamine | 2 |

---

### Ülesanne 5 (12 punkti)

**Püstitus:**

Valguslaine lainepikkus vaakumis λ₀ = 500 nm. Laine levib peeglis, mille murdumisnäitaja n = 1,5.

a) Arvuta laine lainepikkus peeglis.

b) Arvuta laine sagedus vaakumis ja peeglis.

c) Kas sagedus muutub keskkonna vahetus?

**Lahendus:**

**a)** Lainepikkus peeglis:
$$\lambda = \frac{\lambda_0}{n} = \frac{500}{1,5} \approx 333 \text{ nm}$$

**Vastus:** λ ≈ 333 nm

**b)** Sagedus vaakumis (konstant):
$$f = \frac{c}{\lambda_0} = \frac{3 \times 10^8}{500 \times 10^{-9}}$$
$$f = 6 \times 10^{14} \text{ Hz}$$

Sagedus peeglis (sama):
$$f = 6 \times 10^{14} \text{ Hz}$$

**Vastus:** f = 6 × 10¹⁴ Hz (nii vaakumis kui peeglis)

**c)** **Ei, sagedus ei muutu.** Sagedus on suuruse omadus ja jääb keskkonna vahetus samaks. Muutub ainult lainepikkus.

**Vastus:** Ei, sagedus on konstant

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Lainepikkuse valem erinevates keskkondades | 4 |
| a) | Õige arvutus | 2 |
| b) | Sageduse valem | 2 |
| b) | Õige arvutus | 2 |
| c) | Sageduse muutumise analüüs | 2 |

---

### Ülesanne 6 (12 punkti)

**Püstitus:**

Valguslaine läbib difraktsiooniresteid periode N = 1000 joont/mm, lainepikkus λ = 650 nm. Valgusvihk langeb risti restile.

a) Arvuta pilu periood (võre konstant).

b) Arvuta esimese järku difraktsioonimaksimumi nurk.

c) Arvuta kummalisuse järi suurim difraktsioonijärk?

**Lahendus:**

**a)** Pilu periood (võre konstant):
$$d = \frac{1}{N} = \frac{1}{1000 \text{ joont/mm}} = 10^{-3} \text{ mm} = 1 \times 10^{-6} \text{ m} = 1 \text{ μm}$$

**Vastus:** d = 1 μm = 1 × 10⁻⁶ m

**b)** Esimese järgu maksimum (m = 1):
$$d \sin \theta = m \lambda$$
$$\sin \theta = \frac{m \lambda}{d} = \frac{1 \cdot 650 \times 10^{-9}}{1 \times 10^{-6}}$$
$$\sin \theta = \frac{650}{1000} = 0,65$$
$$\theta = \arcsin(0,65) \approx 40,5°$$

**Vastus:** θ ≈ 40,5°

**c)** Suurim difraktsioonijärk (sin θ ≤ 1):
$$\sin \theta_{\text{max}} = 1$$
$$d \sin \theta_{\text{max}} = m_{\text{max}} \lambda$$
$$1 \times 10^{-6} \cdot 1 = m_{\text{max}} \cdot 650 \times 10^{-9}$$
$$m_{\text{max}} = \frac{1 \times 10^{-6}}{650 \times 10^{-9}} = \frac{1000}{650} \approx 1,54$$

Seega suurim täisarv: **m_max = 1** (ainult esimene järk on nähtav)

**Vastus:** m_max = 1

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Võre konstanti arvutamine | 3 |
| a) | Õige arvutus ja ühik | 1 |
| b) | Difraktsioonimaksimumi valem | 3 |
| b) | Õige arvutus | 2 |
| c) | Suurima järgu määramine | 3 |

---

## Võnkumised ja lained

### Ülesanne 7 (12 punkti)

**Püstitus:**

Harmooniline võnkumine: amplituud A = 0,1 m, periood T = 0,5 s. Võnkumise ajaline võrrand: x = A sin(ωt).

a) Arvuta nurkkiirus (ω).

b) Arvuta maksimaalse kiirust vedus.

c) Arvuta maksimaalset kiirendust.

**Lahendus:**

**a)** Nurkkiirus:
$$\omega = \frac{2\pi}{T} = \frac{2\pi}{0,5} = 4\pi \text{ rad/s} \approx 12,6 \text{ rad/s}$$

**Vastus:** ω = 4π rad/s ≈ 12,6 rad/s

**b)** Maksimaalne kiirus:
$$v_{\text{max}} = A\omega = 0,1 \cdot 4\pi = 0,4\pi \text{ m/s} \approx 1,26 \text{ m/s}$$

**Vastus:** vmax ≈ 1,26 m/s

**c)** Maksimaalne kiirendus:
$$a_{\text{max}} = A\omega^2 = 0,1 \cdot (4\pi)^2 = 0,1 \cdot 16\pi^2$$
$$a_{\text{max}} = 1,6\pi^2 \approx 15,8 \text{ m/s}^2$$

**Vastus:** amax ≈ 15,8 m/s²

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Nurkkiiruse valem ja arvutus | 4 |
| b) | Maksimaalse kiiruse valem | 3 |
| b) | Õige arvutus | 1 |
| c) | Maksimaalse kiirenduse valem | 2 |
| c) | Õige arvutus | 2 |

---

### Ülesanne 8 (12 punkti)

**Püstitus:**

Mehaaniline laine levib keskkonnaga. Lainepikkus λ = 0,5 m, sagedus f = 100 Hz.

a) Arvuta laine kiirus.

b) Arvuta laine periood.

c) Arvuta laine kõrgus kahe vahemaa kohtadel, mis asuvad λ/4 kaugusel.

**Lahendus:**

**a)** Laine kiirus:
$$v = \lambda f = 0,5 \cdot 100 = 50 \text{ m/s}$$

**Vastus:** v = 50 m/s

**b)** Laine periood:
$$T = \frac{1}{f} = \frac{1}{100} = 0,01 \text{ s}$$

**Vastus:** T = 0,01 s = 10 ms

**c)** Kahel kohale, mis asuvad λ/4 = 0,125 m kaugusel:

Laine võrrand: $y = A \sin(kx - \omega t + \varphi)$

Kahel punktil x₁ ja x₂ = x₁ + λ/4:
$$y_2 = A \sin(k(x_1 + \lambda/4) - \omega t + \varphi)$$
$$y_2 = A \sin(kx_1 + k\lambda/4 - \omega t + \varphi)$$

Kuna $k = \frac{2\pi}{\lambda}$:
$$k\lambda/4 = \frac{2\pi}{\lambda} \cdot \frac{\lambda}{4} = \frac{\pi}{2}$$

Seega:
$$y_2 = A \sin(kx_1 - \omega t + \varphi + \pi/2) = A \cos(kx_1 - \omega t + \varphi)$$

Kõrgused erinevad faasiülemineku π/2 võrra.

**Vastus:** Faaside vahe on π/2, kõrgused on erinevad

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Laine kiiruse valem | 3 |
| a) | Õige arvutus | 1 |
| b) | Periood sageduse kaudu | 3 |
| b) | Õige arvutus | 1 |
| c) | Faaside analüüs λ/4 vahekaugusele | 4 |

---

## Heli

### Ülesanne 9 (12 punkti)

**Püstitus:**

Heli algallikas sagedusega f₀ = 440 Hz liigub vaatleja poole kiirusega v_s = 20 m/s. Heli kiirus õhus on v = 340 m/s. Vaatleja on paigal.

a) Arvuta Doppleri efektiga kuuldav sagedus (allikas liigub vaatleja poole).

b) Arvuta sagedus, kui allikas liigub vaatlejast eemale.

c) Arvuta sageduste suhe.

**Lahendus:**

**a)** Doppleri efekt (allikas liigub vaatleja poole):
$$f' = f_0 \frac{v}{v - v_s} = 440 \cdot \frac{340}{340 - 20}$$
$$f' = 440 \cdot \frac{340}{320} = 440 \cdot 1,0625 = 467,5 \text{ Hz}$$

**Vastus:** f' ≈ 468 Hz

**b)** Doppleri efekt (allikas liigub vaatlejast eemale):
$$f' = f_0 \frac{v}{v + v_s} = 440 \cdot \frac{340}{340 + 20}$$
$$f' = 440 \cdot \frac{340}{360} = 440 \cdot 0,944 = 415,6 \text{ Hz}$$

**Vastus:** f' ≈ 416 Hz

**c)** Sageduste suhe (lähenemine / kaugenemine):
$$\frac{f'_{\text{lähenemine}}}{f'_{\text{kaugenemine}}} = \frac{467,5}{415,6} \approx 1,125$$

**Vastus:** Suhe ≈ 1,125

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Doppleri valemi rakendamine (lähenemine) | 4 |
| a) | Õige arvutus | 2 |
| b) | Doppleri valemi rakendamine (kaugenemine) | 3 |
| b) | Õige arvutus | 1 |
| c) | Suhe arvutamine | 2 |

---

### Ülesanne 10 (12 punkti)

**Püstitus:**

Heli heliintensiivsus allikast on I = 1 × 10⁻¹² W/m² (kuulmispiir), kaugus allikast r = 1 m.

a) Arvuta helirõhk (akustiline rõhk), kui õhu tihedus ρ = 1,2 kg/m³ ja heli kiirus v = 340 m/s.

b) Arvuta helitase detsibellides.

c) Kui allik on kahekordsel kaugusel, millane on uus heliintensiivsus?

**Lahendus:**

**a)** Helirõhk (akustiline rõhk):
$$p = \sqrt{2\rho v I} = \sqrt{2 \cdot 1,2 \cdot 340 \cdot 1 \times 10^{-12}}$$
$$p = \sqrt{816 \times 10^{-12}} = \sqrt{8,16 \times 10^{-10}}$$
$$p \approx 2,86 \times 10^{-5} \text{ Pa}$$

**Vastus:** p ≈ 2,86 × 10⁻⁵ Pa = 28,6 μPa

**b)** Helitase detsibellides (referentsi I₀ = 1 × 10⁻¹² W/m²):
$$L = 10 \log_{10} \frac{I}{I_0} = 10 \log_{10} \frac{1 \times 10^{-12}}{1 \times 10^{-12}}$$
$$L = 10 \log_{10}(1) = 10 \cdot 0 = 0 \text{ dB}$$

**Vastus:** L = 0 dB (kuulmispiir)

**c)** Kahekordsel kaugusel (r' = 2r):

Intensiivsus langeb kvadraatselt kauguse suhtes:
$$I' = I \cdot \frac{r^2}{r'^2} = I \cdot \frac{r^2}{(2r)^2} = I \cdot \frac{1}{4}$$
$$I' = 1 \times 10^{-12} \cdot 0,25 = 0,25 \times 10^{-12} \text{ W/m}^2$$

**Vastus:** I' = 0,25 × 10⁻¹² W/m² = 2,5 × 10⁻¹³ W/m²

**Hindamisskeem:**

| Osa | Kriteerium | Punktid |
|-----|-----------|---------|
| a) | Helirõhu valem ja arvutus | 4 |
| b) | Helitase detsibellides | 4 |
| c) | Intensiivsuse muutumine kaugusega | 4 |

---

**Kokku:** 10 ülesannet × 12 punkti = 120 punkti optika ja lainete kohta

Nende ülesannete harjutamine aitab sul mõista valguse ja helilainete füüsikat!
