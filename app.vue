<template>
  <div class="container">
    <h1>Baby Name Generator</h1>
    <p>Choose your options and click the "Find Names" button bellow</p>
    <div class="options-container">
      <div class="option-container">
        <h4>1) Choose a gender</h4>
        <div class="option-buttons">
          <button>Boy</button>
          <button>Unisex</button>
          <button>Girl</button>
        </div>
      </div>
        <div class="option-container">
        <h4>2) Choose the name's popularity</h4>
        <div class="option-buttons">
          <button>Trendy</button>
          <button>Unique</button>
        </div>
      </div>
         <div class="option-container">
        <h4>3) Choose name's length</h4>
        <div class="option-buttons">
          <button>Long</button>
          <button>All</button>
          <button>Short</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  font-family: Arial,Helvetica,sans-serif;
  color: rgb(27, 60, 138);
  max-width: 50rem;
  margin: 0 auto;
  text-align: center;
}

.container .h1{
  font-size: 3rem;
}
</style>