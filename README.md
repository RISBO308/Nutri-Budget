# Nutri-Budget
nutribudget est une application mobile et web qui aide les ménages camerounais à mieux gérer leur budget alimentaire tout en améliorant la qualité nutritionnelle de leurs repas.
ANGULAR TALENT LAB 2026
0. En-tête du document

Projet : NutriBudget Cameroun — Manger mieux sans dépenser plus

Auteur : Boris Dorine

Type : Projet individuel

Version : v1.0

Date : Juin 2026

Formateur référent : À compléter

1. Présentation et contexte

Le Cameroun connaît une hausse progressive du coût de la vie et des dépenses alimentaires. De nombreux ménages consacrent une grande partie de leurs revenus à l'alimentation sans disposer d'outils simples pour planifier leurs achats et équilibrer leurs repas.

Par ailleurs, plusieurs aliments locaux nutritifs restent sous-utilisés alors qu'ils sont souvent plus abordables que certains produits importés.

NutriBudget Cameroun est une application web qui aide les ménages à construire des menus équilibrés à partir de leur budget disponible tout en valorisant les produits agricoles locaux.

2. Problème et objectifs
Problème

Les ménages camerounais ont des difficultés à gérer efficacement leur budget alimentaire et à composer des repas équilibrés malgré la disponibilité d'aliments locaux nutritifs.

Cette situation entraîne des dépenses inutiles, des déséquilibres nutritionnels et parfois du gaspillage alimentaire.

Objectif principal

Permettre à un ménage de générer un plan alimentaire adapté à son budget en moins de trois clics.

Objectifs secondaires
Réduire les dépenses alimentaires inutiles.
Encourager la consommation d'aliments locaux nutritifs.
Aider les ménages à mieux planifier leurs repas hebdomadaires.
3. Périmètre du projet
Inclus	Exclu
Gestion du budget alimentaire	Paiement en ligne
Génération automatique de menus	Livraison de produits
Conseils nutritionnels	Marketplace agricole
Consultation hors connexion partielle	Application mobile native
Calcul du coût des repas	Intelligence artificielle avancée
4. Utilisateurs cibles (Personas)
Ménage urbain
Famille de 4 à 6 personnes.
Budget alimentaire limité.
Utilise un smartphone Android.

Besoin :

Savoir quoi acheter avec son budget.
Étudiant
Vit seul.
Petit budget.

Besoin :

Trouver des repas économiques et équilibrés.
Jeune travailleur
Revenu modeste.
Peu de temps pour planifier.

Besoin :

Organiser rapidement ses repas.
5. Fonctionnalités (Méthode MoSCoW)
MUST (MVP)
Saisir son budget.
Saisir le nombre de personnes.
Générer automatiquement un menu.
Afficher le coût estimatif.
Afficher les informations nutritionnelles.
SHOULD
Rechercher des aliments.
Filtrer selon le budget.
COULD
Favoris.
Partage WhatsApp.
Historique des menus.
WON'T
Vente de produits.
Paiement en ligne.
Géolocalisation des marchés.
6. User Stories
En tant que parent, je veux saisir mon budget afin d'obtenir un menu adapté à mes moyens.
En tant qu'étudiant, je veux connaître les aliments les moins coûteux afin de réduire mes dépenses.
En tant qu'utilisateur, je veux voir la valeur nutritionnelle de mon menu afin d'améliorer mon alimentation.
7. Arborescence et écrans
Accueil
Présentation de l'application.
Bouton commencer.
Budget
Saisie du budget.
Nombre de personnes.
Résultat
Menu généré.
Coût estimé.
Nutrition
Analyse nutritionnelle.
Conseils
Astuces anti-gaspillage.
Navigation

Accueil
↓
Budget
↓
Résultat
↓
Nutrition
↓
Conseils

