<template>
<div>
</div>
</template>

<script>
let x = 2;
</script>

<script lang="coffee">
[a, b...] = [1, 2, 3]
</script>

<script setup>
  const five = 5;
</script>

<script setup lang="js">
  const five = 5;
</script>

<script lang="js" setup>
  const five = 5;
</script>


<i18n>
{
  "en": {
    "hello": "hello world!"
  },
  "ja": {
    "hello": "こんにちは、世界！"
  }
}
</i18n>

<style scoped>
.looks-fine-to-me {
    color: red;
}
</style>

<style lang="sass" scoped>
.looks-fine-to-me
  color: red
</style>

<style key="value" scoped module lang="scss" another-key="another_value?">
#important
  color: red
</style>
