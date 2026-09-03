# Lecteur rapide

Lecteur RSVP (Rapid Serial Visual Presentation) : les mots défilent un par un,
la lettre de focus reste toujours à la même position. De 100 à 900 mots/minute.

Tout se passe dans le navigateur. Aucun texte n'est envoyé nulle part :
pas de requête réseau, pas de serveur, pas de stockage distant.

## Mise en ligne

1. Créer un dépôt GitHub public et y envoyer les 8 fichiers, tous à la racine (aucun sous-dossier).
2. Settings → Pages → Source : `main`, dossier `/ (root)`. Attendre ~1 min.
3. Ouvrir `https://<compte>.github.io/<depot>/` sur le téléphone.
4. Menu Chrome → **Installer l'application**.

## Formats acceptés

`.txt`, `.md`, `.html`, `.docx` (décompressé nativement par le navigateur),
ou simple copier-coller.

## Raccourcis

| Touche | Action |
|---|---|
| Espace | lecture / pause |
| ← → | reculer, avancer de 10 mots (50 avec Maj) |
| ↑ ↓ | vitesse ±25 mpm |
| Échap | revenir à l'accueil |

## Mettre à jour

Après avoir modifié `index.html`, incrémenter `CACHE` dans `sw.js`
(`lecteur-rapide-v1` → `v2`), sinon les appareils déjà installés
garderont l'ancienne version en cache.
