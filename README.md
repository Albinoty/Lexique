# Lexique définition

Le lexique est écrit à partir de la coding school et mis à jour au fil du temps

## Définition

* **Terminal**: Un terminal est un moyen de communiquer avec la machine sous forme de ligne de commande
	> Exemples d'une commande:
	>	**cd** en ligne de commande, permet de naviguer entre les répertoires

*  **OS** : Un O.S _(operating system ou système d'exploitation)_ est un ensemble de programmes qui communique et dirige tous les composants d'un ordinateur. C'est le programme qui permet de communiquer entre machine et utilisateur via l'interface graphique.
* **Bash** : Le bash est un langage qui interprète des commandes spécifiques via un terminal pour exécuter une action précise.
* **racine** : La racine est la base d'une succession de dossier.
*  **~** : Le titlde est un signe qui à pour but sur le terminal de viser le dossier utilisateur. 
* **.** : Le point dans un chemin signifie le dossier courant.
*  **\.\.** : le double point dans un chemin signifie le dossier parent.
* **permission** : Une permission est un moyen d'attribuer à un fichier ou dossier, un droit d'accès suivant l'utilisateur qui utilise (administrateur, groupe et autres)
	> **Exemple:** d rwx r-x --x
	>  **D** signifie *directory*, **R** pour *read* , **W** pour *write* et **X** pour execute
	>  * Le premier groupe **"rwx"** signifie les droits d'un administrateur
	>  * Le deuxime groupe **"r-x "** signifie les droits de groupe entre "session"
	>  * Le troisième groupe **"r-x"** signifie les droits pour autres utilisateur.
	>
	> **Valeur de droits**
	> 	X -> 1
	> W -> 2
	>  R -> 4
* **chemin absolue** : Un chemin absolue signifie qu'on défini le chemin à partir de la racine.
*  **chemin relatif** : Un chemin relatif signifie qu'on défini le chemin à partir du répertoire qu'on se situe.
*  **HTML** : Le HTML (HyperText Markup Language) est un langage de balise qui permet de faire des sites web. L'extension se défini par **.html** ou **.htm**.
*  **Balise** :  Une balise est un objet en HTML qui permet d'identifier un élément d'un contenu. Il existe 2 types de balises
	> **Balise paire** : C'est une balise qui fonctionne par paire c'est a dire il y'a un début et une fin
	 ```html
		<div>
		
		</div>
	```
	> **Balise orphline**: C'est un balise qui fonctionne en un ligne et qui prend aucun contenu entre.
	```html
		<img src="" alt="" />
	```
	
*  **Attribut** : Un attribut est un élément qu'on rajoute dans une balise qui défini une valeur supplémentaire pour configurer la balise en question.
* **Entité** : Une entité en HTML est une chaîne de caractère qui commence par esperluette "&" et se termine par un point-virgule ";". Il permet d'afficher des caractères spéciaux.
	````html
	&nbsp; permet de faire un espacement
	&copy; permet d'afficher le signe copyright
	````
* **IDE** : Une IDE (integrated development environment, *environnement de développement en français*) est un ensemble de fonctionnalité pour la programmation qui regrouper un éditeur de texte, compilateur, débogueur, ...
* **Indentation** : L'indentation en langage de programmation signifie de restructurer les lignes de codes sous forme d'espaces pour une meilleur lisibilité.
* **Git**: Git est un logiciel qui permet de faire des versions d'un projet et de poster dans un serveur. Il fonctionne sous forme de branche pour plusieurs utilisateur permettant de travailler en parallèle.
* **GitHub** : GitHub est une plateforme qui permet d’héberger ces travaux sous forme de répertoire.
*  **Snipet**: Snipet en langage de programmation est une fonctionnalité qui permet d'afficher un bout de code prédéfini.
* **CSS** : Le CSS Cascading Style Sheets (feuilles de style en cascade) est un langage pour le web qui permet transformer les balises, donner du style **style**.  Il existe 2 familles pour les propriétés:
	> Formatage de texte (celui qui touche le texte).
	> Layout de la boite ().
	* **Sélecteur**: Un sélecteur en css est le noms qui défini la balise.
	* **Propriété**: Une propriété en css est une propriété qu'on défini
	* **Valeur**: Une valeur en css est celui qui va rajouter les données pour les propriétés
	* **Sélecteur**: Un sélecteur en css est celui qui va cibler une balise, une identifiant ou une classe
	* **Référence pour les propriétés** : [https://www.w3schools.com/cssref/](https://www.w3schools.com/cssref/)
	* **Padding** : espacement interieur
	* **Margin** : espacement exterieur
	* **Absolue et relative** Si le parent est relative et l'enfant est absolu, l'enfant va agir seulement sur le parent.
	*  **flexbox**: defini la direction de l'axe principal
		* flex-direction
		* justify-content: aligne les elements selon l'axe principal
		* align-items: Aligne les elements flex selon l'axe transversal
		* flex-wrap: Specifie si les elements flex sont forcés à etre sur une seule ligne ou peuvent etre envelopé sur plusieurs ligne
	* **Pseudo-classe**: Une pseudo-classe est un mot-clé qui peut être ajouté à un sélecteur. Il indique un état spécifique dans l'élement.
		Lien -> [https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-classes](https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-classes)
		````CSS
			selecteur:pseudo{
				propriete: valeur;
			}
		````
	* **Pseudo-élément**: Un pseudo-élément est un mot-clé qui peut être ajouté à un sélecteur. Il permet de mettre en forme certaines parties d'un élement ciblé par la règle
		````CSS
			selecteur::pseudo-element{
				propriete: valeur;
			}
		````
		Lien ->[https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-%C3%A9l%C3%A9ments](https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-%C3%A9l%C3%A9ments)
	* **@media queries**: Media queries est une fonction en CSS3 permetant d'ajuster le contenu d'un page à diférrente taille d'écran(Pc, tablette, smartphone,...).
	Pour les sélecteurs -> [https://www.w3schools.com/cssref/css_selectors.asp](https://www.w3schools.com/cssref/css_selectors.asp)
* **Internet**: Internet est un systeme de connexion entre plusieurs ordinateur relier entre eux qui permet d’accéder a des donnes de toutes sortes(textes, musiques, vidéos, photos,..)
* **Protocole HTTP**: HTTP (HyperText Transfer Protocol) est un protocole de communication entre client et serveur.
* **Côté client**:Le coté client signifie tout ce qui est la vue d'une application.
* **Côté serveur**: Le coté serveur signifie tout ce qui est les requêtes serveur, la gestion des données.
* **Objet connecté** : Un objet connecté est un objet qui est capable d'envoyer ou de recevoir des données via une connexion internet.
* **Package**: Un package est un ensemble de logiciel.
* **Bootstrap**: Bootstrap est une librairie css.
* **SASS** Syntactically Awesome Stylesheet) est un langage dynamique qui génère des feuilles de style en cascade. Il permet de fragmenter son css, créer des variables, importer/exporter les fichiers.
idem q
------

## Git 

### Quelques petites définitions:

**Git**: Git est un logiciel qui permet de poster dans un serveur ces codes avec plusieurs version d'un projet. Il fonctionne sous forme de branche pour plusieurs utilisateur permet de travailler en parallèle. Par plus tard, on peut le faire rejoindre les modification sous forme de sauvegarde ou version.
* **Stage**: Le Stage dans git est un répertoire qui prépare un fichier ou plusieurs fichiers pour être en compression et faire une sauvegarde. Lors du processus du Stage, git va créer un dossier et un fichier caché. Le dossier est essentiel car c'est celui qui va prendre les fichiers et préparer a faire la sauvegarde du projet.
* **Commit**: Le Commit dans git est un processus qui permet de créer une sauvegarde dans tous ce qui trouve dans le stage.

		
	![alt image](https://i.stack.imgur.com/zLTpo.png)
		


### Sous le terminal:

Ligne de commande| Description | Exemple
-----|-----|------
git init| Initialise le dossier courant. C'est le début d'un phase pour sauvegarder les fichiers/dossiers| git init
git add | Permet d'ajouter un **ou** plusieurs fichiers dans le stage | git add *nomFichier* **ou** git add --all *(l'ensemble des fichiers )*
git commit -m| Permet de faire une sauvegarde en local des fichiers du stage et **-m** permet de rajouter le nom de la sauvegarde| git commit -m"*description save*"
git log| Permet d'afficher les sauvegardes effectuer avec le **commit**| git log
git log --oneline | La même chose que le log sauf qu'il montre en une ligne|git log --oneline
git statuts| Affiche les fichiers qui sont dans le stage| git statuts
git rm --cached| Retire le fichier du stage | git rm --cached *nomFichier*
git checkout| Mets à jour la branche avec les modifications | git checkout 'idCommit'
git checkout master | Mets à jour la branche **master** avec les modifications |git checkout master
git checkout -b | Permet de créer une branche et de ci rendre | git checkout -b 'albi'
git merge | Fusionne une branche vers l'autre | "albi -> master" git merge albi
git push | Envoi le répertoire (stage) actuel dans le cloud | git push 
git pull | Télécharge  le répertoire (stage) à partir du cloud | git pull
git clone | Télécharge un répertoire complet en cherchant sur le site Github| git clone *Lien*
git reset --hard | Restaure la version avec le code alpha-numerique| git reset --hard *a9694a1*
**code**| Permet d'ouvrir VS code dans le terminal| code *nomDuDossier* **ou** code *.* (*dossierCourant*)

## Bash

|Ligne de commande|Description|Exemple|
------------|----------|-----
**sudo**| Permet de faire une action en mode administrateur| sudo *commandes*
**echo**| Affiche du texte dans le terminal| echo *texte*
**cd**| Permet de naviguer entre les répertoires| cd *repertoire1/*
**ls**| Permet d'afficher la liste des fichiers et/ou répertoire dans le **dossier courant**| ls **ou** ls ./
**mkdir** | Créer un dossier | mkdir *nomDuDossier/*
**rmdir** | Permet de supprimer un répertoire | rmdir *repertoire_a_supprimer/*
**rm** | Permet de supprimer un fichier | rm *nom_fichier*
**rm -rf** | Permet de supprimer un dossier qui n'est pas vide | rm -rf *dossier/*
**nano** | Ouvre un éditeur de texte sous terminal | nano *nomDuFichier*
**cat**| Permet d'afficher le contenu d'un fichier | cat *fichier.ext*
**cp** | Permet de copier un ou plusieurs fichiers ou dossiers | cp */répertoire_source/nom_fichier_à_copier /répertoire_destination/nom_fichier*
**chmod** | Permet d'attribuer les droits d'accès d'un fichier pour chaque utilisateur| chmod *valeurDroit* *Fichier* **ou** *Dossier/*  
**pwd**| Affihce le chemin absolue du répertoire actuel | pwd 
**touch** | Permet de créer un fichier | touch *nomFichier*
**mv**| Changer de nom **OU** Permet de déplacer un fichier | mv *nomA* *nomB* **//** *repertoire_A/fichier* *repertoire_B*
**clear** | Permet de replacer la ligne de commande en haut de la fenêtre | clear
**man** | Accède au manuel de la commande en question | man *nomCommande*
**tree**| Affiche l'arborescence du dossier en question (*commande à installer*)| tree *nomDossier/*
------

## Javascript

### Quelques petites définitions:

Javascript est un langage de programmation orienté objet qui permet de rentre dynamique un site web. Il est programmé sous formes de scripts. Les scripts sont introduit en fin de page pour d'abord charger la page html, ensuite les scripts pour optimiser le chargement.

Il est aussi un langage de type ( String, Int, Float, ...).

* **Variable** : Une variable en programmation est un nom qui représente sur la mémoire centrale qui lui donne un nom et stocke l'information. Il existe plusieurs type de variable
	> **let** et **var** : une valeur qui évolue dans le temps
	> **const** : une valeur qui sera définitif
	> ````Javascript
	> var maVariable = maValeur; ou let maVariable = maValeur;
	> const maVaribleFixe;
	>````
	> Pour les noms de variables : [https://mathiasbynens.be/notes/javascript-identifiers](https://mathiasbynens.be/notes/javascript-identifiers)
* **Conditions** : Une condition en programmation est une fonction qui permet de faire des calculs ou action en fonction d'une valeur vrai **true**  ou faux **false**.
	>````Javascript
	>if(maVariable == true){
	>		Code à exécuter si true
	>}
	>else{
	>		Code à exécuter si false
	>}
	>````
* **Boucles**: Une boucle en programmation est un processus de boucle qui tourne en fonction de condition. Il existe plusieurs type de boucles:
	> while**: La boucle while est utilisé si on ne sait pas combien de fois on doit faire tourner
	>````Javascript
	>while(boolean){
	>		code à exécuter si true
	>		pour sortir de la boucle la variable doit être modifier
	>}
	>````
	>
	>**for**: la boucle for est utilisé si on a un tour défini, connu.
	>````Javascript
	>	- (let i=a): La premire partie permet d'initialiser le compteur de boucle.
	>	- (i<nbToursVoulu): La deuxième partie permet définir la condition de boucle.
	>	- (i++): La troisime partie permet d'incrémenter, c'est a dire de faire +1.
	>for(let i=a;i<nbToursVoulu;i++){
	>		Code à exécuter si true
	>}
	>````
	> **foreach**: la boucle foreach agit comme le for mais qui est plutôt utilisé pour chaque élément d'un tableau.
	>````Javascript
	>array.forEach(e =>{
	> 	Code à excuter;
	>}); 
	>````
* **Switch**: Un switch est une instruction qui prend une variable et va vérifier si il y'a une correspondance avec **case**. S'il existe, alors la parti case avec la variable correspondant va exécuter le code qui contient.

	> ````Javascript
	>	switch(maVariable){
	>		case (number ou String):
	>			//Code à executer;
	>			break;
	>		.
	>		.
	>		.
	>		.
	> 		default:     //Si aucune variable correspond, la case default va s’exécuter.
	>			Code à executer;
	>			break;
	>	}
* **Tableau**: Un tableau (array) permet de stocker les donnees dans un tableau.
	>````Javascript
	>		//Declare une variable avec un tableau
	>		let tab = [];
	>		//Pour stocker des donnees
	>		let tab = [1,2,3];
	>			//ou
	>		let tab = ["test","yolo","lol"];
	>
	>````
	
* **Fonction**: Une fonction (function) 	est un morceau de code qu'on pourra utiliser plusieurs fois en appellant par son nom.
	>````Javascript
	>		function nomDeMaFonction(VariableEnParametre){
	>			//Code à executer;
	>		}
	>````
	> Il existe aussi les fonction fléché
	>````Javascript
	> ([param],[param]) => {
	>		//Code à executer;
	>}
	>````

----
## Orienté Objet

### Quelques petites définitions:

**Définition:** Un objet est un élément qui peut regrouper plusieur information et/ou de methode. Un objet regroupe des propriétés.

* **Propriétés**: Un objet regroupe des propriétés:
	````Javascript
	let personne = {
		nom:zak, 
		prenom:zak, 
		age:27
	};
  ````

* **New**:  On peut créer un objet avec ces propriétés, on **instancie** un objet:
	````Javascript
	let noty = new Personne('albi','noty',21);
	````
* **Modifier un Objet**:  On peut modifer un objet en appelant la variable qui la stock suivant de la propriétes voulu:	construct
	````Javascript
	noty.prenom = "Albi";
	````
* **Classe**: Une classe en orienté objet est un ensemble de propriétes, de methode communs a l'objet. 
	````Javascript
	class Personne{
		constructor(nom, prenom){
			this.nom = nom;
			this.prebom = prenom;
		}
	}
	````

* **this**: Le mot clé this représente l'objet pour lequel on désire accéder a une propriété ou un méthode:
	````Javascript
	afficherNom(){
		return this.nom;
	}
	````

* **Méthode** : Une méthode est une "fonction" mais qui appartient uniquement à un objet. Elle se porte juste a l'appel de l'objet.
	````Javascript
	bonjour(){
		return "Bonjour";
	}
	````
	- On peut les appeler dans un fichier sous forme:
	````Javascript
	albi.bonjour();
	````
* **Héritage** : L'héritage en orienté objet est la définition d'une classe qui s'étend ces caractéristique d'une classe vers une autre. Par exemple, on a créer une classe Personne(nom, prénom,..) et par après on crée une classe Coach, Eleve, qui s’étend de la Personne
	````Javascript
		class Personne{
			constructor(nom, prenom){
				this.nom = nom;
				this.prenom = prenom;
			}
		}
	````
	- Extends
	- Le **super** permet de recupéré les proriétés de l'objet 
	````Javascript
		// Classe Coach qui s'etends Personne
		class Coach extends Personne{
			constructor(nom, prenom){
				super(nom, prenom);
			}
		}
		// Classe Eleve qui s'etend Personne
		class Eleve extends Personne{
			constructor(nom, prenom){
				super(nom, prenom);
			}
		}
	````

	![alt image](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Heritage_informatique.svg/1024px-Heritage_informatique.svg.png)


* **Import/Export**: L'import et l'export de fichier en js permet de d'importer les fichies qu'on a besoin et exporter les fichiers vers un autre. Dans le HTML, il faudra pas oublier d'écrire type module dans la balise script.
	- HTML:
	````HTML
		<script src="./assets/js.main.js" type="module"></script>
	````
	- Javascript:
	````Javascript
		export default class Player{
		}
		
		import Player from './Player.js';
	````

- Annexe: le fichier main.js/app.js est le nom de base qu'on défini pour le fichier principal de js.

## DOM
### Quelques petites définitions:

* **Définition** : Le DOM ( *Document Object model* ) est une représentation d'un model en objet. Les balises html ou texte sont représenter par des nœuds. Il existe 2 types de nœuds:
	- **Node Element** (un nœud de type élément): Celui qui représente les balises
	- **Node Text** (un nœud de type texte): Celui représente le contenu texte. Il est **enfant** et ne **peut pas avoir d'enfant**
	![alt image](https://www.w3schools.com/js/pic_htmltree.gif)

* **Type Node**: il est possible de verifier quel type est l'élément qu'on veut cibler
	````JavaScript
		let ele = document.getElementById('#ele').nodetype;
		console.log(ele);
	````
	Il renvoi un nombre entre 1 et 12 suivant quel type d'élément.
	 [Pour connaitre le type node du nombre.](https://www.w3schools.com/jsref/prop_node_nodetype.asp)

* **childNodes**: le childNodes permet de récupérer les enfants d'un élément sous forme de tableau
	 ````HTML
	 <body>
		 <div id="div1"></div>
 		 <div id="div2"></div>		 
 		 <div id="div3"></div>
	 </body>
	````
	Javascript:
	````JavaScript
	let ele = document.body.childNodes;
	//Ele contient maintenant un tableau avec 3 element
	// car dans le body il y a 3 enfants 
	// qui sont des <div>
	````
	
* **parentNode**: le parentNode permet de récupérer le parent d'un élément.
	````HTML
	 <body>
		 <div id="div1"></div>
 		 <div id="div2"></div>		 
 		 <div id="div3"></div>
	 </body>
	````
	Javascript:
	````JavaScript
	let ele = document.getElementById(#div1).parentNode;
	//Renvoi l'element parent qui le body
	//Renvoi <body>...</body>
	````
	
* **getElementById**: Le getElementById permet de récupérer un élément grâce à son id. 
	/!\ **Attention l'affectation de l'id, un element peut avoir un ET un seul id.** /!\
	````HTML
	<body>
		<div id="div1"></div>
		<div id="div2"></div>		 
		<div id="div3"></div>
	 </body>
	````
	Javascript:
	````Javascript
	//Je veux recuperer le div avec id div1
	let ele = document.getElementById('div1');
	//Recupere l'element
	//Resultat : <div id="div1"></div>
	````
	
* **getElementsByClassName**: Le getElementsByClassName permet de récupérer un tableau dont les éléments avec la class voulu. 
	````HTML
	<body>
		<div class="maDiv">a</div>
		<div class="maDiv">b</div>		 
		<div class="maDiv">c</div>
	 </body>
	````
	Javascript:
	````Javascript
	//Je veux recuperer les div avec la classe div
	let ele = document.getElementsByClassName('div');
	//Pour cibler le premier element du tableau
	console.log(ele[0]);
	//Recupere l'element du tableau en index 0
	//Resultat : <div class="maDiv">a</div>
	console.log(ele[2]);
	//Recupere l'element du tableau en index 2
	//Resultat : <div class="maDiv">c</div>
	````
	
* **getElementsByTagName**:Le getElementsByTagName permet de récpérer un tableau dont les éléments sont la balise voulu
	````HTML
	<body>
		<div class="maDiv">a</div>
		<div class="maDiv">b</div>		 
		<div class="maDiv">c</div>
	</body>
	````
	Javascript:
	````Javascript
	//Je veux recuperer les div
	let ele = document.getElementsByTagName('div');
	//Pour cibler le premier element du tableau
	console.log(ele[0]);
	//Recupere l'element du tableau en index 0
	//Resultat : <div class="maDiv">a</div>
	console.log(ele[2]);
	//Recupere l'element du tableau en index 2
	//Resultat : <div class="maDiv">c</div>
	````
	
* **querySelector**: Le querySelector agit comme le getElement mais il a sa particularité. En paramètre, il agit comme le css c-à-d qu'il faut indiquer le sélecteur (div, #monId, .maClasse).
	````HTML
	<body>
		<div>a</div>
		<div id="maDiv">b</div>	 
		<div class="maDiv">c</div>
	</body>
	````
	Javascript:
	````Javascript
	let ele = document.querySelector('div');
	let ele1 = document.querySelector('#maDiv');
	let ele2 = document.querySelector('.maDiv');
	
	console.log(ele);
	//Recupere l'element dont balise div
	//Resultat : <div>a</div>
	console.log(ele1);
	//Recupere l'element dont l'id est #maDiv
	//Resultat : <div id="maDiv">c</div
	console.log(ele2);
	//Recupere l'element dont la class est .maDiv
	//Resultat : <div class="maDiv">c</div
	````

* **querySelectorAll**: Le querySelectorAll agit comme getElement mais il a sa particularité. En parametre, il agit comme le css c-à-d qu'il faut indiquer le sélecteur (div, .maClasse). Mais, il renvoi un tableau avec les elements qui correspond.
	````HTML
	<body>
		<div>a</div>
		<div id="maDiv">b</div>	 
		<p class="monP">Aurvoir</p>
		<p class="monP">Merci</p>
	</body>
	````
	Javascript:
	````Javascript
	let ele = document.querySelectorAll('div');
	let eleP = document.querySelectorAll('.monP');
	
	console.log(ele);
	//Recupere le tableau dont les element sont 
	//les balise div
	//Resultat : NodeList(2)
	console.log(eleP);
	//Recupere le tableau dont les elements sont
	//class .maDiv
	//Resultat : NodeList(2)
	//Verifier dans la console
	````

* **innerHTML**: Le innerHTML permet de renvoyer du contenu html à un élément (c'est a dire qu'on peut modifier son contenu).
	````HTML
	<h1 id="test">Hello World</h1>
	````
	Javascript:
	````JavaScript
	let ele = document.getElementById('test');
	
	ele.innerHTML = "Salut Mec";
	````
	Résultat en HTML:
	````HTML
	<h1 id="test">Salut Mec</h1>
	````

* **getAttribute()**: il permet de récupérer l'attribut d'une balise HTML.
HTML
	 ````HTML
	<h1 id="test" class="titre">Hello World</h1>
	````
	Javascript:
	````Javascript
	let ele = document.getElementById('test');
	let attribut = ele.getAttribute('class');
	//ou
	document.getElementById('test').getAttribute('class')
	
	console.log(attribut);
	//renvoi titre
	````

* **classList**: Il permet de renvoyer un tableau avec toutes les class d'une balise. Mais aussi on pourra ajouter, supprimer, remplacer ou modifier. [Source](https://developer.mozilla.org/fr/docs/Web/API/Element/classList)
*  **createElement()**: Il permet de créer un élément html en spécifiant sa balise.
	````Javascript
	let el = document.createElement('div');
	//Pour le mettre dans le html, il faudra utiliser appendchild.
	````
* **createTextNode()**: Il permet de creer un texte qu'on pourra le push dans l'html.
	````Javascript
	let el = document.createTextNode('Something to write here...');
	````
* **appendChild():** Il permt d'ajouter un element à l'enfant d'un balise.
	````Javascript
	let a = document.createElement('div');
	let body = document.querySelector('body');
	
	body.appendChild(a);
	````

* **.remove()**: Il permet de supprier un element dans l'html.
	````Javascript
	let a = document.getElementById('test');

	a.remove();
	````	
	
* **removeChild()**: Il permet de permet d'effacer un enfant d'un element.
	````Javascript
	let body = document.getElementByTag('Body')
	body.removeChild();
	````
* **.style**: Il permet de donner du style a un élement.
	 ````Javascript
	 let el = document.querySelector('#test');
	 el.style.marginTop = "5px";
	 ````


* **Evenement**: Un événement en dom est un moment qu'on peut détecter suivant les actions de l'utilisateur. On peut parler d'écouteur. Il s'applique sur élément. Pour déclencher un événement, il faudra cibler l'élément en question et qu'il doit l'écouter avec **addEventListener**.

	- Le premier parametre va servir à dire qu'elle type d'événement il doit écouter.
	- Le second paremetre est l'éxecution d'une fonction
	
	````JavaScript
		bouton.addEvenetListener('event','function');
	````
	Exemple sur un click:
	````JavaScript
		let bouton = document.getElementById('bouton');
		//Ici nous allons agir lorsque le bouton est cliquer
		//Execute la fonction qui fait un console.log
		bouton.addEventListener('click', () => {
			console.log("Bonjour");
		});
	````


	Exemple pour input :
	````JavaScript
		input.addEventListener('input', () => {
			console.log('md');
		});
	````
	Dans un event, il est possible de récuperer ce qu'une personne introduit dans un input.
	````JavaScript
	input.addEventListener('input', (e) =>{
		//Affiche l'objet de l'event
		console.log(e)
	}
	````

	Pour voir les autres types d'event: [https://developer.mozilla.org/fr/docs/Web/Events](https://developer.mozilla.org/fr/docs/Web/Events)


### Liste de méthode

|Nom|Effet|
|-----|-----|
|push()|Insère un élément à la dernière position du tableau|
|pop()|Supprime un élément à la dernière position du tableau|

-----
## React

### Quelques petites définitions

* **Définition**: React est une libraire Js créer par les developpeurs de 
Facebook. Il permet de faciliter la construction d'une ou plusieurs interface(s) pour utilisateur (UI) sous forme de composant.
Le react est utilisé car le DOM en javascript est difficile de prévoir dans quel état il sera à l'instant T et certes rapide mais lent pour les interactions. Il est basé aussi sur l'ES6-7 (ECMA Script).

* **Virtual DOM**: Le virtual DOM est sous forme d'objet Js. Il est plus rapide à manipuler. Mais, il permet de garder une memoire du DOM précédent.

* **Spread operator**: Le spread operator est un opérateur qui permet de parcourir une variable sous forme de boucle. Il est utiliser sous forme de ... 

	````Javascript
	let a = [1,2,3];
	let b = [4,5,6];
	let c = [...a, ...b]
	````

* **Mutation et Réassignation**: Les deux mots signifie une modification d'une variable ou d'un objet. Mais, ils sont très différent.
	 * **Mutation**: La mutation signifie qu'on ajoute une valeur directement dans la variable.

		````Javascript
		let a = [1,2,3];

		let b = a;

		a.push(4);

		a === b // true
		````
	* **Réassignation**: La reassignation signifie qu'on va redéfinir la variable en ajoutant la modification.
		````JavaScript
		let a = [1,2,3];

		let b = a;

		a = [...,4];

		a === b;
		````
 * **map()**: La méthode map va permettre de parcourir un tableau et lancer une fonction qui va permettre d'executer quelque chose

	````JavaScript
	let a = [1,2,3];
	
	a.map(num => num*2);
	
	console.log(a) // renvoi [2,4,6]
	````

* **filter()**:
	````JavaScript
	let a = [1,2,3,4];

	a = a.filter(num => num % 2 === 0);

	console.log(a) //Renvoi [2,4]
	````	



dossier public:
￼
npx create-react-app : permet de creer l'application avec tous les composants s

/*pwa*/

pour creer un fichier voir vscode

render() : toujours avec un return
JSX: on peut envoyer dans le render une balise


props: permet de passer des donnees via les balises de l'importation

pour faire passer un objet on utilise {{}}

state: cest la ou les donnes vont etre stocker 
on peut inserer un objet dans le state. permet avoir les donnees dans une page
      



cycle de vie d'un composant

setState: permet de redefinir la state


[https://reactjs.org/docs/events.html#supported-events](https://reactjs.org/docs/events.html#supported-events)

handling events: ressemble addEveentListener
bind pour assigner 
ex:
	
button onClick(this.handleChangeTitle.bind(this))



conditional rendering: L'affichage conditionel ( Conditional Rendering ) permet de mettre des conditions pour afficher un contenu voulu. On peut passer des props des conditions et ensuite verifier en condition:
	- condition javascript(if else ...)
	- condition && ( {condition && le bloc jsx})
	- condition ternaire.

condition ternaire: une methode de rendu conditionnel

(condition ? vrai : faux)

Cache React: https://www.robinwieruch.de/local-storage-react




-----
## Raccourci clavier

### Sur VS Code
| Description | Touche clavier |
|-----|---|
Ouvrir la commande palette | CTRL + SHIFT + P
Replace le code dans la limite de la fenêtre | ALT + Z
Dupliquer la ligne de code vers le bas | SHIFT + ALT + flche de bas
Afficher la prévisualition d'un ficher markdown sur Vs code | CTRL + K + V	

----

### Sous Linux
| Description | Touche Clavier
|--------|------|
Ouvrir le terminal|CTRL + ALT + T
Dans le terminal, permet de compléter rapidement| Tab 
Dans le terminal, permet de voir les commandes introduites précédemment | Flche de Haut
Rechercher dans le code | CTRL + F
Permet d'aller sur le fichier | CTRL + P

## SASS

### Importation

* Importation: L' importation permet en sass de diviser le code css en plusieurs morceau. Pour eviter que le fichier soit compiler, il faut indiquer avec un underscore devant le nom.
	ex: _nomFichier.scss

	````SCSS
	@import:'./footer';
	@import:'./header';
	````

* variable: On peut déclarer une variable, stocké une propriété et l'appel dans le sass.
	````SCSS Puis selectionner NonAjout
	$ variable : 10 px;
	//Exemple d'appel variable
	font-size:$variable;
	````

* _variables.scsss: c'est la qui sera stocké les variables. Il faudra indiquer le fichier qui stocke les variables.

	````SCSS
		@import './variables';
		@import './footer';
		@import './header';
	```` 


## PHP

### Installer PHP et MySQL
**Source**: [https://websiteforstudents.com/install-phpmyadmin-apache2-and-mysql-on-ubuntu-18-04-lts-beta-server/](https://websiteforstudents.com/install-phpmyadmin-apache2-and-mysql-on-ubuntu-18-04-lts-beta-server/)
* 1) Installer MySQL
	- sudo apt install mysql-server mysql-client
* 2) Installer Apache2 HHTP Server
	- sudo apt install apache2
* 3) Installer PHP et tous ces modules
	- sudo apt-get install php php-cgi libapache2-mod-php php-common php-pear php-mbstring
* 4) Configurer Apache2 pour utiliser PHP
	- sudo a2enconf php7.2-cgi
	Ensuite
	- sudo service apache2 restart
* 5) Installer phpMyAdmin
	Avant de lancer l'installation, il faut ajouter le répertoire de phpmyadmin car il a reçu un problème récemment
	-	sudo add-apt-repository ppa:phpmyadmin/ppa  
	- sudo apt-get update
	Ensuite, nous pouvons continuer à installer.
	- sudo apt install phpmyadmin php-gettext
	Suivre les étapes:
		- Selectionner apache2
		- Puis selectionner Non
* 6) Ajouter une ligne dans  *apache2.conf* pour permettre de link phpmyadmin au localhost
	- sudo nano /etc/apache2/apache2.conf
	-  À la fin du fichier, il faudra ecrire: **Include /etc/phpmyadmin/apache.conf**
* 7) Pour finir, restart le service apache
	-	 sudo service apache2 restart
		
### Créer un user pour phpMyAdmin
**Source**: [https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql](https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql)
Pour pourvoir donner l'acces au phpmyadmin, il faudra creer un utilsateur et donner les privileges.
* 1) Pour commencer, il faudra utiliser mysql dans le terminal
	- sudo mysql
* 2) Créer un utilisateur avec le nom user et son mot de passe
	- CREATE USER '*nomUser*'@'localhost' IDENTIFIED BY '*motDePasse*';
