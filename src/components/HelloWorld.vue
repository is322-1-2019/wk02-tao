<template>
<div class="container">
  <h2>Hover Rows</h2>
  <p>The .table-hover class enables a hover state (grey background on mouse over) on table rows:</p>            
  <table class="table table-hover">
    <thead>
      <tr>
        <th>Firstname</th>
        <th>Lastname</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>John</td>
        <td>Dominica</td>
        <td>john@example.com</td>
      </tr>
      <tr>
        <td>Mary</td>
        <td>Moe</td>
        <td>mary@example.com</td>
      </tr>
      <tr>
        <td>July</td>
        <td>Dooley</td>
        <td>july@example.com</td>
      </tr>
    </tbody>
  </table>



  <h2>Progress Bar With Label</h2>
  <div class="progress">
    <div class="progress-bar" style="width:90%">90%</div>
  </div>

<h2>Animated Progress Bar</h2>
  <p>Add the .progress-bar-animated class to animate the progress bar:</p> 
  <div class="progress">
    <div class="progress-bar progress-bar-striped progress-bar-animated" style="width:40%"></div>
  </div>



<h2>Stretched Link in Card</h2>
  <p>Add the .stretched-link class to a link inside the card, and it will make the whole card clickable (the card will act as a link):</p>
  <div class="card" style="width:400px">
    <img class="card-img-top" src="img_avatar1.png" alt="Card image" style="width:100%">
    <div class="card-body">
      <h4 class="card-title">John Doe</h4>
      <p class="card-text">Some example text some example text. John Doe is an architect and engineer</p>
      <a href="#" class="btn btn-primary stretched-link">See Profile</a>
    </div>
  </div>



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
</style>
