<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="bg-black text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar class="q-ml-sm" style="width: 200px" size="50px">
            <img src="~assets/logo.png" />
          </q-avatar>
        </q-toolbar-title>
        <q-toolbar-title>
          <q-tabs active-color="warning" no-caps class="absolute-center">
            <q-route-tab exact replace label="Home" to="/" />
          </q-tabs>
        </q-toolbar-title>


      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>


<script>
import { onMounted } from "@vue/runtime-core";
import { useQuasar } from 'quasar';
import { ref } from 'vue';
import AOS from "aos";
export default {
  props: {
    msg: String,
  },
  setup() {
     const $q = useQuasar();
    onMounted(() => {
      AOS.init();
    });
    return {
      toggleDarkMode() {
        $q.dark.toggle();
      },
      first: ref(false),
    };
  },
};
</script>

<style>
body.body--dark {
  background: #333333;
}
</style>