* 3) Ensuite, on va donner tous les privilèges
	- GRANT ALL PRIVILEGES ON \* . \* TO '*nomUser*'@'localhost';
* 4) Pour terminer, on va affecter les privilèges
	- FLUSH PRIVILEGES;
* 5) Pour régler le soucis de caching_sha2_password
    - ALTER USER '*nomUser*'@'localhost' IDENTIFIED WITH mysql_native_password BY '*motDePasse*';
* 6) Pour sortir de l'interface de MYSQL
	- exit
	
## Wordpress

3 parties:
	-WP classic
	-Dev des themes
	-Dev des plugins

CMS: Content management system)

Pour commencer un projet il faut d'abord commencer par installer PHP, Mysql et WordPress Command Line Interface (wp cli).


### Installer Wp Cli
**Source**: [https://wp-cli.org/fr/](https://wp-cli.org/fr/)
* 1) Télécharger le fichier wp-cli.phar
	- Si curl n'est pas installer : sudo apt install curl
	- curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
	Vérifier si sa fonctionne:
		- php wp-cli.phar --info
* 2) Ensuite il faudra rentre le fichier executable et permettre de l'utiliser grace au PATH
	- chmod +x wp-cli.phar
	- sudo mv wp-cli.phar /usr/local/bin/wp