8. Modèle de données
Aliment
id
nom
catégorie
prix
protéines
glucides
vitamines
Menu
id
jour
alimentId
coût
Utilisateur
id
budget
nombrePersonnes
9. Parcours utilisateur principal
L'utilisateur ouvre l'application.
Il saisit son budget.
Il indique le nombre de personnes.
Il clique sur "Générer".
L'application crée un menu adapté.
Il consulte le coût total.
Il consulte les informations nutritionnelles.
10. Spécifications techniques
Framework : Angular 20
Langage : TypeScript
Style : SCSS + Angular Material
Stockage : fichier JSON local (v1)
Authentification : non nécessaire
Hébergement : GitHub Pages ou Vercel
11. Exigences non fonctionnelles
Connectivité
Fonctionnement avec faible connexion internet.
Responsive
Compatible smartphone et ordinateur.
Performance
Chargement inférieur à 3 secondes.
Accessibilité
Interface lisible.
Contraste élevé.
Sécurité
Aucune donnée sensible stockée.ANGULAR TALENT LAB 2026
0. En-tête du document

Projet : NutriBudget Cameroun — Manger mieux sans dépenser plus

Auteur : Boris Dorine

Type : Projet individuel

Version : v1.0

Date : Juin 2026

Formateur référent : À compléter

1. Présentation et contexte

Le Cameroun connaît une hausse progressive du coût de la vie et des dépenses alimentaires. De nombreux ménages consacrent une grande partie de leurs revenus à l'alimentation sans disposer d'outils simples pour planifier leurs achats et équilibrer leurs repas.

Par ailleurs, plusieurs aliments locaux nutritifs restent sous-utilisés alors qu'ils sont souvent plus abordables que certains produits importés.

NutriBudget Cameroun est une application web qui aide les ménages à construire des menus équilibrés à partir de leur budget disponible tout en valorisant les produits agricoles locaux.

2. Problème et objectifs
Problème

Les ménages camerounais ont des difficultés à gérer efficacement leur budget alimentaire et à composer des repas équilibrés malgré la disponibilité d'aliments locaux nutritifs.

Cette situation entraîne des dépenses inutiles, des déséquilibres nutritionnels et parfois du gaspillage alimentaire.

Objectif principal

Permettre à un ménage de générer un plan alimentaire adapté à son budget en moins de trois clics.

Objectifs secondaires
Réduire les dépenses alimentaires inutiles.
Encourager la consommation d'aliments locaux nutritifs.
Aider les ménages à mieux planifier leurs repas hebdomadaires.
3. Périmètre du projet
Inclus	Exclu
Gestion du budget alimentaire	Paiement en ligne
Génération automatique de menus	Livraison de produits
Conseils nutritionnels	Marketplace agricole
Consultation hors connexion partielle	Application mobile native
Calcul du coût des repas	Intelligence artificielle avancée
4. Utilisateurs cibles (Personas)
Ménage urbain
Famille de 4 à 6 personnes.
Budget alimentaire limité.
Utilise un smartphone Android.

Besoin :

Savoir quoi acheter avec son budget.
Étudiant
Vit seul.
Petit budget.

Besoin :

Trouver des repas économiques et équilibrés.
Jeune travailleur
Revenu modeste.
Peu de temps pour planifier.

Besoin :

Organiser rapidement ses repas.
5. Fonctionnalités (Méthode MoSCoW)
MUST (MVP)
Saisir son budget.
Saisir le nombre de personnes.
Générer automatiquement un menu.
Afficher le coût estimatif.
Afficher les informations nutritionnelles.
SHOULD
Rechercher des aliments.
Filtrer selon le budget.
COULD
Favoris.
Partage WhatsApp.
Historique des menus.
WON'T
Vente de produits.
Paiement en ligne.
Géolocalisation des marchés.
6. User Stories
En tant que parent, je veux saisir mon budget afin d'obtenir un menu adapté à mes moyens.
En tant qu'étudiant, je veux connaître les aliments les moins coûteux afin de réduire mes dépenses.
En tant qu'utilisateur, je veux voir la valeur nutritionnelle de mon menu afin d'améliorer mon alimentation.
7. Arborescence et écrans
Accueil
Présentation de l'application.
Bouton commencer.
Budget
Saisie du budget.
Nombre de personnes.
Résultat
Menu généré.
Coût estimé.
Nutrition
Analyse nutritionnelle.
Conseils
Astuces anti-gaspillage.
Navigation

