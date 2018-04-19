# Le contrôle d'accès

Le contrôle d’accès est une technique qui consiste à soumettre l’entrée d’un établissement ou, de locaux à l’intérieur d’une entreprise, à une autorisation d’accès.
Pour L’autorisation d’accès Il y a trois façons de prouver son identité face à un système informatique :
-  de montrer ce que l’on sait (un mot de passe ou code).

- de montrer ce que l’on possède (un objet, telle une carte à puce, un badge).

- de prouver qui l’on est grâce à une caractéristique physique propre (biométrie).

## 1.Comment faire du contrôle d’accès ?
A l’aide :
	- De gardiennage : Un gardien à une porte, contrôle les entrées et les sorties par reconnaissance visuelle des personnes ou par lecture d’un badge avec photo d’identité ou bien encore par la vérification d’un laissez-passer.

	- De moyens mécaniques : Un portillon, un sas, une barrière…peuvent être utilisés pour filtrer les entrées, les compter ou ne permettre qu’à une seule personne à la fois de franchir l’accès. Ces moyens sont souvent conjugués avec la présence d’un gardien ou l’emploi d’un système d’identification.

	- De systèmes d’identification qui analysent : 
 Les codes (clavier).
 Les cartes d’accès (magnétiques, optiques, électromagnétiques).
 Les caractéristiques physiologiques d’une personne (empreintes, iris…).

## 2.L’identification
L’identification est la première fonction primaire intervenant dans la configuration d’un système de contrôle d’accès. Elle permet de déterminer avec beaucoup de précision, quel est l’usager qui se présente à l’accès pour lui donner une autorisation de passage ou un refus. Le système est automatisé, une erreur sur l’accord de passage ne serait plus rattrapable, et par conséquent l’identification doit être la plus fiable possible. Il sera donc associé à chaque usager un identifiant mnémonique ou physique. La base de données du système de contrôle d’accès définira pour chaque identifiant ses droits d’accès. 

Il existe différents types de lecteurs qui dépendent des technologies des identifiants sélectionnés. On peut distinguer trois familles principales d’identifiants :
•	A codes mnémoniques
•	A badges ou implants (les implants peuvent être utilisés sur différents supports comme des clés par exemple)
•	Biométriques

Certaines applications mixent ces différentes technologies :
•	Badge + code
•	Badge + biométrie
•	Code + biométrie

### 1 LES LECTEURS DE BADGES :
- Définition:

Ce sont des dispositifs qui permettent la lecture des informations contenues dans des identifiants à badges ou implants. L’usager présente son badge au lecteur, qui décrypte les informations contenues et les transmet à l’unité de traitement pour comparaison avec la base de données.

Dans ce cas, la disparition de badge identifiant peut être rapidement connue avec une réaction immédiate par paramétrage, sans avoir à modifier le matériel installé.

Il existe différents types de badges qui dépendent des technologies utilisées :

**BADGE A CONTACT:
Les lecteurs de badges qui nécessitent un contact doivent être accessibles à l’extérieur de la zone sécurisée. Les contacts entraînent des frottements et par conséquent des usures. Les différents types de badges à contact rencontrés sont :

•	Les badges magnétiques :

-  Les cartes à couche simple : une bande magnétique codée et visible est placée sur le bord de la carte comme pour les cartes bancaires (mémorisation de 40 à 90 caractères alphanumériques). Le coût du badge est plutôt faible, mais il est sensible aux champs magnétiques, poussières, rayures. La copie à l’identique est facilement réalisable.

- Les cartes à couche épaisse : une patte magnétique invisible et codée est noyée à l’intérieur du plastique de la carte (mémorisation de 20 à 40 caractères alphanumériques).

- La carte à induction baryum-ferrite : une technologie de moins en moins employée. Cette carte contient un certain nombre d'aimants qui, suivant leur orientation, représentent la valeur binaire 0 ou 1. Par association de ces valeurs en quartets, on code les chiffres 1 à 9 pour former un nombre qui peut être reconnu par une matrice de bobines. Peu utilisée pour des grandes configurations, cette technologie, par sa simplicité, représente pas mal d'avantages dont le coût et l'insensibilité aux chocs et aux rayures.

