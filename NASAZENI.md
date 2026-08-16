# Nasazení na GitHub Pages

## 1. Repozitář

Nový veřejný repozitář, doporučený název `zajecov`.

**Description** (pole nahoře vpravo, klik na ozubené kolo):

> Analýza situace obce Zaječov a návrh dlouhodobých priorit. Občanský podnět z veřejných dat.

**Website:** `https://petrapavlis.github.io/zajecov/`

**Topics:** `zajecov` `obec` `komunalni-politika` `otevrena-data` `csu` `brdy` `verejna-sprava`

## 2. Nahrát soubory

```
index.html          studie
README.md           úvodní stránka repozitáře
CHANGELOG.md        historie oprav
LICENSE             CC BY 4.0
.nojekyll           vypne zpracování Jekyllem
assets/og-card.html podklad pro náhledový obrázek
assets/og-image.png doplníte podle kroku 4
zdroje/README.md    soupis primárních podkladů
zdroje/*.pdf        stažené dokumenty
```

## 3. Zapnout Pages

Settings → Pages → Source: _Deploy from a branch_ → Branch: `main`, složka `/ (root)` → Save.

Za minutu běží na `https://petrapavlis.github.io/zajecov/`.

## 4. Náhledový obrázek

Otevřete `assets/og-card.html` v prohlížeči, vyfoťte samotnou bílou kartu
(musí mít přesně 1200 × 630 px) a uložte jako `assets/og-image.png`.

Bez něj se odkaz na Facebooku i v Messengeru zobrazí jako holý text.

## 5. Nahradit zástupný text

V `index.html`, `README.md` a `NASAZENI.md` je na několika místech `petrapavlis`.
Nahraďte svým GitHub jménem — jinak nebudou fungovat odkazy v meta tagách
ani náhledový obrázek.

## 6. Vlastní doména (nepovinné)

Máte-li volnou doménu, `Settings → Pages → Custom domain`. Adresa typu
`zajecov2046.cz` působí na obecním úřadě důvěryhodněji než github.io.
U poskytovatele nastavte CNAME na `petrapavlis.github.io`.

## 7. Kam to poslat

- **Datová schránka obce:** `wfkb4qa` — dokument tím skončí v evidenci, ne jen na sociální síti
- **E-mail:** `obec@zajecov.cz`, `kancelar@zajecov.cz`
- **Instagram:** odkaz do bia, v postu „odkaz v biu" (v popiscích nejsou odkazy klikací)
- **Story s link stickerem** a uložit do Highlights
