# jogo
jogo de carro
<!DOCTYPE html>
<html lang="en" >
<head>

  <meta charset="UTF-8">
  <title>Race game</title>
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover"><link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Muli:400,700,900&amp;display=swap'><link rel="stylesheet" href="./style.css">

</head>
<body>
<!-- partial:index.partial.html -->
<header>0</header>
<div class="difficulty-select">
    <h1>Select Difficulty</h1>
    <button type="button" data-difficulty="0" disabled>Easy</button>
    <button type="button" data-difficulty="1" disabled>Medium</button>
    <button type="button" data-difficulty="2" disabled>Hard</button>
    <button type="button" data-difficulty="3" disabled>Brutal</button>
</div>
<div class="tutorial">
    <p><strong>Steer:</strong></p>
    <p><kbd>A</kbd> <kbd>D</kbd><br>or<br><kbd>&#8592;</kbd> <kbd>&#8594;</kbd><br>or<br>Drag left/right</p>
</div>
<button type="button" class="replay" disabled>
    <svg class="btn-icon" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="96px" height="96px" viewBox="0 0 96 96" enable-background="new 0 0 96 96">
        <path d="M96,88V60c0-1.083-0.396-2.021-1.188-2.812C94.02,56.396,93.083,56,92,56H64c-1.75,0-2.979,0.833-3.688,2.5
c-0.709,1.625-0.418,3.062,0.875,4.312l8.625,8.625C63.645,77.145,56.374,79.999,48,79.999c-4.333,0-8.469-0.844-12.406-2.531
c-3.937-1.687-7.344-3.969-10.219-6.844s-5.156-6.281-6.844-10.219C16.843,56.467,16,52.332,16,47.999
c0-4.334,0.844-8.469,2.531-12.406c1.687-3.937,3.969-7.344,6.844-10.219s6.281-5.156,10.219-6.844
c3.938-1.688,8.073-2.531,12.406-2.531c7.042,0,13.375,2.072,19,6.219c5.625,4.147,9.479,9.595,11.562,16.345
C78.854,39.521,79.479,40,80.438,40h12.438c0.667,0,1.188-0.25,1.562-0.75c0.416-0.541,0.562-1.104,0.438-1.688
c-1.625-7.291-4.698-13.791-9.219-19.5C81.135,12.354,75.594,7.916,69.031,4.75C62.468,1.584,55.458,0,48,0
c-6.5,0-12.708,1.271-18.625,3.812s-11.021,5.959-15.312,10.25s-7.708,9.396-10.25,15.312S0,41.5,0,48s1.271,12.708,3.812,18.625
s5.958,11.021,10.25,15.312s9.396,7.707,15.312,10.25C35.29,94.729,41.5,96,48,96c6.125,0,12.052-1.156,17.781-3.469
c5.729-2.313,10.822-5.573,15.281-9.781l8.125,8.062c1.207,1.291,2.666,1.582,4.375,0.875C95.188,90.979,96,89.75,96,88z"/>
    </svg>
</button>
<!-- partial -->
  <script src='https://cdnjs.cloudflare.com/ajax/libs/three.js/106/three.min.js'></script>
<script src='https://codepen.io/jkantner/pen/RXNvXV.js'></script><script  src="./script.js"></script>

</body>
</html>
