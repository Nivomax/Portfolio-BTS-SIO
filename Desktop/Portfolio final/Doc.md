# Compétence 1 - Recensement et identification des ressources numériques.
## Recensement d'un parc informatique avec GLPI
## Contexte:
Dans le cadre d'un TP du cours de Support et mise à disposition de services informatiques, j'ai déployé une solution GLPI sur une machine virtuelle Debian afin d’automatiser le recensement des équipements informatiques. L’objectif était de centraliser les informations relatives aux postes, serveurs et logiciels dans une interface unique afin d’améliorer la gestion du parc et d’avoir une meilleure visibilité sur les ressources du système d’information.
## Démarche suivi:
1. Prérequis Système
	- Vérification des ressources nécessaires (RAM, stockage, réseau)
	- Installation d’une machine virtuelle Debian
2. Installation de l'environnement
	- Installation d’Apache, PHP et MariaDB
	- Configuration des dépendances nécessaires
3. Configuration de la Base de Données
	- Création de la base GLPI
	- Attribution des droits
4. Installation de GLPI
	- Déploiement de l’application
	- Configuration via interface web
5. Mise en place de l'inventaire automatique
	- Installation de l’agent GLPI
	- Vérification des remontées d’informations
C1 - img 
Documentation installation glpi + agent
## Conclusion
Cette activité m’a permis de comprendre l’importance du recensement des ressources dans un système d’information. Elle m’a également permis d’acquérir des compétences en déploiement d’outils d’inventaire et en exploitation des données collectées

<br>

## Recensement des identifiants et mots de passes des différents outils, BDD, accès FTP...
## Contexte:
Dans le cadre de mon alternance, l’entreprise gère de nombreux accès pour différents clients. Afin d’éviter les pertes d’information et de sécuriser les accès, un outil interne est utilisé pour centraliser tous les identifiants.
## Démarche suivi
1. Identification des informations
- Distinction entre accès internes et clients
- Classification selon leur usage
2. Organisation des accès
- Création d’espaces par client
- Structuration des données
3. Enregistrement des données
- Ajout des identifiants
- Vérification des accès
## Conclusion
Cette outils permet un accès rapide et clair à tous les outils, sans devoir effectuer de renouvellement de mots de passe. Cette solution m'a été bénéfique puisque aujourd'hui, j'utilise le même outils pour un usage personnel

<br><br><br><br><br>

# Compétence 2 - Exploiter des référentiels, normes et standards adoptés par le prestataire informatique
## Rédaction d'une procédure ITIL de gestion des incidents
## Contexte
Dans le cadre d’un hackathon, j’ai participé à la rédaction d’une procédure de gestion des incidents basée sur ITIL afin de structurer le support informatique.
## Démarche suivi
1. Étude du référentiel ITIL
- Analyse des processus
- Identification des bonnes pratiques
2. Définition des étapes
- Détection
- Qualification
- Résolution
3. Formalisation
- Rédaction
- Définition des rôles
4. Validation
- Présentation
- Ajustement
## Conclusion
Permet d’appliquer un standard reconnu pour améliorer la gestion des incidents.

<br><br><br><br><br>

# Compétence 3 - Mettre en place et vérifier les niveaux d’habilitation associés à un service
## Revue des habilitations utilisateurs (Conformité Loi DORA)
## Contexte
Dans le cadre de mon alternance, j’ai participé à une revue des habilitations utilisateurs sur plusieurs applications critiques de l’entreprise (Back-Office, Gitlab, Wiki). Cette mission s’inscrivait dans une démarche de conformité à la loi DORA (Digital Operational Resilience Act), qui impose un contrôle strict des accès aux systèmes d’information critiques afin de limiter les risques opérationnels et de sécurité.
L’objectif principal était de vérifier que chaque utilisateur disposait uniquement des droits nécessaires à l’exercice de ses fonctions, conformément au principe du moindre privilège.
## Démarche suivi
1. Identification des applications et des profils concernés
- Recensement des applications critiques soumises aux exigences DORA.
- Identification des rôles et profils utilisateurs par application (utilisateur, administrateur, superviseur).
2. Analyse des habilitations existantes
- Extraction des listes d’utilisateurs et de leurs droits depuis chaque application.
- Comparaison des habilitations accordées avec les fonctions réelles des utilisateurs.
- Détection des anomalies : comptes dormants, droits excessifs, accès non justifiés.
3. Vérification du respect des bonnes pratiques de sécurité
- Application du principe du moindre privilège.
- Contrôle de la séparation des rôles (utilisateur / administrateur).
- Vérification de la présence de comptes génériques ou partagés.
4. Actions correctives et validation
- Proposition de suppression ou réduction des droits non conformes.
- Désactivation des comptes inactifs ou non utilisés.
- Validation des modifications avec les responsables applicatifs et métiers.
5. Traçabilité et documentation
- Mise à jour des matrices d’habilitation.
- Documentation des contrôles réalisés (preuves, dates, responsables).
- Contribution à l’audit de conformité dans le cadre de la réglementation DORA.
## Conclusion
Cette revue des habilitations a permis de renforcer la sécurité des applications critiques en garantissant une gestion rigoureuse des accès utilisateurs. La démarche a contribué à réduire les risques liés aux accès excessifs ou non maîtrisés et à améliorer la conformité réglementaire de l’entreprise vis-à-vis de la loi DORA.

