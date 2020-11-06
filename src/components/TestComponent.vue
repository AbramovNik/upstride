<template>
  <div>
    <p>Test Text</p>
    <h1>{{ testText }}</h1>
  </div>
</template>

<script>
export default {
  name: "TestComponent",
  props: {
    testText: String,
  },
};
</script>