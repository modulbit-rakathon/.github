<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/readme-banner-dark.png">
  <img alt="PillGaze – Z fotky krabičky k přesné farmakologické anamnéze." src="assets/readme-banner-light.png" width="100%">
</picture>

Mobilní AI nástroj, který z fotografií léků a ručně psaných poznámek sestaví strukturovaný přehled medikace pro ošetřujícího lékaře.

Zadavatel: **Masarykův onkologický ústav**

</div>

---

## 🩺 Problém

Sběr farmakologické anamnézy je zdlouhavý a náchylný k chybám. Pacienti často nosí na vyšetření tašku plnou krabiček, letáků a ručně psaných poznámek o dávkování. U onkologických pacientů je situace ještě citlivější – kombinují protinádorovou léčbu s dalšími léky, doplňky stravy a volně prodejnými přípravky, a každá neodhalená interakce může mít vážné následky.

## 💡 Řešení

PillGaze promění fotografie krabiček a ručně psaných poznámek v přesnou, strukturovanou anamnézu:

1. **📸 Vyfoť** – pacient (nebo zdravotník) nafotí krabičky léků a poznámky v mobilu.
2. **🔍 Rozpoznej** – AI identifikuje užívané léky, sílu, dávkování i onkologickou léčbu.
3. **⚠️ Upozorni** – systém zkontroluje možné lékové interakce a označí rizikové kombinace.
4. **📋 Shrň** – vznikne přehledný strukturovaný výpis medikace.
5. **🔒 Předej** – výsledek se bezpečně a srozumitelně předá ošetřujícímu lékaři.

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'fontFamily': 'Plus Jakarta Sans, sans-serif', 'primaryColor': '#ECFCF7', 'primaryTextColor': '#14123F', 'primaryBorderColor': '#3DD9B3', 'lineColor': '#3DD9B3'}}}%%
flowchart LR
    A[📸 Fotky krabiček<br/>a poznámek] --> B[🔍 Rozpoznání léků<br/>a dávkování]
    B --> C[⚠️ Kontrola<br/>interakcí]
    C --> D[📋 Strukturovaný<br/>přehled]
    D --> E[🔒 Bezpečné předání<br/>lékaři]
```

## ✨ Klíčové funkce

- **Rozpoznání léků z fotografie** – názvy přípravků, účinné látky, síla, léková forma
- **Čtení ručně psaných poznámek** – dávkovací schémata, časy užívání, poznámky pacienta
- **Podpora onkologické léčby** – zachycení protinádorových režimů a podpůrné medikace
- **Upozornění na interakce** – zvýraznění potenciálně nebezpečných kombinací
- **Strukturovaný výstup** – přehled připravený k rychlé kontrole lékařem
- **Bezpečné sdílení** – předání dat ošetřujícímu lékaři s důrazem na ochranu osobních údajů

## 🛠️ Technologie

- Web aplikace - React Native (JS/TS)
- Backend - go

## 🔐 Bezpečnost a soukromí

Pracujeme se zdravotními údaji, a proto:

- s daty zacházíme v souladu s **GDPR** a zásadou minimalizace dat,
- přenos i uložení dat je **šifrované**,
- výstup je určen **výhradně ošetřujícímu lékaři**.

## ⚠️ Upozornění

PillGaze je **podpůrný nástroj**, nikoli zdravotnický prostředek. Nenahrazuje odborný úsudek lékaře ani lékárníka. Veškeré výstupy – včetně upozornění na interakce – musí ověřit kvalifikovaný zdravotník.

## 👥 Tým

| Jméno | Role |
| --- | --- |
| Jonáš Hubený (jonashubeny) | Frontend |
| Vít Smolík (smoliicek) | Backend |
| Matyáš Vlk (vlcak27) | JavaScript/vibecoding |

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/pillgaze-mark-dark-128.png">
  <img alt="PillGaze" src="assets/pillgaze-mark-color-128.png" width="64">
</picture>

Vytvořeno pro <b>Masarykův onkologický ústav</b> 💙

</div>
