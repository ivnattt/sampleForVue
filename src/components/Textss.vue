<template>
<div class="maalik">
    <div class="wordshere" contenteditable>
        Sample: I am delighted.
    </div>
    <div class="analysis" >
        <p>---scores---</p>
        <p>---Plutchik---</p>
        <p>---VAD---</p>
    </div>


</div>
  
</template>

<script>
export default {
    name:"Textss"
}
</script>

<style scoped>


.maalik{
    border: 3px solid #fff;
    padding:20px;
}

.wordshere {
  height: 100vh;
  background: rgb(29, 130, 143);
  width: 70%;
  color:white;
  font-size: 2rem;
  text-align: center;
  float:left;
}

.analysis{
  height: 100vh;
  background: yellow;
  width:30%;
  text-align: center;
  font-size: 2rem;
  float:right;
}

body {
  font-family: system-ui, serif;
}

</style>