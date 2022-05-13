# EstudioContable
Estudio Contable Luis Morales
class="ellos" style="border: solid 2px #04AA6D 


css



/* Navegacion */

body {
  margin: 0;
  padding: 0;
}
#container-mobile {
  display: none;
}
#container {
  margin: auto;
  width: 960px;
  margin-right: 70px;
}
#nav-container {
  margin: 0;
  margin-right: 40px;
  width: 750px;
  float: right;
  
  height: 100px;
}
ul#navbar {
  margin: 20px;
  margin-left: -50px;
  padding: 0;
  list-style: none;
  display: inline-block;
  vertical-align: bottom;
}
ul#navbar:after{
  content:'';
  display:table;
  clear:both;
}
ul#navbar > li {
  display: inline;
  vertical-align: bottom;
  float: left;
  
}
ul#navbar > li > a {
  padding: 5px;
  display: block;
  text-decoration: none;
  font-size: 25px;
  text-align: center;
  color: black;
  border-right: 1px black solid;
}
ul#navbar > li > a:hover {
  background-color: #6e6e6e33;
}
ul#navbar > li > a > p{
  vertical-align: bottom;
}
#logo{
  display:inline-block;
}
div#nav-container:after {
    content: '';
    height: 100%;
    display: inline-block;
    vertical-align: middle;
}

.container-superior {

  background-color: white;
  
  border: solid 2px rgb(248, 244, 244);
  
  position: sticky;
  
  top: 0%;
  
  }


       /* IMAGEN INDEX */

    header {
        
      height: 150px;
      padding-top: 12px;
      
      background-size: cover;
      background-repeat:repeat;
      background-position: center center;
      

  }

  .estudio {

    background-image: url("/public/estudio/2.jpg");
  }
  

  .contable {
      background-image: url("../ProyectoContable/public/imagencontabilidad.jpg");
      width: 100%;
      height: 300px;
      background-attachment:fixed;
      background-repeat: no-repeat;
      font-weight: bolder;

      padding-top: 25px;
      padding-bottom: 25px;
      text-shadow: 2px 2px 3px #969696;
      text-align: center;
  }

  .imagen-estudio {

    width: 100%;
    
    
  }
  .index{
    background-image: url("public/imagencontabilidad.jpg");
    padding: 100px;
    text-align: center;
    
}

  .letras {
      background-color:#0c0c0c;
      opacity: 0.5;
      margin-left: -150px;
      width: 40%;
      position:static;
      
      }


    .links { 
    
        margin-top: -50px;
        
        font-family: 'Roboto', sans-serif;
        font-size: 50px;
        color: #fffdfd;   
        text-align: end;
        padding-left: 20px;
    }
    




    /* Grid en servicios*/

    .grid-container {
      display: grid;
      grid-template-columns: auto auto auto;
      grid-column-gap: 50px;
      background-color: rgb(192, 189, 189);
      padding: 10px;
    }
    .grid-item-1  {
      
      background-color: rgba(255, 255, 255, 0.8);
      border: 1px solid rgba(0, 0, 0, 0.8);
      padding: 20px;
      font-size: 18px;
      text-align: center;
      
    
    }

    .encabezado {
      
      background-color: rgba(255, 255, 255, 0.8);
      border: 1px solid rgba(0, 0, 0, 0.8);
      padding: 20px;
      font-size: 24px;
      text-align: center;
      color: #44ab95;
    
    }

  


   

    



ul {
    list-style-type: none;
}

ul li {
    
    display: inline-block;
    
    margin: 0 5px;

}

/* Estudio e index*/

.nosotros {
   display: block;
    justify-content: block;
    text-align: center;
    font-family: 'Roboto', sans-serif;
    font-size: 20px;
  
}

.oficina {

margin-top: 75px;
}

.box-model {

    /* Agrego Separacion */

    display: block;
    justify-content: block;
    text-align: left;
    font-family: 'Roboto', sans-serif;
    font-size: medium;
    text-align: center;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    

}


/* el famoso Footer*/

footer {
    color: white; }

