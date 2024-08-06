

<template>
<div>
    <HelloWord>

        <!-- <template v-slot:name>
            {{user.name }}
        </template>
        
        <template v-slot:age>
            {{user.age }}
        </template>

        <p>{{user.name}}</p> -->

        <div
            class="text.green"
        >
        {{ user.name }}
        </div>
    </HelloWord>



    <!-- <div v-if="user.age < 15"
    >
        
          mon age
    </div> 
    
    <div>
        else
    </div> -->
    <!-- <input type="text" v-model="user.name" v-on:input="display "  >
    <input type="text" v-model="user.age"   > -->
</div>
</template>

<script setup>
import HelloWord from './components/HelloWord.vue';

import {ref} from 'vue';

const user = ref({
    name: 'Ndiaye',
    age: 90,
});


const display = () => {
    // console.log(name, age );
    
}
display()
</script>  

<style scoped>
.text.red{
    color: indianred ;  
} 
.text.green{
    color: green;
}
</style> 

  