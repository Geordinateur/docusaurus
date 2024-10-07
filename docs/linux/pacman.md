# Pacman

## Installer un paquet 
```pacman -S *pkg*```

## Installer et mettre à jour la liste des paquets
```pacman -Syu *pkg*```

## Désinstaller un paquet 
```pacman -Rsc *pkg*```

## Chercher un paquet 
```pacman -Ss *query*```

## Faire une upgrade 
```pacman -Syu```

## Lister les paquets installés 
```pacman -Qe```

## Chercher un paquet installé 
```pacman -Qs *query*```

## Lister les paquets inutiles
```pacman -Qdt```

## Désinstaller les paquets inutiles
```pacman -Rns $(pacman -Qdtq)```
