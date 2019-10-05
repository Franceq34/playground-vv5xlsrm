# Variables & Assignation

?[Quel est le résultat ?]
-[ ] 1
-[ ] 2
-[ ] 3
-[X] 4

```python runnable

a = 1
b = 2
c = 3
print(a+c)
    
```

# 


?[Quel est le résultat ?]
-[ ] 1
-[X] 2
-[ ] 3
-[ ] 4

```python runnable

a = 1
b = 2
c = a
b = a
print(a+c)
    
```

# 

?[Quel est le résultat ?]
-[ ] 1
-[ ] 2
-[X] 3
-[ ] 4

```python runnable

a = 1
b = 2
c = a + b
a = b
c = c - a
print(a+c)
    
```

?[Quel message va s'afficher ?]
-[ ] Bonjour Hello
-[ ] Hello Bonjour
-[X] Hello
-[ ] Bonjour

```python runnable

def message():
    print("Bonjour")
    
print("Hello")
    
```

Quel message va s'afficher ?

```python runnable

msg = "c'est moi !"

print("Hello " + msg)
    
```


?[Quel est le résultat ?]
-[ ] 1
-[ ] 2
-[X] 3

```python runnable

a = 1
b = 2

def somme(a, b):
    return a+b

print(somme(a, b))
    
```

# Listes

- Créer une liste vide
- Ajouter trois éléments à cette liste
- Afficher le deuxième élément

```python runnable


```

- Créer une liste vide
- Ajouter deux éléments à cette liste
- Modifier le deuxième élément

```python runnable


```

- Créer une liste de 3 éléments
- Afficher le deuxième et troisième élément
(indice : afficher à partir du deuxième élément)

```python runnable

```

```

Listes en compréhension


```python runnable

list=[x for x in range(10)]
print(list)

```

- Créer une liste de 10 éléments
- Afficher sa taille
- retourner la liste


```python runnable


```

#Boucles

FOR

Qu'affiche ce code ?

```python runnable

for i in range(1,3) :
    print(i)

```

Qu'affiche ce code ?
(indice : str() transforme son paramètre en chaine de caractère pour permettre la concaténation)

```python runnable

for i in range(1,4) :
    print("Et "+str(i)+"!")
    
print("Zéro!")

```

En utilisant une boucle for écrire un programme qui crée la liste des 10 premiers entiers strictements positifs.
Puis, par compréhension de liste, compléter le programme afin qu'il crée une liste de 10 nombres entiers aléatoires compris entre 1 et 6 inclus.
(indice : module random)

```python runnable


```


