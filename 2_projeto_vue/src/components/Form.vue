<template>
    <h2>Meu formulário:</h2>
    <form action="">
        <div>
            <InputText />
        </div>
        <div>
            <InputText />
        </div> 
        <div>
            <Submit />
        </div>
    </form>
</template>

<script>
    import InputText from './InputText'
    import Submit from './Submit.vue'
    export default{
        name: 'Form',
        components:{
            InputText,
            Submit
        }
    }
</script>