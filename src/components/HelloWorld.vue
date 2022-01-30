<template>
  <div class="hello">
    <h5>Hello Kithinga, you are great</h5>
    <p>This is another way to serve</p>

    <form action="">
      <button class="one">Colours</button>
      <button class="two">Ideaas</button>
      <button class="three">Artkit</button>
      <button class="four">Websites</button>
    </form>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.one{
  border: none;
  height:20rem;
  border-radius:5px;
  background-color:cyan;
  width: 20rem;
  font-size:2.1rem;
  font-weight:500;
  margin:1.2rem;
}
.two{
  border: none;
  height:20rem;
  border-radius:5px;
  background-color:rgb(217, 255, 0);
  width: 20rem;
  font-size:2.1rem;
  font-weight:500;
  margin:1.2rem;
}
.three{
  border: none;
  height:20rem;
  border-radius:5px;
  background-color:rgb(201, 181, 170);
  width: 20rem;
  font-size:1.4rem;
  font-weight:500;
  margin:1.2rem;
}
.four{
  border: none;
  height:20rem;
  border-radius:5px;
  background-color:rgb(227, 238, 238);
  width: 20rem;
  font-size:1.2rem;
  font-weight:520;
  margin:1.2rem;
}
</style>
]