<br><br><br><br><br>

# Compétence 4 - Vérifier les conditions de la continuité d’un service informatique
## Batch de maintenance : Mise à jour de plugins tous les mois
## Contexte
Dans mon alternance, j’ai participé à la maintenance mensuelle des sites web afin d’assurer leur bon fonctionnement et leur sécurité.
## Démarche suivi
1. Création d'un environnement de test
- Création d'un sous-domaine
- Duplication des fichiers et de la base de données
2. Mise à jour progressive
- Identifications des plugins non à jours
- Mise à jour des plugins 1 par 1 en vérifiant que le service fonctionne toujours correctement
3. Correction
- Analyse des erreurs
- Correction des erreurs
4. Push en production
- En cas d'aucunes erreurs, les mises à jour sont éffectuée en sur le site en production.
- En cas d'erreurs, les fichiers modifiés sont dirrectement remplacer par les fichiers corrigés en environnement de test
4. Tenir au courant le clients
- Rédaction d'un document listant les plugins mis à jours
- Description des solutions apporter en cas d'erreurs.
- Envoie d'un mail au client.
## Conclusion
Cette procédure m'a permis de prendre conscience de maintenir un service à jour afin d'éviter un maximum de cyberattaque et d'assurer la continuité des services pour les utilisateurs.

<br><br><br><br><br>
 
# Compétence 5 - Gérer des sauvegardes
## Réalisation de snapshots des VM des membres de l'équipe et backups des fichiers des sites et BDD.
## Contexte
Dans le cadre du cours de Support et mises à disposition des services informatique du BTS SIO, j'ai réaliser dans le cadre d'un Hackathon, une gourvernance permettant d'assurer une reprise d'activité en cas d'incidents malveillant. Pour celà nous avons effectué des backups des machines virtuelles, des fichiers et de la base de données des différents sites.
## Démarche suivi
1. Machines virtuelles
- Snapshots effectué à la fin de chaque séance ainsi qu'à chaques avancés majeures
2. Services en lignes
- Sauvegarde des fichiers 
- Sauvegarde de la base de données hebdomadaire

<br>

## Backups des  fichiers des sites et des bases de données
## Contexte
En entreprise, nous proposons un service d'hébergement (Scarsity).
Des sauvegardes sont effectué automatiquement tous les jours. En cas de perte de données, le client peut nous contacter pour récupérer des fichiers disparus ou restaurer une version précédente après une modification destructive.
## Démarche suivi
1. Analyse de la demande utilisateur
- Identification du fichier ou dossier concerné.
- Vérification de la date de suppression.
2. Restauration via l'outils Plesk
- Restauration d'une version antérieur grâce à l'historique. 
3. Vérification de l’intégrité des données
- Validation du contenu avec l'utilisateur.
- Confirmation de la reprise normal de l'activité.
## Conclusion
Ces interventions permettent de rétablir rapidement l'accès aux données sans interruption prolongée de l'activités des utilisateurs. ELLE démontrent l'importance d'une bonne maîtrise des mécanisme de sauvegarde et de restauration.

<br><br><br><br><br>

# Compétence 6 - Vérifier le respect des règles d’utilisation des ressources numériques
## Création d'une charte informatique
## Contexte
Dans le cadre d'un hackahton, j'ai réalisé une charte informatique pour l'utilisation de notre service.
## Démarche suivi
1. Identification des règles
2. Rédaction
3. Validation

