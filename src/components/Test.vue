<template>
  <div>{{ bar }}</div>
</template>
<script>
export default {
  data() {
    return { bar: "" };
  },
  created() {
    this.foo();
    this.bar = "Turing";
  },
  methods: {
    foo() {
      this.bar = "Welcome to Turing";
    },
  },
};
</script>

const WelcomeTuring = { props: { showMe: { type: Boolean, required: true, "lam a
developer at Turing" }s }s template:

<div v-if="showMe">

| am a developer at Turing.

</div>

. "lam a developer at Turing" and error message occurs in the 7 console } new
Vue({ el: '‘#app', components: { WelcomeTuring, } None of above template: ©

<div>

<WelcomeTuring showMes="" />
</div>
