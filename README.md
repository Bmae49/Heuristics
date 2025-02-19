---

**Contexte :**  
Un groupe textile spécialisé dans la production de tee-shirts souhaite lancer une opération promotionnelle à l’occasion des soldes afin d’écouler ses stocks. L’entreprise dispose d’un parc d’articles (tee-shirts) invendus qu’elle cherche à valoriser en les regroupant par lots. Chaque article est caractérisé par :  
- Un nombre d’exemplaires disponibles,  
- Un indice commercial reflétant sa « côte » auprès du public (lié à son style),  
- Un prix de vente unitaire.  

Pour simplifier, on considère que tous les tee-shirts concernés sont d’une taille unique. Ces articles doivent être regroupés en lots dans une unité de conditionnement avant d’être expédiés par messagerie vers des magasins de détail.  

**Contraintes :**  
Pour des raisons commerciales, le nombre de types de lots distincts ne peut pas dépasser un seuil fixé. Chaque type de lot, pour être éligible, doit satisfaire les contraintes suivantes :  
- Les articles constituant un lot doivent tous être distincts,  
- Un nombre minimal et maximal d’articles doit être respecté pour la constitution d’un lot,  
- L’indice commercial d’un lot doit être supérieur à un seuil fixé. L’indice d’un lot est la somme des indices des articles qui le composent,  
- Le prix de vente d’un lot correspond à la somme des prix de vente unitaires des articles qui le constituent, à laquelle s’ajoute un coût fixe de conditionnement.  

**Objectif :**  
L’objectif est de maximiser le profit net généré par la vente de ces lots. Le profit net de l’opération s’exprime comme la différence entre le prix de vente total sur l’ensemble des lots (potentiellement) vendus (c’est-à-dire les lots de chaque type constitués sur la base du parc d’articles disponibles) et le coût total généré par le conditionnement de ces lots.  

**Unité de conditionnement :**  
L’unité de conditionnement est constituée de 10 postes de travail. Le conditionnement consiste, pour un lot donné, à :  
1. Collecter les articles qui le composent,  
2. Les packager,  
3. Y apposer des données publicitaires et commerciales au moyen de stickers.  

Chaque poste de travail possède une capacité limitée sur l’horizon considéré (une semaine), exprimée en nombre de lots traités pondéré par la taille de ces lots. On peut supposer que la capacité de travail cumulée de l’unité de conditionnement est suffisante pour satisfaire toute campagne commerciale.  

**Problématique :**  
La problématique consiste à déterminer, sur la base du parc d’articles disponibles sur l’horizon considéré :  
- Les types de lots à constituer (en nombre et en composition),  
- La répartition du conditionnement sur les différents postes de travail,  
Dans l’objectif de dégager un profit net maximal.  

---
