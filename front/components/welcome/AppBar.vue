<template>
  <v-app-bar
    app
    dark
  >
    <v-toolbar-title>
      {{ appName }}
    </v-toolbar-title>
  </v-app-bar>
</template>

<script>
export default {
  data ({ $config: { appName } }) {
    return {
      appName
    }
  }
}
</script>