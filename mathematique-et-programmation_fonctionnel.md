# Mathématique et programmation fonctionnel

## Mathématique

### Structures algébriques

Un *ensemble* c'est un grand "sac" contenant des éléments.

Une *structure*, c'est rajouté quelque chose en plus pour structurer notre ensemble. Une *structure algébrique* est le fait que l'on va rajouter **une ou plusieurs** opérations.

#### Propriétés des opérations

Ces opérations sont normalement appelées **lois de composition interne**.
(Interne car nous restons toujours dans le même ensemble après une composition, et composition  parceque nous composons **deux** éléments ensemble pour en faire un troisième.)

commutativité

<p align="center">
  <img src="http://chart.apis.google.com/chart?cht=tx&chl=\forall{x,y}\in\mathbb{E},x\ast%20y=y\ast%20x"/>
</p>
	
associativité

	∀x,y,z ∈ E,  (x * y) * z = x * (y * z)
	
élément neutre
	
	e ∈ E, ∀x  x * e = e * x = e

#### Les Magmas

C'est un ensemble quelconque avec une opération quelconque. C'est le minimum de ce que l'on peut faire avec une structure algébrique.

	Magma(E, *)
	
Pour dénifir une opération, nous pouvons définir une table (comme pour les tables de multiplications).

#### Les Monoïdes

Un monoïde est un magma associatif et unifère (qui admet un élément neutre).

Résumé

Pour (M, *)

la loi * est interne

la loi * est associative 

Il y a un élement neutre e

Exemple 

	(N, +) --> entiers naturels
	
Composition de fonction
	
	(R^R, ∘) f: x -> 2x, g: x ->x^2. f∘g = 2x^2 (d'abord on applique g puis f).
	
L'élément neutre étant la fonction identité (Id)

	f: x -> x

On dit qu'un élément a ∈ E est **simplifiable** si à chaque fois qu'on a 

	a * x = a * y

on peut en déduire que 

	x = y
	
On dit qu'un élément a ∈ E est **symétrisable** s'il existe un autre élément _a ∈ E tel que  

	a * _a = _a * a = e

_a est appelé le symétrique de a.

###### Théorème

Si a ∈ E est symétrisable alors il est simplifiable.

#### Les Groupes

Un group G est un monoïde avec une rêgle supplémentaire tel que : Tout élément de G a un symétrique

	∀x ∈ G, ∃x' ∈ G,  x * x' = x' * x = e
	
###### Théorème

Dans un groupe fini, si on compose un certain nombre de fois un élément avec lui-même, on finit par tomber sur l'élément neutre

#### Les anneaux

	(A, +, x)
	
(A, +) est un groupe

(A, x) est un monoïde

#### Lectures

[Vidéos sur les structures](https://www.youtube.com/watch?v=RaqlxOihGxw&list=PLNefH6S6myiMFlgsEIGHb8KZaLKE2eAZQ&index=1)

### Théorie des ensembles

### [Théorie des catégories](https://fr.wikipedia.org/wiki/Th%C3%A9orie_des_cat%C3%A9gories)



#### Lectures

[PDF](http://sma.epfl.ch/~dzaganid/TP_Categories.pdf)

[Application](https://fr.wikipedia.org/wiki/Application_(math%C3%A9matiques))

[Théorie des catégories](https://fr.wikipedia.org/wiki/Th%C3%A9orie_des_cat%C3%A9gories)

