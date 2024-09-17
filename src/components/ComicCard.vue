<script>
export default {
  data() {
    return {
      
    }
  },

  props : {
    comicThumb : {
        type: String,
        required: true,
    },
    comicPrice: {
        type: String,
        required: true
    },
    comicSerie: {
        type: String,
        required: true
    },
    comicType: {
        type: String,
        required: true
    }
  }
}
</script>

<template>
    <div id="card">

    </div>
</template>

<style scoped>
</style>