<br>

## Onboarding et sensibilisation des nouveaux collaborateur
## Contexte
Dans le cadre de mon alternance, j’ai participé au processus d’onboarding des nouveaux collaborateurs au sein de l’entreprise. Cette activité visait à garantir une prise de poste conforme aux règles d’utilisation des ressources numériques dès l’arrivée de l’utilisateur.
## Démarche suivi
- Présentation de l’environnement informatique et des outils mis à disposition (poste de travail, messagerie, outils collaboratifs).
- Explication des règles de sécurité : gestion des mots de passe, verrouillage de session.
- Rappel des règles d’utilisation du matériel professionnel et des ressources réseau.
## Conclusion
Cette phase d’onboarding permet de poser un cadre clair dès l’arrivée du collaborateur et de limiter les comportements à risque liés à une mauvaise utilisation des ressources numériques.



<br><br><br><br><br><br><br><br><br><br>



# Compétence 7 - Collecter, suivre et orienter des demandes
## Gestion de tickets via l'outil Gitlab et Giraph pour les clients
## Contexte: 
Dans le cadre de mon alternance, j'ai participé à la gestion des demandes client concernant leurs sites internets, ainsi que leur installation réseaux.
## Démarche suivi:
1. Collecte et analyse des demandes
- Réception des tickets via Gitlab pour les demandes de dévellopement.
- Réception des tickets via Giraph pour les demandes de réseaux.
2. Orientation
- Qualification du degré de priorité
- Attribution aux collaborateurs concernés
3. Documentation et amélioration continue
- Rédaction et mise à jour de procédures sur Confluence.
- Capitalisation des solutions pour améliorer la qualité du support.
## Conclusion
La gestion structurée des tickets utilisateurs permet d’assurer un support efficace, un meilleur suivi des demandes et une amélioration continue des services proposés.

<br><br><br><br><br>

# Compétence 8 - Traiter des demandes concernant les services réseau et système, applicatifs
## Intervention chez le client ADETEM pour résoudre des problemes et de réseaux d'imprimante
## Contexte
Dans le cadre de mon aternance, j'ai été amené à me rendre sur dans les locaux du clients ADETEM. 
J'ai réorganisé leurs baie, et réaliser une documentation shématique représentant la nouvelle baie avec les connections de chaque cable et outils. J'ai également effectué la configuration d'une imprimante d'entreprise. 
## Démarche suivi
1. Problème de connexion
- Analyse de la source du problème: une boucle était présente sur la baie suite à l'intervention d'un technicien Orange.
- Réorganisation de la baie.
- Rédaction d'un document schématique représentant la baie et ses différentes connexions.
- Test de la connexion wifi sans fil et de la connexion filaire ethernet.
2. Configuration de l'imprimante
- Analyse du problème: mauvaise configuration IP.
- Configuration de la nouvelle adresse IP réseaux sur l'imprimante.
- Test d'impression 
## Conclusion
La prise en charge des demandes liées aux services réseau permet de garantir un environnement de travail fonctionnel chez les clients. Ces missions permettent de se confronter aux réalités du terrain.

<br><br><br><br><br>

# Compétence 9 - Traiter des demandes concernant les applications
## Résolution de problèmes applicatif des clients
## Contexte
Dans le cadre de mon alternance, j'ai assuré la maintenance plusieurs sites internets pour des cients externes. 
L'objectif était d'apporter une réponse rapide et adaptées aux utilisateurs tout en garantissant la traçabilité des demandes et le respect des procédures internes.
## Démarche suivi
1. Réception du ticket
2. Analyse et diagnostic de la demande correction
3. Résolution réalisée dans un environnement de test
4. Déploiement en production une fois la solution apporté

<br><br><br><br><br>

## Evolution des sites internet interne et ceux des clients
## Contexte
Dans le cadre de mon alternance, j'ai assuré l'évolution de plusieurs sites internets internes et pour des cients externes. 
L'objectif était d'apporter une réponse adaptées aux clients tout en garantissant la traçabilité des demandes et le respect des procédures internes.
## Démarche suivi
1. Réception du ticket ou du cachier des charges.
2. Analyse et diagnostic de la demande d'évolution
3. Evolution réalisée dans un environnement de test
4. Déploiement en production une fois la solution apportée
## Conclusion
La prise en charge des demandes concernant les applications permet de garantir la continuité d'un service en rectifiant rapidement les problêmes, ainsi que de permettre une évolution adaptée aux attentes du clients.
<br><br><br><br><br><br><br><br><br><br>



