<script setup>
const features = [
  {
    title: "Find your LBS",
    description:
      "Use our search and figure out where to go for your bike. We have a map that will help you find the nearest bike shop.",
    icon: "bx:bxs-briefcase",
  },
  {
    title: "Check out services",
    description:
      "Figure out what type of service and maintanance you want for your bike. We have a list of services that you can choose from.",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "Book a date",
    description:
      "Check avaliable date and book it, if you know workers you can directly choose them.",
    icon: "bx:bxs-data",
  },
  {
    title: "Get notified",
    description:
      "When the time comes, we will mail you with the details of your service and when you should drop off your bike.",
    icon: "bx:bxs-bot",
  },
  {
    title: "Wait for it",
    description:
      "Now its all up to the bikeshop. When they are all done you will get a mail that you can pick up your bike.",
    icon: "bx:bxs-file-find",
  },
  {
    title: "Rate your service",
    description:
      "Now you can share your expirience, rating and reviewing your service.",
    icon: "bx:bxs-user",
  },
];
</script>

<template>
  <div class="mt-16 md:mt-0">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      Everything you need to know
    </h2>
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-3 mt-16 gap-16">
    <div v-for="item of features" class="flex gap-4 items-start">
      <div class="mt-1 bg-black rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
</template>
