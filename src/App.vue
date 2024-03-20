<script>
export default {
  data(){
    return{
      title:'hello world!',
      text:'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fugiat nam iure tenetur error consectetur accusamus, sit laudantium tempora, reiciendis dicta praesentium cupiditate commodi! Esse eligendi corrupti sunt labore facilis quod. '

    }
  }
  
}
</script>

<template>

  <h2>{{ title }}</h2>
  <div>{{ text }}</div>

</template>

<style scoped >
h2{
  color: cornflowerblue;
  border: 2px dotted rgb(101, 165, 42);
  padding: 20px;

}
div{
  color: cornflowerblue;
}
</style>
