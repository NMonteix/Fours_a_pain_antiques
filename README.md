![Calendrier rustique de Saint-Romain-en-Gal, MAN83116](https://www.photo.rmn.fr/CorexDoc/RMN/Media/TR4_MD5/0/1/6/b/12-553052.jpg)

# Les fours à "pain" antiques (Ve s. av. n.è. - Ve s. de n.è.) : données
Ce [fichier](https://github.com/NMonteix/Fours_a_pain_antiques/releases/download/Derniere_version/fours_donnees10.csv) présente les informations sur les fours à pain antiques, issues des rapports et publications de fouille, et rassemblées en particulier pour la rédaction de l'article soumis en février 2021 à *Gallia*. La liste rassemblée n'a aucune prétention à l'exhaustivité sur l'arc chronologique ou sur l'espace géographique concernés. Le format CSV permet la lecture du fichier dans n'importe quel tableur. Les données sont proposées sous licence [![Creative Commons Attribution -  Partage dans les Mêmes Conditions 4.0 International](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/deed.fr).

## Remerciements
Le rassemblement de ces données n'aurait pas pu être réalisé sans l'aide de celles et ceux qui ont soit transmis leurs rapports d'opération, soit servi de relais vers les responsables d'opération, soit répondu avec diligence à des demandes groupées de rapports. Que toutes et tous en soient sincèrement remerciés.
- **Antea Archéologie**: Murer Axelle.
- **Archéologues indépendants**: Florent Guillaume, Gomes Manuel.
- **ARON bv**: Reygel Patrick.
- **CNRS**: Lesguer Fabien, Py Michel.
- **Eveha**: Blondeau Rémi, Cartron Gaël, Delauney Antoine, Delhoofs Hervé, Gomez Sébastien, Loiseau Christophe, Peyne Nicolas.
- **Hadès archéologie**: Ephrem Brice.
- **Inrap**: Barberan Sébastien,  Bataille Gérard,  Blondiau Lydie,  Bruley-Chabot Gaelle,  Célié Marc,  Gaudefroy Stéphane,  Houix Bertrand,  Le Gaillard Ludovic,  Lepaumier Hubert,  Mathelart Pierre,  Rollet Philippe,  Vauterin Chris-Cécile,  Villard Jean-François.
- **Paleotime**: Fénéon Laetitia.
- **Services régionaux de l'archéologie**:  Bellanca-Penel Delphine, Lacoste Elisabeth, Ollivier Laurence (Auvergne - Rhône-Alpes), Charmot Anne, Chenevoy Marie-Hélène, Kaurin Jenny, Prieto Josépha (Bourgogne - Franche-Comté), Cadars Laure (Bretagne), Clément Isabelle, Gautier Basset (Grand-Est), Courtiller Mickaël, Masson Bertrand (Hauts-de-France), Bolo Nathalie, Coulthard Nicola, Moitrel Patricia (Normandie), Bordillon Pascal (Nouvelle-Aquitaine), Dieulafait Christine, Pascal Henriette (Occitanie), Dewaelsche Gisèle, Vitali Gabrielle (PACA).
- **Services archéologiques de collectivités**: Amoroso Hugo, Duvauchelle Anika (Site et Musée romains d’Avenches), Brkojewitsch Gaël (Metz Métropole), Couturier David (Pôle archéologique de la Ville de Paris), Dargery Vincent (Conseil général de l’Oise), Henrotay Denis (Agence wallonne du patrimoine), Le Bihan Jean-Paul (Centre de Recherche Archéologique du Finistère), Lefeuvre Aurélien (Service départemental archéoloique du Val d'Oise), Munier Claudine (Ville de Besançon), Petit Jean-Paul (Conservation départementale d’archéologie de Moselle).
- **Universités**: Monteil Martial (U. de Nantes), Paridaens Nicolas (U. Libre de Bruxelles), Vermeersch Didier (U. de Cergy-Pontoise), Vilvorder Fabienne (UCLouvain).

## Collaborer
Pour signaler des erreurs ou ajouter des fours à cette liste, envoyer les informations permettant de remplir tous les champs, éventuellement assorties d'un plan et d'une photo, à <nicolas.monteix@univ-rouen.fr> ou bien intégrer les données dans le [fichier](https://github.com/NMonteix/Fours_a_pain_antiques/releases/) et créer une *Pull request*.

## Explications sur les champs déployés
- **ID**: identifiant unique du four, de 1 à *n*. Les identifiants absents de la liste correspondent soient à des fours situés dans d'autres pays que ceux de la version concernée, soit à des effacements en cours de saisie
- **pays** : nom moderne du pays dans lequel le four a été découvert
- **ville_commune** : nom moderne de la commune dans laquelle se trouve le four
- **site** : nom du lieu-dit spécifique où se trouve le four
- **nom_antique**: éventuelle mention du nom antique de l'agglomération dans laquelle le four a été découvert
- **appellation** : identifiant donné au four lors de la fouille
- **publication** : mention de la source sous la forme ***Auteur date, pagination***. Les références bibliographiques complètes sont proposées [en ligne](https://www.zotero.org/groups/2764383/fours_a_pain_antiques)
- **type_publication** : les ***Rapport***s non édités sont distingués des références éditées (***Article/monographie***)
- **Y**, **X** : coordonnées d'un point du four, théoriquement le centre de la sole, exprimées en degrés décimaux dans le système **WGS84**
- **precision** : évaluée de ***0*** à ***3***, la précision des coordonnées permet une estimation de la localisation du four. ***3*** : coordonnées d'un point de la sole ; ***2***: le four se trouve dans un rayon de 20 m autour des coordonnées indiquées ; ***1***: le four se trouve dans un rayon de 100 m autour des coordonnées indiquées ; ***0*** : les coordonnées sont très approximatives, au pire le four se situe dans le territoire de la commune dont les coordonnées du centroïde sont données
- **DateMin** : première année de l'arc chronologique durant lequel le four est estimé avoir fonctionné
- **DateMax** : dernière année de l'arc chronologique durant lequel le four est estimé avoir fonctionné
N.B. : Pour rappel, il n'y a pas d'année 0. Le Ier s. de notre ère aura ***1*** comme **`DateMin`**, ***100*** comme **`DateMax`**
- **profondeur_sole** : mesure longitudinale de la sole (en m), sans prendre en considération l'ouverture
- **largeur_sole** : mesure transversale *maximale* de la sole (en m), orthogonale à **`profondeur_sole`**
- **largeur_ouverture** : mesure transversale de l'ouverture (en m)
- **profondeur_ouverture** : mesure longitudinale de l'ouverture (en m)
- **hauteur_conservee** : hauteur *maximale* conservée (en m) de la chambre de cuisson, mesurée à partir de la surface de la sole
- **surface_restituee** : surface de *la sole du four* (sans prendre en compte l'emprise complète de celui-ci), évaluée en considérant que la sole est une ellipse. Formule appliquée : **&pi; x `profondeur_sole` x `largeur_sole` /4** (en m²)
- **dimensions_observees** : ***VRAI*** si des mesures précises ont pu être mesurées sur un plan, ***FAUX*** si seule une approximation des mesures est donnée dans le texte du rapport et qu'il n'a pas été possible de prendre des mesures précises
- **mobilite** : les fours peuvent être fixés au sol (***immobilier***) ou être déplacés (***mobilier***)
- **base** : la base du four, entendue comme le volume situé sous le niveau de la sole, peut être caractérisée par les techniques de construction mises en oeuvre (***maçonnerie***, ***remblais***, ***remploi***, ***terre crue***) ou bien simplement ***excavée***. Seuls les fours céramiques préfabriqués ont une base en ***terre cuite***
- **elevation** : l'élévation' du four, entendue comme le volume situé au-dessus du niveau de la sole formant la chambre de cuisson, peut être caractérisée par les techniques de construction mises en oeuvre (***maçonnerie***, ***remblais***, ***remploi***, ***terre crue***) ou bien simplement ***excavée***. Seuls les fours céramiques préfabriqués ont une élévation en ***terre cuite**
- **couverture** : on distingue les fours selon qu'ils sont sans couverture (***extérieur***), que seule leur ***aire de travail*** est couverte ou bien qu'ils sont dans un espace ***couvert***
- **foyer** : description qualitative de la construction du foyer. Elle peut être caractérisée par les éléments le constituant (***calcaire***, ***céramique***, ***dalle***, ***galets***, ***moellons***, ***mortier***, ***terres cuites architecturales***). Le foyer est dit ***simple*** s'il n'est constitué que par une couche de terre battue ou aplanie, ***armé*** si des tessons ou des pierres de petites dimensions ont été incorporés à cette terre. Seuls les fours mobiles céramiques sont ***sans*** foyer
- **autel** : ***VRAI*** si une plateforme permettant notamment d’entreposer très temporairement les pâtons attendant d’être enfournés a été identifiée en avant de la gueule, ***FAUX*** dans le cas contraire
- **event** : ***VRAI*** si la chambre de cuisson est perforée par une ouverture ou un conduit facilitant la prise d'air, ***FAUX*** dans le cas contraire
- **ergonomie** : qualification de la position de la sole par rapport au niveau d'où opère la personne chargée de la cuisson: soit de ***plain-pied***, soit en ***élévation*** (à partir de 0,20 m au-dessus du niveau de circulation)
- **classe_four** : le four peut être ***préfabriqué*** (généralement en terre cuite) ailleurs que sur son lieu d'utilisation, ou bien être mis en oeuvre sur son lieu d'utilisation (on distingue alors les fours ***excavé***s des fours ***construit***s qui nécessitent un apport de matériel)
- **type** :  les fours à ***coupole*** sont distingués des fours à sole verticale (***clibanus***), à condition que l'élévation soit suffisante pour avoir ds certitudes quant au type
- **type_hypothetique** : proposition de distinction entre les fours à ***coupole*** et les  fours à sole verticale (***clibanus***), quelles que soient les conditions de conservation de l'élévation
- **contexte** : si la principale distinction est faite entre les fours en contexte ***Rural*** des fours en contexte ***Urbain*** ou ***Aggloméré***, les fours découverts dans en contexte ***Militaire*** ou de ***Sanctuaire*** sont également mentionnés
- **contexte_specifique** : hors contexte rural, la principale distinction tient entre une destination ***Domestique*** ou ***Commercial***e de la production issue du four. En contexte rural, la même distinction s'applique, mais ont également été distingués les fours parfois installés à distance de tout habitat dans des structures préexistantes partiellement remblayées (***Fosse***, ***Fossé***, ***Mare***). D'autres situations particulières sont également mentionnées (***Nécropole***, ***Minier***)
- **interpretation** : ***VRAI*** si l'interprétation comme four à "pain" est déjà proposée dans la source des données ;  ***FAUX*** s'il existe des doutes quant à l'interprétation comme four à "pain", qu'ils soient émis par le compilateur ou par la source des données (une discussion devrait être menée en ce cas)
- **notes** : champ libre dans lequel des données supplémentaires et des remarques sont proposées
- **nombre** : valeur permettant de pondérer la permanence d'un four. Si la valeur maximale est fixée à ***1***, elle peut être réduite lorsque plusieurs fours distingués à la fouille se superposent au même endroit sans solution de continuité. En ce cas, la valeur est divisée par le nombre de four, éventuellement multipliée par le nombre de soles
- **nombre sole** : indication du nombre de soles superposées dans un même four
- **valeur_ponderee** : nombre de four pondéré par la longueur de l'arc chronologique durant lequel le four est supposé avoir fonctionné. Cette valeur permet de corriger les fortes approximations pouvant caractériser les datations proposées : pour le tracé des courbes d'évolution, elle réduit le poids des fours datés de manière très lâche. Formule appliquée : **`nombre`/ (`DateMax`- `DateMin`)**

## Citation
**Monteix N. 2021** : Les fours à « pain » antiques (Ve s. av. n.è. - Ve s. de n.è.) : données (v. 1.0), _GitHub_ \[URL : [https://github.com/NMonteix/Fours_a_pain_antiques/](https://github.com/NMonteix/Fours_a_pain_antiques/)\].

**[Fichier RIS](https://github.com/NMonteix/Fours_a_pain_antiques/blob/main/fours_donnees.ris)** pour importer la référence.

## Notes de version
### 1.0
Le [fichier](https://github.com/NMonteix/Fours_a_pain_antiques/releases/download/Derniere_version/fours_donnees10.csv) comporte les fours de France, Belgique, Pays-Bas, Luxembourg, Allemagne et Suisse. Principalement fondé sur le dépouillement de [Dolia](dolia.inrap.fr/) et de la bibliographie courante (*Carte archéologique de la Gaule*, *Bilans scientifiques régionaux*, *[Signa romana](https://signaromana.wordpress.com/)*, *Annuaire d’Archéologie Suisse*, etc.), le recensement des fours a été arrêté au 31 décembre 2020.