Accueil
↓
Budget
↓
Résultat
↓
Nutrition
↓
Conseils

8. Modèle de données
Aliment
id
nom
catégorie
prix
protéines
glucides
vitamines
Menu
id
jour
alimentId
coût
Utilisateur
id
budget
nombrePersonnes
9. Parcours utilisateur principal
L'utilisateur ouvre l'application.
Il saisit son budget.
Il indique le nombre de personnes.
Il clique sur "Générer".
L'application crée un menu adapté.
Il consulte le coût total.
Il consulte les informations nutritionnelles.
10. Spécifications techniques
Framework : Angular 20
Langage : TypeScript
Style : SCSS + Angular Material
Stockage : fichier JSON local (v1)
Authentification : non nécessaire
Hébergement : GitHub Pages ou Vercel
11. Exigences non fonctionnelles
Connectivité
Fonctionnement avec faible connexion internet.
Responsive
Compatible smartphone et ordinateur.
Performance
Chargement inférieur à 3 secondes.
Accessibilité
Interface lisible.
Contraste élevé.
Sécurité
Aucune donnée sensible stockée.ANGULAR TALENT LAB 2026
0. En-tête du document

Projet : NutriBudget Cameroun — Manger mieux sans dépenser plus

Auteur : Boris Dorine

Type : Projet individuel

Version : v1.0

Date : Juin 2026

Formateur référent : À compléter

1. Présentation et contexte

Le Cameroun connaît une hausse progressive du coût de la vie et des dépenses alimentaires. De nombreux ménages consacrent une grande partie de leurs revenus à l'alimentation sans disposer d'outils simples pour planifier leurs achats et équilibrer leurs repas.

Par ailleurs, plusieurs aliments locaux nutritifs restent sous-utilisés alors qu'ils sont souvent plus abordables que certains produits importés.

NutriBudget Cameroun est une application web qui aide les ménages à construire des menus équilibrés à partir de leur budget disponible tout en valorisant les produits agricoles locaux.

2. Problème et objectifs
Problème

Les ménages camerounais ont des difficultés à gérer efficacement leur budget alimentaire et à composer des repas équilibrés malgré la disponibilité d'aliments locaux nutritifs.

Cette situation entraîne des dépenses inutiles, des déséquilibres nutritionnels et parfois du gaspillage alimentaire.

Objectif principal

Permettre à un ménage de générer un plan alimentaire adapté à son budget en moins de trois clics.

Objectifs secondaires
Réduire les dépenses alimentaires inutiles.
Encourager la consommation d'aliments locaux nutritifs.
Aider les ménages à mieux planifier leurs repas hebdomadaires.
3. Périmètre du projet
Inclus	Exclu
Gestion du budget alimentaire	Paiement en ligne
Génération automatique de menus	Livraison de produits
Conseils nutritionnels	Marketplace agricole
Consultation hors connexion partielle	Application mobile native
Calcul du coût des repas	Intelligence artificielle avancée
4. Utilisateurs cibles (Personas)
Ménage urbain
Famille de 4 à 6 personnes.
Budget alimentaire limité.
Utilise un smartphone Android.

Besoin :

Savoir quoi acheter avec son budget.
Étudiant
Vit seul.
Petit budget.

Besoin :

Trouver des repas économiques et équilibrés.
Jeune travailleur
Revenu modeste.
Peu de temps pour planifier.

Besoin :

