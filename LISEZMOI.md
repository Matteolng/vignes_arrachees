# Vignes arrachées, Entre-deux-Mers

Site du projet de Matteo Lannelongue : que deviennent les vignes arrachées, et qu'en faire ?

## Contenu du dossier

| Fichier | Rôle |
|---|---|
| `index.html` | La page |
| `data.js` | Les données des 8 501 parcelles (export du pipeline du 12 octobre 2026) |
| `img/` | Les figures |
| `videos/vignes_arrachees.mp4` | La vidéo explicative (5 min, 13 Mo) |
| `videos/vignes_arrachees.jpg` | L'image affichée avant la lecture |

Garde exactement cette arborescence : la page cherche la vidéo dans `videos/` à côté d'elle. Les noms sont sensibles à la casse.

## Mettre le site en ligne avec GitHub Pages

1. Crée un dépôt public sur GitHub (par exemple `vignes-arrachees`).
2. Dans le dépôt : **Add file**, puis **Upload files**. Glisse le contenu du dossier (les fichiers `index.html`, `data.js` et les dossiers `img` et `videos`), pas le dossier parent. Valide avec **Commit changes**.
3. Va dans **Settings**, puis **Pages** (section « Code, planning, and automation »).
4. Sous **Build and deployment**, choisis **Source : Deploy from a branch**, la branche `main` et le dossier `/(root)`, puis **Save**.
5. Après une à deux minutes, le site est en ligne à l'adresse `https://<ton-identifiant>.github.io/vignes-arrachees/`.

Par le navigateur, GitHub accepte des fichiers de 25 Mo au plus : la vidéo fait 13 Mo, elle passe.

## Si la vidéo ne s'affiche pas

* Vérifie que `videos/vignes_arrachees.mp4` est bien dans le dépôt, à ce chemin exact.
* Ouvre `https://<ton-identifiant>.github.io/vignes-arrachees/videos/vignes_arrachees.mp4` : si le fichier ne se lit pas, il manque ou il est mal nommé.
* Le reste du site fonctionne sans la vidéo, qui affiche alors un message à sa place.
