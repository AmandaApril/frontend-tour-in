<template>
  <section class="recipes">
      <article class="recipe">
       <div class="thumbnail" style="background-image: url('https://assets-a1.kompasiana.com/items/album/2019/10/31/computer-by-indiamart-5dba4523d541df2c7334a0a2.png')"></div>
       <h1>Title</h1>
        <p>Some nice preview text</p>
      </article>
      <article class="recipe">
       <div class="thumbnail" style="background-image: url('https://assets-a1.kompasiana.com/items/album/2019/10/31/computer-by-indiamart-5dba4523d541df2c7334a0a2.png')"></div>
       <h1>Title</h1>
        <p>Some nice preview text</p>
      </article>
      <article class="recipe">
        <div class="thumbnail" style="background-image: url('https://assets-a1.kompasiana.com/items/album/2019/10/31/computer-by-indiamart-5dba4523d541df2c7334a0a2.png')"></div>
       <h1>Title</h1>
        <p>Some nice preview text</p>
      </article>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.recipes{
   display: flex;
   flex-flow: row wrap; 
}

.recipe{
    box-sizing: border-box;
    width: 280px;
    padding: 8px;
    border: 1px solid #ccc;
    box-shadow: 0 2px 2px #aaa;
    margin: 10px;
}

.thumbnail{
    background-position: center;
    background-size: cover;
    width: 260px;
    height: 260px;
}
</style>>


