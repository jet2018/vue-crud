<template>
  <div>
    <b-table striped hover :student="students" :fields="fields"></b-table>
  </div>
</template>



<script>
  export default {
    data() {
      return {
        // Note `isActive` is left out and will not appear in the rendered table
        fields: ['first_name', 'last_name', 'sex', 'grade'],
        students: []
      }
    }
    methods:{
    	
    }
  }
</script>