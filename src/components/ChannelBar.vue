<script setup>
import { ref } from 'vue';
const topics = ref(['tailwind-css', 'react']);
const questions = ref(['jit-compilation', 'purge-files', 'dark-mode']);
const random = ref(['variants', 'plugins']);
const selectTopic = ''
const selectQuestion = ''
const selectRandom = ''

</script>
    
<template>
<div className='channel-bar shadow-lg'>
    <ChannelBlock />
    <div className='channel-container'>
        <!-- <select v-model="selectTopic">
            <option v-for="topic in topics" :value="topic">{{topic}}</option>
        </select>
        <select v-model="selectQuestion">
            <option v-for="q in questions" :value="q">{{q}}</option>
        </select>
        <select v-model="selectRandom">
            <option v-for="r in random" :value="r">{{r}}</option>
        </select> -->
    <!-- <dropfow header='Topics'/>
    <Dropdown header='Questions' />
    <Dropdown header='Random'  /> -->
    </div>
</div>
</template>
    
<style scoped>

</style>
