<template>
  <div id="app">
    <entrylist :entriesListData="this.fileList" />
  </div>
</template>

<script>
import entrylist from './components/EntryList.vue';

export default {
  name: 'App',
  components: {
    entrylist
  },
  data() {
    return {
      fileList: [
          {id: 1, name: "Anotacoes.txt"}, 
          {id: 2, name: "Arquivo2.txt" }
        ]
    };
  }
}
</script>

<style>
#app {

}
</style>
