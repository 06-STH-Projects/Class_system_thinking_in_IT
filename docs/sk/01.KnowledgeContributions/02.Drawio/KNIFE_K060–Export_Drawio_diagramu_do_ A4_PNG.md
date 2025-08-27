---
id: K060
title: "Export Draw.io diagramu do A4 PNG"
author: "Roman Kazička"
date: "2025-08-24 23:50"
tags: ["KNIFE", "draw.io", "diagrams.net", "A4", "export", "PNG", "tips", "knowledge-contribution"]
status: "draft"
---

# KNIFE K060 – Export Draw.io diagramu do A4 PNG

## 🧭 Kontext
Pri exporte diagramov z **Draw.io (diagrams.net)** do formátu PNG je častý problém, že obrázok nemá rozmery A4 alebo je „nalepený“ na okraje.  
Tento príspevok zachytáva praktické riešenia, ako získať konzistentný výstup vo formáte A4.

---

## 🔑 Rýchly návod (Top Level)
1. Nastaviť **Page Setup → A4** (portrait/landscape).  
2. Alebo v exporte **PNG → manuálne rozmery** podľa DPI.  
3. Alebo exportovať do **PDF → Fit to A4** a previesť na PNG.  

---

## 📜 Detailný postup

### 1. Page Setup – A4
- Menu: **Arrange → Page Setup** alebo klik na pozadie → panel *Page*.  
- Nastav **Page Size = A4**.  
- Diagram vlož do rámika.  
- Export → PNG → hotovo.

### 2. Manuálne DPI (pri PNG exporte)
- Zadať rozmery pre A4:
  - 72 DPI → `595 × 842 px`
  - 150 DPI → `1240 × 1754 px`
  - 300 DPI → `2480 × 3508 px`

### 3. Export cez PDF
- Export do **PDF** s voľbou **Fit to A4**.  
- Následne konverzia PDF → PNG (Preview, Acrobat, GIMP).  

---

## 💡 Tip
- Použi **A4 rámik ako šablónu** s prázdnym okrajom.  
- Pri exporte označ **Selection Only** → diagram sa oreže do správneho formátu.  
- Tento postup je opakovateľný a vhodný pre študentov/komunitu.  

---

## 🔖 Tagy
`#KNIFE #drawio #A4 #export #knowledge`

---

✅ **Hodnota**: Zrýchlenie práce pri exporte, konzistentné výstupy, jednoduchá replikácia v tíme alebo komunite.