Organiser rapidement ses repas.
5. Fonctionnalités (Méthode MoSCoW)
MUST (MVP)
Saisir son budget.
Saisir le nombre de personnes.
Générer automatiquement un menu.
Afficher le coût estimatif.
Afficher les informations nutritionnelles.
SHOULD
Rechercher des aliments.
Filtrer selon le budget.
COULD
Favoris.
Partage WhatsApp.
Historique des menus.
WON'T
Vente de produits.
Paiement en ligne.
Géolocalisation des marchés.
6. User Stories
En tant que parent, je veux saisir mon budget afin d'obtenir un menu adapté à mes moyens.
En tant qu'étudiant, je veux connaître les aliments les moins coûteux afin de réduire mes dépenses.
En tant qu'utilisateur, je veux voir la valeur nutritionnelle de mon menu afin d'améliorer mon alimentation.
7. Arborescence et écrans
Accueil
Présentation de l'application.
Bouton commencer.
Budget
Saisie du budget.
Nombre de personnes.
Résultat
Menu généré.
Coût estimé.
Nutrition
Analyse nutritionnelle.
Conseils
Astuces anti-gaspillage.
Navigation

Accueil
↓
Budget
↓
Résultat
↓
Nutrition
↓
Conseils

8. Modèle de données
Aliment
id
nom
catégorie
prix
protéines
glucides
vitamines
Menu
id
jour
alimentId
coût
Utilisateur
id
budget
nombrePersonnes
9. Parcours utilisateur principal
L'utilisateur ouvre l'application.
Il saisit son budget.
Il indique le nombre de personnes.
Il clique sur "Générer".
L'application crée un menu adapté.
Il consulte le coût total.
Il consulte les informations nutritionnelles.
10. Spécifications techniques
Framework : Angular 20
Langage : TypeScript
Style : SCSS + Angular Material
Stockage : fichier JSON local (v1)
Authentification : non nécessaire
Hébergement : GitHub Pages ou Vercel
11. Exigences non fonctionnelles
Connectivité
Fonctionnement avec faible connexion internet.
Responsive
Compatible smartphone et ordinateur.
Performance
Chargement inférieur à 3 secondes.
Accessibilité
Interface lisible.
Contraste élevé.
Sécurité
Aucune donnée sensible stockée.ANGULAR TALENT LAB 2026
0. En-tête du document

Projet : NutriBudget Cameroun — Manger mieux sans dépenser plus

Auteur : Boris Dorine

Type : Projet individuel

Version : v1.0

Date : Juin 2026

Formateur référent : À compléter

1. Présentation et contexte

Le Cameroun connaît une hausse progressive du coût de la vie et des dépenses alimentaires. De nombreux ménages consacrent une grande partie de leurs revenus à l'alimentation sans disposer d'outils simples pour planifier leurs achats et équilibrer leurs repas.

Par ailleurs, plusieurs aliments locaux nutritifs restent sous-utilisés alors qu'ils sont souvent plus abordables que certains produits importés.

NutriBudget Cameroun est une application web qui aide les ménages à construire des menus équilibrés à partir de leur budget disponible tout en valorisant les produits agricoles locaux.

2. Problème et objectifs
Problème

Les ménages camerounais ont des difficultés à gérer efficacement leur budget alimentaire et à composer des repas équilibrés malgré la disponibilité d'aliments locaux nutritifs.

Cette situation entraîne des dépenses inutiles, des déséquilibres nutritionnels et parfois du gaspillage alimentaire.

Objectif principal

Permettre à un ménage de générer un plan alimentaire adapté à son budget en moins de trois clics.

Objectifs secondaires
Réduire les dépenses alimentaires inutiles.
Encourager la consommation d'aliments locaux nutritifs.
Aider les ménages à mieux planifier leurs repas hebdomadaires.
3. Périmètre du projet
Inclus	Exclu
Gestion du budget alimentaire	Paiement en ligne
Génération automatique de menus	Livraison de produits
Conseils nutritionnels	Marketplace agricole
Consultation hors connexion partielle	Application mobile native
Calcul du coût des repas	Intelligence artificielle avancée
4. Utilisateurs cibles (Personas)
Ménage urbain
Famille de 4 à 6 personnes.
Budget alimentaire limité.
Utilise un smartphone Android.

Besoin :

Savoir quoi acheter avec son budget.
Étudiant
Vit seul.
Petit budget.

Besoin :

