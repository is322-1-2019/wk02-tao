<template>
<div class="container">




  <h2>Stay focused, be present</h2>
              
  <br /> 
  <br /> 
  <br /> 


  <div class="progress">
    <div class="progress-bar" style="width:90%">90%</div>
  </div>



<br /> 
<br /> 




<br /> 
<br /> 
  <button type="button" class="btn btn-success">Plant</button>



</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}



// Set the date we're counting down to
var countDownDate = new Date("Jan 5, 2021 15:37:25").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();
    
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
    
  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  // Output the result in an element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";
    
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);



</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
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


body  {
  
 background-image: url("https://d2v9y0dukr6mq2.cloudfront.net/video/thumbnail/YqGSkmb/abstract-natural-green-organic-motion-background_s_knbmmm__F0007.png");
}


p {
  text-align: center;
  font-size: 60px;
  margin-top: 0px;
}


</style>
