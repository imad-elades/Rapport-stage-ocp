# Étude Observationnelle du Système OPM dans l’Industrie Minière 🏭⛏️

> **Stage d'Observation | OCP - Mine Sidi Chennane | Transformation Digitale Industrielle**

Ce dépôt contient mon rapport de stage effectué au sein du groupe **OCP (Office Chérifien des Phosphates)**, leader mondial de l'industrie des phosphates. L'étude se concentre sur le système **OPM (OCP Process Manufacturing)**, une solution technologique avancée pour la surveillance en temps réel et l'optimisation de la flotte d'engins miniers.

![OCP Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/OCP_Group.svg/1200px-OCP_Group.svg.png)
*(Remplacez ce lien par une image pertinente si disponible)*

## 📄 Aperçu du Projet

Le système OPM agit comme une "tour de contrôle" numérique pour la mine. Il centralise les données opérationnelles des équipements lourds (camions, bulldozers, pelles hydrauliques) afin d'améliorer leur disponibilité, leur productivité et la sécurité des opérations.

Ce rapport détaille l'architecture matérielle et logicielle de ce système, son déploiement sur le terrain et son impact sur la maintenance préventive.

## 🛠️ Technologies et Architecture Système

L'étude couvre l'ensemble de la chaîne de valeur de la donnée, de la collecte sur l'engin jusqu'à l'analyse décisionnelle :

### 1. Composants Embarqués (Hardware)
- **IPAN (Intelligent Panel) :** Cœur du système embarqué, interface tactile sous Windows pour les opérateurs.
- **Réseau TETRA (Motorola MTM5400) :** Communication radio sécurisée pour la transmission des données.
- **Capteurs IoT & Télémétrie :**
  - **NB-04 (GPS) :** Géolocalisation haute précision et suivi de vitesse.
  - **GEMAC :** Capteur d'inclinaison pour la sécurité sur terrains accidentés.
  - **TPMS (OTR Schrader) :** Surveillance pression/température des pneus en temps réel.
  - **LLS (Liquid Level Sensor) :** Gestion précise de la consommation de carburant.
  - **CAN Crocodile :** Lecture non-intrusive des données du Bus CAN (protocole **J1939**).

### 2. Solutions Logicielles (Software)
- **FMS (Fleet Monitoring System) :** Plateforme centrale de supervision et d'analyse.
- **GMAO :** Intégration pour la planification de la maintenance.
- **Tableaux de Bord :** Visualisation temps réel des KPIs (Disponibilité, MTBF, MTTR).

## 🚀 Apports et Optimisations

L'analyse démontre comment la transformation digitale impacte les opérations minières :
- **Maintenance Prédictive :** Anticipation des pannes grâce à la remontée d'alertes en temps réel (ex: surchauffe moteur, pression pneus).
- **Efficacité Opérationnelle :** Réduction des temps d'arrêt non planifiés et optimisation des cycles de transport.
- **Sécurité Accrue :** Suivi des comportements de conduite et alertes immédiates en cas de danger.

## 📈 Pistes d'Amélioration Future

Le rapport propose également des axes d'évolution pour le système OPM :
- **Migration vers la 4G/LTE :** Pour pallier les limites de bande passante du réseau TETRA.
- **Intelligence Artificielle (IA) :** Exploitation du Big Data pour des modèles prédictifs plus poussés (Machine Learning).
- **Renforcement Matériel :** Solutions durcies pour résister aux conditions extrêmes (vibrations, poussière).

## 👤 Auteur

**Imad ELADES**
*Élève Ingénieur en Transformation Digitale Industrielle*
*École Nationale des Sciences Appliquées (ENSA) de Béni Mellal*

---
*Ce projet s'inscrit dans le cadre de la modernisation et de la digitalisation des processus industriels (Industrie 4.0).*
