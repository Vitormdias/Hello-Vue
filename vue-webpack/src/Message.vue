<template>
    <div>
        <h1>This is a great message!</h1>
        <app-input></app-input>
    </div>
</template>

<script type="text/javascript">
    import Input from './Input.vue';

    export default {
        components: {
            'app-input': Input
        }
    }
</script>
