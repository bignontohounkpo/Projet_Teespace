<template>
  <div :class="{ 'border-green': showtext }" class="flex-container shadow-sm">
    <span
      :class="{
        'text-white': showtext,
        'fw-bold': true,
      }"
    >
      {{ title }}
    </span>
    <button @click="toggle" class="btn-no-border">
      <img :src="showtext ? minusIcon : plusIcon" alt="Toggle Icon" />
    </button>
  </div>

  <p v-if="showtext" class="text-secondary">
    To make a T-shirt design, you first need to install specific graphic design
    software. Once you’ve done that, start your creation and make sure that your
    final design is at least 220 PPI so it won’t be pixelated when printed…
    <br />
    To design your own T-shirt, you can upload your design to the front of your
    tee and add custom elements like text. For some of our T-shirts, reverse
    side printing is also available
  </p>
  <hr />
</template> 
  <script>
export default {
  name: "AccordionItem",
  props: {
    title: {
      type: String,
      required: true,
    },
  },
  data() {
    return {
      showtext: false,
      plusIcon: "/Icon.svg", // Chemin vers votre image plus dans le dossier public
      minusIcon: "/Icon.svg", // Chemin vers votre image moins dans le dossier public
    };
  },
  methods: {
    toggle() {
      this.showtext = !this.showtext;
    },
  },
};
</script>

  <style>
.flex-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 5px;
}
.flex-container.border-green {
  border-radius: 5px;
  padding: 15px;
  background: #2ebb77;
}
.btn-no-border {
  background-color: transparent;
  border: none;
  cursor: pointer;
  font-size: 1rem;
}
.btn-no-border:focus {
  outline: none;
}

@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap");
#app {
  font-family: "Plus Jakarta Sans";
}
</style> 