<head>

<script src="https://kit.fontawesome.com/0c87a70838.js"></script>
<link href="//db.onlinewebfonts.com/c/6aa06a9a432b84171f60d8351aa310?family=Torus+Notched"
rel="stylesheet"
type="text/css"/>

<link rel="stylesheet" href="style.css" />
</head>

<body>
  <header>
    <nav>
      <div class="logo">
        <a href="/">Accueil</a>
      </div>
      <div class="onglets">
        <a href="">Les créations</a>
        <a href="">Me contacter</a>
        <a href="">S'enregistrer</a>
      </div>
    </nav>
    <div class="principal">
      <h1> <i class="fas fa-globe-americas"> </i> Ma passion, la programmation</h1>
      <h4>Le Monde de demain demande à ce qu'on le protége. La programmation responsive doit prendre en compte les problèmes d'énergie !</h4>
    </div>
  </header>

  <section class="premieres-presentations">
  <div class="gauche">
    <p>
Mon poéme préféré : "N’entre pas apaisé dans cette bonne nuit,
Les vieux devraient tonner, gronder quand le jour tombe ;
Rage, mais rage encor lorsque meurt la lumière.

Si le sage à la fin sait que l’ombre est la norme,
Comme aucun de ses mots n’a fourché en foudre il
N’entre pas apaisé dans cette bonne nuit.

Le bon, près de la vague ultime, qui déplore
Que sa vie frêle eût pu danser en verte baie,
Il rage, il rage encor lorsque meurt la lumière.

Le fou qui prit, chanta, le soleil en plein vol,
Et conscient, trop tard, d’avoir bridé sa course,
N’entre pas apaisé dans cette bonne nuit.

Le juste, agonisant, qui voit d’un œil aveugle
Qu’un œil aveugle peut briller, gai, météore,
Il crie, il crie encor lorsque meurt la lumière.

Et toi, mon père, là, sur ces tristes hauteurs,
Maudis-moi, bénis-moi de pleurs durs, je le veux !
N’entre pas apaisé dans cette bonne nuit.
Mais rage, rage encor lorsque meurt la lumière.""
    </p>
  <div>

  </section>

   <section class="offres" id="offres">
    <h1>J'aide les développeurs</h1>
    <p>La tarification concernant les cours de programmation est à 60 euros de l'heure</p>
    
    <div class="offres-cartes">
        
      <div class="carte" align="center">
        <h1>Progresser</h1>
      </div>
      <div class="carte" align="center">
        <h1>Apprendre</h1> 
       
      </div>
      <div class="carte" align="center">
        <h1>Pratiquer</h1>
      
      </div>
      
    </div>
    
  </section>
  
   <section class="partenaires" id="partenaires">
     
     <h1><i class="fas fa-hands-helping"></i> Ils me font confiance</h1>
     
     <div class="partenaires-images">
       <p><img src="https://cutt.ly/gzaaBUs" alt=""></p>
       <p><img src="https://cutt.ly/Qzaa0gV" alt=""></p>
       <p><img src="https://cutt.ly/Dzaa3DQ" alt=""></p>
       <p><img src="https://cutt.ly/Bzan3x2" alt=""></p>
     </div>
     
   </section>
  
  <footer>
    <p>&copy; Contactez-nous au 07 77 78 ** **</p>
    <div class="social-media">
      <p><i class="fab fa-facebook-f"></i></p>
      <p><i class="fab fa-twitter"></i></p>
      <p><i class="fab fa-instagram"></i></p>
      <p><i class="fab fa-linkedin-in"></i></p>
    </div>
  </footer>

</body>



<style>
 @import url('https://fonts.googleapis.com/css2?family=Raleway&display=swap');

html{
  scroll-behavior:smooth;
}

body{
  margin: 0;
  padding:0;
  font-family: 'Raleway', sans-serif;
}

header{
  height:80vh;
  background: url('https://static.hitek.fr/img/up_m/1665192418/interstellar.webp');
  background-repeat: no-repeat;
background-position: center;
  color: #900;
  text-align:center;
}

header nav{
  display:flex;
  flex-wrap:wrap;
  justify-content:space-between;
  padding:20px;
  color:#000;
}

header nav a{
  color:#bababa;
  text-decoration:none;
  margin-right:10px;
}


header nav a:hover {
  color:#990;
  border-bottom: #919191 solid 1px;
}

header .principal{
  margin-top: 40px;
  display:flex;
  flex-direction:column;
  justify-content:center;
}

header .principal h4{
  margin-top: -20px;
  padding:20px;
}

.premieres-presentations{
  background-color: #222f3e;
  color:#990;
  padding:30px;
  display:flex;
  flex-wrap:wrap;
}

.premieres-presentations .gauche{
  width: 60%;
  margin-right:10px;
  text-align: center;
}

.offres{
  padding:30px;
  background: url('https://cutt.ly/TzaFkYJ');
  background-position:center;
  color:#fff;
}

.offres h1, .offres p{
  text-align:center;
}

.offres .offres-cartes{
  margin-top: 30px;
  display:flex;
  flex-wrap:wrap;
  align-items:center;
  justify-content:center;
}

.offres .carte{
  background-color:#fff;
  color:#000;
  padding:20px;
  margin-right: 30px;
  margin-bottom: 20px;
}

.offres .carte img{
  height: 60px;
}

.partenaires{
  padding-top: 20px;
  padding-bottom: 30px;
  background-color: #222f3e;
  color:#fff;
}

.partenaires h1{
  text-align:center;
}

.partenaires .partenaires-images{
  margin-top: -30px;
  padding:20px;
  display:flex;
  overflow-x: auto; 
}

.partenaires .partenaires-images p{
  margin-right: 30px;
}

.partenaires .partenaires-images p img{
  height:40px;
}

footer {
  background-color: #18212b;
  padding: 30px;
  color: #fff;
  display: flex;
  flex-wrap:wrap;
  justify-content: space-between;
}

footer .social-media{
  display: flex;
}

footer .social-media p{
  margin-right: 15px;
  border: 1px solid #fff;
  border-radius: 100%;
  padding: 5px;
  text-align:center;
  width: 20px;
  cursor:pointer;
}

@media screen and (max-width: 810px){
  .premieres-presentations .gauche{
    width: 100%;
    margin-right:10px;
  }
}

</style>