---
# clicks:3
---

## Prognose

<div class="absolute text-center text-sm top-10 left-10">

  <div class="flex justify-around">
    <div class="w-34 border-white border-2 rounded p-1">
      pAVK<br>bei Stadium II
    </div>
  </div>

  <div class="flex justify-around h-12">
    <div class="flex space-x-18 items-center">
      <div class="h-1 w-22 bg-white rounded-full -skew-y-20 highlight" v-click='1' />
      <div class="h-1 w-22 bg-white rounded-full skew-y-20" v-click='2'/>
    </div>
  </div>

  <div class="flex justify-around">
    <div class="flex space-x-32">
      <div class="w-40 border-white border-2 rounded p-1 pt-4 highlight" v-click='1' >
        5-Jares -<br>Gesamtprognose
      </div>
      <div class="w-40 border-white border-2 rounded p-1"  v-click='2'>
        5-Jahres<br>Prognose<br>für das Bein
      </div>
    </div>
  </div>

  <div class="flex justify-around h-12">
  </div>

  <div class="flex justify-around">
    <div class="flex space-x-8">
      <div class="flex space-x-4">
        <div class="w-40 border-white border-2 rounded p-1 pt-4 highlight">
          35% kardiovaskuläre<br>Ereignisse
        </div>
        <div class="w-40 border-white border-2 rounded p-1">
          60%<br>ereignisfreies<br>Überleben
        </div>
        <div class="w-40 border-white border-2 rounded p-1">
          5%<br>Tod nicht<br>vaskulär
        </div>
      </div>
      <div class="flex space-x-4">
        <div class="w-40 border-white border-2 rounded p-1">
          75%<br>Stabilisation
        </div>
        <div class="w-40 border-white border-2 rounded p-1">
          25%<br>Verschlechterung
        </div>
      </div>
    </div>
  </div>

  <div class="flex justify-around h-12">
  </div>

  <div class="flex justify-between">
    <div class="flex space-x-4">
      <div class="w-40 border-white border-2 rounded p-1 highlight">
        10%<br>nicht letales kardio-<br>vaskuläres Ereignis
      </div>
      <div class="w-40 border-white border-2 rounded p-1">
        25%<br>kardiovaskulärer<br>Tod
      </div>
    </div>
    <div class="flex space-x-4">
      <div class="w-40 border-white border-2 rounded p-1">
        2%<br>Extremitäten<br>Amputatoin
      </div>
    </div>
  </div>
  
</div>

<style>
.slidev-vclick-current.highlight,.slidev-vclick-prior.highlight {
  border-color: red !important;
}
</style>
