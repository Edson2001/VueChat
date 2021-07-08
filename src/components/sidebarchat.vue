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
           <list-user nameUser="Ana bela" imgUser="https://cdn.lifehack.org/wp-content/uploads/2014/03/shutterstock_97566446.jpg"></list-user>
        </li>
        <li>
           <list-user nameUser="Jomo Costa" imgUser="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoKJPxxwPeNvISnBbZsZHe887Ws0FnrL7o0w&usqp=CAU"></list-user>
        </li>
        <li>
           <list-user nameUser="Júnior Andrade" imgUser="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQgIUF7SE6CROioPfFm3jxwN5cPMxD_MobRdw&usqp=CAU"></list-user>
        </li>
        <li>
           <list-user nameUser="Carla Andrade" imgUser="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-Co-LuDThF3mYduP4-cXrkQ8IOnfsM6PvqA&usqp=CAU"></list-user>
        </li>
        <li>
           <list-user nameUser="Ana Cristina" imgUser="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbj3G2a5kfFxKDhEcbQhheeXp6gIALkCSKU2xS1J8PPjHgGiJVQDLOtXqTOlGrYne4OcU&usqp=CAU"></list-user>
        </li>
    </ul>

   </div>

</template>

<script>
import ListUser from "./sidebarItens/ListUser.vue"

export default {

    components:{ListUser},
    
   

}
</script>