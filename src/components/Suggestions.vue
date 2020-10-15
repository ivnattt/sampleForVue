<template>
    <div class="maalkin">
        <p>----------------------</p>
        <h1>Suggestions:</h1>
        <div class="suggestions">
            <p>Sample:</p>
            <p>Synonyms : Happy, Impressed</p>
            <p>Antonyms : Disgusted</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "Suggestions"
}
</script>

<style scoped>

.maalkin{
    border: 3px solid #fff;
    padding:20px;
    text-align: center;
}
.suggestions{
  height: 100vh;
  background: rgb(132, 240, 44);
  font-size: 2rem;
}

body {
  font-family: system-ui, serif;
}
</style>