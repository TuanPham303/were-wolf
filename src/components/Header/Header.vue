<template>
  <div v-on:click='click'> 
    WERE WOLF
  </div>  
</template>


<script>
export default {
  name: 'Header',
  props: {
    msg: String
  },
  methods: {
    click: () => {
      console.log('asd')
    }
  }
}
</script>


