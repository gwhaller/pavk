## Prognose

<div class="absolute text-center text-sm top-10 left-10">

  <div class="flex justify-around ml-42">
    <div class="w-34 border-white border-2 rounded p-1">
      pAVK<br>bei Stadium II
    </div>
  </div>

  <div class="flex justify-around h-12  ml-22">
    <div class="flex space-x-26 items-center">
      <div class="h-1 w-42 bg-white rounded-full -skew-y-10" v-click="5"/>
      <div class="h-1 w-22 bg-white rounded-full skew-y-15" v-click="1"/>
    </div>
  </div>

  <div class="flex justify-around  ml-22">
    <div class="flex space-x-72">
      <div class="w-40 border-white border-2 rounded p-1 pt-4" v-click="5">
        5-Jares -<br>Gesamtprognose
      </div>
      <div class="w-40 border-white border-2 rounded p-1" v-click="1">
        5-Jahres<br>Prognose<br>für das Bein
      </div>
    </div>
  </div>

  <div class="flex h-12">
    <div class="flex space-x-14 items-center ml-28">
      <div class="h-1 w-22 bg-white rounded-full -skew-y-15" v-click="6" />
      <div class="w-1 h-8 bg-white rounded-full"  v-click="9"/>
      <div class="h-1 w-22 bg-white rounded-full skew-y-15"  v-click="10"/>
    </div>
    <div class="flex space-x-14 items-center ml-58">
      <div class="h-1 w-12 bg-white rounded-full -skew-y-30" v-click="2"/>
      <div class="h-1 w-12 bg-white rounded-full skew-y-30" v-click="3"/>
    </div>
  </div>

  <div class="flex justify-around">
    <div class="flex space-x-8">
      <div class="flex space-x-4">
        <div class="w-40 border-white border-2 rounded p-1 pt-4 highlight" v-click="6">
          35% kardiovaskuläre<br>Ereignisse
        </div>
        <div class="w-40 border-white border-2 rounded p-1" v-click="9">
          60%<br>ereignisfreies<br>Überleben
        </div>
        <div class="w-40 border-white border-2 rounded p-1" v-click="10">
          5%<br>Tod nicht<br>vaskulär
        </div>
      </div>
      <div class="flex space-x-4">
        <div class="w-40 border-white border-2 rounded p-1"  v-click="2">
          75%<br>Stabilisation
        </div>
        <div class="w-40 border-white border-2 rounded p-1"  v-click="3">
          25%<br>Verschlechterung
        </div>
      </div>
    </div>
  </div>

  <div class="flex h-12">
    <div class="ml-20 mt-2 w-1 h-8 bg-white rounded-full" v-click="7"/>
    <div class="ml-6 mt-6 w-36 h-1 bg-white rounded-full skew-y-10" v-click="8"/>
    <div class="ml-136 mt-2 w-1 h-8 bg-white rounded-full"  v-click="4"/>
  </div>

  <div class="flex justify-between">
    <div class="flex space-x-4">
      <div class="w-40 border-white border-2 rounded p-1 highlight" v-click="7">
        10%<br>nicht letales kardio-<br>vaskuläres Ereignis
      </div>
      <div class="w-40 border-white border-2 rounded p-1 highlight" v-click="8">
        25%<br>kardiovaskulärer<br>Tod
      </div>
    </div>
    <div class="flex space-x-4">
      <div class="w-40 border-white border-2 rounded p-1 highlight" v-click="4">
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
