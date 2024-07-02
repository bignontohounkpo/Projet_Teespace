<template>
  <div class="flex-container">
    <span :class="{'text-success': showtext, 'fw-bold': true}">{{ myText }}</span>
    <button
      @click="toogle"
      :class="{'text-success': showtext, 'btn-no-border': true}"
    >
      {{ showtext ? "-" : "+" }}
    </button>
  </div>
  <hr :class="{ 'line-success': showtext }">
  <p v-if="showtext" class="text-secondary">
    To make a T-shirt design, you first need to install specific graphic design
    software. Once you’ve done that, start your creation and make sure that your final design is at
    least 220 PPI so it won’t be pixelated when printed… <br />
  </p>
</template>

<script>
export default {
  props: ["myText"],
  data() {
    return {
      showtext: false,
    };
  },
  methods: {
    toogle() {
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
}

.btn-no-border {
  background-color: transparent;
  border: none;
  cursor: pointer;
  font-size: 1rem;
  padding: 0;
}

.btn-no-border:focus {
  outline: none;
}

.text-success {
  color: green;
}

.line-success {
  border-color: green;
}

@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap");

#app {
  font-family: "Plus jakarta Sans";
}
</style>
