<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="purple">{{ msg }}</h1>
    <h3>
      Being able to have good cosmetics that meet your needs is another happiness that will allow us to beautify with more confidence and of course Bobbi Brown is another quality brand that will not disappoint you. Of course 🥰💘You’ve successfully created a project with
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 750;
  font-size: 4rem;
  top: -15px;
}

h3 {
  font-size: 0.3rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: center;
  }
}
</style>
