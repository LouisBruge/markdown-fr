# Titres 

Lorsque l'on commence à rédiger un document markdown, nous avons besoin d'ajouter un titre et des sous-titres

Markdown supports two styles of headers, Setext and atx.
Le langage markdown support deux styles de titre, Setext et atx.

Les titres de type Setext sont "soulignés" avec des signes égal (pour le premier niveau de titre) et des tirets (pour le second niveau de titre. Par exemple:


```
Ceci est un H1
=============

Ceci est un H2
-------------
```

Peu importe le nombre de = ou de -, ça fonctionne toujours

Les titres de type axt utilise 1-6 caractères dièses au début de la ligne, correspondant au niveau des titres 1-6. Par exemple:

```
# C'est un H1 

## C'est un H2

###### C'est un H6
```


De manière optionnel, vous pouver "fermer" les titres de type atx. C'est purement esthétique - vous pouvez l'utiliser si vous trouvez ça plus joli. Les dièses de fin n'ont jamais besoin de correspondre au nombre de dièses employés pour ouvrir le titre. (Le nombre de dièses ouvrants détermine le niveau du titre.):

```
# C'est un H1 #

## C'est un H2 ##

### C'est un H3 ###
```


---

Un quiz à propos des titres markdown.

Selectionne le titre valide:
- [x] `# bonjour`
- [ ] `#bonjour`

> Les titres ont besoin d'un espace entre le texte et le caractère dièse;

Selectionne le titre valide
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seul '=' et '-' sont accepted pour souligner un titre.

---


