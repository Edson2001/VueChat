<template>

    <a href="">
        <img :src="imgUser" alt="">
        <div class="user-details">
            <h4 class="user-name">{{nameUser}}</h4>
            <p>{{message.substring(0, 30)}}...</p>
        </div>
        <div class="list-data">
            <span>22:50 PM</span>
        </div>
    </a>
    
</template>

<script >

import {ref} from "vue"
export default {

    props:['imgUser', 'nameUser'],
    setup(){
        const message = ref("Lorem ipsum dolor sit amet, consectetur adipisicing elit.")
        return {message}

    }
}
</script>
