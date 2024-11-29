## Prognose

<div class="absolute text-center text-sm top-16 left-10">

  <div class="flex justify-around">
    <div class="ml-24 w-34 border-(white 2) rounded p-1">
      pAVK<br>bei Stadium II
    </div>
  </div>

  <div class="relative flex ml-44 mt-12">
    <div class="flex space-x-86">
      <div class="box pt-4 before:(line -skew-y-15 h1 w28 -top-6 left-28)" v-click="5">
        5-Jares -<br>Gesamtprognose
      </div>
      <div class="box before:(line skew-y-15 h1 w28 -top-6 left-98)" v-click="1">
        5-Jahres<br>Prognose<br>für das Bein
      </div>
    </div>
  </div>

  <div class="relative flex mt-12 ml-4">
    <div class="flex space-x-26">
      <div class="flex space-x-6">
        <div class="box highlight before:(line -skew-y-15 h1 w22 -top-7 left-22)" v-click="6">
          35%<br>gefäßbedingte<br>Ereignisse
        </div>
        <div class="box before:(line w-1 h-8 -top-10 left-56)" v-click="9">
          60%<br>ereignisfreies<br>Überleben
        </div>
        <div class="box before:(line skew-y-15 h1 w22 -top-7 left-70)" v-click="10">
          5%<br>Tod nicht<br>gefäßbedingt
        </div>
      </div>
      <div class="flex space-x-6">
        <div class="box pt-4 before:(line -skew-y-30 h1 w12 -top-7 left-156)"  v-click="2">
          75%<br>Stabilisation
        </div>
        <div class="box pt-4 before:(line skew-y-30 h1 w12 -top-7 left-185)"  v-click="3">
          25%<br>Verschlechterung
        </div>
      </div>
    </div>
  </div>

  <div class="relative flex justify-between mt-12 ml-4">
    <div class="flex space-x-6">
      <div class="box highlight before:(line w-1 h-8 -top-10 left-17)" v-click="7">
        10%<br>nicht tötliches<br>Ereignis
      </div>
      <div class="box highlight before:(line skew-y-20 h1 w18 -top-6 left-27)" v-click="8">
        25%<br>gefäßbedingter<br>Tod
      </div>
    </div>
    <div class="flex space-x-6">
      <div class="box pt-4 highlight before:(line w-1 h-8 -top-10 left-197)" v-click="4">
        2%<br>Amputation
      </div>
    </div>
  </div>
  
</div>

<style>
.slidev-vclick-current.highlight,.slidev-vclick-prior.highlight {
  border-color: red !important;
}
</style>
