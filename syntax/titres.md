# Titles
Quand on commence à écrire un document markdown, on a besoin d'ajouter un titre et des sous-titres.

Markdown a deux types de titres: Setext and atx.

Les titres Setext-style sont soulignés en utilisant le signe "égal" (pour les titres les plus importants) and tirets (pour les titres de second niveau). 

Par exemple

```
C'est un H1
=============

C'est un H2
-------------
```

N'importe quel nombre de signes = or - convient.

Les titres Atx-style utilisent 1-6 caractères "#" en début de ligne, qui corresponf la la taille 1-6 du titre. 
Par exemple:

```
# C'est un titre H1

## C'est un titre H2

###### C'est un titre H6
```


Optionnellement, vous pouvez "encadrer" les titres atx-style. C'est uniquement esthétique, vous pouvez le faire si vous trouvez ça mieux.
Le nombre de dièse à la fin, n'a pas d'importance. (C'est le nombre de dièse du début qui détermine le niveau de titre.) :

```
# C'est un H1 #

## C'est un H2 ##

### C'est un H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
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

> Only '=' and '-' are accepted for underlining an header.

---


