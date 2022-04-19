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
        <section>
            <h3>Reminder of what I am talking about</h3>
            <div class="mt-20"></div>
            <OrderedList 
                :items="bigIdeas"
                :highlighted="[1, 2]"
                :stricken="[0]"
            />
        </section>
    </section>
</template>