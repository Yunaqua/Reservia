<!DOCTYPE html>
<html>
  <head>
   <meta charset="utf-8" />
   <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- mediaquery -->

   <link href="flex.css"  rel="stylesheet" type="text/css"/>
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css"> <!-- Icone de recherche -->
   <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
   <title>Reservia</title> <!-- Icone de recherche fas -->
  </head>

  <body>
    <div class="main">


      <header>
        <div class="container">
          
          <div class="navigations">
            <div class="logo-wrap">
              <img class="reservia" src="images/logo/Reservia@3x.png" alt="Reservia" title="Reservia"/>
            </div>
            <div class="mobile-wrap">
              <a href="#inscription" class="inscription-mobile" title="inscrire">S'inscrire</a>
            </div>
            <div class="divnav">
              <ul id="navigation" class="nav">
                <li><a href="#hebergements" title="Hebergements">Hébergements</a></li>
                <li><a href="#activites" title="Activité">Activité</a></li>
                <li class="inscription-desktop"><a href="#inscription" class="inscription" title="inscrire">S'inscrire</a></li>
              </ul>
            </div>
          </div> <!-- navigations -->
        </div> <!-- container -->

      </header>

      <section>
        <div class="container">
          <div class="info">
            <h2> Trouver votre hébergement pour des vacances de rêve</h2>
            <p>En plein centre ville ou en pleine nature</p>
          </div>
          

          <div>
            <div>
              <form class="search">

                <span><i class="fas fa-map-marker-alt"></i><input type="text" class="searchTerm" placeholder="Marseille, France"><button type="submit" class="searchButton">Rechercher</button></span>

                </form>
              </div>


              <!-- Control buttons -->
              
              <div id="filtre">

                <div>
                  <span>Filtres</span>
                </div>
                <div>
                  <button class="filtrebouton" onclick="filterSelection('economique')"><i class="fas fa-money-bill-wave"></i><strong>Economique</strong></button>
                <button class="filtrebouton" onclick="filterSelection('familial')"><i class="fa fa-child"></i><strong>Familial</strong></button>
                <button class="filtrebouton" onclick="filterSelection('romantique')"><i class="fa fa-heart"></i><strong>Romantique</strong></button>
                <button class="filtrebouton" onclick="filterSelection('animaux')"><i class="fas fa-dog"></i><strong>Animaux autorisés</strong></button>
                </div>
                
              </div> <!-- filtre -->


            </div>

            <p><span class="fa-stack fa">
          <!-- <i class="fa fa-circle fa-stack icon-background"></i> -->
          <i class="fa fa-info fa-stack-1x"></i> 
         </span><em>Plus de 500 logements sont disponibles dans cette ville</em></p>
            

        </div> <!-- container -->
      </section> <!-- section1 -->

      <section id="hebergements">
        <div class="container">
          <div  class="flex-container">
            <div class="hebergement">
              <h2> Hébergements à Marseille</h2>

                <div class="conteneur">


                  <figure class="contour">
                   
                    <div class="picture" style="background:url('images/hebergements/2_large/marcus-loke-WQJvWU_HZFo-unsplash.jpg') no-repeat center"></div> 
                    <figcaption><h2>Auberge la Cannebière</h2></figcaption>

                    <div>
                      <p>Nuit à partir de <strong>25€</strong></p>

                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star"></span>
                    </div>
                    
                  </figure>

                  <figure class="contour">
                    <div class="picture" style="background:url('images/hebergements/2_large/fred-kleber-gTbaxaVLvsg-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h2>Hôtel du port</h2></figcaption>

                    <div>
                      <p>Nuit à partir de <strong>52€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                    </div>

                  </figure>

                  <figure class="contour">
                    <div class="picture" style="background:url('images/hebergements/2_large/reisetopia-B8WIgxA_PFU-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h2>Hôtel Les Mouettes</h2></figcaption>

                    <div>
                      <p>Nuit à partir de <strong>76€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star"></span>
                    </div>

                  </figure>

                  <figure class="contour">
                    <div class="picture" style="background:url('images/hebergements/2_large/annie-spratt-Eg1qcIitAuA-unsplash.jpg') no-repeat center"></div>
                   <figcaption><h2>Auberge de la Mer</h2></figcaption>

                    <div>
                      <p>Nuit à partir de <strong>46€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star"></span>
                      <span class="fa fa-star"></span>
                    </div>

                  </figure>

                  <figure class="contour">
                    <div class="picture" style="background:url('images/hebergements/2_large/nicate-lee-kT-ZyaiwBe0-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h2>Auberge le Panier</h2></figcaption>

                    <div>
                      <p>Nuit à partir de <strong>23€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star"></span>
                    </div>

                  </figure>

                  <figure class="contour">
                    <div class="picture" style="background:url('images/hebergements/2_large/febrian-zakaria-M6S1WvfW68A-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h2>Hôtel chez Amina</h2></figcaption>

                    <div>
                      <p>Nuit à partir de <strong>96€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                    </div>

                  </figure>


                </div><!-- fin des images hebergements -->

             <h2>Affichez plus</h2>

           </div><!-- herbegement -->

            <div class ="populaire">
              <div >
                <div class="poputitre">
                  <h2> Les plus populaires </h2><i class="fa fa-line-chart"></i>
                </div>

                <div class="conteneur">

                  <figure class="popu">
                    <div class="picture" style="background:url('images/hebergements/2_large/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg') no-repeat center"></div>
                   <figcaption>
                      <h2>Hôtel Le soleil du matin</h2>
                      <div class="gna">
                      <p>Nuit à partir de <strong>128€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                    </div>

                    </figcaption>

                    
                  </figure>

                  <figure class="popu">
                    <div class="picture" style="background:url('images/hebergements/2_large/aw-creative-VGs8z60yT2c-unsplash.jpg') no-repeat center"></div>
                   <figcaption>
                      
                      <div>
                      <h2>Au coeur de l'eau Chambres d'hôtes</h2>
                      <p>Nuit à partir de <strong>71€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star"></span>
                    </div>

                    </figcaption>

                    
                  </figure>

                  <figure class="popu">
                    <div class="picture" style="background:url('images/hebergements/2_large/febrian-zakaria-sjvU0THccQA-unsplash.jpg') no-repeat center"></div>
                   <figcaption>
                      
                      <div>
                      <h2>Hôtel Tout bleu et Blanc</h2>
                      <p>Nuit à partir de <strong>68€</strong></p>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star checked"></span>
                      <span class="fa fa-star"></span>
                    </div>

                    </figcaption>

                    


                  </figure>
                  

                </div><!-- fin des images -->
                
              </div> <!-- populaire -->
            </div> <!-- populaire -->

          </div> <!-- flex-container -->
          
        </div> <!-- container -->
        
      </section> <!-- section2 -->

      <section id="activites" >
        <div class="container">
          <div>
              <div class ="activite">
            <h2> Activité à Marseille</h2>
            
            <div>
              <div class="actigrid">
                <div class ="actigrdbloc">
                  <figure class="contouract">
                    <div class="imagactigrd" style="background:url('images/activites/3_medium/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h3>Vieux Port</h3></figcaption>
                  </figure>
                </div>
                <div class ="actigrdbloc">
                  <figure class="contouract">
                    <div class="imagacti2" style="background:url('images/activites/3_medium/paul-hermann-QFTrLdQIRhI-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h3>Fort de Pomègues</h3></figcaption>
                  </figure>
                  <figure class="contouract">
                    <div class="imagacti3" style="background:url('images/activites/3_medium/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h3>Iles du Frioul</h3></figcaption>
                  </figure>
                </div>

                <div class ="actigrdbloc">
                  <figure class="contouract">
                    <div class="imagactigrd" style="background:url('images/activites/3_medium/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h3>Parc National des Calanques</h3></figcaption>
                  </figure>
                </div>
                <div class ="actigrdbloc">
                  <figure class="contouract">
                    <div class="imagacti3" style="background:url('images/activites/3_medium/florian-wehde-xW9e8gdotxI-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h3>Notre-Dame-de-la-Garde</h3></figcaption>
                  </figure>
                  <figure class="contouract">
                    <div class="imagacti2" style="background:url('images/activites/3_medium/lena-paulin-wH2-EJoDcV0-unsplash.jpg') no-repeat center"></div>
                    <figcaption><h3>Parc Longchamp</h3></figcaption>
                  </figure>
                </div>

              </div> <!-- actigrid -->
            </div>
            
            
            
          </div> <!-- activite -->
          </div> <!-- flex-container -->
        
          
        </div> <!-- container -->
        
      </section> <!-- section3 -->

      <footer class ="container">
          <div class="basdepage">
         
            <div >

            <ul class="list">
              <li><h2>A propos</h2></li>
              <li>Fonctionnelent du site</li>
              <li>Conditions générales de vente</li>
              <li>Données et confidentialité</li>
            </ul>

          </div>

        <div>

          <ul class="list">
            <li><h2>Nos herbegerments</h2></li>
            <li>Charte qualité</li>
            <li>Soumettre votre hôtel</li>
          </ul>
        </div>

        <div>

          <ul class="list">
            <li><h2>Assistance</h2></li>
            <li>Centre d'aide</li>
            <li>Nous contacter</li>
          </ul>
        </div>
         

          

        </div> <!-- basdepage -->
        
        
      </footer>  <!-- container -->

    </div> <!-- main -->
    



  </body>
</html>