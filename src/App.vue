<template>
  <div>
    <!-- <user-view>
     </user-view> -->
    <router-view></router-view>
  </div>
</template>

<script>
// import QuestionView from './views/element/QuestionView.vue'
//import ElementView from './views/element/ElementView.vue'
// import UserView from './views/element/UserView.vue'
export default {
  // components: {QuestionView },
  data() {
    return {
      message: "hello vue",
    };
  },
  methods: {},
};
</script>

<style>
h1 {
  color: red;
}
</style>