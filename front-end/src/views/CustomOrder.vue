<template>
  <div class="custom-order">
    <div class="pageHeader">
      <h1 class="center">CUSTOM ORDER</h1>
    </div>
    <div class="center" id="order-content">
        <p>Pricing depends on the item so please give us a call to get a quote!</p>
        <p>MWF 7:30AM–5PM</p>
        <p>(212) 555-0044</p>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
#order-content {
  margin-top: 100px;
  margin-bottom: 100px;
  text-align: left;
}
#recipe-form {
  position: relative;
  align-items: left;
  margin: 0;
  padding: 0;
  width: auto;
  text-align: left;
}
#search-form-content {
  margin-top: 100px;
}
#dietary_options {
  margin-top: 30px;
}
#custom-order-submit-button {
  background-color: #3F5957;
  border: none;
  color: white;
  padding: 10px 15px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
#custom-order-submit-button:hover {
  background-color: #73908F;
}
#query-answer {
  display: block;
  margin-left: 100px;
  margin-right: 100px;
}
.recipe_response {
  display: block;/*grid;
  grid-template-rows: auto auto auto;
  grid-auto-flow: column;*/
  width: 100%;
  margin: 20px;
  margin-top: 50px;
  margin-bottom: 50px;
}
#query-answer h3 {
  height: auto;
}
#query-answer img {
  width: 100px;
  height: 100px;
}
@media screen and (min-width: 400px) {
}

@media screen and (min-width: 900px) {
  #query-answer {
    display: flex;
    margin-left: 150px;
    margin-right: 150px;
  }
  #query-answer img {
    width: 100px;
    height: 100px;
  }
}

</style>