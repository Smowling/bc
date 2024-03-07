<script setup>
definePageMeta({
  layout: "landing",
});

</script>

<template>
  <LandingContainer>
    <LandingSectionhead>
      <template v-slot:title>About project</template>
    </LandingSectionhead>

    <div class="flex flex-col gap-3 mx-auto max-w-4xl mt-16">
      <h2 class="font-bold text-3xl text-gray-800">
        What is it all about?
      </h2>
      <p class="text-lg leading-relaxed text-slate-500">
        Hi, I'm Daniel, and I hate to leave my bike for weeks to gather dust and wait for a fix, so I have built Bikecheck!
      </p>
    </div>
    <div class="flex justify-center md:grid-cols-3 gap-10 mx-auto max-w-xl mt-12">
      <div class="group">
        <div class="w-full aspect-square">
          <img
            src="~/assets/img/me.jpg"
            width="480"
            height="560"
            format="avif"
            alt="Daniel Smółka"
            class="w-full h-full object-cover rounded transition group-hover:-translate-y-1 group-hover:shadow-xl"
          />
        </div>

        <div class="mt-4 text-center">
          <h2 class="text-lg text-gray-800">Daniel Smółka</h2>
          <h3 class="text-sm text-slate-500">One man army</h3>
        </div>
      </div>
    </div>
  </LandingContainer>
</template>