Trouver des repas économiques et équilibrés.
Jeune travailleur
Revenu modeste.
Peu de temps pour planifier.

Besoin :

Organiser rapidement ses repas.
5. Fonctionnalités (Méthode MoSCoW)
MUST (MVP)
Saisir son budget.
Saisir le nombre de personnes.
Générer automatiquement un menu.
Afficher le coût estimatif.
Afficher les informations nutritionnelles.
SHOULD
Rechercher des aliments.
Filtrer selon le budget.
COULD
Favoris.
Partage WhatsApp.
Historique des menus.
WON'T
Vente de produits.
Paiement en ligne.
Géolocalisation des marchés.
6. User Stories
En tant que parent, je veux saisir mon budget afin d'obtenir un menu adapté à mes moyens.
En tant qu'étudiant, je veux connaître les aliments les moins coûteux afin de réduire mes dépenses.
En tant qu'utilisateur, je veux voir la valeur nutritionnelle de mon menu afin d'améliorer mon alimentation.
7. Arborescence et écrans
Accueil
Présentation de l'application.
Bouton commencer.
Budget
Saisie du budget.
Nombre de personnes.
Résultat
Menu généré.
Coût estimé.
Nutrition
Analyse nutritionnelle.
Conseils
Astuces anti-gaspillage.
Navigation

Accueil
↓
Budget
↓
Résultat
↓
Nutrition
↓
Conseils

8. Modèle de données
Aliment
id
nom
catégorie
prix
protéines
glucides
vitamines
Menu
id
jour
alimentId
coût
Utilisateur
id
budget
nombrePersonnes
9. Parcours utilisateur principal
L'utilisateur ouvre l'application.
Il saisit son budget.
Il indique le nombre de personnes.
Il clique sur "Générer".
L'application crée un menu adapté.
Il consulte le coût total.
Il consulte les informations nutritionnelles.
10. Spécifications techniques
Framework : Angular 20
Langage : TypeScript
Style : SCSS + Angular Material
Stockage : fichier JSON local (v1)
Authentification : non nécessaire
Hébergement : GitHub Pages ou Vercel
11. Exigences non fonctionnelles
Connectivité
Fonctionnement avec faible connexion internet.
Responsive
Compatible smartphone et ordinateur.
Performance
Chargement inférieur à 3 secondes.
Accessibilité
Interface lisible.
Contraste élevé.
Sécurité
Aucune donnée sensible stockée.ANGULAR TALENT LAB 2026
0. En-tête du document

Projet : NutriBudget Cameroun — Manger mieux sans dépenser plus

Auteur : Boris Dorine

Type : Projet individuel

Version : v1.0

Date : Juin 2026

Formateur référent : À compléter

1. Présentation et contexte

Le Cameroun connaît une hausse progressive du coût de la vie et des dépenses alimentaires. De nombreux ménages consacrent une grande partie de leurs revenus à l'alimentation sans disposer d'outils simples pour planifier leurs achats et équilibrer leurs repas.

Par ailleurs, plusieurs aliments locaux nutritifs restent sous-utilisés alors qu'ils sont souvent plus abordables que certains produits importés.

NutriBudget Cameroun est une application web qui aide les ménages à construire des menus équilibrés à partir de leur budget disponible tout en valorisant les produits agricoles locaux.

2. Problème et objectifs
Problème

Les ménages camerounais ont des difficultés à gérer efficacement leur budget alimentaire et à composer des repas équilibrés malgré la disponibilité d'aliments locaux nutritifs.

Cette situation entraîne des dépenses inutiles, des déséquilibres nutritionnels et parfois du gaspillage alimentaire.

Objectif principal

Permettre à un ménage de générer un plan alimentaire adapté à son budget en moins de trois clics.

