<template>
  <div class="like">
      <button @click="toggleLike">{{ isLiked ? '추가됨'  : '추가'}}</button>
  </div>
</template>

<script>
export default {
    data(){
        return{
            isLiked:false,
        }
    },
    methods:{
        toggleLike() {
            this.isLiked = !this.isLiked;
        }
    }
}

</script>


<style scoped>

</style>
