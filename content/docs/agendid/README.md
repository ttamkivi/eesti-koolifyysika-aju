# AI-agendid füüsika õppimiseks ja õpetamiseks

See kaust sisaldab AI-agentide juhendeid (prompte) mida saab kasutada mis tahes AI-tööriistaga — Claude, ChatGPT, Gemini, Copilot jne.

## Saadaval agendid

| Agent | Kellele | Mida teeb |
|-------|---------|-----------|
| [**Füüsika tuutor**](fuusika-tuutor.md) | Õpilasele | Personaalne tuutor: selgitab teemasid, annab vihjeid, kohandab taset |
| [**Ülesannete generaator**](ylesannete-generaator.md) | Mõlemale | Genereerib ülesandeid koos lahenduste ja hindamisskeemiga |
| [**Tunni planeerija**](tunni-planeerija.md) | Õpetajale | Loob 45-min tunnikava diferentseerimise ja materjalidega |

## Kuidas kasutada?

### Samm 1: Vali agent
Ava vastav `.md` fail ja kopeeri sealt `Süsteemi prompt` sektsioon.

### Samm 2: Kleebi AI-tööriista
- **Claude.ai** → kleebi esimese sõnumina
- **ChatGPT** → Custom Instructions → "How should ChatGPT respond?"
- **API** → `system` parameeter

### Samm 3: Lisa teadmistebaas
Kopeeri juurde vajalikud failid repost:
- Kursuse kaart `oppekava/` kaustast
- Teooria fail `teemad/` kaustast
- Õppevahendid `opetajale/oppevahendid.md`

### Samm 4: Alusta vestlust
Ütle agendile mida vajad — ta küsib vajadusel täpsustavaid küsimusi.

## Kombineerimine

Agente saab kombineerida:
1. **Tunni planeerija** loob tunnikava
2. **Ülesannete generaator** loob tunni jaoks harjutusülesanded
3. **Füüsika tuutor** aitab õpilasel kodutööd teha

## Panustamine

Uue agendi lisamiseks:
1. Loo `.md` fail selle kausta
2. Järgi sama formaati: päis → süsteemi prompt → kasutamine → seotud materjalid
3. Tee pull request
