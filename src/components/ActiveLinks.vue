<template>
    <div>
        <table>
            <tr v-for="activeLink of activeUserLinks">
                <td>
                    shortLink
                </td>
                <td>
                    actualLink
                </td>
            </tr>
        </table>
    </div>
</template>
<script setup lang="ts">
import { ref } from 'vue';

const activeUserLinks = ref<string[]>(['','','','','','','','','']);
</script>