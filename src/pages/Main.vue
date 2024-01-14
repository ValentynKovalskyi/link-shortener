<template>
    <div class="flex flex-col justify-center items-center content-center bg-blue h-screen">
        <LinkCreator class="w-1/2 h-1/2 shadow-lg"/>
        <ActiveLinks />
    </div>
</template>
<script setup lang="ts">
import ActiveLinks from '@/components/ActiveLinks.vue';
import LinkCreator from '@/components/LinkCreator.vue';

</script>