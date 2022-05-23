<template>
    <div>
        <h3>Formulário</h3>
            <div class="inputs">
                <inputText />
                <inputText />
                <inputButton />
            </div>
    </div>
</template>

<script>
import inputText from './inputs/inputText.vue'
import inputButton from './inputs/inputButton.vue'
export default {

    name: 'Form',
    components: {
        inputButton,
        inputText,
    }

}
</script>

<style scoped>


.inputs {
    display:flex;
    flex-direction: column;
    gap:15px;
}
</style>