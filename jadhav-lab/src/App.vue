<template>
  <div id="app" class="body">
    <nav class="navbar navbar-expand-lg navbar-light bg-light rounded border" style="margin: 1em">
      <a class="navbar-brand">Jadhav Lab</a>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Research</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Publication</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Positions</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">People</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">News</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </nav>

    <div class="container">
      <div class="card">
        <img src="src/images/labgroup.jpg" class="card-img-top">
      </div>

      <div class="card">
        <div class="card-body">
          <h2 class="card-title"> Learning, Memory and Decision Making in the Mammalian Brain </h2>
          <p class="card-text">
            The Jadhav Lab integrates behavior, electrophysiology, optogenetics and computational analysis to investigate the neural basis of learning, memory and decision making in the mammalian brain.
          </p>
          <p class="card-text">
            The brain has a remarkable capacity to learn and to use past experience to guide our daily behavior. 
            Multiple brain regions coordinate activity to form representations of the external world, learn new experiences, store and retrieve memories, and make decisions. 
            We are interested in understanding the neural basis of these cognitive abilities by studying processing at the cellular and network level in neuronal circuits of the rodent brain. 
          </p>
          <p class="card-text">
            The Jadhav Lab integrates behavior, electrophysiology, optogenetics and computational analysis to investigate the neural basis of learning, memory and decision making in the mammalian brain.
          </p>
        </div>
      </div>
    
      <div class="card">
      </div>
    </div>
  </div>
</template>

<script>
import jQuery from 'jquery'
global.jQuery = require('jquery');
var $ = global.jQuery;
window.$ = $;

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Jadhav Lab!'
    }
  }
}
</script>

<style>
  @import url('https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css');
  body{
    background-image: url("/src/images/funky-lines.png");
    -webkit-animation: slide 20s linear infinite;
  }

  @-webkit-keyframes slide {
    from { background-position: 0 400px; }
    to { background-position: 400px 0; }
}
</style>
