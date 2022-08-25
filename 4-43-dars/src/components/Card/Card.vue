<template>

    <div :class="style.card" v-for="item in items">
        <div class="style card_title">
            {{title}}
        </div>
        <div class="style card_text">
            {{text}}
        </div>
    </div>
</template>


<script>
import style from './card.module.scss'
    export default {
        name: "Card",

        data(){
            return{
                style,
                items:[
                    {
                        title: "dksondojfnrj",
                        text:"iewbdiewbh"
                    },
                    {
                        title: "jknkfejrnkfjnejk",
                        text:"iewbdiewbh"
                    },
                    {
                        title: "remnlkgne",
                        text:"iewbdiewbh"
                    }
                ]
            }
        }
    }
</script>

<style scoped>

</style>