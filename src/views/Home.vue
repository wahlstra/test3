<template>
  <v-container fluid fill-height id="Home" class="grey lighten-2">
    <toolbarMain/>
    <workspace/>

</v-container>

</template>

<script>
  import toolbarMain from '../components/ToolbarMain'
  import workspace from '../components/Workspace'
  export default {
    components: {
      toolbarMain,
      workspace
    }
  }
</script>


<style>
    #Home{

      /*height:100vh;*/
    }
</style>
