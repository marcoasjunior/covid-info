<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>

        <q-toolbar-title>
          COVID INFO
        </q-toolbar-title>

      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script>

export default {
  name: 'MainLayout',

  data () {
    return {
      leftDrawerOpen: false,
      essentialLinks: [
        {
          title: 'Dados Países',
          caption: 'Tabela',
          icon: 'assessment',
          link: '/tableData'
        }
      ]
    }
  }
}
</script>
