<template>
  <q-footer v-if="$q.screen.lt.sm" elevated class="bg-grey-8 text-white">
  <q-toolbar>
      <q-toolbar-title>
        <q-avatar>
          <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg">
        </q-avatar>
        Title
      </q-toolbar-title>
    </q-toolbar>
  </q-footer>
</template>

<script>
export default {
  name: 'ToolBar'
}
</script>

<style scoped>

</style>
