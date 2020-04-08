<template>
  <div class="hello">
    <input type="text" v-model="$attrs.value.salutation">
    <input type="text" v-model="$attrs.value.name">
  </div>
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>