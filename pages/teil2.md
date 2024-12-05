---
layout: image
image: /evolution.png
backgroundSize: 80%
class: bg-white  font-bold text-7xl tracking-tight text-center
---

<div class="-mt-6 p-2 bg-white text-blue-6">Evolution</div>
<div class="mt-77 p-2 bg-white text-blue-6">macht uns krank ?</div>

---
layout: center
class: text-center text-6xl
---

Gesundheit

<div class="text-3xl m-8">ist</div>

Eigenverantwortung

---
layout: image-right
image: /essen.avif
clicks: 3
---

## Ernährung

<br>

<div v-click=1 class="relative mb-10 makronaehrstoff">
    <el-hand-right v-if="$clicks === 3" class="absolute top-8 left-60 motion-translate-x-loop-25 motion-blur-in-sm size-10 mt-7 ml-10 text-yellow-5" />

### Makronährstoffe

- Proteine - Eiweiß
- Kohlenhydrate
- Fette

</div>

<div v-click=2>

### Mikronährstoffe

- Vitamine
- Mineralien <span class="ml-6 text-sm">Kochsalz, Kalium, Calcium, Magnesium</span>
- Spurenelemente

</div>

<style>
.slidev-vclick-prior.makronaehrstoff {
  opacity: 1.0 !important;
}
</style>

---
layout: image-right
image: /baustoffe.webp
---

# Proteine = Eiweiß

<span class="*:size-12 *:mx-2">
  <twemoji-cut-of-meat />
  <emojione-v1-fish />
  <fluent-emoji-flat-glass-of-milk />
  <twemoji-cheese-wedge />
  <emojione-egg />
  <twemoji-beans />
  <img src="/walnut.png" class="inline-block align-top"/>
</span>

<br>
<br>

### Baustoff

#### kann nicht gespeichert werden

<br>
<v-clicks>

- Reparatur
- Organe, Muskeln, Knochen, Gelenke, Haut
- Antikörper
- Enzyme
- Hormone
- Transport

</v-clicks>

---
layout: image-right
image: /papier.avif
---

## Kohlenhydrate

<div class="*:size-12 *:m-2" >
  <emojione-baguette-bread />
  <emojione-croissant />
  <emojione-pancakes />
  <noto-cooked-rice />
  <emojione-spaghetti />
  <emojione-hamburger />
  <emojione-pizza />
  <twemoji-banana />
  <streamline-emojis-candy />
  <img src="/ketchup.png" class="inline-block align-top"/>
  <noto-beverage-box />
  <img src="/cola.png" class="inline-block align-top"/>
</div>

<br>
<br>

### Brennstoff

#### Schnell verfügbare Energie

#### Speicherbar

<v-clicks depth="2">

- Leber (kurzfristige Energie ca 60 Min)
- als Fett (langfristig)

</v-clicks>

---

<div class="grid grid-cols-2 gap-4">

<div>

## Fett

<br>

<v-click>

### gesättigte Fettsäuren

</v-click>

<div class="flex justify-between mb-20">

  <div v-click=1 class="flex space-x-2xl *:size-12">
    <img class="size-12" src="/butter2.png"/>
    <noto-v1-bacon/>
    <emojione-avocado/>
    <twemoji-coconut/>
  </div>
  <div>
    <span v-click class="mr-10">Brennstoff</span><br>
    <span v-click v-mark.underline.red="3">Vitamine</span>
  </div>
</div>

<v-click at=4>

### ungesättigte Fettsäuren

</v-click>

<div class="flex justify-between">
  <div v-click=4  class="flex space-x-2xl *:size-12">
    <img src="/olive-oil.png"/>
    <openmoji-olive/>
    <emojione-v1-sunflower/>
    <twemoji-fish/>
  </div>
  <div v-click=5 class="mr-10 pt-4">Chemikalien</div>
</div>

</div>

<div>
  <img src="/kohle.webp" class="h-60"/>
  <img src="/putzmittel.avif" class="h-54 mt-4"/>

</div>
</div>

---
layout: image-right
image: /transfette.avif
---

## Transfette <emojione-v1-black-skull-cross-bones class="ml-6"/>

<v-clicks>

- Pommes, Chicken Wings, Krapfen
- Sonnenblumenölmargarine
- Chips, Cornflakes
- Wurst
- Fertigsuppen
- Müsliriegel
- Cappucino-Pulver
- <span v-mark.underline.red="8">Fertiggerichte</span>

</v-clicks>

<!--
In Dänemark dürfen Lebensmittel bereits seit 15 Jahren nicht mehr als zwei Prozent Transfette enthalten. Seitdem ist die Zahl der Herzerkrankungen laut einer Studie deutlich zurückgegangen, um etwa 700 Todesfälle pro Jahr. In Deutschland gibt es derzeit keine gesetzlichen Regelungen für Transfette in Lebensmitteln.
-->

---

## Eiweiß - Proteine

<span class="*:size-12 *:mx-2">
  <twemoji-cut-of-meat />
  <emojione-v1-fish />
  <fluent-emoji-flat-glass-of-milk />
  <twemoji-cheese-wedge />
  <emojione-egg />
  <twemoji-beans />
  <img src="/walnut.png" class="inline-block align-top"/>
</span>

<v-clicks>

- Baumaterial
- ca 20 % der Körpermasse
- ca 50.000 verschiede Eiweißstoffe im menschlichen Körper
- Grundbausteine sind die 20 Aminosäuren
- davon 9 Aminosäuren <span v-mark.underline.red="5">unentbehrlich</span> !
  > Weizen fehlt es an der <span class="text-red-300 font-bold">Lysin</span><br>
  > Hülsenfrüchten mangelt es an <span class="text-red-300 font-bold">Methionin</span>
- Aufnahme beindert durch Magenschutztabletten
- tgl ca 300 g Eiweiß recycled
- überschüssige Eiweiße werden verbrannt

</v-clicks>

<img src="/darm_eiweiss.jpg" class="abs-br w-130 p-4"/>

---
layout: two-cols
---

## <emojione-baguette-bread mr-4/> Lysin-Mangel

- Wachstumsstörungen bei Kindern
- Kollagenmangel
- erhöhte Infektanfälligkeit
- Übelkeit
- Müdigkeit und Konzentrationsschwäche
- rote Augen
- Haarausfall
- beeinträchtigte Proteinsynthese

::right::

## <twemoji-beans mr-4/>Methionin-Mangel

- Wassereinlagerungen
- erhöhte Infektanfälligkeit
- erhöhtes Arteriosklerose-Risiko
- Neigung zu Haarausfall
- Verschlechterung bestehender Allergien
- eingeschränkte Entgiftungsfunktion

---

## Kohlenhydrate

<div class="*:size-12 *:m-2" >
  <emojione-baguette-bread />
  <emojione-croissant />
  <emojione-pancakes />
  <noto-cooked-rice />
  <emojione-spaghetti />
  <emojione-hamburger />
  <emojione-pizza />
  <twemoji-banana />
  <streamline-emojis-candy />
  <img src="/ketchup.png" class="inline-block align-top"/>
  <noto-beverage-box />
  <img src="/cola.png" class="inline-block align-top"/>
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
