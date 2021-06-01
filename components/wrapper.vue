<template>
  <div  :style="`height:${height};width:${width}`">
      <slot>
      </slot>
  </div>
</template>

<script>
export default {
    props:{
        height:{
            default:"auto"
        },
        width:{
            default:"auto"
        }
    }

}
</script>

<style scoped>

</style>