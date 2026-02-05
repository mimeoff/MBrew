# Politique de confidentialité MBrew

Date d’entrée en vigueur : 2026-01-04

## Introduction
MBrew est une application de bureau locale basée sur Electron et Vue, destinée à la gestion des recettes de bière artisanale et à l’assistance au brassage. Nous accordons une grande importance à la vie privée : les données sont traitées localement autant que possible. Nous ne téléchargeons ni ne partageons les données des utilisateurs vers des serveurs distants.

## Collecte et utilisation des données
- Nous ne collectons pas d’informations personnelles identifiables (nom, e‑mail, adresse, téléphone, etc.).
- Nous ne collectons pas d’informations financières, de santé, de contacts, de photos/documents ni de contenus générés par l’utilisateur.
- Nous ne collectons pas d’identifiants d’appareil (p. ex. identifiant publicitaire), de données de localisation ou d’informations sensibles.
- Les données métier (recettes, ingrédients, inventaire, historiques de brassage) sont stockées localement sur l’appareil de l’utilisateur (répertoire de données de l’application ou chemin de fichier sélectionné par l’utilisateur pour la sauvegarde/import/export).
- L’application n’envoie pas ces données aux serveurs du développeur ni à des services tiers.

## Services tiers et réseau
- L’application peut accéder à des pages de documentation ou vérifier les mises à jour via HTTPS/TLS. Aucune donnée personnelle n’est collectée ni analysée.
- L’application n’intègre pas de SDK d’analyse tiers (p. ex. Google Analytics, Sentry).
- Tous les accès externes sont en lecture seule (documentation, vérification de version) et n’impliquent pas de téléversement de données utilisateur.

## Déclaration de suivi
- L’application n’effectue pas de suivi intersites ou interapplications.
- Aucune technologie publicitaire ou de suivi tiers n’est utilisée.
- Aucune donnée n’est partagée avec des tiers à des fins publicitaires ou de profilage.

## Autorisations et sandbox
- Accès aux fichiers : lecture/écriture uniquement lorsque l’utilisateur sélectionne un chemin (conforme à `files.user-selected.read-write` dans le bac à sable macOS).
- Accès réseau : utilisé pour charger des documents externes ou vérifier les mises à jour (sans données utilisateur).
- L’application ne demande pas l’accès à la caméra, au microphone, aux contacts ni à la localisation.

## Sécurité des données
- Toutes les données sont stockées localement.
- Les sauvegardes/imports/exports utilisent des fichiers JSON ; l’utilisateur gère lui‑même les emplacements de stockage.
- Nous utilisons le chiffrement de transport HTTPS/TLS du système pour la sécurité réseau et n’implémentons pas de chiffrement personnalisé ou générique côté application.

## Confidentialité des enfants
- L’application s’adresse aux adultes dans le contexte de la gestion du brassage et n’est pas conçue pour les enfants.
- Nous ne collectons pas d’informations personnelles d’enfants.

## Modifications
- En cas de mise à jour de cette politique, une nouvelle version sera publiée sur la page d’accueil de l’application ou dans la documentation du projet.
- Les modifications importantes indiqueront clairement la date d’effet et les détails du changement.

## Contact
- Page du projet : https://github.com/mimeoff/MBrew
- Support : veuillez soumettre vos problèmes ou suggestions via GitHub Issues

