# Changelog

Toute modification liée au code exécuté en production sera documenté dans ce fichier.

Le présent format s'appuie sur [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

Ce fichier ne doit pas être mis à jour directement, il faut utiliser le fichier
`CHANGELOG-UNRELEASED.md`.
Par la suite les changements de `CHANGELOG-UNRELEASED.md` sont reversé dans ce
fichier lors de la création d'une nouvelle release.

## [1.104.0] - 2021-11-24

- TRV-539:  Mise à jour d'usager sans adresse postale
- SEJ-1325: DCEM - Template de convocation à modifier
- SEJ-1439: DCEM - Flux 40 - Tronquer champs
- SEJ-1320: BPI - Creer feature flag BPI
  - Nouveau feature flag: `BENEFICIAIRE_PROTECTION_INTERNATIONALE`
  - `./manage.py referentials references_techniques load misc/referentiel_references_techniques.csv -d ';'`
- SEJ-1431: DCEM - anomalie dans le flux 40 AGDREF sur le n° de la demande
- ANTM-570: Extraction CSV Ajustements mineurs suite recette interne
- SEJ-721: TVE - Finalisation de l'instruction
- NAT-444: Lancement automatique du flux DGSI
  - `Nouveau feature flag : anf_lancement_auto_dgsi`
- ANTM-307: Ecran de suivi des usagers SOP : écran fiche détail (Mesures administratives)