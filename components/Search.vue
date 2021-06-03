<template>
  <div class="min-w-screen min-h-screen bg-gray-200 flex items-center justify-center px-5 py-5">
    <div class="w-full mx-auto rounded-xl bg-gray-100 shadow-lg p-10 text-gray-800 relative overflow-hidden min-w-80 max-w-3xl" x-data="app()" x-init="generatePassword()">
      <div class="relative mt-1">
        <input type="text" id="password" class="w-full pl-3 pr-10 py-2 border-2 border-gray-200 rounded-xl hover:border-gray-300 focus:outline-none focus:border-blue-500 transition-colors" placeholder="Rechercher une station">
        <div class="relative items-center justify-center">
          <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
            Rechercher
          </button>
        </div>
      </div>
     </div>
  </div>
</template>

<script>
export default {
  name: "Search",
  data() {
    return {
      q: ''
    }
  },
  methods: {
    searchTask(){

    }
  }
}
</script>

<style scoped>

</style>
