<template>
	<div>
	  <h1>Hello World</h1>
	  <!-- <p>{{ props.user.name }} {{ props.user.age }}</p> -->

	<slot name="name">
	
	</slot>

	<slot name="age">
	
	 </slot>
	</div>
  </template>
  
  <script setup>


   const props = defineProps(['user']);
  </script>   