* 3) Derniere étape, verifier si sa fonctionne
	- wp --info

### Installer Wordpress
Pour installer Wordpress, on passera en ligne de commande.
* 1) Tout d'abord on va créer son projet.
	- mkdir *nomProjet* && cd *nomProjet*
* 2) Ensuite on va télécharger les fichier
	- wp core download 
* 3) Apres installation, il faut lancer le serveur
	- wp server
* 4) Créer une base de donnéeqw
	- Aller dans le phpmyadmin *localhost/phpmyadmin*
	- Créer la base de donnée
	- Indiquer un nom à la base de donnée et indiquer en **utf8_unicode_ci**
* 5) Configurer wordpress
	- Aller dans le navigateur dans l'adresse *localhost:8080*
	- Suivre les étapes

**Extensions**:
	- Elementor: permet de build la page sous forme de drag n drop

### Installer Xdebug

**Source**: [https://xdebug.org/](https://xdebug.org/)

 * 1) Aller dans download / custom installation instructions
 * 2) Ensuite, lancer wp server dans le projet wordpress et dans le fichier index.php, mettre tous en commentaire et intrduire phpinfo();
	 - phpinfo();
 * 3) Copier toutes les données de la page qui est afficher dans l'index.php
	 - CTRL+A et CTRL+C
 * 4) Collez le tous sur dans le champs texte de la page de custom installation instructions
	 - CTRL+V
 * 5) Suivre les étapes indiquer
 * 6) Avant de modifier un fichier, il faudra ajouter des lignes
	- zend_extension = /usr/lib/php/20170718/xdebug.so
	- [XDebug]
	- xdebug.remote_enable = 1
	- xdebug.remote_autostart = 1
 * 7) Relancer le service apache ```
	 - sudo service apache2 restart
 * 8) Derniere etape, installer 

[http://www.dieuwe.com/blog/xdebug-ubuntu-1604-php7](http://www.dieuwe.com/blog/xdebug-ubuntu-1604-php7)php debug sur vscode est c'est fini

### Travailler localement sur un projet
Pour travailler sur un projet sans utiliser wp server de wordpress, on va utiliser php -S.
Tout d'abord aller sur le projet en question. Ensuite, lancer le terminal a partir du projet et lancer la commande **php -S** suivi de l'adresse qu'on veut lui attribuer et le port .
	
		sudo php -S 127.0.0.1:1000

Et pour finir aller sur le navigateur et introduire l'adresse complet pour avoir l'aperçu du projet.








[http://www.dieuwe.com/blog/xdebug-ubuntu-1604-php7](http://www.dieuwe.com/blog/xdebug-ubuntu-1604-php7)
	
## Laravel

### Intro 
Laravel est un framework PHP qui utilise la structure mvc (Models, Views, Controller). Il est utiliser plus pour créer une platforme .

* **MVC**: ```
	-**V**iew: cest la partie vue, la partie front end
	-**C**ontroller: permet de faire des controlles (ex: acceder a une page si on est admin)
	-**M**odel: traiter les donnees, backend 
