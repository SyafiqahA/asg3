<template>
<div class="flex p-1">
  <div class="flex-none w-44 relative">
    <img src="../assets/iqah1.jpeg" alt="" class="h-48 w-full object-cover md:w-48" />
  </div>
  <form class="flex-auto py-7 px-8">
    <div class="flex flex-wrap items-baseline">
      <h3 class="w-full flex-none text-3xl  text-red-500 mb-1.5">
        Nur Syafiqah binti Abdullah
      </h3>
    </div>
    <p class="text-sm text-blue-300">
        Hobbies: 
      </p>
    <p class="text-sm text-blue-300">
      Watching korean drama and reading
    </p>
  </form>
</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
