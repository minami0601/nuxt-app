<template>
  <v-container>
    <event-editor />
    <v-btn>
      Go!!
    </v-btn>
  </v-container>
</template>
<script>
export default {
  name: 'TopPage',
  head () {
    return {
      title: 'New Event'
    }
  }
}
</script>