### Installation
 - Installer Composer
		sudo apt-get install composer
 - Dans Composer installer laravel de maniere global
		 composer global require laravel/installer
 - Ensuite, avant d'installer laravel il faut modifier le fichier bashrc pour pouvoir utiliser laravel new
		 nano ~/.bashrc
		- Ajouter a la fin : 
				export PATH="\$HOME/.config/composer/vendor/bin:$PATH"
				**Attention** Bien verifier ou ce trouve le dossier composer
		- Enregistrer et redemarrer


**Si tu lis ceci, il y a une mise à jour qui arrive**

### AdminLTE
AdminLTE est un template fait en bootstrap qui se consacre à un dashboard pour le côté gestion du site (admin)

#### Installation
Pour commencer, nous allons ajouté dans nos paquets.

````BASH
	composer require jeroennoten/laravel-adminlte
````
Ensuite, nous allons ajouté le dans nos paquets laravel/ui et intégrer les controllers réserver à la l'auth.
````BASH
	composer require laravel/ui
	php artisan ui:controllers
````
Pour terminer, installer adminlte dans le projet
````BASH
	php artisan adminlte:install
````

Des que l'installation est fait, il y a des fichiers qui a été créer. 
- config/adminlte.php : Se fichier est consacré à la configuration du adminlte. Il touche du style jusqu'au sidebar. Pour aller plus loin, le lien de la doc: [https://github.com/jeroennoten/Laravel-AdminLTE](https://github.com/jeroennoten/Laravel-AdminLTE)