Objectifs secondaires
Réduire les dépenses alimentaires inutiles.
Encourager la consommation d'aliments locaux nutritifs.
Aider les ménages à mieux planifier leurs repas hebdomadaires.
3. Périmètre du projet
Inclus	Exclu
Gestion du budget alimentaire	Paiement en ligne
Génération automatique de menus	Livraison de produits
Conseils nutritionnels	Marketplace agricole
Consultation hors connexion partielle	Application mobile native
Calcul du coût des repas	Intelligence artificielle avancée
4. Utilisateurs cibles (Personas)
Ménage urbain
Famille de 4 à 6 personnes.
Budget alimentaire limité.
Utilise un smartphone Android.

Besoin :

Savoir quoi acheter avec son budget.
Étudiant
Vit seul.
Petit budget.

Besoin :

Trouver des repas économiques et équilibrés.
Jeune travailleur
Revenu modeste.
Peu de temps pour planifier.

Besoin :

Organiser rapidement ses repas.
5. Fonctionnalités (Méthode MoSCoW)
MUST (MVP)
Saisir son budget.
Saisir le nombre de personnes.
Générer automatiquement un menu.
Afficher le coût estimatif.
Afficher les informations nutritionnelles.
SHOULD
Rechercher des aliments.
Filtrer selon le budget.
COULD
Favoris.
Partage WhatsApp.
Historique des menus.
WON'T
Vente de produits.
Paiement en ligne.
Géolocalisation des marchés.
6. User Stories
En tant que parent, je veux saisir mon budget afin d'obtenir un menu adapté à mes moyens.
En tant qu'étudiant, je veux connaître les aliments les moins coûteux afin de réduire mes dépenses.
En tant qu'utilisateur, je veux voir la valeur nutritionnelle de mon menu afin d'améliorer mon alimentation.
7. Arborescence et écrans
Accueil
Présentation de l'application.
Bouton commencer.
Budget
Saisie du budget.
Nombre de personnes.
Résultat
Menu généré.
Coût estimé.
Nutrition
Analyse nutritionnelle.
Conseils
Astuces anti-gaspillage.
Navigation

Accueil
↓
Budget
↓
Résultat
↓
Nutrition
↓
Conseils

8. Modèle de données
Aliment
id
nom
catégorie
prix
protéines
glucides
vitamines
Menu
id
jour
alimentId
coût
Utilisateur
id
budget
nombrePersonnes
9. Parcours utilisateur principal
L'utilisateur ouvre l'application.
Il saisit son budget.
Il indique le nombre de personnes.
Il clique sur "Générer".
L'application crée un menu adapté.
Il consulte le coût total.
Il consulte les informations nutritionnelles.
10. Spécifications techniques
Framework : Angular 20
Langage : TypeScript
Style : SCSS + Angular Material
Stockage : fichier JSON local (v1)
Authentification : non nécessaire
Hébergement : GitHub Pages ou Vercel
11. Exigences non fonctionnelles
Connectivité
Fonctionnement avec faible connexion internet.
Responsive
Compatible smartphone et ordinateur.
Performance
Chargement inférieur à 3 secondes.
Accessibilité
Interface lisible.
Contraste élevé.
Sécurité
Aucune donnée sensible stockée.ANGULAR TALENT LAB 2026
0. En-tête du document

Projet : NutriBudget Cameroun — Manger mieux sans dépenser plus

Auteur : Boris Dorine

Type : Projet individuel

Version : v1.0

Date : Juin 2026

Formateur référent : À compléter

1. Présentation et contexte

Le Cameroun connaît une hausse progressive du coût de la vie et des dépenses alimentaires. De nombreux ménages consacrent une grande partie de leurs revenus à l'alimentation sans disposer d'outils simples pour planifier leurs achats et équilibrer leurs repas.

Par ailleurs, plusieurs aliments locaux nutritifs restent sous-utilisés alors qu'ils sont souvent plus abordables que certains produits importés.

NutriBudget Cameroun est une application web qui aide les ménages à construire des menus équilibrés à partir de leur budget disponible tout en valorisant les produits agricoles locaux.

2. Problème et objectifs
Problème

Les ménages camerounais ont des difficultés à gérer efficacement leur budget alimentaire et à composer des repas équilibrés malgré la disponibilité d'aliments locaux nutritifs.

