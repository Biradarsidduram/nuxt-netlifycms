<template>
  <h2>Probably the index page...</h2>
</template>

<script lang="ts">
export default {
  name: "IndexPage",
  head() {
    return {
      script: [
        { src: "https://identity.netlify.com/v1/netlify-identity-widget.js" },
      ],
    };
  },
  data() {
    return {};
  },
};
</script>