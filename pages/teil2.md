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
- Fett (langfristig)

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
<br><br>

### Natürlich vorkommende Kohlenhydrate

<img src="/gute-kh.webp" class="abs-bl w-110 m-6 ml-10"/>
<img src="/verdauung_kohlenhydrate.jpg" class="abs-br w-110 m-6 mr-10"/>

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

### Raffinierte Kohlenhydrate

#### Zucker === Mehl

<img src="/raffinierte-kh.jpg" class="abs-bl w-93 m-6 ml-10"/>
<div class="relativ">
  <img src="/verdauung_zucker.jpg" class="abs-br w-110 m-6 mr-10"/>
  <!-- <fluent-emoji-cross-mark class="absolute size-10" /> -->
</div>

---

## Kohlenhydrate

<div class="flex mt-8 mb-4">
  <div class="text-2xl myt-4 mr-2">
    Kurze Geschichte des Zuckers
  </div>
    <img src="/wuerfelzucker.png" class="inline-block align-top"/>
</div>

- galt lange Zeit als äußerst rar und kostbar
- Kolonialzeit: Zuckerrohr aus MIttel- und Südamerika
- späten 18. Jahrhundert: Rübenzucker
- zweite Hälfte des letzten Jahrhunderts: industrielle Massenfertigung
  - gleichzeitig Supermärkte und Fast-Food-Ketten
  - immer mehr zuckerhaltige Fertigprodukte und Getränke
- 70er: High Fructose Corn Sirup
- Zuckerkonsum pro Kopf: 1850 8g Zucker - Heute im Durchschnitt 100g am Tag

  <img src="/zucker.jpg" class="abs-tr w-110 m-6 mr-10"/>

---

<div class="flex">
  <div class="text-3xl mt-4 mr-2">
    Kohlenhydrate
  </div>
  <div class="*:size-12 *:m-2" ><emojione-baguette-bread />
    <img src="/wuerfelzucker.png" class="inline-block align-top"/>
  </div>
</div>

### <br>Zucker

- bevorzugte Energiequelle
- kann Gewebestrukturen schädigen<br>
  -- karamellisieren (HbA1c)

### <br>Insulin

- Masthormon
- schleust Zucker in die Zelle
- fördert die Bildung von Fett
- verhindert den Fettabbau

<img src="/Apfel-Karamell.png" class="abs-tr w-50 m-6 mr-20"/>
<div class="abs-br">
  <span class="absolute text-red-500 top-50 left-75 text-sm">Basiswerte</span>
  <img src="/insulin_kurve.png" class=" w-100 m-6 mr-20" />
</div>

---

<div class="flex">
  <div class="text-3xl mt-4 mr-2">
    Kohlenhydrate
  </div>
  <div class="*:size-12 *:m-2" ><emojione-baguette-bread />
    <img src="/wuerfelzucker.png" class="inline-block align-top"/>
  </div>
</div>
<br>

<v-click>

### Moderater Zucker- und Mehl-Konsum<img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/><br>

- im Tagesverlauf: Blutzucker<la-arrow-up class="mt-1"/> => Insulin<la-arrow-up class="align-middle"/><br>
- Nüchtern Blutzucker und Insulin im Normbereich <oui-dot class="text-green-500" />

</v-click>
<v-click>

### <br>Erhöhter Konsum<img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/><img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/><img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/>

- Nüchtern-Insulin steigt (bis 10x) Blutzucker normal <oui-dot class="text-yellow-500" /><br>
  <span class="ml-4">-> Prä-Diabetes (viele Jahre unentdeckt)</span>
- Nüchtern-Blutzucker steigt <oui-dot class="text-red-500" /><br>
  <span class="ml-4">-> Diabetes</span>

</v-click>

<div class="abs-br">
  <el-arrow-up v-if="$clicks === 2" class="absolute text-blue-500 top-40 left-70 size-12 motion-translate-y-loop-25"/>
  <img src="/insulin_kurve.png" class=" w-95 mr-20 mb-20" />
</div>

---

<div class="flex">
  <div class="text-3xl mt-4 mr-2">
    Kohlenhydrate
  </div>
  <div class="*:size-12 *:m-2" ><emojione-baguette-bread />
    <img src="/wuerfelzucker.png" class="inline-block align-top"/>
  </div>
</div>

### Prä-Diabetes

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
