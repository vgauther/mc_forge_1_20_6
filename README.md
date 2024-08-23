# Minecrat Server 1.20.1

## Pour installer le server
Étape 1
```
git clone https://github.com/vgauther/mc_forge_1_20_6.git
```
Étape 2

```
cd mc_forge_1_20_6
sh installer.sh
```

Étape 3 
Il faut modifier le fichier run.sh pour ajouter `-nogui`. Ici, avec Vim mais nano ou emacs fonctionnent très bien.
```
vi run.sh
```
Il faut rajouter -nogui avant le dernier paramètre

Étape 4
```
sh run.sh
```

Étape 5
```
vi eula.txt
```
dans ce fichier, il faut remplacer `false` par `true`

Étape 6 
Relancer le serveur

```
sh run.sh
```
## Pour les joueurs

Il faut installer forge pour la version 1.20.1 
0-> Installer Minecraft et lancer le jeu avec la derniere version
1-> Télécharger : https://maven.minecraftforge.net/net/minecraftforge/forge/1.20.1-47.3.0/forge-1.20.1-47.3.0-installer.jar
2-> Ouvrir le fichier .jar avec Java (normalement c'est ce qui est choisi par défaut) et Choissir Install Client
3-> Lancer la version Forge de Minecraft depuis le Laucher Minecraft (Normalement elle a une icone de four et s'appelle configuration sans nom)
4-> Attendre que ca se lance et fermer le jeu
5-> Télécharger les mods contenu ici : https://github.com/vgauther/mc_forge_1_20_6/tree/main en cliquant sur Code en Vert puis Download as Zip
6-> Dézipper et mettre le contenu du dossier mods dans le .minecraft/mods (si le dossier mods n'existe pas il faut le créer) pour aller dans le .minecraft faire Windows + R et entrer %appdata% 
7-> relancer le jeu et c'est bon

Liste Mod Lucas
RGP Style More Weapon
Winery
Botania
Dungeons And Taverns
Epic Dungeons
Applaied Energistics
Warp Portals
Rotted
Minecolonies
Gravestone
AdditionalEnchantedMiner
THT (Truc des arbres)
Region Unexplored
Productive Bees
