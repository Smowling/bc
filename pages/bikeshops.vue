<template>
    <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>What to expect</template>
      <!-- <template v-slot:desc>Do you own a bikeshop? Lets talk.</template> -->
    </LandingSectionhead>

    <BikeshopFeatures></BikeshopFeatures>

  </LandingContainer>
</template>

<script setup>
definePageMeta({
  layout: "landing",
});

</script>

<style lang="scss" scoped>

</style>