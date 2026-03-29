 Lab 02 — Manipulation de fichiers et répertoires

 Objectif
Maîtriser la création, copie, déplacement et suppression
de fichiers et répertoires en ligne de commande.

 Commandes pratiquées

| Commande | Description | Exemple |
|----------|-------------|---------|
| `touch` | Créer un fichier vide | `touch fichier.txt` |
| `mkdir` | Créer un répertoire | `mkdir mon-dossier` |
| `mkdir -p` | Créer des répertoires imbriqués | `mkdir -p a/b/c` |
| `cp` | Copier un fichier | `cp source.txt dest.txt` |
| `cp -r` | Copier un répertoire | `cp -r dossier/ copie/` |
| `mv` | Déplacer ou renommer | `mv ancien.txt nouveau.txt` |
| `rm` | Supprimer un fichier | `rm fichier.txt` |
| `rm -r` | Supprimer un répertoire | `rm -r dossier/` |
| `cat` | Afficher le contenu | `cat fichier.txt` |

 Attention
- `rm -r` supprime TOUT sans confirmation
- `rm -rf /` → NE JAMAIS EXÉCUTER (détruit tout le système)
- Toujours vérifier avec `ls` avant de supprimer

 Captures
À ajouter après le lab
