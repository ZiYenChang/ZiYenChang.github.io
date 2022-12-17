<template>
    <nav class="navbar navbar-expand-lg bg-light py-1">
        <div class="container-fluid mx-5">
            <div>
                <!-- <router-link :to="{ name: 'Home' }" custom v-slot="{ navigate }"> -->
                    <button>
                        <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-house"
                            viewBox="0 0 16 16">
                            <path d="M8.707 1.5a1 1 0 0 0-1.414 0L.646 8.146a.5.5 0 0 0 .708.708L2 8.207V13.5A1.5 1.5 0 0 0 3.5 15h9a1.5 1.5 0 0 0 1.5-1.5V8.207l.646.647a.5.5 0 0 0 .708-.708L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.707 1.5ZM13 7.207V13.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V7.207l5-5 5 5Z" />
                        </svg>
                    </button>
                <!-- </router-link> -->
            </div>
            <span class="navbar-text">
                <svg  xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor"
                            class="bi bi-person-circle" viewBox="0 0 16 16">
                            <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z" />
                            <path fill-rule="evenodd"
                            d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm8-7a7 7 0 0 0-5.468 11.37C3.242 11.226 4.805 10 8 10s4.757 1.225 5.468 2.37A7 7 0 0 0 8 1z" />
                </svg> 
            </span>
        </div>
    </nav>
</template>

<script>
import { defineComponent } from 'vue'

// export default defineComponent({
//     data(){
//       return{
        
//       };
//     },
//     components:{
        
//     },
//     mounted() {
        
//     },
//     methods: {
        
//     }
// })
</script>

<style scoped>
a {
  text-decoration: none; /* no underline */
  padding-right: 1em;
}
</style>