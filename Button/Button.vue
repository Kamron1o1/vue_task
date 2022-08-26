<template>
    <button :class="styles.btn">
       <slot>

       </slot>
    </button>
</template>


<script>
import styles from "./Button.module.scss"
    export default {
        name: "Button",
        data(){
            return{
                styles
            }
        }
    }
</script>
