<template>
    <div class="page-success">
        <div class="columns is-multiline">
            <div class="column is-12">
                <h1 class="title">Thank You</h1>

                <p>Your order will be processed in 48 hours</p>
            </div>
        </div>
    </div>
</template>

<script>
import axios from 'axios'

export default {
    name: "Success",
    data(){

    },
    mounted(){
        document.title = "Success || Djackets"
    },
}
</script>