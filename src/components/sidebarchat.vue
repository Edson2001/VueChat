<template>
    
   <div class="sidebarChat">
       
    <div class="options">
        <span>Chats</span>
        <span>
            <i class="fas fa-sort-amount-down"></i>
        </span>
    </div>

    <div class="search-options">
        <input type="text">
        <i class="fa fa-search"></i>
    </div>

    <ul class="list-user">
        <li>
            <a href="">
                <img src="https://franklininfo.net/images/icons/man-beard.png" alt="">
                <div class="user-details">
                    <h4 class="user-name">Júnior Andrade</h4>
                    <p>{{message.substring(0, 30)}}...</p>
                </div>
                <div class="list-data">
                    <span>22:50 PM</span>
                </div>
            </a>
        </li>
    </ul>

   </div>

</template>

<script>
import {ref} from "vue"
export default {
    
    setup(){
        const message = ref("Lorem ipsum dolor sit amet, consectetur adipisicing elit.")
        return {message}

    }

}
</script>