# Compétence 10 - Participer à la valorisation de l’image de l’organisation sur les médias numériques

## Participation aux développement des sites internet de l'entreprise pour présenter nos prestations
## Contexte
Dans le cadre de mon alternance, j'ai participé au développement des sites internet de SteveGates, Giraph et PowerValet. Ce sont trois services proposés par notre groupe.
## Démarche suivi:
1. Réception Cachier des charges.
2. Développement ou évolution réalisé dans un environnement de test
3. Déploiement en production une fois la solution apportée

<br><br>

## Optimisation de la visibilité des services grâce au référencement naturel (SEO)
## Contexte:
Dans le cadre de mon alternance, j'ai participé à l'amélioration de la visibilité de nos sites à l'aide du référencement naturel (SEO).
## Démarche suivi:
1. Analyse du services proposé
2. Installation du plugin Yoast SEO
3. Rédaction de Q&A et de blogs.
4. Rédaction de meta description et de meta title
## Conclusion
Ces activités m’ont permis de contribuer activement à la valorisation de l’image de l’organisation sur les médias numériques. À travers le développement des sites et l’optimisation SEO, j’ai participé à améliorer la présentation des services ainsi que leur visibilité en ligne. Cela a renforcé l’attractivité des offres proposées et permis de mieux répondre aux attentes des utilisateurs et des prospects.

<br><br><br><br><br>

# Compétence 11 - Référencer les services en ligne de l’organisation et mesurer leur visibilité
## Mise en place du suivi de visibilité via Google Analytics
## Contexte
Afin de mesurer la visibilité et l’utilisation de mon portfolio en ligne, j’ai mis en place un outil de suivi statistique. L’objectif était de comprendre le comportement des visiteurs et d’identifier les axes d’amélioration du site.
## Démarche suivi
1. Intégration de Google Analytics au portfolio.
2. Étude des interactions utilisateurs afin d’optimiser les contenus.
## Conclusion
Le suivi de visibilité permet d’avoir une vision objective de la fréquentation du site et de son efficacité

<br><br><br><br><br>

# Compétence 12 - Participer à l’évolution d’un site Web exploitant les données de l’organisation
## Développement d'un site web pour l'association EfreiPoker
## Contexte
Durant ma formation, j'ai eu l'occasion de rejoindre l'association EfreiPoker en tant que responsable informatique. Mon rôle est de développer un site internet pour la visibilité de l'association, mais également un espace administrateur permettant la gestion des membres et des évènements pour le bureau restreint.
## Démarche suivi
1. Analyse du cahier des charges et des besoins
2. Création de la base de données et de l'interface administrateur
3. Mise en place d’une interface cohérente et professionnelle pour les utilisateurs.
4. Validation et mise en production
5. Evolution et maintenance au fil de l'eau
## Conclusion
Ce projet me permet de participer concrètement à l’évolution d’un site web en exploitant les données de l’organisation. J’ai développé des compétences en conception de base de données, en développement d’interfaces et en gestion d’un espace administrateur adapté aux besoins des utilisateurs. La mise en production et les évolutions continues permettent également de renforcé ma capacité à maintenir un service fonctionnel et à l’adapter aux besoins réels de l’association.

<br><br><br><br><br><br><br><br><br><br>

