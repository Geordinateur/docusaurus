# Pense-bête Neovim avec kickstart.nvim

## Raccourcis Personnalisés

### Commandes de Fichier
- `<leader>w` : Sauvegarder le fichier
- `<leader>q` : Quitter Neovim
- `<leader>x` : Sauvegarder et quitter

### Navigation et Mouvement
- `Ctrl + h` : Aller à la fenêtre de gauche
- `Ctrl + j` : Aller à la fenêtre du bas
- `Ctrl + k` : Aller à la fenêtre du haut
- `Ctrl + l` : Aller à la fenêtre de droite

### Gestion des Fenêtres
- `<leader>sv` : Diviser la fenêtre verticalement
- `<leader>sh` : Diviser la fenêtre horizontalement
- `<leader>sc` : Fermer la fenêtre courante
- `<leader>se` : Équilibrer les fenêtres

### Recherche et Remplacement
- `<leader>ff` : Trouver des fichiers
- `<leader>fg` : Rechercher du texte dans les fichiers
- `<leader>fb` : Rechercher dans les buffers
- `<leader>fh` : Trouver dans l'historique

### Gestion des Buffers
- `<leader>bn` : Aller au buffer suivant
- `<leader>bp` : Aller au buffer précédent
- `<leader>bd` : Fermer le buffer courant

### Gestion des Plugins
- `<leader>pi` : Installer les plugins
- `<leader>ps` : Synchroniser les plugins
- `<leader>pc` : Nettoyer les plugins inutilisés
- `<leader>pu` : Mettre à jour les plugins

### Débogage et Tests
- `<leader>tt` : Exécuter les tests
- `<leader>tn` : Exécuter le test suivant
- `<leader>tp` : Exécuter le test précédent

### Git Integration
- `<leader>gs` : Statut Git
- `<leader>gc` : Commit Git
- `<leader>gp` : Push Git
- `<leader>gl` : Log Git

### Nvim-Tree
- `<leader>e` : Afficher/Masquer Nvim-Tree

### Pliage de Code (Folding)
- `zM` : Fermer tous les pliages
- `zR` : Ouvrir tous les pliages

## Plugins Utilisés
- **Telescope** : Interface de recherche
- **Lualine** : Barre de statut
- **Treesitter** : Amélioration de la coloration syntaxique
- **Nvim-LSP** : Support Language Server Protocol
- **GitSigns** : Indicateurs Git
- **Nvim-Tree** : Explorateur de fichiers

## Commandes Utiles
- `:PackerInstall` : Installer les plugins
- `:PackerSync` : Synchroniser les plugins
- `:PackerClean` : Nettoyer les plugins inutilisés
- `:PackerUpdate` : Mettre à jour les plugins
- `:LspInfo` : Informations sur le LSP
- `:Mason` : Interface de gestion des serveurs LSP, DAP, Linters & Formatters
- `:TSUpdate` : Mettre à jour Treesitter

## Configuration Personnalisée
- **Fichier de configuration** : `init.lua`
- **Dossier des plugins** : `lua/user/plugins`

### Raccourcis pour le LSP (Language Server Protocol)
- `gd` : Aller à la définition
- `gD` : Aller à la déclaration
- `gi` : Aller à l'implémentation
- `gr` : Voir les références
- `K` : Afficher la documentation flottante
- `<leader>rn` : Renommer
- `<leader>ca` : Actions de code

### Linting et Formatting
- `<leader>lf` : Formater le fichier courant
- `<leader>li` : Afficher les diagnostics
- `<leader>ln` : Aller au diagnostic suivant
- `<leader>lp` : Aller au diagnostic précédent

### Manipulation de Texte
- `>` : Indenter la ligne sélectionnée vers la droite
- `<` : Indenter la ligne sélectionnée vers la gauche
- `=` : Ré-indenter la ligne courante
- `ciw` : Changer le mot sous le curseur
- `caw` : Changer tout le mot sous le curseur
- `:x,y s/^/c/` : Ajout de `c` au **début** de la ligne x à la ligne y
- `:x,y s/$/c/` : Ajout de `c` à la **fin** de la ligne x à la ligne y
- `:%s/a/b/g` : Modifie les occurences de `a` par `b` sur tout le fichier
- `:x,y s/a/b/g` : `Modifie les occurences de `a` par `b` de la ligne x à la ligne y
- `:x,y sort` : Trie une plage de lignes
- `:x,y [copy/move] z` : Copie oú déplace une plage de ligne après la ligne z

### Macros et Enregistrements
- `q<letter>` : Commencer l'enregistrement d'une macro dans le registre `<letter>`
- `q` : Arrêter l'enregistrement
- `@<letter>` : Exécuter la macro du registre `<letter>`

### Utilisation Avancée de Nvim-Tree
- `a` : Ajouter un nouveau fichier
- `r` : Renommer un fichier ou un dossier
- `d` : Supprimer un fichier ou un dossier
- `R` : Rafraîchir l'arborescence
- `x` : Couper un fichier
- `c` : Copier un fichier
- `p` : Coller un fichier

### Gestion des Onglets (Tabs)
- `:tabnew` : Ouvrir un nouvel onglet
- `:tabc` : Fermer l'onglet courant
- `gt` : Aller à l'onglet suivant
- `gT` : Aller à l'onglet précédent
- `K` : Aller à l'onglet suivant
- `J` : Aller à l'onglet précédent

### Mode Visuel
- `v` : Mode visuel
- `V` : Mode visuel en ligne
- `Ctrl + v` : Mode visuel en blocs