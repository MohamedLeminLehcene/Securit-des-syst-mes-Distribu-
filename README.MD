<h2>Compte rendu pour sécuritée une application wallet qui est développer par Systéme distribuée en utilisant Keycloak.</h2>
<h3>Partié 1 :  </h3>

<ul>
    <li>1. Télécharger Keycloak 19</li>
<br>
    <img src="./IMGS/img01.png"/>
<hr/>
<li>2. Démarrer Keycloak</li>
<img src="./IMGS/img02.png"/>
<hr/>
<img src="./IMGS/img03.png"/>
<hr/>
<li>3. Créer un compte Admin</li>
<img src="./IMGS/img04.png"/>
<hr/>
<img src="./IMGS/img05.png"/>
<hr/>
<img src="./IMGS/img06.png"/>
<hr/>
<img src="./IMGS/img07.png"/>
<hr/>
<li>4. Créer une Realm</li>
<img src="./IMGS/img08.png"/>
<hr/>
<img src="./IMGS/img09.png"/>
<hr/>
<img src="./IMGS/img10.png"/>
<hr/>
<img src="./IMGS/img11.png"/>
<hr/>

<li>5. Créer un client à sécuriser</li>
<img src="./IMGS/img12.png"/>
<hr/>
<img src="./IMGS/img13.png"/>
<hr/>
<img src="./IMGS/img14.png"/>
<hr/>
<img src="./IMGS/img15.png"/>
<hr/>
<img src="./IMGS/img16.png"/>
<hr/>
<img src="./IMGS/img17.png"/>
<hr/>
<li>6. Créer des utilisateurs</li>


<img src="./IMGS/img18.png"/>
<hr/>
<img src="./IMGS/img19.png"/>
<hr/>
<img src="./IMGS/img20.png"/>
<hr/>
<img src="./IMGS/img22.png"/>
<hr/>
<img src="./IMGS/img24.png"/>
<hr/>
<img src="./IMGS/img25.png"/>
<hr/>
<img src="./IMGS/img26.png"/>
<hr/>
<img src="./IMGS/img27.png"/>
<hr/>
<img src="./IMGS/img29.png"/>
<hr/>
<img src="./IMGS/img36.png"/>
<hr/>
<li>7. Créer des rôles</li>
<img src="./IMGS/img30.png"/>
<hr/>
<img src="./IMGS/img31.png"/>
<hr/>
<img src="./IMGS/img32.png"/>
<hr/>
<img src="./IMGS/img33.png"/>
<hr/>
<img src="./IMGS/img34.png"/>
<hr/>
<li>8. Affecter les rôles aux utilisateurs</li>

<img src="./IMGS/img37.png"/>
<hr/>

<img src="./IMGS/img39.png"/>
<hr/>
<img src="./IMGS/img41.png"/>
<hr/>
<img src="./IMGS/img42.png"/>
<hr/>
<img src="./IMGS/img43.png"/>
<hr/>
<img src="./IMGS/img44.png"/>
<hr/>
<img src="./IMGS/img45.png"/>
<hr/>
<img src="./IMGS/img46.png"/>
<hr/>
<img src="./IMGS/img47.png"/>
<hr/>

<li>8. Affecter les rôles aux utilisateurs</li>
<h5>- Tester l'authentification avec le mot de passe</h5>
<img src="./IMGS/img48.png"/>
<hr/>
<img src="./IMGS/img49.png"/>
<hr/>
<img src="./IMGS/img50.png"/>
<hr/>
<img src="./IMGS/img51.png"/>
<hr/>
<img src="./IMGS/img52.png"/>
<hr/><img src="./IMGS/img49.png"/>
<hr/>
<img src="./IMGS/img53.png"/>
<hr/>
<img src="./IMGS/img54.png"/>
<hr/>
<img src="./IMGS/img55.png"/>
<hr/>
<img src="./IMGS/img56.png"/>
<hr/>
<img src="./IMGS/img57.png"/>
<hr/>

<h5>- Analyser les contenus des deux JWT Access Token et Refresh Token</h5>

<img src="./IMGS/img59.png"/>
<hr/>
<img src="./IMGS/img60.png"/>
<hr/>
<img src="./IMGS/img61.png"/>
<hr/>
<img src="./IMGS/img62.png"/>
<hr/>
<img src="./IMGS/img63.png"/>
<hr/>
<img src="./IMGS/img64.png"/>
<hr/>
<img src="./IMGS/img65.png"/>
<hr/>
<img src="./IMGS/img66.png"/>
<hr/>
<h5>- Tester l'authentification avec le Refresh Token</h5>
<img src="./IMGS/img67.png"/>
<hr/>
<img src="./IMGS/img68.png"/>
<hr/>
<img src="./IMGS/img69.png"/>
<hr/>
<h5>- Tester l'authentification avec Client ID et Client Secret</h5>
<img src="./IMGS/img70.png"/>
<hr/>
<img src="./IMGS/img71.png"/>
<hr/>
<img src="./IMGS/img72.png"/>
<hr/>
<img src="./IMGS/img73.png"/>
<hr/>

<img src="./IMGS/img71.png"/>
<hr/>

<img src="./IMGS/img77.png"/>
<hr/>
<img src="./IMGS/img78.png"/>
<hr/>
<img src="./IMGS/img79.png"/>
<hr/>

<h5>- Changer les paramètres des Tokens Access Token et Refresh Token</h5>

<h3>Partié 2 :  </h3>

<p>Dans cette partie, je souhaite sécuriser une application de portefeuille développée avec une architecture de système distribué utilisant Spring Boot Cloud et Angular. J'ai utilisé Keycloak comme moyen de sécurité dans Spring Boot Sécurité. Ainsi, notre application propose deux types d'utilisateurs : "user" et "admin". Certains itinéraires sont réservés exclusivement aux administrateurs. De plus, si l'utilisateur n'a pas encore effectué d'authentification, le système de sécurité oblige l'utilisateur qui tente de consulter l'application à effectuer une authentification.</p>
<h2> Sécuriser application Wallet avec Keycloak : </h2>

<li></li>
<br>
<img src="./IMG2/img40.png"/>
<li></li>
<img src="./IMG2/img42.png"/>
<br>
<li></li>
<img src="./IMG2/img43.png"/>
<br>
<li></li>
<img src="./IMG2/img29.png"/>
<br>
<li></li>

<img src="./IMG2/img30.png"/>
<br>
<li></li>
<img src="./IMG2/img31.png"/>
<br>
<li></li>
<img src="./IMG2/img32.png"/>
<br>
<li></li>
<img src="./IMG2/img33.png"/>
<br>
<li></li>
<img src="./IMG2/img34.png"/>
<br>
<li></li>
<img src="./IMG2/img35.png"/>
<br>
<li></li>
<img src="./IMG2/img36.png"/>
<br>
<li></li>
<img src="./IMG2/img37.png"/>
<br><br>
<img src="./IMG2/img38.png"/>
<br>
<li></li>
<img src="./IMG2/img39.png"/>
</ul>






