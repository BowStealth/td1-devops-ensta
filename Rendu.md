# Rendu TD1 - [Votre Nom]

## Exercice 1
- Lien PR : https://github.com/BowStealth/td1-devops-ensta
- Pourquoi crée-t-on une branche plutôt que de committer directement sur main ? [1-2 phrases]

## Exercice 2 - Capture The Bug

### Bug 1
- Déclencheur : si le numéro dépasse le nombre d'enregistrement
- Commit fautif : 7abdaed
- Auteur : Serpico
- Ligne problématique : 46
- Correction appliquée : gestion avec le len du nolbre d'enregistrement

### Bug 2
- Déclencheur : si on ne mets rien dans le filtrage du produit
- Commit fautif : f7cceb3
- Auteur : feris bueller
- Ligne problématique : 14
- Correction appliquée : ajout du cas si count =0

### Bug 3
- Déclencheur : si on ne mets rien ou alors un carctère spécial dans la recherche 
- Commit fautif : e9b5614
- Auteur : Serpico
- Ligne problématique : 27
- Correction appliquée : gestion des expressions régulières

## Exercice 3
- Commit de résolution : 10b1420
- Qu'est-ce qu'un conflit Git et pourquoi survient-il ? [1-2 phrases]
- (Bonus) Différence entre merge et rebase : [1-2 phrases]

## Exercice 4
- Commande utilisée pour squasher les 3 commits : [commande]
- Pourquoi squasher avant de merger ? [1 phrase]
- Différence entre `--soft`, `--mixed` et `--hard` : [1-2 phrases]
- Hash du commit hotfix sur main : 6f2cc50
- Pourquoi cherry-picker vers dev plutôt que merger main dans dev ? [1 phrase]

## Exercices 5/6
- Lien vers le workflow GitHub Actions : [URL]
- Qu'apporte la CI par rapport à des tests lancés manuellement ? [1-2 phrases]
- Pourquoi filtrer les fichiers qui déclenchent la CI ? [1 phrase]