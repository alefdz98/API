<script>
    import {
    Button, Container, Jumbotron,
    
  } from "sveltestrap";
  </script>
  
  <main>
      
      <h1>SOS2021-02</h1>
      <a href="old_index_static.html"> Ver la información de los componentes del grupo</a>

      
    <Jumbotron>
        <p>API DATOS VINO</p>
        <a href="#/wine-production-stats"
                ><Button color="primary">Datos vino</Button></a
              >
        <a href="https://sos2021-02.herokuapp.com/api/v2/wine-production-stats"
              ><Button color="primary">URL base (Backend)</Button></a
            >
        <a href="https://documenter.getpostman.com/view/14969253/TzJoDfre"
          ><Button color="primary">Documentación de Postman</Button></a
        >
        <a href="https://documenter.getpostman.com/view/14969253/TzRNEpmA"
          ><Button color="primary">Documentación de Postman v2</Button></a
        >
        <a href="#/wine-graph"
        ><Button color="warning">Gráfica</Button></a
      >
        
        <ul>
            <p1>Alejandro Fernández Baena. Fuente: <a href="https://sos2021-02.herokuapp.com/api/v2/wine-production-stats"> wine-production-stats</a></p1>
        </ul>
    </Jumbotron>
    

            <a href="https://github.com/gti-sos/SOS2021-02"> Repositorio del grupo</a>
      
   </main>

   <style>
       p {
            color: rgb(0, 0, 0);
            width: 300px;
            border: 1px solid black;
            
            margin-bottom: 25px;
            margin-left: 43%;
            text-align: center;
          }
      ul {
          margin-top: 25px;
      }
      div{
        text-align: center;
      }
   </style>