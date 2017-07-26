---
layout: post
title: "Premier Poste"
quote: "On va voir ce que l'on peux faire ^^."
image:
      url: /media/2014-02-27-hello-cosette/cover.jpg
video: false
comments: true
theme_color: 302F2D
---

# Titre Principal

Ceci est un simple texte. 
_ceci est un texte en italique_.

Pour inclure une image avec/sans commentaire: 
{% include image.html url="/media/2014-02-27-hello-cosette/cosette.jpg" width="100%" description="Amanda Seyfried as Cosette on the 2012 movie." %}


## Menu

### Sous Menu

#### Sous sous Menu

vous pouvez mettre en avant du code avec :  `code`. 

On peux aussi ajouter un petit asterix  `_config.yml`[^1].

Pour les liens [c'est comme ceci](http://hahaha)

Mettre un texte en evidence avec : 
> Thinny 2.1 is already [available for download on GitHub](https://github.com/camporez/Thinny/releases).


On peux regrouper le code
~~~
  - icon:   [the genericon name for the social network]
    url:    [the url to follow]
    desc:   [a small description for the link (e.g. "Follow me on twitter")]
~~~


Exemple de liste:

- the site `title`, `description`, `icon` and default `cover` image.
- text of the `copyright` message.
- the number of posts per page (`paginate`).
- the `permalink`'s structure (see [the docs](http://jekyllrb.com/docs/pagination/)).


Exemple de tableau:

|----
| Version | Codename | Platform | Release date
|:-:|:-:|:-:|:-:
| [0.3](https://github.com/camporez/Thinny/releases/tag/v0.3-alexandra) | [Alexandra](http://nikita2010.wikia.com/wiki/Alexandra_Udinov) | Ghost 0.3.x |November 2013
| [2.0](https://github.com/camporez/Thinny/releases/tag/v2.0-bianca) | [Bianca](http://memoriaglobo.globo.com/programas/entretenimento/novelas/caras-bocas/caras-bocas-bianca-isabelle-drummond.htm) | Jekyll | January 2014 |
| [2.1](https://github.com/camporez/Thinny/releases/tag/v2.1-cosette) | [Cosette](http://lesmiserables.wikia.com/wiki/Cosette) | Jekyll | February 2014
| 2.2 | [Dolores](http://en.wikipedia.org/wiki/Dolores_Haze) | Jekyll | _Soon..._[^2]
|----



-----
On separe les asterix en pied de page

[^1]: This file is placed in your root directory. It's the main file of configuration. For more information, read [the docs](http://jekyllrb.com/docs/configuration/).
[^2]: See the [issues list](https://github.com/camporez/camporez.github.io/issues?milestone=3).