Cette situation entraîne des dépenses inutiles, des déséquilibres nutritionnels et parfois du gaspillage alimentaire.

Objectif principal

Permettre à un ménage de générer un plan alimentaire adapté à son budget en moins de trois clics.

Objectifs secondaires
Réduire les dépenses alimentaires inutiles.
Encourager la consommation d'aliments locaux nutritifs.
Aider les ménages à mieux planifier leurs repas hebdomadaires.
3. Périmètre du projet
Inclus	Exclu
Gestion du budget alimentaire	Paiement en ligne
Génération automatique de menus	Livraison de produits
Conseils nutritionnels	Marketplace agricole
Consultation hors connexion partielle	Application mobile native
Calcul du coût des repas	Intelligence artificielle avancée
4. Utilisateurs cibles (Personas)
Ménage urbain
Famille de 4 à 6 personnes.
Budget alimentaire limité.
Utilise un smartphone Android.

Besoin :

Savoir quoi acheter avec son budget.
Étudiant
Vit seul.
Petit budget.

Besoin :

Trouver des repas économiques et équilibrés.
Jeune travailleur
Revenu modeste.
Peu de temps pour planifier.

Besoin :

Organiser rapidement ses repas.
5. Fonctionnalités (Méthode MoSCoW)
MUST (MVP)
Saisir son budget.
Saisir le nombre de personnes.
Générer automatiquement un menu.
Afficher le coût estimatif.
Afficher les informations nutritionnelles.
SHOULD
Rechercher des aliments.
Filtrer selon le budget.
COULD
Favoris.
Partage WhatsApp.
Historique des menus.
WON'T
Vente de produits.
Paiement en ligne.
Géolocalisation des marchés.
6. User Stories
En tant que parent, je veux saisir mon budget afin d'obtenir un menu adapté à mes moyens.
En tant qu'étudiant, je veux connaître les aliments les moins coûteux afin de réduire mes dépenses.
En tant qu'utilisateur, je veux voir la valeur nutritionnelle de mon menu afin d'améliorer mon alimentation.
7. Arborescence et écrans
Accueil
Présentation de l'application.
Bouton commencer.
Budget
Saisie du budget.
Nombre de personnes.
Résultat
Menu généré.
Coût estimé.
Nutrition
Analyse nutritionnelle.
Conseils
Astuces anti-gaspillage.
Navigation

Accueil
↓
Budget
↓
Résultat
↓
Nutrition
↓
Conseils

8. Modèle de données
Aliment
id
nom
catégorie
prix
protéines
glucides
vitamines
Menu
id
jour
alimentId
coût
Utilisateur
id
budget
nombrePersonnes
9. Parcours utilisateur principal
L'utilisateur ouvre l'application.
Il saisit son budget.
Il indique le nombre de personnes.
Il clique sur "Générer".
L'application crée un menu adapté.
Il consulte le coût total.
Il consulte les informations nutritionnelles.
10. Spécifications techniques
Framework : Angular 20
Langage : TypeScript
Style : SCSS + Angular Material
Stockage : fichier JSON local (v1)
Authentification : non nécessaire
Hébergement : GitHub Pages ou Vercel
11. Exigences non fonctionnelles
Connectivité
Fonctionnement avec faible connexion internet.
Responsive
Compatible smartphone et ordinateur.
Performance
Chargement inférieur à 3 secondes.
Accessibilité
Interface lisible.
Contraste élevé.
Sécurité
Aucune donnée sensible stockée.ANGULAR TALENT LAB 2026
0. En-tête du document

Projet : NutriBudget Cameroun — Manger mieux sans dépenser plus

Auteur : Boris Dorine

Type : Projet individuel

Version : v1.0

Date : Juin 2026

Formateur référent : À compléter

1. Présentation et contexte

Le Cameroun connaît une hausse progressive du coût de la vie et des dépenses alimentaires. De nombreux ménages consacrent une grande partie de leurs revenus à l'alimentation sans disposer d'outils simples pour planifier leurs achats et équilibrer leurs repas.

