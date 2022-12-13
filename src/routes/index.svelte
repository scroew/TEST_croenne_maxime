
<body>

    <section class="page">
    <!-- Barre de navigation-->
    <nav>

        <div class="onglets">
          <a href="/page">Mes sociétés</a>
          <a>Les créations</a>
          <a>Me contacter</a>
        </div>

        <div class="buttons">
        <button class="login">J'ai déjà un compte</button>
        <button class="register">S'enregistrer</button>
        </div>

    </nav>
    <!-- Fin de barre de navigation-->

    <!-- Header-->

    <header>
    
    <h1>La nature a toujours été une passion</h1>
    
    </header>
    
    <!-- Fin de la partie Header-->
    </section>

    <footer>

      <h5>Des questions ? Appelez le 0474-989-756</h5>
      <div class="colonnes">

      <div class="colonne">
          <p>Relations clients</p>
          <p>Relations Investissseurs</p>
          <p>Modes de lecture</p>
          <p>Mentions légales</p>
      </div>
      <div class="colonne">
          <p>Centre d'aide</p>
          <p>Les meilleurs protecteurs</p>
          <p>Entreprise mondiale</p>
          <p>Chiffre d'affaire</p>
          <p>Les arbres</p>
      </div>

      <div class="colonne">
          <p>FAQ</p>
          <p>Recrutement</p>
          <p>Conditions d'utilisation</p>
          <p>Nous contacter</p>
      
      </div>
      <div class="colonne">

          <p>Compte</p>
          <p>S'enregistrer</p>
          <p>Se connecter</p>
          <p>Nous contacter</p>
      
      </div>
      
      </div>

 <p>CROENNE Maxime codeur</p>
    </footer>

</body>


<style>
 .container {
 max-width: 600px;
 margin: 50px auto;
 }

 @import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');

body {
    font-family: 'Lato', sans-serif;
    background-color: #141414;
    padding: 0;
    margin: 0;
    color: #fff;
}

body .page{
  margin: 20px 80px;
}
/*Barre de navigation*/

nav{

  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  /*permet de fixer la barre de nav*/
  position: sticky;
  top:0;
  /*permet d'afficher la barre de nav'*/
  background-color: #141414;
  padding: 10px 0px;

}

nav .onglets{
  display: flex;
  flex-wrap: wrap;
  /* afin de décaler et d'aligner */
  margin-top: 5px;
}

nav .onglets a{
  margin-right: 20px;
  cursor: pointer;
  /*Pour ne pas rendre visible les href*/
  text-decoration: none;
  color: #fff;
}

nav .buttons button{
padding: 13px 20px;
color: #fff;
border:none;
font-size: 15px;
cursor:pointer;
outline: none;
}

nav .buttons .login{
background-color: inherit;
margin-right: 10px;
color: #8f8f8f;
}

nav .buttons .register{
  background-color: #f54266;
  margin-right: 10px;
  color: #fff;
  }
  
/*Barre de navigation*/

/*Partie Header*/
header{
    margin-top: 40px;
    background:url('https://officialpsds.com/imageview/rn/62/rn6205_large.png?15213164');
    background-repeat: no-repeat;
    background-position: center;
    background-color: 400px 400px;
}

header h1{
  text-align: center;
  font-size: 60px;
  padding: 150px;
}
/*Fin de Partie Header*/

/*Pied de page*/
footer{
  background-color: #1a1a1a;
  padding: 25px 100px;
  color: #828282
}

footer .colonnes{
 display: flex;
 flex-wrap:wrap;
 justify-content: space-between;

}

@media screen and (max-width: 640px){ body .page{margin: 10px;} nav .onglets{display: none;} header{margin-top: 20px; background-size: 250px 250px;} header h1{font-size: 30px; padding: 100px;}}
/*Fin du pied de page*/

</style>