# Compétence 13 - Analyser les objectifs et les modalités d’organisation d’un projet0
## Réalisation d'un cahier des charges pour le site de l'association EfreiPoker
## Contexte:
Dans le cadre de mon rôle de responsable informatique au sein de l’association EfreiPoker, j’ai été chargé de concevoir un site internet destiné à améliorer la visibilité de l’association et à faciliter la gestion interne des membres et des événements. Avant de débuter le développement, il était nécessaire de formaliser précisément les besoins afin de cadrer le projet, définir les objectifs et anticiper les contraintes techniques et organisationnelles. La réalisation d’un cahier des charges a donc permis de structurer le projet et d’aligner les attentes des différents acteurs (bureau, utilisateurs, développeur).
## Démarche suivi:
1. Recueil des besoins
- Échanges avec les membres du bureau pour identifier les attentes (gestion des membres, organisation des tournois, visibilité externe)
- Identification des utilisateurs cibles (administrateurs, membres, visiteurs)
2. Analyse des objectifs
- Définition des objectifs principaux du site (communication, gestion interne, automatisation)
- Priorisation des fonctionnalités (inscription, gestion des événements, tableau de bord admin)
3. Identification des contraintes
- Contraintes techniques (hébergement, base de données, sécurité)
- Contraintes organisationnelles (temps, ressources disponibles)
4. Rédaction du cahier des charges
- Description des fonctionnalités attendues
- Définition des parcours utilisateurs
- Structuration du document (besoin, solution, contraintes, planning)
5. Validation
- Présentation du cahier des charges au bureau
- Ajustements en fonction des retours
## Conclusion
La réalisation de ce cahier des charges m’a permis d’analyser en profondeur les objectifs du projet et d’en structurer l’organisation. Cette étape a été essentielle pour clarifier les besoins, anticiper les contraintes et garantir une base solide pour le développement du site. Elle m’a également permis de développer mes compétences en gestion de projet et en communication avec les parties prenantes.


<br><br><br><br><br>

# Compétence 14 - Planifier les activités
## Utilisation d'un Trello pour l'équipe de développeur
## Contexte
En entreprise et à l'école, nous utilisons l’outil Trello pour organiser nos projets de développement web et assurer une bonne répartition des tâches au sein de l’équipe. Cet outil permet de visualiser l’avancement des projets, de prioriser les demandes et de structurer le travail collaboratif. Il est particulièrement utile dans un environnement où plusieurs projets sont gérés en parallèle, avec des délais et des priorités différents.
## Démarche suivi
1. Création et structuration du tableau
- Mise en place des colonnes (Backlog / À faire / En cours / Terminé)
- Organisation des tâches par projet ou client
2. Création des tâches
- Décomposition des projets en tâches unitaires
- Description précise des actions à réaliser
- Ajout de pièces jointes ou de liens utiles
3. Priorisation et planification
- Attribution d’un niveau de priorité
- Définition des échéances
- Organisation des tâches selon les urgences
4. Attribution des tâches
- Affectation des tâches aux membres de l’équipe
- Clarification des responsabilités
5. Suivi de l’avancement
- Mise à jour des cartes selon leur état
- Suivi quotidien de l’évolution
- Ajustement en cas de retard ou imprévu
## Conclusion
L’utilisation de Trello m’a permis de mieux planifier les activités et d’avoir une vision claire de l’avancement des projets. Cet outil facilite la coordination entre les membres de l’équipe, améliore la gestion des priorités et contribue à respecter les délais fixés.

<br><br><br><br><br>

# Compétence 15 - Évaluer les indicateurs de suivi d’un projet et analyser les écarts
## Evaluation des KPI des tâches réalisés par les membres de l'équipe de développement
## Contexte
Dans le cadre de mon alternance, j’ai participé au suivi de l’avancement des projets de développement web au sein de l’équipe. Afin d’assurer le respect des délais et d’optimiser l’organisation du travail, des indicateurs de performance (KPI) étaient utilisés pour mesurer l’efficacité des tâches réalisées. L’objectif était d’identifier les écarts entre le travail prévu et le travail réellement effectué afin d’améliorer la gestion des projets et la productivité de l’équipe.
## Démarche suivi
1. Définition des indicateurs
- Identification des KPI pertinents (temps estimé vs temps réel, nombre de tâches terminées, respect des délais)
- Mise en place d’indicateurs simples et exploitables
2. Collecte des données
- Récupération des informations depuis les outils de gestion (Trello, Gitlab)
- Suivi du temps passé sur les tâches
- Analyse des tickets clôturés
3. Analyse des écarts
- Comparaison entre les estimations initiales et le temps réellement passé
- Identification des retards ou des tâches plus complexes que prévu
- Mise en évidence des points de blocage
4. Interprétation des résultats
- Analyse des causes des écarts (mauvaise estimation, imprévus techniques, dépendances)
- Évaluation de l’impact sur le projet global
5. Proposition d’amélioration
- Ajustement des estimations futures
- Amélioration de l’organisation des tâches
- Optimisation de la communication au sein de l’équipe
## Conclusion
Cette activité m’a permis de comprendre l’importance du suivi des indicateurs dans la gestion de projet. L’analyse des écarts entre les prévisions et les réalisations permet d’identifier les axes d’amélioration, d’optimiser la planification et d’augmenter l’efficacité globale de l’équipe de développement.

