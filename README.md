# ⚔ DnD Manage — la table de jeu chez soi

La table de jeu de ton groupe de jeu de rôle, dans le navigateur : fiches de personnages, carte et
pions, brouillard de guerre, initiative, bestiaire, sorts, ambiances musicales, appels — pour le
Maître du Jeu et ses joueurs.

Ce dépôt contient uniquement les **installeurs** (voir **[Releases](../../releases/latest)**).

## Installer

### Sur un PC Windows (le plus simple)

1. Télécharger **`DnDManage-Installeur-x.y.z.exe`** dans la [dernière version](../../releases/latest).
2. Le lancer : « Suivant, Suivant, Installer » — aucun droit d'administrateur demandé.
3. Ouvrir **DnD Manage** (menu Démarrer ou bureau). Une fenêtre noire s'ouvre — elle fait tourner le
   site, la garder ouverte pendant la partie — puis le navigateur.
4. Le **Grimoire** (assistant) crée ton compte de Maître du Jeu et installe une première aventure,
   *La Crypte de l'Aube*, avec 4 personnages prétirés.
5. Si Windows demande d'autoriser l'accès au réseau : accepter (réseaux privés), pour que tes joueurs
   puissent te rejoindre.

Tes campagnes sont rangées dans `Documents\DnD Manage` (à sauvegarder).

### Sur un serveur Linux (Docker)

```bash
curl -fsSL https://github.com/piouscott/dndmanage-installeur/releases/latest/download/install.sh | bash
```

ou à la main :

```bash
docker run -d --name dndmanage -p 8765:8765 -v dndmanage-data:/data ghcr.io/piouscott/dndmanage:latest
```

## Jouer à distance

L'assistant peut ouvrir un **lien Internet** gratuit (via Cloudflare), sans compte ni réglage de la
box. Il change à chaque démarrage : le bouton « Copier le lien d'invitation » donne toujours le bon.

## Licence du contenu de règles

Monstres et sorts : *Document de Référence du Système 5.1* (SRD 5.1, version française) de Wizards of
the Coast, sous licence [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).
Dungeons & Dragons est une marque de Wizards of the Coast ; DnD Manage n'est ni affilié ni approuvé
par Wizards of the Coast. La campagne de démonstration, sa carte et les illustrations sont originales.
