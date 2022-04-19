<script setup>
import OrderedList from '../OrderedList.vue';

defineProps({
    'bigIdeas': {
        type: Array,
        required: true
    }
})
</script>

<template>
    <section>
        <section data-auto-animate>
            <h3>What are we trying to do?</h3>
            <h4>Three questions:</h4>
            <div class="mt-20"></div>
            <OrderedList 
                :items="bigIdeas"
            />
        </section>
        <section data-auto-animate>
            <h3>What are we trying to do?</h3>
            <h4>Three questions:</h4>
            <div class="mt-20"></div>
            <OrderedList 
                :items="bigIdeas"
                :highlighted="[0]"
            />
        </section>
    </section>
</template>