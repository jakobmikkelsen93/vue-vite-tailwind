<template>
  <div className="sidebar-icon group"> 
    <font-awesome-icon :icon=icon :size=size />
    <span class="sidebar-tooltip group-hover:scale-100">
     {{text}}
    </span>
</div>
 
</template>

<script>
    export default {
    props: {
        icon: String,
        text: String,
        size: String
    }
    }

</script>