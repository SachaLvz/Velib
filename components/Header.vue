<template>
  <nav class="bg-gray-800">
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
      <div class="relative flex items-center justify-between h-16">
        <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">

        </div>
        <div class="flex-1 flex items-center justify-center sm:items-stretch">
          <div class="flex-shrink-0 flex items-center">
            <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-mark-indigo-500.svg" alt="Workflow">
          </div>
        </div>
        </div>
    </div>
  </nav>
</template>

<script>
import Search from "./Search";
export default {
  name: "Header",
  components: {Search},
}
</script>

<style scoped>

</style>
