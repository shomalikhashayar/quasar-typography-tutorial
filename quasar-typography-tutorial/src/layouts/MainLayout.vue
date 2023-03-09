<template>
  <q-layout view="hHh lpR fFf">
    <q-header class="bg-deep-purple-10 text-white q-pa-md shadow-2 shadow-10">
      <q-toolbar>
        <q-toolbar-title> Quasar Typography Tutorial </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-deep-purple-10 text-white">
      <q-toolbar>
        <q-toolbar-title class="flex flex-center">
          <div class="text-subtitle2 text-weight-regular">
            Made with ❤️ by Khashayar Shomali
          </div>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script setup></script>
