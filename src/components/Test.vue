<script>
export default {
  data() {
    return {
      rawHtml: '<span style="color: red">red text</span>'
    }
  }
}
</script>

<template>
  <p>Using interpolation: {{ rawHtml }}</p>
  <p>Using directive <div v-html="rawHtml"></div></p>
</template>