
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/alec42/actulab-2019">
    <img src="01_DocumentPrincipal/src/GuideEnActuariat/couverture.jpg" alt="Logo" height="280">
  </a>

  <h3 align="center">Guide de survie en actuariat</h3>

  <p align="center">
    Ressources d’études pour les étudiants du baccalauréat en actuariat à l’université Laval.
    <br />
    <a href="https://github.com/ressources-act/Guide_de_survie_en_actuariat/tree/master/02_Cheatsheets"><strong>Explorer les feuilles »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/contributeurs/contributeurs-cheatshts.pdf/">Voir les contributeurs</a>
  </p>
</p>

# Guide de survie en actuariat

## Table des matières

- [Sigles et noms de cours](#siglenomind)
- [Structure du répertoire](#structure)
- [Contribuer](#contrib)
- [Contenu du répertoire](#contents)
- [Contributeurs](#contributors)

<a name="siglenomind"/>

## Lien vers les cheatsheets des cours :

### « *Cheatsheets* » exhaustives
Sujet | Sigles des cours reliés 
--------- | --------
[Gestion des risques financiers (GRF)](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-GRF-ACT2011-ACT1006.pdf)  | ACT-1006: Gestion des risques financiers I
 &nbsp; | ACT-2011: Gestion des risques financiers II

### Cheatsheets
Sigle | état  | Nom du cours 
---   | ----  | --------
ACT-1001  | développement, pas encore de feuille dédiée | [Mathématiques financières](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT1XXX.pdf)
ACT-1002  | en cours de rédaction | [Analye probabiliste des risques actuariels](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT1002.pdf)
ACT-1003  | développement, pas encore de feuille dédiée | [Compléments de mathématiques](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT1XXX.pdf)
ACT-2001  | en cours de rédaction | [Introduction à l'actuariat II](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2001.pdf)
ACT-2000  | en cours de rédaction | [Analyse statistique des risques actuariels](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2000%20(MAS-I)%20(TEMP).pdf)
ACT-2002  | développement, pas encore de feuille dédiée | [Méthodes numériques](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT1XXX.pdf)
ACT-2003  | première version complétée, en cours d'amélioration | [Modèles linéaires](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2003.pdf)
ACT-2004  | première version complétée | [Mathématique actuarielles vie I](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2004.pdf)
ACT-2005  | première version complétée, en cours d'amélioration | [Mathématique actuarielles IARD I](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2005.pdf)
ACT-2009  | première version complétée, en cours d'amélioration | [Processus stochastiques](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2009.pdf)
ACT-1005  | première version complétée | [Analyse et traitement collectif du risque](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT1005.pdf)
ACT-2007  | première version complétée | [Mathématique actuarielles vie II](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2007.pdf)
ACT-2008  | première ébauche complétée | [Mathématique actuarielles IARD II](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT2008.pdf)
ACT-3000  | première ébauche complétée | [Théorie du risque](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT3000.pdf)
ACT-3114  | première ébauche complétée | [Apprentissage statistique en actuariat](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT3114.pdf)
ACT-4105  | première ébauche complétée | [Tarification en assurance IARD](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-ACT4105.pdf)
FRN-3003  | première ébauche complétée | [Français avancé: grammaire et rédaction II](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-Francais.pdf)


### Cheatsheets de R
Sigle | Nom du cours
--- | --------
ACT-3114  | [Apprentissage statistique en actuariat](https://github.com/ressources-act/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/cheatsht-R-ACT3114.pdf)

<a name="structure"/>


## Structure

### 00_Archive

Contenu non adapté à la structure du document principal.

> **Aucun pull request ne devrait ajouter du contenu à ce répertoire**

### 01_DocumentPrincipal

Environnement de compilation du document principal. Pour créer un nouvelle section, suivre les règles suivantes:

- **Chapter-\<nomDuChapitre\>.tex** : Chapitre portant sur une matière précise.
- **Appendix-\<nomDeAppendix\>.tex** : Ajout pouvant être utile dans plusieurs matières/chapitres.
- **Main-\<nomDuDocument\>.tex** : Fichier servant à la construction du document principal.
- **src/\<nomDuChapitre>** : Dossier contenant tous les img/.R/etc utilisé dans la section en question.
  
  ### 02_Cheatsheets
  
  Environnement de compilation des feuilles de formules. **Important**, elles doivent tous utiliser le même préambule (**cheatsht-preamble-general.tex**).
- **cheatsht-ACT\<XXXX\>.tex** : Code source de la feuille de formule concernant le cours ACT-\<XXXX\>.

### 03_Docs

Autres documents d'aide.

<a name="contrib"/>

##  Contribuer

Voir le fichier CONTRIBUTING.md pour les étapes détaillées avec des images.

## Contents

> TODO

<a name="contributors"/>
# Contributeurs

- [aut.] Nicholas Langevin [:octocat:](https://github.com/NicholasLangevin)
- [aut., diplômé] Gabriel Crépeault-Cauchon [:octocat:](https://github.com/gabrielcrepeault)
- [aut., cre.] Alec James van Rassel [:octocat:](https://github.com/alec42)
- [aut., cre.] Olivier Côté [:octocat:](https://github.com/OliCoSide)
- [ctb., cre.] Félix Cournoyer [:octocat:](https://github.com/felix5960)

Pour les contributeurs aux feuilles de formules ainsi qu'une description des différents rôles, voir [ce fichier](https://github.com/NicholasLangevin/Guide_de_survie_en_actuariat/blob/master/02_Cheatsheets/contributeurs-cheatshts.pdf).

