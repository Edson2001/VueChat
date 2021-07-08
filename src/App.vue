<template>

  <div class="container">

    <sidebar></sidebar>
    <sidebar-chat ></sidebar-chat>
    <messages></messages>

  </div>

</template>

<script>

import Sidebar from "./components/sidebar.vue"
import SidebarChat from "./components/sidebarchat.vue"
import Messages from "./components/messages.vue"


export default {
  name: 'App',
  components: {Sidebar, SidebarChat, Messages}
}
</script>

<style>

</style>
