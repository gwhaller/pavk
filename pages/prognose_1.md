## Prognose

<div class="absolute text-center text-sm top-10 left-10">

  <div class="flex justify-around ml-42">
    <div class="w-34 border-(white 2) rounded p-1">
      pAVK<br>bei Stadium II
    </div>
  </div>

  <div class="flex justify-around ml-22 mt-12">
    <div class="flex space-x-72">
      <div class="relative w-40 border-(white 2) rounded p-1 pt-4 before:(content-[''] absolute bg-white rounded-full -skew-y-10 h1 w42 -top-7 left-30)" v-click="5">
        5-Jares -<br>Gesamtprognose
      </div>
      <div class="relative w-40 border-(white 2) rounded p-1 before:(content-[''] absolute bg-white rounded-full skew-y-15 h1 w22 -top-7 -left-13)" v-click="1">
        5-Jahres<br>Prognose<br>für das Bein
      </div>
    </div>
  </div>

  <div class="flex justify-around mt-12">
    <div class="flex space-x-8">
      <div class="flex space-x-4">
        <div class="relative w-40 border-(white 2) rounded p-1 pt-4 highlight before:(content-[''] absolute bg-white rounded-full -skew-y-15 h1 w22 -top-7 left-28)" v-click="6">
          35% kardiovaskuläre<br>Ereignisse
        </div>
        <div class="relative w-40 border-(white 2) rounded p-1 before:(content-[''] absolute bg-white rounded-full w-1 h-8 -top-10 left-20)" v-click="9">
          60%<br>ereignisfreies<br>Überleben
        </div>
        <div class="relative w-40 border-(white 2) rounded p-1 before:(content-[''] absolute bg-white rounded-full skew-y-15 h1 w22 -top-7 -left-9)" v-click="10">
          5%<br>Tod nicht<br>vaskulär
        </div>
      </div>
      <div class="flex space-x-4">
        <div class="relative w-40 border-(white 2) rounded p-1 pt-4 before:(content-[''] absolute bg-white rounded-full -skew-y-30 h1 w12 -top-7 left-23)"  v-click="2">
          75%<br>Stabilisation
        </div>
        <div class="relative w-40 border-(white 2) rounded p-1 pt-4 before:(content-[''] absolute bg-white rounded-full skew-y-30 h1 w12 -top-7 left-4)"  v-click="3">
          25%<br>Verschlechterung
        </div>
      </div>
    </div>
  </div>

  <div class="flex justify-between mt-12">
    <div class="flex space-x-4">
      <div class="relative w-40 border-white border-2 rounded p-1 highlight before:(content-[''] absolute bg-white rounded-full w-1 h-8 -top-10 left-20)" v-click="7">
        10%<br>nicht letales kardio-<br>vaskuläres Ereignis
      </div>
      <div class="relative w-40 border-white border-2 rounded p-1 highlight before:(content-[''] absolute bg-white rounded-full skew-y-10 h1 w36 -top-7 -left-17)" v-click="8">
        25%<br>kardiovaskulärer<br>Tod
      </div>
    </div>
    <div class="flex space-x-4">
      <div class="relative w-40 border-white border-2 rounded p-1 highlight before:(content-[''] absolute bg-white rounded-full w-1 h-8 -top-10 left-18)" v-click="4">
        2%<br>Extremitäten<br>Amputation
      </div>
    </div>
  </div>
  
</div>

<style>
.slidev-vclick-current.highlight,.slidev-vclick-prior.highlight {
  border-color: red !important;
}
</style>
