<template>
  <div id="foo">
    <div id="bar">HELLO PUSSY</div>
    <div id="bee">HELLO FAGUT</div>
    <div id="tes">HELLO DIRT
      <div id="tes1">this is absolute position</div>
    </div>
    <div id="abs">content is here</div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      text: 'I love you till the end of the world!'
    }
  }
}
</script>

<style>
#foo{
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
  border: solid blue 10px;
  /* box-sizing: border-box; */
}
#bar{
  position: relative;
}
#bee{
  position: fixed;
  top: 0px;
  left: 0px;
  border: solid black 10px;
}
#tes{
  position: relative;
  width: 200px;
  height: 200px;
  border: solid black 10px;
}
#tes > #tes1 {
  position: absolute;
  top: 50px;
  left: 100px;
  border: solid green 10px;
}
#abs{
  position: absolute;
  top: 20%;
  left: 50%;
  border: solid black 10px;
}
</style>
