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
    <div class="col">
        <div class="card" style="width: 10rem;">
        <img :src="comicThumb" class="card-img-top" alt="...">
        <div class="card-body">
            <h5 class="card-title"> {{ comicSerie }}</h5>
        </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
 @use "../../node_modules/bootstrap/dist/css/bootstrap.min.css";
</style>