<template>
  <div id="app">
	 <demo>
		<p>知名大学</p>
		<span>清华</span>
		 <span>北大</span>
		 <template v-slot:eat>
			<p>菜系</p>
			<span>川菜</span>
		 </template>
	 </demo>
	  
  </div>
</template>

<script>
import demo from './demo.vue'
export default {
	components:{
		demo,
	},
  methods: {
	
  },

}
</script>

<style>
#app {	
  font-family: Helvetica, sans-serif;
  text-align: center;
}
</style>
