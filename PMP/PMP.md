# **Table des matières**

## **Glossaire**

- PPE : Premium Plateform Electric
- ECU : Electic Controller Unit
- CLR : Customer Line Return
- FF : Freeze Frame

## **Introduction**

Dans le cadre de ma 5ème année de cycle d'ingénieur (FISA 27), d’Ingénieur Systèmes Electriques Electronique Embarqués (S3E), il nous est proposé de réaliser un projet de fin d’études. Ce projet constitue une opportunité d’appliquer les compétences techniques et méthodologiques acquises tout au long de ma formation, tout en développant mes capacités de gestion de projet, de management d’équipe et de pilotage budgétaire.

L’objectif de ce projet est de me confronter aux réalités du métier d’ingénieur en abordant différentes facettes essentielles : la gestion des ressources humaines et matérielles, le respect des contraintes budgétaires et des délais, ainsi que la mise en place de stratégies adaptées aux enjeux du projet. À travers ce travail, je devrai démontrer ma capacité à structurer et conduire un projet en entreprise, en respectant un cahier des charges précis et en atteignant les objectifs fixés.

Ce document définira les attendus du projet, les méthodologies de gestion employées (WBS, RBS, GANTT, OBS, PBS), ainsi que les aspects financiers et l’analyse des risques. Il servira de référence pour assurer un suivi rigoureux du projet et garantir son bon déroulement jusqu’à la soutenance prévue en septembre 2024, au cours de laquelle mon travail sera évalué en fonction des critères établis.

## **Presentation du projet**

### **Contexte**

FORVIA HELLA est un équipementier automobile allemand de renommée internationale, coté en bourse et spécialisé dans les technologies d'éclairage haute performance ainsi que l’électronique embarquée. Fort de son expertise, l’entreprise joue un rôle clé dans l’innovation et l’évolution du secteur automobile en fournissant des solutions avancées en matière d’électronique, d’énergie et de connectivité.

En France, la filiale de FORVIA HELLA développe et produit divers équipements destinés aux véhicules, notamment des on-board chargers, des calculateurs de direction assistée, ainsi que des transformateurs. Ces composants sont essentiels pour améliorer l’efficacité énergétique, la sécurité et la fiabilité des systèmes automobiles modernes. Grâce à une forte intégration des nouvelles technologies, FORVIA HELLA contribue activement à la transition vers des véhicules plus intelligents et durables.

### **Sujet et problématique**

La filiale française de FORVIA HELLA a lancé le développement d’un calculateur de direction assistée il y a huit ans, dans le cadre du projet PPE commandé par Volkswagen. Ce produit, récemment mis en circulation, fait désormais l’objet de retours clients signalant divers défauts. Le Customer Line Return (CLR) se charge du rapatriement des ECUs défectueux, tandis que notre entreprise est responsable de leur analyse.

À leur réception, les testeurs doivent identifier l’origine des dysfonctionnements. Pour faciliter ce diagnostic, l’entreprise a intégré dans ses calculateurs des programmes capables de générer des Freeze Frames. Ces chaînes hexadécimales contiennent un ensemble de données enregistrées au moment de l’incident (vitesse, niveau de batterie, température du calculateur, etc.), offrant ainsi un instantané des conditions dans lesquelles le problème est survenu.

De plus, FORVIA HELLA voit l’émergence de nouveaux projets, nécessitant le développement de logiciels embarqués avancés dédiés au diagnostic, appelés HPM. Ces outils doivent être capables de traiter efficacement les nouvelles générations de calculateurs de direction assistée, garantissant ainsi une meilleure fiabilité et un suivi optimisé des performances des systèmes embarqués.

### **Enjeux**

