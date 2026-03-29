# F6 — Elektromagnetism

**Kursus:** F6 | **Klass:** 11. klass | **Eeldused:** F5 (Elektrostaatika ja vool)

## 1. Magnetväli ja selle kirjeldamine

Magnetväli tekib liikuvate laengute tõttu. Püsimagneti juures on magnetväli ka statsionaarsete aatomite siseselt olevate elektronide tõttu.

Magnetvälja tugevust kirjeldab **magnetinduktsioon** $B$ (ühik tesla, T). Magnetvälja suunda näitavad magnetvälja jooned, mis väljuvad N-pooluselt ja sisenevad S-poolusele.

Magnetvälja mõju voolu kandvale juhile:

$$F = BIl\sin\alpha$$

kus:
- $F$ — jõud (N)
- $B$ — magnetinduktsioon (T)
- $I$ — voolu tugevus (A)
- $l$ — juhi pikkus magnetvälis (m)
- $\alpha$ — nurk juhi ja magnetvälja suuna vahel

**Jõu suund** määratakse vasaku käe reegliga: pöial näitab voolu suunda, sõrmed magnetvälja suunda, peopesa näitab jõu suunda.

## 2. Lorentzi jõud

Üksik liikuv laeng magnetväljas kogeb jõudu:

$$F_L = Bqv\sin\alpha$$

kus:
- $q$ — laeng (C)
- $v$ — kiirus (m/s)
- $\alpha$ — nurk kiiruse ja magnetvälja suuna vahel

Lorentzi jõud on alati risti kiirusega, seega see ei muuda laengu kineetilise energia suurust, vaid ainult suunda.

## 3. Magnetvoo mõiste

**Magnetvoog** $\Phi$ läbi pinna näitab, kui palju magnetvälja jooni seda pinda läbib:

$$\Phi = BS\cos\alpha$$

kus:
- $S$ — pinna pindala (m²)
- $\alpha$ — nurk pinna normaali ja magnetvälja suuna vahel

Magnetvoo ühik: weber (Wb), kus 1 Wb = 1 T·m²

## 4. Elektromagnetiline induktsioon

Kui magnetvoog juhtiva silmuse läbi muutub, tekib silmuses **indutseeritud elektromotoorjõud** (EMJ):

$$\varepsilon_i = -\frac{\Delta\Phi}{\Delta t}$$

**Lenzi reegel:** Indutseeritud vool tekitab magnetvälja, mis takistab magnetvoo muutumist.

Praktiliselt tähendab see:
- Kui magnetvoog suureneb, tekib indutseeritud vool, mis loob magnetvälja, mis seda voogu vähendab
- Kui magnetvoog väheneb, tekib indutseeritud vool, mis loob magnetvälja, mis seda voogu suurendab

## 5. Eneseinduktsioon

Muutuv vool juhis tekitab muutuvat magnetvälja, mis indutseerib juhis endale elektromotoorjõu:

$$L = \frac{\Delta\Phi}{\Delta I}$$

kus $L$ on **induktiivsus** (ühik henry, H).

Indutseeritud EMJ:
$$\varepsilon_i = -L\frac{\Delta I}{\Delta t}$$

Magnetväljas salvestunud energia:
$$E = \frac{LI^2}{2}$$

## 6. Ferromagnetism

Mõned materjalid (raud, nikkel, koobalt) võivad muutuda magnetiksi. Selle põhjuseks on aatomite omamagneetilisus ja nende järjestamine magnetvälja suunas.

**Käitumine:**
- Väikeses magnetväljas magnetiseeruvad kergesti
- Suures magnetväljas satureeruvad (magnetiseeritus saavutab maksimumi)
- Magneetimise eemaldamisel jäävad osaliselt magnetiseerituks (remanents)

## 7. Vahelduvvool

Vahelduvvoolu tekitab generaator, mis pöörleb magnetväljas. Magnetvoog läbi mähise muutub:

$$u = U_m\sin\omega t$$

kus:
- $U_m$ — amplituudpinge (V)
- $\omega$ — nurksagedus (rad/s)
- $t$ — aeg (s)

Sagedus $f$ (Hz) ja periood $T$ (s) seotud: $T = \frac{1}{f}$, $\omega = 2\pi f$

**Efektiivväärtused** vahelduvvoolu korral:
- Pinge: $U_{eff} = \frac{U_m}{\sqrt{2}} \approx 0,707 U_m$
- Vool: $I_{eff} = \frac{I_m}{\sqrt{2}}$

Elektrivõrgus näidatav pinge (nt 230 V) on efektiivväärtus.

