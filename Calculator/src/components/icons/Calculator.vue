<template>
  <div class="Calculator_wrapper">
    <div id="Calculator_display"></div>
    <div id="Calculator_body">
      <div class="Calculator_body_inputs">7</div>
      <div class="Calculator_body_inputs">8</div>
      <div class="Calculator_body_inputs">9</div>
      <div class="Calculator_body_inputs">/</div>
      <div class="Calculator_body_inputs">4</div>
      <div class="Calculator_body_inputs">5</div>
      <div class="Calculator_body_inputs">6</div>
      <div class="Calculator_body_inputs">*</div>
      <div class="Calculator_body_inputs">1</div>
      <div class="Calculator_body_inputs">2</div>
      <div class="Calculator_body_inputs">3</div>
      <div class="Calculator_body_inputs">-</div>
      <div class="Calculator_body_inputs">(-)</div>
      <div class="Calculator_body_inputs">0</div>
      <div class="Calculator_body_inputs">,</div>
      <div class="Calculator_body_inputs">+</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Calculator",
  setup() {
    return {}
  }
}
</script>

<style scoped>
#Calculator_body{
  display: grid;
  grid-template: repeat(4,1fr)/repeat(4,1fr);
}
</style>