---
layout: post
title: Transmission de données entre pages
---

Vous réaliserez les exercices dans un dossier nommé `transmission-donnees`.

Le résultat obtenu dans le navigateur doit toujours être une page conforme au standard HTML5 (balises <html>, <head> et <body> présentes et correctement imbriquées).

## Exercice 1

Ecrivez la page `employes.php` affichant une liste de 3 employés avec un lien vers leurs détails. Ce lien doit pointer vers une URL de la forme `employe.php?id=<identifiant>`, le paramètre `<identifiant>` valant 1, 2 ou 3.

![](../assets/transmission-donnees/employes.png)
{:.centered}

Ecrivez ensuite la page `employe.php` qui affiche l'identifiant de l'employé reçu en paramètre dans l'URL.

![](../assets/transmission-donnees/employe-1.png)
{:.centered}

Le cas où aucun identifiant n'est fourni doit être géré.

![](../assets/transmission-donnees/employe-2.png)
{:.centered}

**Bonus** : écrivez la page `employes-bis.php` dans laquelle la liste des employés est générée par une boucle. Le nombre d'employés est passé en paramètre dans l'URL, exemple : `employes.php?nombre=8`.

![](../assets/transmission-donnees/employes-bis-1.png)
{:.centered}

Le cas où aucun nombre n'est fourni doit être géré.

![](../assets/transmission-donnees/employes-bis-2.png)
{:.centered}
