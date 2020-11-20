# ECWFinale2020

Cette année, j'ai eu la chance de participer à le finale de l'European Cyber Week, organisé par le Pôle d'Excellence Cyber et Airbus. C'était ma première expérience d'un CTF en "lab", et ce fut pour moi une excellente introduction à ce type d'environnement plus réaliste.

Cet événement s'est tenu le 18/11/2020, de 10h à 17h, et était en équipes de 4. Mon équipe était composée de `Killbit` et `D3DS3C` de l'INSA Toulouse, et de `Kkameleon` et moi-même de Télécom Paris. Nous avons fini à la 8ème place sur un total de 12 équipes.

N'ayant pas l'habitude des environnements "lab", je pense a posteriori que nous ne nous sommes pas assez focalisé sur la reconnaissance du réseau. En effet, il n'était pas rare que nous ne trouvions pas toutes les machines sur lesquelles étaient présent un challenge, et que nous ne sachions pas où chercher. Nous réalisions tous nos scans nmap sur `192.168.0.0/16`, ce qui prenait un temps très long et n'était pas économique, alors qu'une meilleure connaissance du réseau aurait permis de ne scanner qu'une dizaine de `/24`... Pour ma part, ceci est probablement dû à un manque de pratique en réseau et en reconnaissance. Une forte corrélation a pu être observée entre les équipes ayant su obtenir une cartographie du réseau suffisante si ce n'est parfaite et leur rang dans le classement.

En ce qui concerne la résolution des challenges, nous avons globalement pu résoudre la majorité des challenges que nous avons trouvé dans le lab. Ceux-ci comprenaient des injections SQL, un challenge de cryptographie sur les courbes elliptiques, un transfert de zone DNS, de la "stéganographie" (c'est un grand mot poir décrire le challenge, il suffisait de regarder dans les EXIFs d'images), et quelques challenges plus atypiques.

### Topologie réelle du réseau

