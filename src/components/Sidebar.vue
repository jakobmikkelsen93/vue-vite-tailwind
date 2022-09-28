<script setup>
import { ref } from 'vue'
import SidebarIcon from './SidebarIcon.vue';

const count = ref(0)
</script>

<template>
<div className="fixed top-0 left-0 h-screen w-16 bg-gray-900 text-white shadow-lg flex flex-col">
    <SidebarIcon icon="fa-solid fa-chart-simple" size="lg" text="Dashboard"/>
    <hr className="sidebar-hr" />
    <SidebarIcon icon="fa-solid fa-plus" size="lg" text="Add new employee"/>
    <SidebarIcon icon="fa-solid fa-bolt-lightning" size="lg" text="Giv et rap over fingerne"/>
    <SidebarIcon icon="fa-solid fa-snowflake" size="lg" text="Juleferie"/>
    <hr className="sidebar-hr" />
    <SidebarIcon icon="fa-solid fa-users" size="lg" text="Medarbejdere"/>

</div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
