<template>
  <div>
    <h2>Tag: {{ params.slug }}</h2>
  </div>
</template>

<script>
export default {
  asyncData({ params }) {
    return { params };
  },
};
</script>
