# DELF C1 — Préparation 🌸

Een persoonlijke oefen-app voor het DELF C1 schrijftentamen.

## Snel deployen op GitHub Pages (5 min)

### 1. Maak een nieuwe GitHub repo
- Ga naar github.com → New repository
- Naam: `delf-c1` (of wat je wilt)
- Maak 'm **public** (vereist voor gratis GitHub Pages)

### 2. Upload het bestand
- Klik in je nieuwe repo op **"Add file" → "Upload files"**
- Sleep `index.html` erin
- Commit ("Add app")

### 3. Activeer GitHub Pages
- Repo → **Settings** → **Pages** (links in het menu)
- Source: **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Save

Na ~1 minuut staat je app live op:
```
https://JOUW-GEBRUIKERSNAAM.github.io/delf-c1/
```

### 4. Open op je iPhone
- Open de link in **Safari**
- Tik op **Delen** (vierkant met pijl omhoog)
- Scroll → **"Zet op beginscherm"**
- Geef 'm een naam ("DELF") → Voeg toe
- Nu staat de app als echt icoon op je beginscherm, fullscreen, geen browser-chrome

### 5. Eerste keer openen
- De app vraagt naar je Anthropic API-sleutel
- Plak 'm in → de app test 'm meteen
- Klaar! Je sleutel blijft veilig in je telefoon-storage

## Voor je vriendin

Stuur haar dezelfde URL. Zij doet stap 4 en 5 op haar eigen iPhone. Ze heeft haar eigen API-sleutel nodig **of** ze gebruikt jouw sleutel (vertel haar 'm dan persoonlijk — niet via de URL).

Haar voortgang en jouw voortgang staan apart (elk in haar/jouw eigen browser-storage).

## API-sleutel krijgen

1. `console.anthropic.com` → account aanmaken
2. **Billing** → laad €5–10 op
3. **API Keys** → Create Key → kopieer de `sk-ant-...` sleutel
4. Plak in de app

Kosten: ~€0.01 per essay-feedback met Sonnet, ~€0.10 met Opus. €5 is genoeg voor 4 weken intensief oefenen.

## Privacy & veiligheid

- Je API-sleutel staat alléén in je eigen browser (localStorage)
- Alle voortgang/essays staan in je browser, niet op een server
- Calls gaan rechtstreeks naar Anthropic, niet via een tussenpartij
- Wis alles via **Instellingen → Reset alles**

## Wijzigen?

Edit `index.html` rechtstreeks op GitHub (potlood-icoon) en commit. Binnen 1 min staat de nieuwe versie live.

Veel succes met 15 juni! 🌸
