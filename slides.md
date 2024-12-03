---
title: pAVK
theme: default
# theme: seriph
# theme: academic
layout: cover
wakelock: true
background: /wanderer.jpg
titleTemplate: "%s"
info: false
class: text-left
drawings:
  persist: false
transition: slide-left
mdc: true
favicon: /favicon.ico
# overviewSnapshots: true
---

# Arterienverkalkungen und arterielle Verschlusskrankheit

## = schicksalshafte Erkrankung?

<div class="abs-bl m-6">
Klinik im Dialog - 09. Dezember 2024
</div>

---
src: ./pages/anatomie.md
---

---
title: Arterien
---

<div class="abs-tl ml-26 mt-20 !text-(shadow-lg 6xl)">
 <h1>Arterien</h1>
 <ul class="text-xl">
  <li>Sauerstoff</li>
  <li>Nährstoffe</li>
  <li>alle Organe</li>
 </ul>
</div>
<SlidevVideo autoplay>
<source src="/vid_arterien.mp4" type="video/mp4" />
</SlidevVideo>

---
layout: image-left
image: /plaque.avif
title: Erkrankungen
---

# Erkrankungen

<v-clicks>

- Bluthochdruck
- Erweiterungen (Aneurysma)
- Entzündungen (rheumatisch)
- <span v-mark.underline.red="4">Arteriosklerose</span> (Arterienverkalkung)

</v-clicks>

---
layout: image
image: /nil.jpg
title: Nil
---

---
layout: image-left
image: /schlaganfall.avif
---

# Arterienverkalkung

## Schlaganfall

---
layout: image-right
image: /herz.jpg
title: Herzinfarkt
---

# Arterienverkalkung

## Herzinfarkt

---
layout: image-right
image: /wade.jpg
title: pAVK
---

# Arterienverkalkung

<h3 class="text-red">arterielle Verschlusskrankheit</h3>
<h3 class="text-red">pAVK</h3>

<br>

<v-clicks>

| Stadium | Bescherden           |
| ------- | -------------------- |
| I       | keine                |
| II      | Schmerzen beim Gehen |
| III     | Schmerzen in Ruhe    |
| IV      | Wunden               |

</v-clicks>

---
layout: image
image: /bahnhof.jpg
title: Bahnhof
---

<div class="abs-bl left-10 bottom-10 !text-(shadow-lg 5xl)">arterielle Verschlusskrankheit</div>

---
src: ./pages/prognose_1.md
---

---
layout: image-left
image: /fuesse.avif
---

# arterielle Verschlusskrankheit

<h2 class="text-red">Durchblutungstörungen</h2>

<v-clicks>

- <span v-mark.underline.red="1">Schmerzen</span> beim Gehen
  - Füße, Wade, Oberschenkel, Gesäß
- kühle, blasse oder marmorierte Haut
- trockene Haut
- starke Verhornung
- langsam wachsende Fußnägel
- Erektionsstörungen
- schlecht heilende <span v-mark.underline.red="7">Wunden</span>

</v-clicks>

---
layout: image-left
image: /fusspulse.jpg
---

## Untersuchung

<v-clicks>

- Fußpulse
- ABI-Messung
- Ultraschalluntersuchung
- Computertomografie
- Kernspin-Untersuchung

</v-clicks>

<div   v-motion
  :initial="{ x: -50 }"
  :enter="{ x: 0 }"
  :click-6="{ x: 20 }"
  :leave="{ x: 0 }">
  <el-hand-right class="size-10 mt-5 ml-6 text-yellow-5" v-click/>
</div>

---
layout: image
image: /abi-messung.jpg
title: ABI
---

<div class="abs-tl left-26 top-10 !text-(shadow-lg 4xl) text-black">ABI-Messung</div>

---
layout: image
image: /abi.jpg
title: ABI-Ausdruck
---

<!-- <span v-mark.circle.blue="1">Wunden</span> -->

<span v-mark="{ at: 1, color: 'blue', type: 'circle', strokeWidth: '7' }" class="text-transparent abs-tl mt-108 ml-60">XXXXXXXX</span>
<span v-mark="{ at: 2, color: 'blue', type: 'circle', strokeWidth: '7' }" class="text-transparent abs-tl mt-22 ml-60">XXXXXXXX</span>
<span v-mark="{ at: 3, color: 'blue', type: 'circle', strokeWidth: '7' }" class="text-transparent abs-tl mt-66 ml-60">XXXXXXXXXX</span>

---
title: Ultraschall
---

<SlidevVideo autoplay class="abs-tl">
<source src="/us.mp4" type="video/mp4" />
</SlidevVideo>

<div class="abs-bl bottom-10 !text-(shadow-lg 4xl) ">Ultraschall-Untersuchung</div>

---
layout: two-cols
---

<img src="/ct.jpg" class="w-70"/>

::right::

<SlidevVideo autoplay>
  <source src="/3dct.mp4" type="video/mp4"/>
