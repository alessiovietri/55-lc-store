<script>
import { store } from '../store.js';

export default {
    name: 'ComponentTwo',
    data() {
        return {
            store
        };
    }
}
</script>

<template>
    <div>
        <input type="text" v-model="store.searchText">
    </div>
</template>

<style scoped>
</style>
