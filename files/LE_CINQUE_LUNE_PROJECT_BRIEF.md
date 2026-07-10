# Le Cinque Lune — Website Project Brief

## Il ristorante
- **Nome:** Le Cinque Lune
- **Tipo:** Pasticceria · Caffè · Taverna
- **Indirizzo:** Largo Roma 1, 53026 Pienza (SI), Toscana
- **Atmosfera:** Taverna toscana autentica in un vicolo di pietra dorata. Ferro battuto, lampioni, dehors con ombrelloni. Il locale è nel centro storico di Pienza con vista sulla Val d'Orcia.

## Pagine richieste
1. **Home** (index.html) — Hero, storia, galleria, anteprima menu, info/orari
2. **Menu** (menu.html) — Menu completo con tutti i piatti reali

**NON serve:** pagina prenotazioni

## Navigazione
- Logo in alto a sinistra (dal PDF fornito, estratto come PNG trasparente)
- Link: Home, Menu
- **Dropdown lingua** in alto a destra: Italiano (default), English, 한국어, Русский
- I nomi dei piatti restano in italiano in tutte le lingue (prassi standard per menù autentici)
- Si traducono: titoli sezione, descrizioni piatti, testi UI

## Design / Palette
Ispirato al logo (navy + gold) e all'atmosfera fisica del locale:
- `--navy: #1c2942` (testo primario, header scuro)
- `--gold: #bb9457` (accenti, prezzi, ornamenti luna)
- `--cream: #faf5ea` (sfondo principale)
- `--stone: #e7dcc3` (sfondo secondario)
- `--terracotta: #b1522f` (accento caldo opzionale)

### Font
- **Display/Headline:** Fraunces (serif, Google Fonts) — caldo, editoriale, con italic bello
- **Body/UI:** Manrope (sans, Google Fonts) — pulito, moderno, leggibile

### Estetica
- Warm moonlit Tuscan taverna
- Grain texture su sezioni scure
- Effetto stelline (CSS radial-gradient) sulle sezioni navy
- Hover zoom sulle foto (scale 1.06, transition 1.3s)
- Motivo decorativo: le 5 lune del logo come divider SVG

## Fotografie fornite (nella cartella uploads/)
1. `federico-di-dio-photography-imDFBYDnqI0-unsplash.jpg` — Vicolo fiorito di Pienza
2. `claudio-mota-jFYHpwBHPwE-unsplash.jpg` — Vicolo con vista campagna
3. `roan-lavery-v-1XzaPhQu8-unsplash.jpg` — Portale della chiesa, pietra
4. `doozydoom-_v5HCKSZOkA-unsplash.jpg` — Campagna toscana, cipressi panoramici
5. `PXL_20260709_180304581.jpg` — Foto vera del locale (terrazza/insegna al tramonto)
6. `Screenshot_2026-07-10_at_09_11_05.png` — Insegna del locale (close-up)