## 8. Transformaator

Trafo muudab vahelduvvoolu pinget ilma energiat kadutamata (ideaalsel juhul).

| Primaarpool | Sekundaarpool |
|-------------|---------------|
| $N_1$ keerdumist | $N_2$ keerdumist |
| Sisendpinge $U_1$ | Väljundpinge $U_2$ |
| Sisendvool $I_1$ | Väljundvool $I_2$ |

**Trafo võrrand:**
$$\frac{U_1}{U_2} = \frac{n_1}{n_2} = \frac{N_1}{N_2}$$

Ideaalsel trafo: $U_1 I_1 = U_2 I_2$ (võimsus säilib)

**Pingetõstev trafo:** $N_2 > N_1$, $U_2 > U_1$, $I_2 < I_1$

**Pinge alandav trafo:** $N_2 < N_1$, $U_2 < U_1$, $I_2 > I_1$

## 9. Elektrienergia ülekanne

Elektrit edastatakse suurte pingetega, et vähendada energiakadusid.

Energiakadu juhis: $P_{kaod} = I^2 R$

Suurendades pinget, väheneb vool, mistõttu vähenevad Joule'i soojuskaod. Trafo võimaldab:
1. Elektrijaamast: pinge tõstmine (vähendab voolu)
2. Tarbimiskohas: pinge alandamine (ohutus, seadmete ühilduvus)

| Etapp | Pinge | Vool | Otstarbе |
|-------|-------|------|---------|
| Genereerimine | ~20 kV | kõrge | Jaam |
| Ülekanne | 110–400 kV | madal | Minimaalse kadudega ülekanne |
| Jaotusvõrk | 6–10 kV | keskmine | Piirkondlik jaotus |
| Tarbija | 230/400 V | kõrge | Majapidamised, ettevõtted |

---

## Levinud väärarusaamad

| Väärarusuaam | Õige seletamine |
|--------------|-----------------|
| Magnetväli teeb voolusuunalise jõu liikumise alusel | Jõu suund määratakse vasaku käe reegliga, mitte voolu suunaga |
| Magnetvooks nimetatakse magnetvälja | Magnetvoog on magnetvälja läbi pinna ülekantav kogus; magnetväli ise on erinev mõiste |
| Indutseeritud vool vastustab voolu tekitavat muutust | Lenzi reegli täpne sõnastus: indutseeritud vool tekitab magnetvälja, mis vastustab *muutust*, mitte voolu enast |
| Trafo töötab alalisvoolu korral | Trafo vajab muutuvat magnetvälja, seega ainult vahelduvvool |
| Pinge tõstmine trafo abil muudab energiat suuremaks | Energia säilib; ideaalsel trafo on sisend- ja väljundvõimsus võrdne |

---

## Näidisülesanne

**Ülesanne:** Vaskjuhe pikkusega 0,5 m ja voolu tugevusega 2 A asub homogeenses magnetväljas induktsiooniga 0,8 T. Juhe on magnetväljaga 90° nurga all. Leida jõud, mis mõjub juhile.

**Andmed:**
- $l = 0,5$ m
- $I = 2$ A
- $B = 0,8$ T
- $\alpha = 90°$, seega $\sin 90° = 1$

**Lahendus:**

Kasutame Ampere'i jõu valemit:
$$F = BIl\sin\alpha$$

Asendame arvud:
$$F = 0,8 \times 2 \times 0,5 \times 1 = 0,8 \text{ N}$$

**Vastus:** Juhile mõjub jõud 0,8 N.

---

## Näidisülesanne 2

**Ülesanne:** Transformaatori primaarmähisel on 200 keerdumist, sekundaarmähisel 800 keerdumist. Primaarmähisse antakse vahelduvpinge 50 V. Leida sekundaarmähise pinge.

**Andmed:**
- $N_1 = 200$
- $N_2 = 800$
- $U_1 = 50$ V

**Lahendus:**

Kasutame trafo valemit:
$$\frac{U_1}{U_2} = \frac{N_1}{N_2}$$

Avaldame $U_2$:
$$U_2 = U_1 \times \frac{N_2}{N_1} = 50 \times \frac{800}{200} = 50 \times 4 = 200 \text{ V}$$

**Vastus:** Sekundaarmähise pinge on 200 V. Tegu on pingetõstva trafoga (keerdumiste arv ja pinge suureneb).

---

## Seotud materjalid

- [Kursuse kaart F6](../../oppekava/gymnaasium-F6-elektromagnetism.md)
- Elektromagnetilise induktsiooni eksperimendid ja simulatsioonid
- Generaatoritest ja trafodest