Par ailleurs, plusieurs aliments locaux nutritifs restent sous-utilisés alors qu'ils sont souvent plus abordables que certains produits importés.

NutriBudget Cameroun est une application web qui aide les ménages à construire des menus équilibrés à partir de leur budget disponible tout en valorisant les produits agricoles locaux.

2. Problème et objectifs
Problème

Les ménages camerounais ont des difficultés à gérer efficacement leur budget alimentaire et à composer des repas équilibrés malgré la disponibilité d'aliments locaux nutritifs.

Cette situation entraîne des dépenses inutiles, des déséquilibres nutritionnels et parfois du gaspillage alimentaire.

Objectif principal

Permettre à un ménage de générer un plan alimentaire adapté à son budget en moins de trois clics.

Objectifs secondaires
Réduire les dépenses alimentaires inutiles.
Encourager la consommation d'aliments locaux nutritifs.
Aider les ménages à mieux planifier leurs repas hebdomadaires.
3. Périmètre du projet
Inclus	Exclu
Gestion du budget alimentaire	Paiement en ligne
Génération automatique de menus	Livraison de produits
Conseils nutritionnels	Marketplace agricole
Consultation hors connexion partielle	Application mobile native
Calcul du coût des repas	Intelligence artificielle avancée
4. Utilisateurs cibles (Personas)
Ménage urbain
Famille de 4 à 6 personnes.
Budget alimentaire limité.
Utilise un smartphone Android.

Besoin :

Savoir quoi acheter avec son budget.
Étudiant
Vit seul.
Petit budget.

Besoin :

Trouver des repas économiques et équilibrés.
Jeune travailleur
Revenu modeste.
Peu de temps pour planifier.

Besoin :

Organiser rapidement ses repas.
5. Fonctionnalités (Méthode MoSCoW)
MUST (MVP)
Saisir son budget.
Saisir le nombre de personnes.
Générer automatiquement un menu.
Afficher le coût estimatif.
Afficher les informations nutritionnelles.
SHOULD
Rechercher des aliments.
Filtrer selon le budget.
COULD
Favoris.
Partage WhatsApp.
Historique des menus.
WON'T
Vente de produits.
Paiement en ligne.
Géolocalisation des marchés.
6. User Stories
En tant que parent, je veux saisir mon budget afin d'obtenir un menu adapté à mes moyens.
En tant qu'étudiant, je veux connaître les aliments les moins coûteux afin de réduire mes dépenses.
En tant qu'utilisateur, je veux voir la valeur nutritionnelle de mon menu afin d'améliorer mon alimentation.
7. Arborescence et écrans
Accueil
Présentation de l'application.
Bouton commencer.
Budget
Saisie du budget.
Nombre de personnes.
Résultat
Menu généré.
Coût estimé.
Nutrition
Analyse nutritionnelle.
Conseils
Astuces anti-gaspillage.
Navigation

Accueil
↓
Budget
↓
Résultat
↓
Nutrition
↓
Conseils

8. Modèle de données
Aliment
id
nom
catégorie
prix
protéines
glucides
vitamines
Menu
id
jour
alimentId
coût
Utilisateur
id
budget
nombrePersonnes
9. Parcours utilisateur principal
L'utilisateur ouvre l'application.
Il saisit son budget.
Il indique le nombre de personnes.
Il clique sur "Générer".
L'application crée un menu adapté.
Il consulte le coût total.
Il consulte les informations nutritionnelles.
10. Spécifications techniques
Framework : Angular 20
Langage : TypeScript
Style : SCSS + Angular Material
Stockage : fichier JSON local (v1)
Authentification : non nécessaire
Hébergement : GitHub Pages ou Vercel
11. Exigences non fonctionnelles
Connectivité
Fonctionnement avec faible connexion internet.
Responsive
Compatible smartphone et ordinateur.
Performance
Chargement inférieur à 3 secondes.
Accessibilité
Interface lisible.
Contraste élevé.
Sécurité
Aucune donnée sensible stockée.
