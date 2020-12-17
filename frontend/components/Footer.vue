<template>
<div class="flex justify-between m-6">
  <p class="text-xs font-semibold text-gray-600">Nepali Books: Nepal's biggest library of Nepali Books.</p>
  <div class="flex">
    <a href="https://twitter.com/nepalibooks" class="max-w-xs ml-4">
      <Twitter />
    </a>
    <a href="https://facebook.com/nepalibooks" class="ml-3">
      <Facebook />
    </a>
   
  </div>
</div>
</template>
<script>
import Twitter from "~/components/icons/twitter.vue";
import Facebook from "~/components/icons/facebook.vue";

export default {
  components: {
    Twitter,
    Facebook
  }
}
</script>

<style>
.emoji {
  font-size: 30px;
}
</style>
