<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <title>Practica #6 Lab. Programacion Web</title>
    <link rel="stylesheet" href="estilos.css">
  </head>
  <body>
    <nav class="navbar-expand-lg bg-light">
        <div class="container-fluid">
            <center><b><h1>Laboratorio de Programacion Web</h1></b></center>
          </div>
        <div class="right">
          <div align="right">
            <a href="https://alejandrohg90210.github.io/index.github.io/">
            <input type="button" value="Click INDEX"/>
          </a>
        <h2><p align=left>Practica #6</p></h2>
          </div>
          <h3>¿Que es un canvas?</h3>
          <p>El Canvas es una API de dibujo en dos dimensiones incluida en la especificación HTML5. La inclusión de una API de dibujo nativa permite a los desarrolladores generar imágenes dinámicamente dentro de una página web, por lo general a partir de datos obtenidos desde alguna fuente o a partir de la interacción con el usuario. A diferencia de los formatos conocidos de imágenes como JPG o PNG, los dibujos que se crean con Canvas se pueden modificar en tiempo real.</p>
          <br>
          <h3>Elabora una figura o dibujo complejo de manera dinamica usando el elemento canvas.</h3>
<main class="main-container">
  <canvas id="main-canvas" width="700" height="600"> </canvas>
</main> 
  <script src="js.js"></script>  
<br>
<h4>Instrucciones: </h4>
<ol>
  <li>Haz un dibujo</li>
  <li>Guarda tu dibujo en tu computadora (opcional).</li>
  <li>Refresca la pagina para poder realizar un nuevo dibujo.</li>
</ol>
<br>
<h3>Un dibujo realizado con el comando canvas</h3>
<main class="main-container">
  <canvas id="canvas" width="470" height="250"> </canvas>
</main>
  <script src="javascript.js"></script>
    <h4> Conclusiones </h4>
    <br />
            <b><p>Diego Alberto Oliva Gonzalez </p></b>
            <p>Esta practica me ayudo mucho ya que aprendimos de una mejor manera el uso de canvas, aplicandolos de una manera ilustrativa, y asi poder tener una idea del uso de ellas para en futuros proyectos hacer uso de las canvas</p>
            <b><p>Edrik Alejandro Hernandez Garcia </p></b>
            <p>Esta practica me ayudo mucho para poder comprender lo que conlleva poder agregar un canva a un documento html lo cual nos ayuda bastante y me sirvio de aprendizaje utilizar este nuevo comando el cual nunca habia utilizado para alguna otra practica, por lo que me parecio bastante interesante y de gran utilidad ya sea para realizar alguna figura o dibujo con esta herramienta.</p>
            <b><p>Carlos Alberto Salazar Beltran </p></b>
            <p>Como conclusión sobre esta práctica sobre elaborar una página web, en la cual se elabore una figura o dibujo complejo de manera dinámica. Al igual que nos ayudó para darnos una idea un poco más clara para elaborar una figura sobre las páginas web. La actividad estuvo un poco sencilla para elaborar ya que solo era dibujar una figura de manera dinámica</p>
            <b><p>Jesus Ruben Balleza Rojas </p></b>
            <p>Esta practica me gusto mucho porque te da una infinidad de oportunidades para poder crear formas y dibujos de una manera diferente y super practica. En lo personal, no conocía el elemento de canvas de javascript pero quede muy fascinado con lo que se puede hacer si se aprende bien este elemento.</p>
            <b><p>Diana Nahomi Santos Ortega  </p></b>
            <p>Esta práctica fue muy interesante porque gracias a nuestros conocimientos nos pudimos basar en la realización de ella, permitiendo poner en práctica nuestro aprendizaje para poder llevar a cabo la práctica y es de mucho interés y agrado el participar en este tipo de prácticas porque nos ayuda a seguir aprendiendo pero sobre todo a seguir conociendo formas de como realizar diferentes páginas web, ya sea sencillas o con un poco de grado de dificultad, etc. Esta vez tuvimos que agregar una figura o dibujo de manera dinámica y fue muy llamativo por los diversos colores que se le agregaron.</p>
            <br/>
            <br/>
                <h4>Elaborado por:</h4>
                <table class="default">
                  <div class="container-fluid">
                      <tr>
                        <b>
                        <th><h5>Nombre:</h5></th>
                        <th><h5><center>Hora</center></h5></th>
                      </b>
                      </tr>
                      <tr> 
                        <td>Edrik Alejandro Hernandez Garcia</td>
                        <td><center>M5</center></td>
                      </tr>
                      <tr>
                        <td>Diego Alberto Oliva Gonzalez</td>
                        <td><center>M5</center></td> 
                      </tr>
                      <tr>
                          <td>Diana Nahomi Santos Ortega</td>
                          <td><center>M5</center></td>
                      </tr>
                      <tr>
                        <td>Carlos Alberto Salazar Beltran</td>
                        <td><center>M5</center></td>
                      </tr>
                      <tr>
                        <td>Jesús Rubén Balleza Rojas</td>
                        <td><center>M5</center></td>
                      </tr>
                  </div>
                </table> 
                canvas{
    border:  1px solid rgba(0,0,255,.5);
  }
  body{
    display:  flex;
    justify-content: center;
    align-items: center;
    margin: 0;
  }
  body{
    margin: 3;
    padding: 0;
}

.main-container{
    background-color: none;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

canvas{
    background-color: white;
}
const canvas = document.querySelector('#canvas')
    const ctx = canvas.getContext('2d')
    ctx.fillStyle = '#d30f0e'

    ctx.fillRect(30, 30, 410, 190)
    ctx.strokeStyle = 'rgba(0,0,0,.5)'
    ctx.lineWidth = 5
    ctx.strokeRect(130, 50, 200, 150)


    ctx.strokeStyle = 'black'
    ctx.lineWidth = 3
    ctx.lineTo(200,110)
    ctx.lineTo(220,140)
    ctx.lineTo(180,180)
    ctx.lineTo(255,140)
    ctx.lineTo(240,110)
    ctx.lineTo(290,75)
    ctx.closePath()
    ctx.fillStyle = '#f4c521'
    ctx.fill()
    ctx.stroke()
    
    //Guardar el elemento y el contexto
const mainCanvas = document.getElementById("main-canvas");
const context = mainCanvas.getContext("2d");

let initialX;
let initialY;

const dibujar = (cursorX, cursorY) => {
    context.beginPath();
    context.moveTo(initialX, initialY);
    context.lineWidth = 20;
    context.strokeStyle = "#000";
    context.lineCap = "round";
    context.lineJoin = "round";
    context.lineTo(cursorX, cursorY);
    context.stroke();

    initialX = cursorX;
    initialY = cursorY;
};

const mouseDown = (evt) => {
    initialX = evt.offsetX;
    initialY = evt.offsetY;
    dibujar(initialX, initialY);
    mainCanvas.addEventListener("mousemove", mouseMoving);
};

const mouseClick = (evt) => {
    initialX = evt.offsetX;
    initialY = evt.offsetY;
    dibujar(initialX, initialY);
    mainCanvas.addEventListener("mousemove", mouseMoving);
};

const mouseMoving = (evt) => {
    dibujar(evt.offsetX, evt.offsetY);
};

const mouseUp = () => {
    mainCanvas.removeEventListener("mousemove", mouseMoving);
};


mainCanvas.addEventListener("mousedown", mouseDown);
mainCanvas.addEventListener("mouseup", mouseUp);
              </body>
              
</html>