- La carte à effet Wiegand : il s'agit d'une piste magnétique incorporant des fils métalliques (maillechort) torsadés. Cette carte présente beaucoup d'avantages : rapidité de lecture, fraude et copie difficile, haut niveau de sécurité. Elle est de plus en plus souvent remplacée par la carte à puce.

- La carte magnétique Wratermark : il s'agit d'une carte à 2 pistes magnétiques superposées encodables exclusivement par le fabricant. Non reproductible et infalsifiable.


	 Les badges optiques :

-	Les cartes à opacité variable (ne sont plus utilisées).

-	Les cartes avec un code barre dont la lecture est réalisée à l’aide d’une source infrarouge. Ce type de badge est insensible aux champs magnétiques, aux chocs et aux rayures. Mais si le code barres n’est pas masqué, la copie est possible.


•	Les badges électroniques :

-  Les cartes à puce : elles contiennent un microprocesseur capable d’enregistrer des informations très nombreuses permettant des usages multiples. Elle procure un très haut degré de sécurité mais elle est sensible aux chocs, pliages et torsions et sont coût est assez élevé.

**

*** Avantages:

+ La mémoire des lecteurs permet de programmer beaucoup de cartes
+ En envoie les informations en toute sécurité
+ Pas besoin d'écrire les données a chaque fois 
+ On peut récupérer les donners sur une base de donnée

*** Iconvénients:

- Il est facile de perdre les cartes

*** Coût:

Pour le coût c'est pas facile de donner une valeur exacte, mais ça dépend de l'utilisation pour quelque chose de professionnelle ça peut monter jusqu'a 100€ même plus, par contre pour un projet normale ça dépasse pas 30€.

### 2 LES QR code ou Flash code :
- Définition:

Le principe des flash codes ou QR codes ou Tags est le suivant: il s’agit d’un format données qui fonctionne grâce à un code de pixels formant un pictogramme en 2D composé de carrés et pouvant être reconnus en générale par un terminale mobile disposant d’un lecteur.

Il s’agit du successeur des codes barre et permet de stocker une grande quantité d’informations dans un espace réduit.

il existe 2 types de flash codes:

flash codes directs qui contiennent toute l’information nécessaire pour déclencher une action
flash codes indirects qui permettent d accéder à un serveur contenant l’information qui déclenchera l’action

*** Les différentes utilisation d'un flash code

* se connecter à un site web
* envoyer un SMS, MMS ou e-mail
* émettre un appel
* enregistrer une carte de visite pour les clients
* accéder à du contenu pratique, historique, culturel, ludique

*** Comment le flash code marche-t-il?

* suffit de télécharger une application permettant  de déchiffrer les flash code
* une fois installée, il suffit de lancer l’application
* prendre en photo le flash code
* l’application va déchiffre ce flash code
* l’application va vous transmettre le contenu multimédias contenu dans ce flash code

*** Les avantages du flash code:

* accéder rapidement à une information ciblée
* enregistrer une information conséquente dans un espace réduit
* développer des campagnes de communication multicanale
* facile à mettre en oeuvre et peu cher
* disponible pour toutes les tailles
* véhiculer une promotion, réduction…
* pousser les consommateurs à se déplacer en magasin
* délivrer des informations supplémentaires sur un produit

*** Les inconvénients du flash code:

* le système de code utilisé en France oblige, après décodage du code, à effectuer une liaison de données avec le serveur de l’opérateur téléphonique afin d’obtenir une redirection vers les données de destination du flash code, processus long
* système français étant peu transparent et manquant d’interopérabilité
* impossibilité de shooter un code en mouvement
* assez contraignant car le mobinaute doit ouvrir son lecteur puis prendre une photo