Comment utiliser adminlte dans une blade
*  Le template va utiliser le layout d'une page de adminlte.
	
	````PHP
		@extends('adminlte::page')
	````

* On va indiquer la section 'content' et écrire dessus pour automatiquement cette section soit intégrer.
	````PHP
		@extends('adminlte::page')

		@section('content')
			<div class="container">
				<h1> Hello User</h1>
			</div>
		@endsection	
	````

Pour plus d'info: [https://github.com/jeroennoten/Laravel-AdminLTE](https://github.com/jeroennoten/Laravel-AdminLTE)

Pour utiliser pleinement adminlte, il faudra aller dans le site, de prendre un bloc que nous voulons et la copier. Ensuite, on retourne dans notre blade et on devra l'adapter suivant le besoin.
Lien template: [https://adminlte.io/themes/v3/index.html](https://adminlte.io/themes/v3/index.html)


### Authentication

#### Installation
A partir d'un projet en cours
````bash
	composer require laravel/ui
	php artisan ui bootstrap --auth
````
A partir d'un nouveau projet
````bash
	laravel new projet --auth
````

#### Exploration des fichiers
Maintenant que nous avons installé, nous allons parcourir les dossiers.
	- Dossiers dans view lier au authentication
	- Montrer la route ce qui est ajouté
````PHP
	Auth::routes();
````
	- Montrer les controllers (HomeController, dossier Auth)
	- Afficher dans une blade les infos avec Auth()
````PHP
	Auth::user()->name
````
* Utiliser une condition avec Auth
````PHP
	//en PHP
	@if(Auth::user() != null)
		//code à executer
	@endif
	// Condition si y'a une authentication
	@auth
	//code à executer
	@endauth	
	// Condition le cas contraire
	@guest
	//code à executer
	@endguest
````

### Validation
#### Définition
Une validation est un étape qui vérifie les requêtes introduit par l'user via des réglés défini.

#### Écriture d'une validation dans le controller
Pour commencer, on doit utiliser la **Request $request** en paramètre. Ensuite, nous pouvons écrire les règles pour chaque input.

* Syntaxe dans une méthode
````PHP
	public function store(Request $request){
		$request->validate([
		// Règle pour chaque input
		],[
		// Message pour chaque règles
		]);
	}
````

Le validate() permet de définir les règles qu'on souhaite pour chaque information qu'on récupère lors de la requêtes. Le premier paramètre est la définition des règles et le second est pour les messages à afficher.


* Ecriture des règles

````PHP
	public function store(Request $request){
		$request->validate([
		 'titre' => 'required'
		])
	}
````

* Écriture des messages

````PHP
	public function store(Request $request, $id){
		$request->validate([
		 'titre' => 'required'
		],[
		'titre.required' => 'Le titre est requis'
		]);
	}
````

#### Affichage des erreurs
Si un utilisateur introduit ses informations dans le formulaire et qu'il ne respecte pas les règles défini, il est possible d'afficher les erreurs dans le front.

* Afficher toutes les erreurs
````PHP
	// On vérifie si y'a eu un problème
	// $errors->any() renvoi un booléan
	@if($errors->any())
		// On parcourt notre tableau avec tous les erreurs
		@foreach($errors->all() as $error)
			// Le message d'erreur
			$error
		@endforeach
	@endif
````

* Afficher par élément
````PHP
	// le @error va détecter s'il a eu l'erreur
	// en parametre, il faut préciser par rapport à quel input
	// Si il n'y a pas d'erreur, la partie du message ne s'affiche pas
	<input type="text" name="titre" />
	@error('titre')
		// Affiche le message
		// Attention $message est une variable réservé
		{{$message}}
	@enderror
````

Il est possible d'ajouter un style d'erreur à l'input en question. Par défaut, Laravel a défini une class css pour l'occasion. Pour l'utiliser, il faudra une erreur se produit et ainsi définir **is-invalid** dans l'attribut class.
````PHP
	<input type="text" name="titre"
	 class="@error('titre') is-invalid @enderror"
	 />
	@error('titre')
		$message
	@enderror
````

#### Récupérer les anciennes information lors d'une erreur
Lors de la création d'une requête, il est possible que l'utilisateur ne respecte pas les règles pour les champs. Mais si on traite et qu'il y a une erreur, les champs qu'il a introduit disparaît. Dans ce cas, il est possible de récupérer les anciennes valeur des champ avec le **old**. Le old va récupérer les anciennes valeur en cas d'erreur lors de la requête.

````PHP
	// On doit précisé en parametre quel input doit il récupérer
	<input type="text" name="titre"
	 class="@error('titre') is-invalid @enderror"
	 value="{{old('titre')}}"
	 />
````

#### Création d'une requête 
Nous allons maintenant créer une requête qui va permettre de séparer le côté regles des input et du CRUD.
````BASH
	php artisan make:request PhotoRequest
````

* La syntaxe du fichier s'écrit **NomRequest**

#### Analyse du fichier
Maintenant qu'on a créé le fichier, nous allons analyser ce qui contient. Pour ça, nous allons dans le dossier App/Http/Requests et dans notre fichier en question.

* Méthode authorize():
	- Il détermine si un utilisateur peut utiliser cette requête
````PHP
	public function authorize(){
		return false;
	}
````

* Méthode rules():
	- Il permet d'appliquer les règles de validation dans la requête
	- C'est ici que nous allons migrer les règles depuis le controller et l'indiquer dans le return.
````PHP
	public function rules(){
		return [
			//
		];
	}
````
Et pour finir, nous allons créer une méthodes messages() pour migrer tous les messages depuis le controller

````PHP
	public function messages(){
		return [
			//
		]
	}
````

Ce qui donne ceci
````PHP
	public function rules(){
		return [
			 'titre' => 'required'
		];
	}
	public function messages(){
		return [
			 'titre.required' => 'Le titre est requis'
		];
	}
````
#### Utilisation des requêtes créer précédemment
Maintenant que notre fichier est prêt, nous allons l'utiliser dans nos controllers. Pour ce faire, il faudra import le fichier.

````PHP
	use App\Http\Requests\PhotoRequest;
````

Après l'import dans notre controller, il faudra dire dans nos méthodes qu'il devra utiliser notre requêtes à la place du requêtes par défaut.
````PHP
	public function store(PhotoRequest $request, $id){
		// code à executer
	}
````

#### Les différentes règles
Pour connaitre les différentes règles que nous pouvons appliquer, nous allons nous référé à la documentation de Laravel:
[https://laravel.com/docs/7.x/validation#available-validation-rules](https://laravel.com/docs/7.x/validation#available-validation-rules)

### Middleware
#### Définition
Le middleware est une fonction qui se trouve entre l'appel de la route et l’exécution. Cette fonction va filtrer l'action si un utilisateur peut y accéder ou non

#### Création d'un middleware
	````Bash
	php artisan make:middleware CheckAge
	````

Ici, on remarque qu'il a créé un fichier CheckAge dans le dossier App/Http/Middleware. Le fichier va contenir la class CheckAge ainsi qu'une méthode handle. La méthode va intercepte la requête que l'utilisateur veut faire et permet de la renvoyer vers la page si la condition le permet (Par défaut il renvoi vers la requête).

````PHP
	<?php

	namespace  App\Http\Middleware;

	use Closure;
	class  CheckAge
	{
		/**
		* Handle an incoming request.
		*
		* @param  \Illuminate\Http\Request $request
		* @param  \Closure $next
		* @return  mixed
		*/
		public  function  handle($request, Closure  $next)
		{
			return $next($request);
		}
	}
	?>
````
#### Définition de la logique du middleware
Nous allons définir dans cette middleware que la personne doit avoir plus de 12 ans pour y accéder.

````PHP
	<?php

	namespace  App\Http\Middleware;

	use Closure;
	class  CheckAge
	{
		/**
		* Handle an incoming request.
		*
		* @param  \Illuminate\Http\Request $request
		* @param  \Closure $next
		* @return  mixed
		*/
		public  function  handle($request, Closure  $next)
		{
			if($request->age <= 12)
				return route('home');

			return $next($request);
		}
	}
	?>
````
#### Définir en global notre middleware
Maintenant, nous allons assigner notre middleware dans nos routes pour qu'il soit reconnaissable dans le web.php. La partie qui nous intéresse sa sera la partie **routeMiddleware**. Cette partie va permettre de définir un middleware dans la route et qu'on pourra le chercher via son nom.

Dans le fichier App\Http\Kernel.php
````PHP
<?php

namespace  App\Http;

use  Illuminate\Foundation\Http\Kernel  as  HttpKernel;

class  Kernel  extends  HttpKernel

{

	/**
	* The application's global HTTP middleware stack.
	*
	* These middleware are run during every request to your application.
	*
	* @var  array
	*/

	protected  $middleware  = [
		\App\Http\Middleware\TrustProxies::class,
		\App\Http\Middleware\CheckForMaintenanceMode::class,
		\Illuminate\Foundation\Http\Middleware\ValidatePostSize::class,
		\App\Http\Middleware\TrimStrings::class,
		\Illuminate\Foundation\Http\Middleware\ConvertEmptyStringsToNull::class,
	];

	/**
	* The application's route middleware groups.
	*
	* @var  array
	*/

	protected  $middlewareGroups  = [
		'web' => [
			\App\Http\Middleware\EncryptCookies::class,
			\Illuminate\Cookie\Middleware\AddQueuedCookiesToResponse::class,
			\Illuminate\Session\Middleware\StartSession::class,
			// \Illuminate\Session\Middleware\AuthenticateSession::class,
			\Illuminate\View\Middleware\ShareErrorsFromSession::class,
			\App\Http\Middleware\VerifyCsrfToken::class,
			\Illuminate\Routing\Middleware\SubstituteBindings::class,
		],

		'api' => [
			'throttle:60,1',
			'bindings',
		],
	];

  

	/**
	* The application's route middleware.
	*
	* These middleware may be assigned to groups or used individually.
	*
	* @var  array
	*/

	protected  $routeMiddleware  = [
		'auth' => \App\Http\Middleware\Authenticate::class,
		'auth.basic' => \Illuminate\Auth\Middleware\AuthenticateWithBasicAuth::class,
		'bindings' => \Illuminate\Routing\Middleware\SubstituteBindings::class,
		'cache.headers' => \Illuminate\Http\Middleware\SetCacheHeaders::class,
		'can' => \Illuminate\Auth\Middleware\Authorize::class,
		'guest' => \App\Http\Middleware\RedirectIfAuthenticated::class,
		'signed' => \Illuminate\Routing\Middleware\ValidateSignature::class,
		'throttle' => \Illuminate\Routing\Middleware\ThrottleRequests::class,
		'verified' => \Illuminate\Auth\Middleware\EnsureEmailIsVerified::class,
		//Ici ce fait l'import
		'CheckAge' => \App\Http\Middleware\CheckAge::class
	];

	/**
	* The priority-sorted list of middleware.
	*
	* This forces non-global middleware to always be in the given order.
	*
	* @var  array
	*/

	protected  $middlewarePriority  = [
		\Illuminate\Session\Middleware\StartSession::class,
		\Illuminate\View\Middleware\ShareErrorsFromSession::class,
		\App\Http\Middleware\Authenticate::class,
		\Illuminate\Routing\Middleware\ThrottleRequests::class,
		\Illuminate\Session\Middleware\AuthenticateSession::class,
		\Illuminate\Routing\Middleware\SubstituteBindings::class,
		\Illuminate\Auth\Middleware\Authorize::class,
	];
}
````

#### Assigner dans les routes
Maintenant, nous allons appeler le middleware dans une route.

web.php
````PHP
<?php

// ->middleware fait appel au middleware et en parametre c'est le nom en question

Route::get('forum','ForumController@index')->middleware('CheckAge');

?>
````

Il est possible aussi de rajouter plusieurs middleware pour une seul route
````PHP
<?php

// premier middleware et le second

Route::get('forum','ForumController@index')->middleware('CheckAge','auth');

?>
````

#### Assigner dans le controller

Nous pouvons aussi d'ajouter dans un controller à la place des routes. Pour cela, nous devons dire dans le constructeur 

````PHP
<?php

namespace  App\Http\Controllers;

use  Illuminate\Http\Request;

class  ForumController  extends  Controller
{

	public function __construct(){
		// On déclare le middleware 
		// Par défaut il agit sur l'ensemble des méthode
		$this->middleware('CheckAge');
		// Ici sa sera uniqument sur l'index
		$this->middleware('CheckAge')->only('index');
	}

}
?>
````

### Gate
#### Définition
Gate est un système d’autorisation qui va permettre si un user est autorisé une action spécifique ou non. Par défaut, ils renvoi un booléen.

#### Créer un gate
Pour commencer, nous allons dans le fichier AuthServiceProvider et créer le gate. La gate va vérifier si un utilisateur pourra update un album ou non.

App\Http\Providers\AuthServiceProvider.php
````PHP
<?php

namespace  App\Providers;

use  Illuminate\Foundation\Support\Providers\AuthServiceProvider  as  ServiceProvider;
use  Illuminate\Support\Facades\Gate;
use  App\User;
use  App\Album;

class  AuthServiceProvider  extends  ServiceProvider
{
	/***
	* The policy mappings for the application.
	*
	* @var array
	*/
	
	protected  $policies  = [
		'App\Model' => 'App\Policies\ModelPolicy',
	];

	/**
	* Register any authentication / authorization services.
	*
	* @return  void
	*/

	public  function  boot()
	{
		$this->registerPolicies();
		
		// Gate::define permet de définir une gate
		// Premiere parametre: donner un nom au gate
		// Le second prend execute une fonction
		// la fonction prend en parametre un utilisateur et un album
		// l'user permet de savoir qui est la personne
		// l'album permet de savoir quel album l'user veux acceder
		Gate::define('update-album', function (User $user,Album $album){
			// Verifie si l'album apartient a l'user en question
			// true: peut modifier
			// false: ne peut pas modifier
			return $user_id === $album->user_id;
		});
	}
}
?>
````

#### Utiliser la gate dans le controller
Maintenant que nous avons défini, on peut restreindre les autorisations pour les user. Pour ceci, nous devons aller dans le controller et dans la méthode edit. 
````PHP
	// En parametre, l'album qu'on veut editer
	public function edit(Album $album){
		//Ici on indique la gate a utilisé
		//Premier parametre: le nom de la gate
		//Deuxieme parametre: l'album
		$this->authorize('update-album',$album)
		return view('edit',compact('album'));
	}
````

#### Utiliser la gate dans la route
Nous pouvons aussi définir dans le web.php. Il faudra appeler via le middleware().
````PHP
	//can permet de dire au middleware à la route autorise à executer.
	// album permet de joindre l'album en question
	Route::get('/album/{album}/edit','AlbumController@edit')->middleware('can:update-album,album');
	// ou similaire
	Route::get('album','AlbumController')->middleware('can:update-album,album');
````
#### Condition de rendu dans la blade
Dans certains cas, il est possible que l'autorisation fonctionne mais que les boutons sont visibles pour les users. Dans ce cas la, il faudra mettre une condition pour afficher uniquement les boutons pour les users concerner.
Pour cela, nous allons utiliser le can comme dans les routes. Il garde le même principe que dans la route ou dans le controller. C'est à dire que le premier paramètre on fait appel à la méthode en question et le second l'élément en question a vérifié.
````PHP
	@can('update-album',$album)
		<a  href="/albums/{{$album->id}}/edit"  class="btn btn-primary">Update</a>
	@endcan
	@can('delete-album', $album)
		<a  href="/albums/{{$album->id}}/delete"  class="btn btn-danger">Delete</a>
	@endcan
````
### Policy
#### Définition
Une policy est la même chose qu'une mais il est plus consacré à un CRUD
#### Créer une policy
Pour commencer, nous allons dans le terminal et nous allons créer une policy.
````BASH
	php artisan make:policy AlbumPolicy
````
Le fichier se trouvera dans le dossier App\Policies. Si on examine le fichier, on retrouve la classe **AlbumPolicy**  avec un constructeur. Il est possible de créer les méthodes manuellement ou avec la ligne de commande.
La commande est la même chose sauf que nous allons rajouter --model
````BASH
	php artisan make:policy AlbumPolicy --model=Album
````

On constate que maintenant il y'a les méthodes qui est par rapport au model Album et agit en fonction des actions utilisateur (view, update, delete, ...). Un utilisateur pour faire certaine action si il est autorisé. Chaque méthode renvoi un boolean. 
Par défaut, il n'y a pas de condition du coup il n'y a pas de vérification.
````PHP
	public  function  update(User  $user, Album  $album){
		
	}
````
Il est possible de dire qu'un user peut faire ce qu'il veut peut importe si l'album l'apartient ou non.
````PHP
	public  function  update(User  $user, Album  $album){
		return true;
	}
````
 Pour restreindre il faudra renvoyer une condition du genre si un utilisateur peut mon modifier cette Album.
````PHP
	public  function  update(User  $user, Album  $album){
		// Si l'user update son album
		// true: il est autorisé
		// false: il n'est pas autorisé et renvoi 403
		return  $user->id  ===  $album->user_id;
	}
````

#### Methode before
Le before est une méthode qui va s’exécuter avant les autres. Il a un ordre d’exécution qui va nous permettre dans notre cas de dire si un user est admin ou non. Si il est admin, il pourra faire les modification et les suppressions que les autres user ne peuvent pas faire.
````PHP
	public  function  before($user, $ability){
		// Si l'user à le rôle admin, il est autorisé
		// Sinon il execute les méthodes en dessous
		// et fait la vérification
		if($user->role  ===  "admin")
			return  true;
	}
````

#### Définir en global 
Pour que la policy soit utilisable, il faudra définir en global dans le projet. Pour ce faire, il faudra aller dans le fichier AuthServiceProvider. Dans l'attribut $policies, il faudra indiquer dans le tableau la policy en question.

App\Providers\AuthServiceProvider
````PHP
<?php

namespace  App\Providers;
use  Illuminate\Foundation\Support\Providers\AuthServiceProvider  as  ServiceProvider;

use  Illuminate\Support\Facades\Gate;

class  AuthServiceProvider  extends  ServiceProvider
{
	/**
	* The policy mappings for the application.
	*
	* @var  array
	*/

	protected  $policies  = [
		// 'App\Model' => 'App\Policies\ModelPolicy',
		'App\Album' => 'App\Policies\AlbumPolicy'
	];
	
	/**
	* Register any authentication / authorization services.
	*
	* @return  void
	*/

	public  function  boot()
	{
		$this->registerPolicies();
	}
}
````
Il est possible d'ajouter des autres méthodes au besoin.
#### Utiliser la policy dans le controller
Maintenant que nous avons défini, on peut restreindre les autorisations pour les user. Pour ceci, nous devons aller dans le controller et dans la méthode edit. 
````PHP
	// En parametre, l'album qu'on veut editer
	public function edit(Album $album){
		//Ici on indique la gate a utilisé
		//Premier parametre: le nom de la gate
		//Deuxieme parametre: l'album
		$this->authorize('update',$album)
		return view('edit',compact('album'));
	}
````

#### Utiliser la policy  dans la route
Nous pouvons aussi définir dans le web.php. Il faudra appeler via le middleware().
````PHP
	//can permet de dire au middleware à la route autorise à executer.
	// album permet de joindre l'album en question
	Route::get('/album/{album}/edit','AlbumController@edit')->middleware('can:update,album');
	// ou similaire
	Route::get('album','AlbumController')->middleware('can:update,album');
````
#### Condition de rendu dans la blade
Dans certains cas, il est possible que l'autorisation fonctionne mais que les boutons sont visibles pour les users. Dans ce cas la, il faudra mettre une condition pour afficher uniquement les boutons pour les users concerner.
Pour cela, nous allons utiliser le can comme dans les routes. Il garde le même principe que dans la route ou dans le controller. C'est à dire que le premier paramètre on fait appel à la méthode en question et le second l'élément en question a vérifié.
````PHP
	@can('update',$album)
		<a  href="/albums/{{$album->id}}/edit"  class="btn btn-primary">Update</a>
	@endcan
	@can('delete', $album)
		<a  href="/albums/{{$album->id}}/delete"  class="btn btn-danger">Delete</a>
	@endcan
````

### Autres
#### Déclaration fonction global
Dans Laravel, il est possible si besoin de créer de méthodes et de les utiliser un peur partout. Pour ça il faudra créer un fichier et écrire nos fonctions.
 - Créer un fichier helpers.php dans App
 - Editer le composer.json pour rajouter ce fichier	
	````JSON
	"autoload" :  {
		.
		.
		.
	//ajouter ceci à la suite
	"files": ["app/helpers.php"]
	}
	````
- Ensuite réactualiser le autoload
	````BASH
		composer dump-autoload
	````

		

