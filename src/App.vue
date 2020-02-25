<template>
  <div id="app">
    <!--<DatePicker :value="now" @input="val =>value = val"></DatePicker>-->
    <DatePicker v-model="now"></DatePicker>
  </div>
</template>

<script>
    import DatePicker from './data-picker';
    export default {
    name: 'App',
    components:{
        DatePicker
    },
    data () {
        return {
            now:new Date()
        }
    },
}
</script>

<style>

</style>
