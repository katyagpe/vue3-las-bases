<template>
    <h3>Simple Counter Composition Api</h3>
    <h2>{{ counter }}</h2>
    <h2>{{ counterComputed }}</h2>
    <button @click="increment">Incrementar</button>
    <button @click="decrement">Decrementar</button>
</template>

<script>
import useCounter from '@/composables/useCounter'

export default {
    name: "SimpleCounterCompositionApi",

    setup() {
        const { counter, counterComputed, increment, decrement } = useCounter()
        return { counter, counterComputed, increment, decrement }
    }
}
</script>