<br><br><br><br><br><br><br><br><br><br>



# Compétence 16 - Réaliser les tests d’intégration et d’acceptation d’un service

## Création d'un environnement de test pour le site EfreiPoker
## Contexte:
Dans le cadre du développement du site de l’association EfreiPoker, il était nécessaire de mettre en place un environnement de test afin de valider les nouvelles fonctionnalités avant leur mise en production. Cet environnement permettait de reproduire les conditions réelles d’utilisation tout en évitant d’impacter les utilisateurs finaux lors des phases de développement et de correction.
## Création d'un environnement de developpement pour le site du client Ceramat
## Contexte:
Dans le cadre de mon stage, un environnement de test était utilisés durant le développement du site du client Ceramat.
## Création d'un environnement de test pour chaques sites
## Contexte:
Dans le cadre de mon alternance, des environnements de test étaient systématiquement utilisés durant le développement et la maintenance des sites web. Ces environnements permettaient de tester les évolutions, de les faire valider par les équipes internes puis par les clients, avant leur mise en production afin de garantir la stabilité des services.
## Démarche suivi:
1. Mise en place de l’environnement
- Création d’un sous-domaine de test
- Duplication des fichiers et de la base de données
2. Réalisation des tests
- Tests des fonctionnalités développées
- Vérification des parcours utilisateurs
3. Correction des anomalies
-Identification des bugs
-Correction et nouveaux tests
4. Validation
- Vérification globale du site
- Validation des fonctionnalités attendues
- Mise en production
## Conclusion
L’utilisation d’environnements de test permet de sécuriser les évolutions et de garantir la qualité des services avant leur mise en production. Elle assure également une validation progressive par les équipes et les clients, limitant ainsi les risques d’erreurs en production et améliorant la satisfaction des utilisateurs.

<br><br><br><br><br>

# Compétence 17 - Déployer un service
## Déploiement de GLPI et de différents sites
Dans le cadre de ma formation, j’ai été amené à déployer différents services, notamment une solution GLPI pour la gestion de parc informatique ainsi que des site vitrines. L’objectif était de rendre ces services accessibles aux utilisateurs finaux dans un environnement fonctionnel et sécurisé.

<br>

## Mise en production du site e-commerce pour le client Ceramat 
## Contexte
Dans le cadre de mon stage j’ai participé à la mise en production du site e-commerce du client Ceramat. Après les phases de développement et de test.

<br>

## Mise en production de sites vitrine et e-commerce pour différents clients
## Contexte:
Dans le cadre de mon alternance, j’ai participé régulièrement à la mise en production de sites web (vitrine et e-commerce) pour différents clients. Ces déploiements faisaient suite aux phases de développement et de validation en environnement de test.
## Démarche suivi
1. Préparation du déploiement
- Validation par l'équipe de dev
- Validation par le client
2. Transfert des fichiers
- Envoi des fichiers via FTP
- Vérification de l’intégrité des données
3. Configuration
- Import de la base de données
- Mise à jour des paramètres (URL, accès BDD)
4. Tests en production
- Vérification du bon fonctionnement du site
- Tests des fonctionnalités principales (navigation, commande)
5. Mise en ligne
- Ouverture au public
- Surveillance des premiers retours
## Conclusion
Le déploiement d’un service constitue une étape clé permettant de rendre une solution accessible aux utilisateurs finaux. Ces expériences m’ont permis de maîtriser les différentes étapes d’une mise en production, de la préparation à la validation finale, tout en garantissant la stabilité et la qualité du service déployé.

<br><br><br><br><br>