L'automatisation du décodage des Freeze Frames représente un enjeu majeur pour FORVIA HELLA, tant sur le plan technique qu'opérationnel. Actuellement, l'analyse manuelle des trames hexadécimales est une tâche chronophage, sujette aux erreurs humaines et difficilement scalable face à l’augmentation du nombre d’ECUs à traiter. En développant un outil automatisé de décodage, l’entreprise vise à réduire le temps de diagnostic, améliorer la précision des analyses et accélérer la résolution des problèmes clients.

Par ailleurs, le développement et l’évolution du HPM sont essentiels pour garantir un diagnostic toujours plus précis et performant. La mise en place de ces outils renforce non seulement la capacité de FORVIA HELLA à répondre aux exigences croissantes du secteur automobile, mais elle ouvre également la porte à de nouvelles opportunités de collaboration et d’innovation, consolidant ainsi la position de l’entreprise sur le marché des systèmes embarqués intelligents.

### **Objectifs**

Le projet vise à répondre à plusieurs objectifs clés, prenant en compte les exigences du développement logiciel pour les outils de diagnostic ainsi que les enjeux industriels liés aux calculateurs électroniques :

1. **Objectifs Techniques**

    - Concevoir des outils logiciels robustes permettant de faciliter les tests et le diagnostic des calculateurs électroniques.
    - Automatiser les tests des cartes électroniques sur la chaîne de production afin de réduire les interventions manuelles.
    - Améliorer la précision du diagnostic en minimisant les erreurs humaines dans l’analyse des Freeze Frames.
    - Concevoir une solution évolutive, capable de s’adapter aux futurs calculateurs et nouveaux formats de Freeze Frames.
    - Répondre aux évolutions technologiques pour intégrer efficacement de nouveaux projets HPM.

2. **Objectifs Humains**

    - Former les testeurs et opérateurs à l’utilisation des nouveaux outils logiciels pour garantir une adoption optimale.
    - Fournir une documentation complète et accessible pour assurer une prise en main rapide et efficace des outils.
    - Faciliter la collaboration entre les différentes équipes (France, Roumanie, Allemagne) en assurant une bonne communication des - besoins et des attentes.

3. **Objectifs Organisationnels**

    - Gérer une équipe de développement internationale, en assurant une répartition efficace des tâches et responsabilités.
    - Suivre l’approvisionnement en ressources matérielles et logicielles nécessaires pour garantir le bon déroulement du projet.
    - Assurer la livraison des outils en respectant les délais et les contraintes budgétaires.

### **Méthode gestion de projet**

Étant donné que mon projet repose principalement sur le développement logiciel, j’ai choisi d’adopter une approche Agile, qui permet une gestion flexible et itérative du projet. L’Agile pose sur une adaptation continue aux besoins et aux contraintes techniques, tout en favorisant la collaboration entre les différentes parties prenantes.

Dans cette approche, le développement est organisé en cycles itératifs et incrémentaux, où chaque itération permet de livrer une version partielle mais fonctionnelle des outils logiciels. Plutôt que de suivre un modèle strictement prédéfini, cette méthode favorise une évolution continue en fonction des retours utilisateurs et des éventuels défis techniques rencontrés au fil du projet.

Le découpage des tâches se fait en petites unités indépendantes, chacune représentant une fonctionnalité ou une amélioration spécifique du logiciel. À la fin de chaque itération, un bilan est réalisé pour ajuster les priorités et intégrer les retours des testeurs et opérateurs. Cette approche offre plusieurs avantages :

- Flexibilité et adaptation : Permet de prendre en compte les retours des testeurs en temps réel et d’adapter rapidement le développement en fonction des nouveaux besoins identifiés.
- Amélioration continue : Chaque itération permet d’optimiser les performances des outils et d’intégrer progressivement des fonctionnalités avancées.
- Suivi structuré : Grâce à une planification des itérations et des revues régulières, l’évolution du projet est claire et mesurable.

En appliquant cette méthode Agile, je peux garantir un développement progressif des outils logiciels, en optimisant leur robustesse et leur pertinence pour les utilisateurs finaux.

## **Mise en oeuvre**

