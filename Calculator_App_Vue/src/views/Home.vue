<template>
  <div class="home">
    <Calculator msg="Welcome to My Calculator App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Calculator from '@/components/Calculator.vue';

export default {
  name: 'Home',
  components: {
    Calculator,
  },
};
</script>
