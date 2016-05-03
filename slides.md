% title: Flæg
% subtitle: Une librairie Go pour créer une interface en ligne de commande
% author: Martin Piegay
% author: Journée Team Building
% thankyou: Thanks you!
% contact: <a href="https://twitter.com/">@Martouf42</a>
% contact: <span>github</span> <a href="http://github.com">cocap10</a>
% favicon: figures/golang.icon.png
---
title: /WhoamI : Martin Piegay

 En stage à l'agence Lyonnaise depuis Mars <img src=figures/zenika.icon.jpg />
 
 Mais je suis Stéphanois (et je le vie bien)
 
 Je viens de l'école d'ingé Télécom St-Etienne <img src=figures/tse.icon.png />
 
 Formation info & réseau
 
 J'ai passé les 6 derniers mois en Erasmus à Prague <img src=figures/beer.icon.png />

---
title: Flæg : Build CLI & Load Configuration
class: img-top-center

<img src=figures/flaeg.logo.png />
---
title: Flæg : What is it ?

Une librairie pour le langage <a href="https://golang.org/">Go</a> <img src=figures/golang.icon.png />
 
Génère une interface en ligne de commande <img src=figures/cli.icon.png />

Initialise la structure de configuration avec les arguments

C'est open source, sur <a href="http://github.com/containous/flaeg">github</a> :)

---
title: Go lang

Langage open source crée en 2010 par Google

Syntaxe simple et efficace :

```
func main(){
  fmt.Println("Hello, 世界")
}
```

Compilation de 80 % à 90 % plus rapide que en C

Tout les dépendances sont intégrées dans le binaire

Langage jeune : Encore assez peu de librairie

17/02/2016 : Version 1.6

---
title: Flæg : Why is it better ?

Tout est dynamique, le développeur Go n'a presque rien à faire !

`[--flag=flag_argument]` : Utilise le nom des champs de la structure de configuration
 
Utilise la réflectivité pour initialiser les champs la structure de configuration

C'est générique, le développeur Go peux ajouter des Parsers sur ses objets complexes

C'est personnalisable, il suffit d'ajouter un tag pour changer le nom des flags

---
title: Træfik : A modern reverse-proxy
class: img-top-center

<img src=figures/traefik.logo.png />
---
title: Træfik : Emile Vauge

Emile est un ancien Consultant & Formateur Zenika <img src=figures/zenika.icon.jpg />

Il est certifié Docker formateur <img src=figures/docker.icon.png />

Depuis Septembre 2015 il développe le Reverse-proxy/Load-balancer Traefik en Go

En Février 2016, il a quitté Zenika pour monter la zStartup <a href="https://containo.us/">Containous</a> <img src=figures/containous.icon.png />

Il se consacre exclusivement au développement de  <a href="https://traefik.io/">Træfik</a> <img src=figures/traefik.icon.png />

---
title:  Reverse-proxy/Load-balancer :
class: img-top-center

<img height=500 src=figures/traditionnalArchitecture.png />
---
title: Træfik : Why is it better ?
class: img-top-center

<img height=500 src=figures/traefikArchitecture.svg />
---
title: Træfik : Success story
class: img-top-center

<img height=400 src=figures/docker.image.png /> 
<img height=100 src=figures/traefik.stars.svg />
---
title: Træfik : Old CLI
class: img-top-center

<a href="https://github.com/containous/traefik/blob/master/cmd.go"><img height=500 src=figures/traefikOldCli.png /></a>
---
title: Træfik using Flæg
class: img-top-center

<a href="https://github.com/cocap10/traefik/blob/migrate-to-flaeg/configuration.go"><img height=500 src=figures/traefikFlaegCli.png /></a>
---



