<template>
    <!-- Onde vai ficar o botão de adicionar -->
    <div class="nav navbar">
        <input type="file" @change="onFileSelected">
    </div>

</template>

<script>
    export default {
        name: 'galeria',
        data(){
            return{
                msg: 'Batata'
            }
        }
    },
    methods: {
        onFileSelected(event){
            console.log(event)
            
        }
    }
</script>
