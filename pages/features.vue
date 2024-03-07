<template>
    <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>Features</template>
      <!-- <template v-slot:desc>Do you own a bikeshop? Lets talk.</template> -->
    </LandingSectionhead>

    <LandingFeatures></LandingFeatures>

  </LandingContainer>
</template>

<script setup>
definePageMeta({
  layout: "landing",
});

</script>

<style lang="scss" scoped>

</style>