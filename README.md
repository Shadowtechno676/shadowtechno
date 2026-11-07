# Shadowtechno

Espace de travail personnel Shadowtechno pour regrouper les outils du quotidien dans une application Windows.

## Version disponible

**2.2.1 — code source**

Télécharger l’archive : [Shadowtechno_2.2.1_Source.zip](./Shadowtechno_2.2.1_Source.zip)

L’archive contient le projet Electron, les ressources de l’interface et les fichiers de configuration nécessaires au démarrage.

## Démarrage sous Windows

1. Extraire `Shadowtechno_2.2.1_Source.zip`.
2. Installer Node.js (version LTS recommandée).
3. Ouvrir le dossier `Shadowtechno` extrait.
4. Lancer `CREER_INSTALLATEUR.bat` pour préparer et compiler l’application, selon les prérequis du projet.

## Configuration et sécurité

- La clé Supabase `publishable` présente dans `config.js` est une clé client publique ; elle ne remplace pas les règles de sécurité côté serveur.
- Ne jamais ajouter de clé `service_role`, mot de passe, jeton OAuth ou clé SSH privée au dépôt.
- La fonction Supabase d’administration doit être déployée et configurée côté serveur avant d’utiliser les opérations administrateur.

## État de validation

Le code JavaScript a passé une vérification syntaxique et l’archive ZIP a été vérifiée. La compilation de l’installateur Windows et les intégrations en direct n’ont pas été testées dans cette publication.
