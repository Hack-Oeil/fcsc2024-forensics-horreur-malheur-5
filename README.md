# FCSC 2024 Horreur, malheur 5/5 - Un peu de CTI

Vous venez d’être embauché en tant que Responsable de la Sécurité des Systèmes d’Information (RSSI) d’une entreprise stratégique.

En arrivant à votre bureau le premier jour, vous vous rendez compte que votre prédécesseur vous a laissé une clé USB avec une note dessus : *VPN compromis (intégrité). Version 22.3R1 b1647*.

Vous avez presque fini votre analyse ! Il ne vous reste plus qu’à qualifier l’adresse IP présente dans la dernière commande utilisée par l’attaquant.

Vous devez déterminer à quel groupe d’attaquant appartient cette adresse IP ainsi que l’interface de gestion légitime qui était exposée au moment de l’attaque.

Le flag est au format : *FCSC{<UNCXXXX>:<nom du service>}*.

**Remarque** : Il s’agit d’une véritable adresse IP malveillante, **n’interagissez pas** directement avec cette adresse IP.

Cette épreuve a été découpée en cinq parties :

- Horreur, malheur 1/5 - Archive chiffrée.
- Horreur, malheur 2/5 - Accès initial.
- Horreur, malheur 3/5 - Simple persistance.
- Horreur, malheur 4/5 - Pas si simple persistance.
- **Horreur, malheur 5/5 - Un peu de CTI.**

Auteurs : \E

Origine : [Horreur, malheur 5/5 - Un peu de CTI](https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-5/)


Fichiers :
- [archive.encrypted](archive.encrypted)
- [horreur-malheur.tar.xz](horreur-malheur.tar.xz)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-horreur-malheur-5.git

> cd fcsc2024-forensics-horreur-malheur-5


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-5/