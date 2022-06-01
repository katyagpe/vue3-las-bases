<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <todo-list/>
    <!--<simple-counter-composition-api/>
    <hr />
    <watch-counter/>
    <hr />
    <reactive-computer/>
    <hr />
    <simple-counter/>
    <hr />
    <hello-world/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/00HelloWorld.vue'
import SimpleCounter from '@/components/01SimpleCounter.vue'
import ReactiveComputer from '@/components/02ReactiveCounter.vue'
import WatchCounter from '@/components/03WatchCounter.vue'
import SimpleCounterCompositionApi from '@/components/04SimpleCounterCompositionApi.vue'
import TodoList from '@/components/05TodoList.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    SimpleCounter,
    ReactiveComputer,
    WatchCounter,
    SimpleCounterCompositionApi,
    TodoList
  }
}
</script>
