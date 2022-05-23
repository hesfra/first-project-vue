<template>
    <div>
        <p>Tecnologias que utilizo em FrontEnd:</p>
        <ul>
            <li v-for="(technology, index) in frontTech" v-bind:key="index">
                {{ technology }}
            </li>
        </ul>
        <p>Tecnologias que utilizo em BackEnd:</p>
        <ul>
            <li v-for="technology in BackTech" :key="technology.id">
                {{ technology.Lang }}
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "info",
    data() {
        return {
            frontTech: ["Html", "Css", "JavaScript", "Vue.js"],
            BackTech: [
                { id: 1, Lang: "JavaScript" },
                { id: 2, Lang: "Java" },
                { id: 3, Lang: "Python" },
            ],
        };
    },
};
</script>

<style>
</style>