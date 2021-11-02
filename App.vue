<template>
  <div id="app">
    <head>
      <title>REPOSITORIO - ROLES</title>
    </head>       
    <div id=header >
        <aside id="asidHead">
        <div>
         <img src="./assets/logo.png" alt="Logo Compensar">
        </div>
            <p >REPOSITORIO DE ROLES<br/></p>
        </aside>    
        <section id="sectHead" >
        <br />	<br> <br>
            <label>"ElUsuario"<br>Usuario Activo</label>	
        </section>
    </div>
    
    <div id="nav">
      <router-link to="/">Inicio</router-link> | 
      <router-link to="/Gestor_Parametros">Parametros</router-link> | 
      <router-link to="/Gestor_Politicas">Politicas</router-link> | 
      <router-link to="/Gestor_Reglas">Reglas</router-link>
      
    </div>
    <div class="contenedor">
      <router-view/>
    </div>

    <footer>   
      <h1> <a href="https://www.colsubsidio.com/">       www.colsubsidio.com</a> </h1>	
    </footer>
  </div>  
  
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

 .imag_size{
    width: 60%;
    text-align: left;
}
.imag_size img{
    width:60%;
}

#header{
    font-size:xx-large;
    display:grid;
        grid-template-columns:1fr 1fr;
        grid-template-rows: auto;
        grid-column-gap:auto;
    font-size: auto;
    margin-bottom: 2%;
}
#asidHead{
    font-size: 5vh;
    text-align: center;
}

#sectHead{
    font-size:85%;
    text-align: rigth;
    margin-top: 2%;  
    font-size: 4vh;  
}


</style>