# Compétence 18 - Accompagner les utilisateurs dans la mise en place d’un service
## Rédaction de guides simples et vidéos tutoriels pour l'utilisation du backoffice pour les clients
## Contexte:
Dans le cadre de mon alternance, après la mise en production des sites web (vitrine ou e-commerce), il était nécessaire d’accompagner les clients dans la prise en main de leur backoffice. Les clients n’ayant pas toujours de compétences techniques, la création de supports pédagogiques (guides et vidéos) permettait de faciliter l’utilisation quotidienne de leur site et de réduire les demandes de support.
## Démarche suivi
- Identification des besoins utilisateurs
- Rédaction des guides
- Réalisation de vidéos tutoriels
## Conclusion
La création de guides et de tutoriels permet d’accompagner efficacement les utilisateurs dans la prise en main d’un service. Cette démarche facilite l’autonomie des clients, réduit les erreurs d’utilisation et améliore leur satisfaction. Elle m’a également permis de développer des compétences en pédagogie et en communication technique.

<br><br><br><br><br><br><br><br><br><br>



# Compétence 19 -  Mettre en place son environnement d’apprentissage personnel
## Création d'un espace de travail numérique : OneNote + anki 
## Contexte:
Dans le cadre de ma formation en BTS SIO, j’ai mis en place un environnement d’apprentissage personnel afin d’améliorer mon organisation et mon efficacité dans la révision des cours et la préparation des épreuves. L’objectif était de structurer mes connaissances, centraliser mes ressources et optimiser la mémorisation des notions techniques et théoriques.
## Démarche suivi:
- Utilisation de OneNote pour l’organisation des cours et projets
- Utilisation d’Anki pour la mémorisation active (flashcards)
- Création de sections par matière et par compétence
- Mise à jour régulière des contenus
## Conclusion
La mise en place d’un environnement d’apprentissage personnel m’a permis de mieux structurer mon travail et d’améliorer mon efficacité dans l’acquisition des connaissances. L’utilisation combinée de OneNote et Anki favorise une meilleure organisation ainsi qu’une mémorisation plus durable des notions importantes.

<br><br><br><br><br>

# Compétence 20 - Mettre en œuvre des outils et stratégies de veille informationnelle
## Mise en place d’une veille technologique
## Contexte
Afin de rester informée des évolutions du secteur informatique, j’ai mis en place une veille technologique régulière, principalement orientée vers la cybersécurité.
## Démarche suivi
- Consultation de sources spécialisées en cybersécurité.
- Suivi de l’actualité des vulnérabilités et incidents de sécurité.
## Conclusion
La veille technologique me permet de maintenir mes connaissances à jour, d’anticiper les évolutions du domaine informatique et de renforcer ma pratique professionnelle.

<br><br><br><br><br>

# Compétence 21 - Gérer son identité professionnelle
## Conception du portfolio
## Contexte
Dans le cadre de ma formation en BTS SIO, j’ai conçu un portfolio numérique afin de centraliser et valoriser mes réalisations professionnelles et pédagogiques. 
## Démarche suivi
- Structuration du portfolio par blocs de compétences du référentiel BTS SIO.
- Sélection et rédaction des situations professionnelles significatives.
- Mise en forme claire et cohérente pour faciliter la lecture et la compréhension.
- Mises à jour régulières en fonction de l’évolution de mes compétences.

<br>

## Création et gestion de mes profils professionnels LinkedIn et GitHub
## Contexte
Dans le cadre de mon insertion professionnelle, j’ai créé et structuré mes profils LinkedIn et GitHub afin de développer mon identité professionnelle numérique.
## Démarche suivi
- Création et complétion de mon profil LinkedIn.
- Mise en avant de mes expériences et compétences clés.
- Publication de projets et de codes sources sur GitHub.
## Conclusion
La création d'un portfolio ainsi que la gestion de mes profils professionnels contribue à renforcer ma visibilité, ma crédibilité et mon positionnement dans le secteur informatique.

<br><br><br><br><br>

# Compétence 22 - Développer son projet professionnel

## Fixation d'objectifs (projet) et accompliseement de certifications pour renforcer et découvrir de nouvelles compténces
## Contexte
Dans le cadre de mon parcours en BTS SIO, j’ai travaillé activement sur la définition et l’évolution de mon projet professionnel dans le domaine du numérique.
## Démarche suivi
- Identification des métiers du numérique qui m’intéressent.
- Analyse des compétences requises pour ces métiers.
- Réalisation de projets
- Obtentions de certification dans le domaine visé.
- Échanges avec des professionnels et des étudiants d’autres filières.
- Veille sur les opportunités d’évolution et de poursuite d’études.
## Conclusion
Ces travaux m’ont permis de clarifier mes objectifs professionnels et de construire un projet cohérent en lien avec mes compétences et mes aspirations.
