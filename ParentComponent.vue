<template>
  <child-component :myProp="preciousThing"></child-component>
</template>

<script type="module">
import ChildComponent from 'ChildComponent.vue';

export default 
{
  components: {
    ChildComponent
  },

  data() {
    return {
      preciousThing: 'ring'
    }
  }
}
</script>