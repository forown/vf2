<template>
    <v-footer padless color="primary" dark :footer="footer">
    <v-col
      class="text-center"
      cols="12"
    >
      &copy; {{ new Date().getFullYear() }} — <strong>{{ footer }}</strong>
    </v-col>
  </v-footer>
</template>
<script>
export default {
  props: ['footer']
}
</script>
