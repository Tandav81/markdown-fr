# Titres

Puisque nous avons commencé à écrire un document en Markdown, nous avons besoin d'ajouter un titre et des sous-titres.

Markdown supporte 2 types de titres, Setext et atx.

Les titres Setext-style sont soulignés avec des signes égales (pour le premier niveau de titre) et des tirets (pour le 2e niveau de titre). Par exemple:

```
C'est un titre H1
=================

C'est un titre H2
-----------------
```

Le nombre d'= ou de - n'a pas d'importance, cela fonctionnera.

Les titres Atx-style utilisent 1 à 6 "#" au début d'une ligne, correspondant au niveau du titre à utiliser. Par exemple:

```
# C'est un titre H1

## C'est un titre H2

###### C'est un titre H6
```


On peut fermer la balise "#" mais cela reste optionnelle. Ceci est purement esthétique — vous pouvez l'utiliser si vous trouvez cela plus présentable. Les "#" fermant n'ont même pas besoin d'être aux mêmes nombres que les ouvrantes. (Le nombre de "#" ouvrantes détermine le niveau du titre.) :

```
# C'est un titre H1 #

## C'est un titre H2 ##

### C'est un titre H3 ######
```


---

Voici un quiz sur les titres Markdown.

Sélectionnez le bon titre:
- [x] `# bonjour`
- [ ] `#bonjour`

> Les titres ont besoin d'un espace entre le "#" et le texte.

Sélectionnez le bon titre:
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

> Seulement '=' et '-' sont accéptés pour souligner un texte.

---