## Logo
- **File sorgente:** `le_cinque_lune_logo_digitale_senza_sfondo.pdf`
- **Già estratto come:** PNG trasparente 751×976px (RGB + alpha mask dal PDF)
- Colori logo: Navy (#1c2942) + Gold (#bb9457) su trasparente

## Menu completo (da Menu16_06.pdf, 13 pagine, estratto via OCR)

### COLAZIONE
- Brioche farcite — €3 (Marmellata, cioccolato o crema)
- Brioche ai cereali — €3 (Marmellata, cioccolato o crema)
- Yogurt fresco — €7 (Frutta di stagione, cereali croccanti e miele)
- Selezione di torte artigianali a fette — €7
- French toast — €11 (Frutta fresca, sciroppo d'acero e zucchero a velo)
- Involtini di ricotta — €10 (Miele e noci)
- Crêpes — €9 (Nutella bianca o nera, banana e zucchero a velo)
- Frittelle alla ricotta — €9
- Pancake classico — €9 (Miele, zucchero a velo e panna)
- Pancake — €10 (Marmellata, noci e frutta fresca)
- Omelette classica — €9
- Omelette con prosciutto cotto e formaggio — €11
- Omelette con verdure — €11
- Avocado toast — €13 (Burrata, salmone affumicato, semi di sesamo e pomodorini ciliegino)
- Toast tradizionale — €7 (Prosciutto cotto e formaggio)
- Toast vegetariano — €7
- Selezione di salumi — €16
- Selezione di formaggi della Val d'Orcia — €18 (Miele e marmellate)
- Verdure fresche — €7

### ANTIPASTI
- Parmigiana di melanzane — €13
- Tagliere Cinque Lune (2 persone) — €25
- Degustazione di formaggi toscani — €18 (Miele e marmellate)
- Assortimento di salumi tipici locali — €17
- Carpaccio di Chianina — €16
- Insalata caprese — €15 (Mozzarella di bufala e pomodoro)
- Carpaccio di zucchine — €15 (Menta, acciughe e senape)
- Panzanella toscana — €15

### PRIMI
- Pici al ragù di cinghiale — €15
- Pici cacio e pepe — €15
- Pici all'aglione della Valdichiana — €14
- Pici al ragù bianco di Chianina — €15
- Ravioli ricotta e spinaci — €13 (Al burro e salvia)
- Delizia di gnocchi di semolino — €18 (Con fonduta di pecorino e tartufo fresco)
- Millefoglie di lasagna — €14
- Lasagna al pesto — €14 (Con pomodorini)

### SECONDI
- Pollo alla cacciatora — €17 (Con contorno di verdure)
- Filetto di maiale alle erbe aromatiche con lardo di Colonnata — €19 (E verdure grigliate dell'orto toscano)
- Brasato di manzo al Vino Nobile di Montepulciano — €21 (Con spicchi di patate arrosto)
- Anatra all'arancia arrosto — €22 (Con verdure saltate)
- Vitello tonnato — €20

### INSALATONE
- Insalata Caesar — €13 (Lattuga romana, pollo, crostini, parmigiano, salsa caesar)
- Nordica — €14 (Salmone affumicato, rucola, feta, pomodorini, vinaigrette al limone)
- Vegetariana — €13 (Lattuga, carote, sedano, cetrioli, pomodorini, olive e mais)
- Orto e cereali — €12 (Lattuga, cereali, verdure, quinoa, olio extravergine di oliva)
- Panzanella — €14 (Pomodori, pane raffermo, cetrioli, cipolla rossa, basilico, olio extravergine d'oliva)
- Nizzarda — €15 (Tonno, uovo sodo, fagiolini, patate, olive nere e olio extravergine d'oliva)

### BEVANDE
- Acqua naturale 1L — €2,20
- Acqua frizzante 1L — €2,20
- Acqua naturale 0,5L — €1,70
- Acqua frizzante 0,5L — €1,70
- Coca Cola 330ml — €4,00
- Coca Cola 0,5L — €4,50
- Aranciata 275ml — €4,00
- Chinotto 275ml — €4,00
- Limonata 275ml — €4,00
- Tonica 0,20L — €4,00
- Succhi di frutta — €3,50

### BIRRE
- Ceres 330ml — €5,00
- Corona 330ml — €5,00
- Birra artigianale Olmaia n.5 330ml — €7,00
- Birra artigianale Olmaia n.9 330ml — €7,00
- Birra Messina alla spina 0,2L — €4,00
- Birra Messina alla spina 0,4L — €7,00

### APERITIVI & COCKTAIL
- Crodino — €4,00
- Campari soda — €4,00
- Bitter rosso — €4,00
- Spritz — €6,00
- Campari spritz — €7,00
- Negroni toscano — €9,00
- Mojito — €8,00
- Hugo — €8,00
- Old fashioned — €9,00
- Moscow mule — €9,00
- Margarita — €8,00
- Piña colada — €9,00
- Gin tonic classico — €8,00
- Gin tonic premium — €15,00

### STUZZICHINI
- Selezione di formaggi — €10,00
- Selezione di salumi — €12,00
- Tagliere misto (2 persone) — €18,00
- Stuzzichini (2 persone) — €15,00
- Bruschette miste — €10,00

### VINI AL CALICE & SPINA
- Rosso della Casa Poliziano (calice) — €5,00
- Rosso della Casa Poliziano 0,25L — €6,00
- Rosso della Casa Poliziano 0,5L — €8,00
- Rosso de Ricci Montepulciano (calice) — €6,00
- Nobile de Ricci Montepulciano (calice) — €10,00
- Rosé de Ricci Montepulciano (calice) — €6,00
- Bianco Toscano (calice) — €5,00
- Bianco Toscano 0,25L — €6,00
- Bianco Toscano 0,5L — €8,00
- Ribolla Gialla Alturis (calice) — €6,00
- Prosecco DOC Corte delle Calli (calice) — €6,00

### ROSSI IN BOTTIGLIA
- Rosso de Ricci Montepulciano — €18,00
- Nobile de Ricci Montepulciano — €27,00
- Chianti Salcheto — €15,00
- Rosso Furbata Barbanera — €15,00
- Rosso Carpineto Toscano — €15,00
- Rosso Montalcino Abbadia Ardenga — €23,00
- Brunello Abbadia Ardenga — €35,00
- Pinot Nero Alturis — €18,00
- Rosso Salcheto Montepulciano — €19,00
- Nobile Salcheto Montepulciano — €25,00

### BIANCHI IN BOTTIGLIA
- Ribolla Gialla Alturis — €17,00
- Bianco Pojana Passerina — €16,00
- Bianco Quirico Pecorino — €16,00
- Bianco Traminer Alturis — €19,00
- Chardonnay Alturis — €19,00
- Pinot Grigio Sant'Antimo Col d'Orcia — €19,00
- Prosecco DOC Treviso — €16,00
- Prosecco Valdobbiadene — €19,00
- Franciacorta Conti Ducco Cuvée — €25,00
- Franciacorta Ca' del Bosco — €58,00

### LIQUORI
- Amari — €4,00
- Grappa — €4,50
- Limoncello — €4,00
- Whisky — €7,00
- Crema di Whisky — €4,50
- Cognac — €7,00
- Brandy — €7,00
- Cognac Invecchiato — €9,00
- Vin Santo — €5,00

### CAFFÈ & TÈ
- Caffè — €2,30
- Caffè macchiato — €2,50
- Caffè corretto — €3,50
- Caffè americano — €3,50
- Caffè e panna — €3,00
- Caffè shakerato — €4,00
- Cappuccino (latte o soia) — €3,50
- Latte macchiato — €3,50
- Macchiatone — €3,50
- Caffè latte — €3,50
- Decaffeinato — €2,30
- Ginseng piccolo — €2,50
- Ginseng grande — €3,50
- Orzo piccolo — €2,50
- Orzo grande — €3,50
- Tea & tisane — €4,00
- Spremuta di arancia — €5,00
- Centrifughe frutta e verdura — €6,00

### DESSERT & COPPE
- Tiramisù — €6,00
- Torte artigianali a fette — €7,00
- Panna cotta — €5,00
- Semifreddo cheesecake e lampone — €5,00
- Coppa gelato classic 2 gusti — €5,00
- Coppa gelato 5 Lune — €9,00 (Crema, nocciola, cioccolato, nutella, panna, granella di nocciole)
- Affogato alla fragola — €8,00 (Fior di latte, fragola, fragole fresche, panna, salsa alla fragola)
- Affogato all'amarena — €8,00 (Fior di latte, crema, panna, amarene, salsa all'amarena)
- Affogato al caffè — €8,00 (Crema, fior di latte, caffè espresso, panna)
- Banana split — €10,00 (Crema, cioccolato, fragola, frutta banana, panna, nutella, crumble)
- Uovo al tegamino — €10,00 (Fior di latte, pesca sciroppata, panna, cacao)
- Spaghetti al pomodoro — €10,00 (Crema, salsa alla fragola, cocco rapé)
- Dubai chocolate — €10,00 (Cioccolato, kataifi, crema al pistacchio)
- Dino — €9,00 (Fior di latte, fragola, panna, nutella, smarties)
- Lotus — €10,00 (Caramello salato, crema, salsa al caramello, crumble, biscotto lotus)
- Smile — €8,00 (Fior di latte, cono, nutella, smarties)

---

## File già generati nella sessione precedente
- `assets/images/logo.png` — Logo PNG trasparente (751×976, estratto dal PDF)
- `assets/images/alley-flowers.jpg` — Foto vicolo fiorito (2000×1712, ottimizzata)
- `assets/images/alley-view.jpg` — Foto vicolo con vista (1200×1800)
- `assets/images/church-door.jpg` — Foto portale chiesa (1199×1800)
- `assets/images/countryside.jpg` — Foto campagna cipressi (2400×1350)
- `assets/images/terrace-sunset.jpg` — Foto locale al tramonto (1012×1800)
- `assets/style.css` — CSS design system completo
- `data/ui.json` — Traduzioni UI (IT/EN/KO/RU)
- `data/menu.json` — Menu strutturato con traduzioni descrizioni
- `build_data.py` — Script che genera i JSON dal dizionario Python

## Note tecniche
- I file HTML devono essere standalone (CSS inline, immagini come base64 o percorsi relativi)
- Le foto Unsplash hanno attribuzione inclusa nel messaggio dell'utente
- Il layout responsive: mobile-first, 2 colonne story/menu su desktop
- Senza immagini piatti nel menu (solo testo), ma con placeholder opzionali
