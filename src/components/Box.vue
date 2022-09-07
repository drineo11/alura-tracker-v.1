<template>
    <div class="box has-text-weight-bold">
        <slot></slot>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'Box',

})
</script>

<style scoped>
.box {
    background: #B4CEB3;
    box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.6);
}
</style>