</SlidevVideo>

---

# Behandlungsmöglichkeiten

- Gehtraining
- PTA (Aufdehnen)
- Operationene
  - Ausschäloperation
  - Bypassoperation

---
layout: two-cols
---

<div class="abs-tl ml-20 mt-16 !text-(shadow-lg 5xl)">Gehtraining</div>

<img src="/gehtraining.jpeg" class="object-cover h-full"/>

::right::

<img src="/kollateralen.jpg" class="h-full"/>

---
title: PTA
---

<div class="abs-tl ml-20 mt-16 !text-(shadow-lg 6xl)">PTA</div>

<SlidevVideo autoplay>
<source src="/pta.mp4" type="video/mp4" />
</SlidevVideo>

---

## TEA

---

## Bypass

---

## Risikofaktoren

- Rauchen
- Zuckerkrankheit
- Fettstoffwechselstörungen
- Veranlagung

---

## Ernährung

- Proteine
- Kohlenhydraten
- Fetten

---
layout: image-right
image: /baustoffe.webp
---

## Proteine

<div class="space-x-2xl">
  <twemoji-cut-of-meat class="size-10 mt-5"/>
  <emojione-v1-fish class="size-10 mt-5"/>
  <twemoji-cheese-wedge class="size-10 mt-5"/>
  <twemoji-beans class="size-10 mt-5"/>
  <emojione-egg class="size-10 mt-5"/>
  <twemoji-coconut class="size-10 mt-5"/>
</div>

<br>
<v-clicks depth="2">

- Bausstoff
  - Reparatur
  - Muskeln
  - Knochen
  - Haut
  - Organe
  - Antikörper
  - Enzyme
  - Transport
- kann nicht gespeichert werden

</v-clicks>

---
layout: image-right
image: /papier.avif
---

## Kohlenhydrate

<div class="space-x-2xl">
  <emojione-bread class="size-10"/>
  <game-icons-bowl-of-rice class="size-10"/>
  <emojione-spaghetti class="size-10"/>
  <streamline-emojis-tropical-drink class="size-10"/>
  <twemoji-banana class="size-10"/>
  <streamline-emojis-candy class="size-10"/>
  <img src="/cola.png" class="size-10"/>
</div>

<br>
<v-clicks depth="2">

- Schnell verfügbare Energie
- Speicher:
  - Leber (kurzfristige Energie ca 60 Min)
  - als Fett (langfristig)

</v-clicks>

---

## Fett

- gesättigte Fettsäuren
<div class="space-x-2xl">
  <twemoji-butter class="size-10"/>
  <emojione-bacon class="size-10"/>
</div>

- ungesättigte Fettsäuren

<div class="flex space-x-2xl">
  <img src="/olive-oil.png" class="size-10"/>
  <emojione-v1-sunflower class="size-10"/>
  <twemoji-fish class="size-10"/>
</div>

- Transfette

<div class="flex space-x-2xl">
  <img src="/margarine.png" class="size-10"/>
</div>

---

## Cholesterinhypthese

Nikolai Anitschkow 1913
Ancel keys 50er - viel gesättigtes Fett === cholesterin steigt
Studien vergleicht er den Fettkonsum und die Anzahl der Herztode in mehreren Ländern
In seinen Statistiken kann er eindrucksvoll zeigen: Je mehr Fett und gesättigte Fettsäuren die Menschen essen, desto höher ist auch die Rate an Herzkrankheiten.
2 Studien 6 und 7 (ohne Deutschland, Frankreich Schweiz) - Käse, Schmalz Wurst und Fleisch
Diet-Heart-Hypthese
jeder 2. Herzinfarktpatient völlig normalen Cholesterinspiegel

Georg Mann - Afrika Massai-Krieger - Fleisch, Milch und Rinderblut -extrem Fettreich -schlank kerngesund

John Yudkin - rafinierte Kohlenhydrate - Zucker

1980 Diatary Guidelines der USA - Fettarme Ernährung (tierisch)

2007 Professor Gardner A to Z Study - Low-Carb-Diät - Cholesterin stieg, Trigyceride halbiert, Gewichtsabnahme, Blutdruckabnahme

---

## Plaque-Entstehung

<Arrow x1="10" y1="20" x2="100" y2="200" />

<AutoFitText :max="200" :min="100" modelValue="Some text"/>

---

clean eating
Lege klärt auf
DGE Omega-6- zu Omega-3-Fettsäureverhältniss 5:1
Ölivenöl 126:1
Triglyceride - Kohlenhydrate
HDL-Infusionen
Y-Tube Weigl: Vegane Ernährung und Sport

---

## Ideen

Lehrmeinung - evidence based medizin - Regelwerk
Leitlinien

Erfahrungsmedizin

Rauchen
Bluthochdruck
Zuckerkrankheit
Fettstroffwechselstörungen

Ernährung - Fettarm und Vegan
Bewegung
