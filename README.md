# DELF C1 — Préparation 🌸

Persoonlijke oefen-app voor het DELF C1 schrijftentamen, met mooi roze app-icoontje voor op je iPhone home screen.

## Wat upload je naar GitHub?

**Alle 6 deze bestanden** moeten in de root van je repo:

```
index.html              ← de app
manifest.json           ← PWA-config voor home screen
apple-touch-icon.png    ← icoon op iPhone (180×180)
icon-192.png            ← Android/grote iconen
icon-512.png            ← grote iconen / splash
favicon.png             ← browser tab
```

## Snel deployen op GitHub Pages (5 min)

### 1. Maak een nieuwe GitHub repo
- github.com → New repository
- Naam: `delf-c1` (of wat je wilt)
- Maak 'm **public** (vereist voor gratis GitHub Pages)

### 2. Upload alle 6 bestanden
- Klik in de repo op **"Add file" → "Upload files"**
- Sleep alle 6 bestanden erin (index.html, manifest.json, 4× png)
- Commit ("Add app + icons")

### 3. Activeer GitHub Pages
- Repo → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Save

Na ~1 minuut staat de app live op:
```
https://JOUW-NAAM.github.io/delf-c1/
```

### 4. Toevoegen aan iPhone beginscherm
- Open de link in **Safari** (móet Safari zijn, geen Chrome)
- Tik op **Delen** (vierkant met pijl ↑)
- Scroll naar beneden → **"Zet op beginscherm"**
- Naam (bv. "DELF") → Voeg toe

Nu staat de app met het **roze DELF C1 icoontje** op je beginscherm. Tikken opent 'm fullscreen, zonder browserbalken — voelt als een echte app.

### 5. Eerste keer openen
- De app vraagt je Anthropic API-sleutel
- Plak 'm in → de app test 'm meteen → klaar!

## Voor je vriendin

Stuur haar dezelfde URL. Stappen 4 en 5 doet ze op haar eigen iPhone. Ze gebruikt haar eigen API-sleutel **of** jouw sleutel (dan vertel je 'm haar persoonlijk).

Haar voortgang en jouw voortgang staan apart — ieder in haar/jouw eigen browser.

## API-sleutel krijgen

1. `console.anthropic.com` → account aanmaken
2. **Billing** → laad €5–10 op
3. **API Keys** → Create Key → kopieer de `sk-ant-...` sleutel
4. Plak in de app

**Kosten** (met Sonnet, default):
- ~€0.01 per essay-feedback
- €5 is genoeg voor 4 weken intensief oefenen

In **Instellingen** kun je switchen naar Opus voor betere feedback (~€0.10/feedback).

## Privacy & veiligheid

- API-sleutel en voortgang staan **alléén in je eigen browser** (localStorage)
- Geen tussenpartij — calls gaan direct naar Anthropic
- Wis alles via **Instellingen → Reset alles**

## Iets wijzigen?

Edit `index.html` rechtstreeks op GitHub (potlood-icoon) → commit → 1 min later staat de nieuwe versie live.

---

🌸 Veel succes met 15 juni!
