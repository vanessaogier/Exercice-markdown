Qu'est ce que le Markdown?
==========================

Markdown est un langage de balisage léger créé en 2004 par John Gruber avec Aaron Swartz1,2. Son but est d'offrir une syntaxe facile à lire et à écrire. Un document balisé par Markdown peut être lu en l'état sans donner l’impression d'avoir été balisé ou formaté par des instructions particulières.

Un document balisé par Markdown peut être converti en HTML, en PDF ou en autres formats. Bien que la syntaxe Markdown ait été influencée par plusieurs filtres de conversion de texte existants vers HTML — dont Setext3, atx4, Textile, reStructuredText, Grutatext5 et EtText6 —, la source d’inspiration principale est le format du courrier électronique en mode texte. Évolutions

Depuis sa création originelle par Gruber, Markdown n'a pas connu d'évolution notoire de la part de ses auteurs. De plus, ce format n'a jamais été formellement standardisé.

Un certain nombre de variantes ont donc été développées par d'autres, afin de pallier ce qui a été perçu comme des limitations inhérentes à une syntaxe très simplifiée.

À titre d'exemples, on pourra citer MultiMarkdown et GitHub Flavored Markdown7. Ce dernier est utilisé pour les articles et la documentation sur GitHub lui-même, mais a également été largement adopté sur plusieurs éditeurs de texte supportant le format Markdown au niveau de la coloration syntaxique ou de la prévisualisation.

Il existe également des greffons pour de nombreux logiciels populaires, tels que « Markdown Here » pour Firefox et Chrome, et le système de gestion de contenu WordPress intègre désormais quelques éléments de ce langage nativement depuis la version 4.3.

L'initiative Common Mark8 vise à pallier le manque de standardisation et les ambiguïtés du format. Mises en œuvre Plusieurs mises en œuvre existent et ce dans différents langages de programmation : en Perl9, qui reste la mise en œuvre de référence, en PHP10, en Ruby11, en Python12, en Java13, en C#14, en Haskell15, en Gambas, en R16 et même en JavaScript17, notamment avec strapdown.js18. Depuis la version 2.0 de Swift il est aussi possible d'utiliser le Markdown dans ses playgrounds.

Qu'est-ce qu'un environnement de travail optimisé?
==================================================

Dans la plupart des entreprises, la mission essentielle des Ressources humaines a toujours été d’assurer la gestion du personnel, des rémunérations et des avantages, le recrutement et la formation. La qualité de l’environnement de travail et la collaboration n’étaient pas au centre de leurs préoccupations, mais cela évolue. Un nombre croissant de professionnels des RH participent désormais aux décisions portant sur l’environnement de travail (physique et numérique).

Les principaux moteurs de cette évolution sont les suivants :

   * La guerre des talents – les entreprises peinent de plus en plus à recruter des collaborateurs talentueux possédant des compétences très recherchées. Un environnement de travail attractif devient donc un atout important pour recruter, fidéliser et motiver les talents.
   * Le changement de nature du travail – l’essor de l’économie à la tâche se traduit par le développement d’une approche par projet réunissant ponctuellement différents intervenants. Le travail s’effectue ainsi dans un écosystème dynamique non contraint par les limites d’une entité juridique. L’évolution des attentes des collaborateurs – Le numérique offre à certains professionnels la possibilité de travailler partout, entraînant une évolution de la fonction du bureau qui devient avant tout un lieu où rencontrer des clients et collègues et travailler en collaboration. Les salariés cherchent un environnement de travail confortable et stimulant offrant des installations de qualité, à l’image de celles proposées par les espaces de coworking en pleine multiplication.

# Memo :

## La syntaxe Markdown

Quand vous écrivez en Markdown, vous utilisez des notations raccourcies qui sont remplacées par

les balises HTML correspondantes. Nous allons découvrir la plupart de ces notations raccourcies

ici. À chaque fois, je vous indiquerai l'équivalent HTML de la notation Markdown. 

>Commençons par le plus simple, vous pouvez facilement créer des paragraphes en laissant des lignes vides.

>Pour la mise en valeur, autrement dit l'emphase, il vous suffit de mettre des étoiles pour mettre un mot en **gras** et entourer le mot d'underscore pour le mettre en _italique_.

>Il y a différents niveaux de titres : # Titre de niveau 1 - ## Titre de niveau 2 - ### Titre de niveau 3.

### les listes :

La liste ordonnée se crée avec des chiffres :
1. Ordonnée
2. HTML
3. CSS
4. Javascript

La liste désordonnée se crée avec des étoiles * :
* Désordonnée
* Photoshop
* Indesign
* Illustrator

>Elles peuvent aussi s'imbriquer:

* Une puce !
* Une autre puce !
	* Encore une puce !
	* Et encore une autre !	

>Pour créer une citation, vous devez précéder les lignes citées d'un ">".Voici une citation.

>Pour créer un lien, vous devez placer le texte du lien entre crochets suivis de l'URL entre parenthèses :

```Markdown
[Nom du site cible](url du site cible)
```
exemple : ```[Becode](https://www.facebook.com/becode.org/)``` cela vous donnera la page Facebook de BeCode [Becode](https://www.facebook.com/becode.org/)

>Pour intégrer une image, on utilise la même technique pour les liens sans oublier le point d'exclamation devant les crochets "!" :

```Markdown
![Nom de l'image cible](url de l'emplacement de l'image)
```
exemple : ```![Logo Becode](https://pbs.twimg.com/profile_images/976503221689692161/8s0PJ9xs_400x400.jpg)``` vous donnera:


 ![Logo Becode|400x400,20%](https://pbs.twimg.com/profile_images/976503221689692161/8s0PJ9xs_400x400.jpg)

Pour inssérer un gif
====================

l'inssertion d'un gif se compose de:

(de la valeur: ! [alt Text])

(de lien: https://media.giphy.com/media/zXmbOaTpbY6mA/giphy.gif)

on ajoute les deux et...

![Alt Text](https://media.giphy.com/media/zXmbOaTpbY6mA/giphy.gif)

Les coloration syntaxique
=========================

Une coloration syntaxique se compose de plusieurs partie:

(la valeur: script)

(le type de valeur: type="text/javascript")

(le nom: alert("Julien Cassanra Vannessa");


avec coloration
===============

```javascript
<script type="text/javascript">
    alert("Julien Cassanra Vannessa");
</script>
```
sans coloration
===============

```
<script type="text/javascript">
    alert("Julien Cassanra Vannessa");
</script>
```