.footer-bg {
    
    display: block;
    justify-content: block;
    font-family: 'Roboto', sans-serif;
    font-size: 16px;
    background: #020024;
    background: linear-gradient(90deg, #020024 0%, #093576 21%, #090979 37%, #00d4ff 100%);
    color: white;
    text-align: center;
    text-size-adjust: 2em;
    
  }

.footer-bg p a {
    color: white; }

body {
        font-family: 'Roboto', sans-serif;
        margin: 0px !important;
        padding: 0px; }



  /* Estilo de el Contenido escrito */

.tuki {
    
    display: flex;
    justify-content: center;
    ;
    border: #00d4ff;
    font-size: 36px; 
    padding-bottom: 50px;
    color:#000000;   
    
    font-weight: bolder;
    padding-top: 50px;
    
      
    text-shadow: 2px 2px 3px #969696; 
}

.ellos{
  background-color: #04AA6D;
  border: #04AA6D;
  border-style: solid;
}

/* Aplicando grid a Link interes*/

.grid {
  position: relative;
  display: grid;
  grid-template-areas: "atm anses afip";
  grid-template-columns: 300px 300px 300px;
  grid-template-rows: 100px;
  justify-items: center;
  justify-content: stretch;
  align-items: center; }

.griditem {
  -moz-transform: scale(0.8) rotate(26deg);
  -webkit-transform: scale(0.8) rotate(26deg);
  -o-transform: scale(0.8) rotate(26deg);
  -ms-transform: scale(0.8) rotate(26deg);
  transform: scale(0.8) rotate(26deg); }



  .griditem__titulo {
    font-size: 40px;
  }
  .griditem__imagen{
    width: auto;
  }
  .griditem__boton {
    padding: 10px;
    margin-top: 15px;
    align-items: center;
    border-radius: 4px;
    display: inline-flex;
    flex: 0 0 auto;
    font-weight: 500;
    letter-spacing: .0892857143em;
    justify-content: center;
    outline: 0;
    position: relative;
    text-decoration: none;
    text-indent: .0892857143em;
    text-transform: uppercase;
    transition-duration: .28s;
    transition-property: box-shadow,transform,opacity;
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    vertical-align: middle;
    white-space: nowrap;
    background-color: #1976d2 !important;
    border-color: #1976d2 !important;
    color: white; 
  }


   /* Aplicando grid a Link interes*/

  
.marketing .col-lg-4 {
  margin-bottom: 1.5rem;
  text-align: center;
}
.marketing h2 {
  font-weight: 400;
}

.marketing .col-lg-4 p {
  margin-right: .75rem;
  margin-left: .75rem;
}

  .marketing .col-lg-4 {
  margin-bottom: 1.5rem;
  text-align: center;
  }
  .marketing h2 {
  font-weight: 400;
  }
  .marketing .col-lg-4 p {
  margin-right: .75rem;
  margin-left: .75rem;
  }

  .gx-15 {

    --bs-gutter-x: 15.0rem;;
    margin-left: 0px;
    margin-right: 0px;
    
  }

   /* Contacto-formulario */

body{
  height: 100%; 
  font-family: 'Noto Sans', sans-serif;
  background-color: #faf5f9; 
}


.contact_form{  
  width: 460px; 
  height: auto;
  margin: 80px auto;
  border-radius: 10px;  
  padding-top: 30px;
  padding-bottom: 20px;  
  background-color: #fbfbfb; 
  padding-left: 30px; 
}


input{
  background-color: #fbfbfb; 
  width: 408px; 
  height: 40px; 
  border-radius: 5px;  
  border-style: solid; 
  border-width: 1px; 
  border-color: rgb(22, 212, 149); 
  margin-top: 10px;  
  padding-left: 10px;
  margin-bottom: 20px; 
}


textarea{
  background-color: #fbfbfb; 
  width: 405px; 
  height: 150px; 
  border-radius: 5px;  
  border-style: solid; 
  border-width: 1px; 
  border-color: #44ab95; 
  margin-top: 10px;  
  padding-left: 10px;
  margin-bottom: 20px; 
  padding-top: 15px; 
}


label {
  display: block; 
  float: center;  
}


button{
  height: 45px; 
  padding-left: 5px;
  padding-right: 5px;   
  margin-bottom: 20px; 
  margin-top: 10px;   
  text-transform: uppercase;
  background-color: #44ab95; 
  border-color: #44ab95;  
  border-style: solid; 
  border-radius: 10px;  
  width: 420px;   
  cursor: pointer;
}


button p{
  color: #fff; 
}


span{
  color: #ab4493; 
}


.aviso{
  font-size: 13px;  
  color: #0e0e0e;  
}


h1{
  font-size: 39px;  
  text-align: letf; 
  padding-bottom: 20px; 
  color: #0a080a;
}

.form-title{
    font-size: 16px;
      padding-bottom: 30px;
       color: #0e0e0e;
}
 

::-webkit-input-placeholder {
 color: #a8a8a8;
}


::-webkit-textarea-placeholder {
 color: #a8a8a8;
}


.formulario input:focus{
  outline:0;
  border: 1px solid #97d848;
}


.formulario textarea:focus{
  outline:0;
  border: 1px solid #97d848;
}



/* MEDIA QUERIES */

@media screen and (min-width: 768px) {

  
  
  
  
}

@media screen and (max-width: 768px)  {

  #container {
    display: none;
    margin: auto;
    font-size: 8px;
    

}

.letras {
margin-left: -50px;
  width: 150%;
}


#container-mobile {
  display: block;
}

ul{
  display: none;
}

input:checked  ~ ul{
  display:block;
}



ul#navbar {
  /* margin: 20px; */
  margin-left: 15px;
  /* padding: 0; */
  list-style: none;
  display: inline-block;
  /* font-size: 11px; */
  vertical-align: bottom;
}

ul#navbar > li > a {
  font-size: 13px;
}

 /* servicios */


.grid-container {

    display: grid;
    grid-template-columns: auto;
    grid-row-gap: 20px;
    
    background-color: rgb(192, 189, 189);
    padding: 10px;
 
}

.grid {
  
  position: none;
  grid-template-areas:  "atm"
                        "anses"
                        "afip";
  grid-template-columns: none;
  grid-template-rows: none;
  justify-items: none;
  justify-content: none;
  align-items: none;
  
}

@import "nav";
@import "footer";
@import "media";

// Variables //

$color-primary: #04AA6D; 





    


}