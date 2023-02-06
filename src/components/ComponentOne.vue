<script>
import { store } from '../store.js';

export default {
    name: 'ComponentOne',
    data() {
        return {
            store
        };
    }
}
</script>

<template>
    <div>
        <span>Hai cercato: {{ store.searchText }}</span>
    </div>
</template>

<style scoped>
</style>
