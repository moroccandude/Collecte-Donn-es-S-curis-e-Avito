<h1>🏡 Scraping-Avito-Appartements</h1>
<p>Explorez les techniques de web scraping pour collecter des données immobilières à partir des annonces de biens sur Avito.</p>

<h2>🎯 Objectifs du projet</h2>
<p>Le principal objectif de ce projet est éducatif, visant à aider les utilisateurs à se familiariser avec Python et des frameworks populaires comme Pandas et Selenium.</p>

<h2>🛡 Conformité au RGPD</h2>
<p>Ce projet respecte le RGPD (Règlement Général sur la Protection des Données) en utilisant des pratiques de scraping éthiques et en respectant la vie privée des utilisateurs. Aucune information personnelle n'est collectée.</p>

<h2>⚙️ Prérequis et Configuration</h2>
<p>Pour exécuter ce projet, assurez-vous de respecter les exigences techniques suivantes :</p>
<ul>
  <li><b>Python :</b> 3.13.0</li>
  <li><b>Bibliothèques Requises :</b> Selenium, Pandas, Numpy, et Jupyter</li>
</ul>

<h3>📥 Installation</h3>
<p>Installez les packages requis en utilisant la commande suivante :</p>

<pre>
<code>pip install jupyter selenium pandas numpy</code>
</pre>

<h3>🔧 Configuration du Projet</h3>
<ol>
  <li>Clonez le dépôt :</li>
  <pre><code>git clone https://github.com/your-username/Scraping_Avito.git</code></pre>

  <li>Naviguez vers le répertoire du projet :</li>
  <pre><code>cd Scraping_Avito</code></pre>

  <li>Installez les dépendances comme indiqué ci-dessus.</li>
</ol>

<h2>🚨 Gestion des Erreurs et Journalisation</h2>
<p>Le projet inclut une gestion d'erreurs spécifique pour une exécution robuste :</p>
<ul>
  <li><b>TimeoutException :</b> Lancée lorsque <code>WebDriverWait</code> ne peut pas trouver un élément dans le délai spécifié.</li>
  <li><b>NoSuchElementException :</b> Lancée si un élément ne peut pas être localisé, retournant "NON SPÉCIFIÉ."</li>
  <li><b>ElementClickInterceptedException :</b> Lancée si un bouton est intercepté et ne peut pas être cliqué.</li>
</ul>
<p>Ces exceptions garantissent une exécution fluide du programme, avec un traitement approprié pour améliorer la stabilité.</p>

<h2>⚡ Stratégies d'Optimisation</h2>
<p>Deux approches de scraping sont fournies :</p>
<ul>
  <li><b>Simulation de l'Agent Utilisateur :</b> Imite le comportement naturel des utilisateurs pour un scraping discret à un rythme plus lent.</li>
  <li><b>Collecte de Données Rapide :</b> Optimisée pour la rapidité afin de collecter les données rapidement, avec un risque accru de détection.</li>
</ul>

<h2>📚 Ressources</h2>
<p>Pour plus d'informations approfondies, consultez la <a href="https://www.selenium.dev/documentation/">documentation de Selenium</a>.</p>

<h2>📝 Licence</h2>
<p>J'ai contacté le Partenaire RH d'Avito concernant les autorisations mais je n'ai pas encore reçu de réponse.</p>

<h2>🏁 Conclusion</h2>
<p>Ce projet est conforme aux règlements du RGPD et est strictement réservé à un usage éducatif, sans soutien pour des fins malveillantes.</p>
