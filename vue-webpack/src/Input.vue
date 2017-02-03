<template>
    <div class="">
        <input type="text" v-model="message">
        <p> {{ message }} </p>
    </div>
</template>

<script type="text/javascript">
    export default {
        data() {
            return {
                message: ''
            }
        }
    }
</script>
