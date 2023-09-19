# proyect<html></html><!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
   
</head>
<style>
    #p1 {
      color: red;
      background-color: blue;
    }
    h2{
        color: blueviolet;
        background-color: aqua;
        font-family:  impact;
        border: solid black;  
        padding: 25px;
        margin-bottom: 30px;

    }
    #p1 #p2 h2 h1 {
        text-align: center;
    }
</style>
<body>

    <link rel="stylesheet" type="text/css" href="estilos.css" />
    <script> src="js/programacio.js"</script>
    <section>
        <ul>
    <div>
        <h1 style="font-family: fira sans extra condensed;">CV DEL TRABAJO FINAL</h1> 
<h2>Nombre:Russell </h2>
<h2>Apellido:Harvey</h2>
<img src="https://randomuser.me/api/portraits/men/78.jpg" alt="imagen no encontrada"> <br>
<p1 style="font-family:Times ;"> Estudiante de Administración de Empresas. <br>
    Me considero una persona proactiva, responsable y ordenada. <br>
    Estoy buscando mi primera experiencia laboral. <br></div>
    <br>
    <h3 style="font-family: Impact;">INFORMACION PRECISA</h3>
    
    <div>
     </p1>

     <p2 style="font-family:'Times New Roman'"> 

     <ul>
       <li> Voluntariado <br> </li>
       <li> ONG Verde Bendito <br> </li>
       <li> Participación en colectas para repartir en escuelas de bajos recursos. <br> </li>
       <li> Estudios: 
        Universidad Borcelle <br> </li>
       <li>Carrera de Administracion de Empresas. <br> </li>
       <li> 2021 - actualidad. 
        Escuela secundaria Fauget <br> </li>
       <li> 2017-2021 
        Bachiller con orientación en Economía. <br> </li>
        <li>Inglés avanzado. 
        Español nativo. <br> </li>
        <li>Herramientas de software <br> </li>
        <li>Procesador de texto. <br> </li>
        <li>Hoja de cálculo. <br> </li>
        <li>Presentación de diapositivas. <br> </li>
        <li>Experiencia laboral 
        Casa Colombia 
        2021 
        Vendedor, Atención al cliente. <br></p2></li> </p2></div>
    </ul>
                                                         
<p id="demo" style="display:none">Mi correo electronico es:wade.hicks@ejemplo.com  <br>
                                  Mi dirección es 8172 Preston Rd <br>
                                  Mi número de teléfono es 429 825-6554 <br>
                                  Mi contraseña es mi bebé <br></p>
<button type="button" onclick="document.getElementById('demo').style.display='block'">APARECER INFORMACION</button>

<button type="button" onclick="document.getElementById('demo').style.display='none'">DESAPARECER INFORMACION</button>

<script>
    fetch('https://jsonplaceholder.typicode.com/todos/1')
      .then(response => response.json())
      .then(json => console.log(json)
        )

    const persona = '{"nombre":"Russell", "edad":35, "ciudad":"CABA" , "apellido:" "Harvey" , "pais:" "argentina" , "provincia:""CABA" , "coreo:" "wade.hicks@ejemplo.com"}';
    const obj = JSON.parse(persona);
    console.log(obj);
    document.getElementById("demo").innerHTML =
    "Nombre: " + obj.nombre +
    "|Edad: " + obj.edad +
    "|Ciudad: " + obj.ciudad +
    "|Apellido: " + obj.apellido +
    "|Pais: " + obj.pais +
    "|Provincia: " + obj.provincia +
    "|Coreo: " + obj.coreo;
</script>
</ul>

</section>
</body>

</html>ocv.github
