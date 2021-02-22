Voici les commandes de base pour git

#gestion du depot
git clone <url:ssh\http>  => cloner un depot distant local (copie)
git fetch => recupere un maximum d'infos

#branches 
git branch => Lister les branches
git checkout<branche> => se deplacer sur une branche existante
git checkout -b <branche> => cree et se deplacer sur une nouvelle branche
git pull => vient recuperer les changements depuis le remote sur le local

#commits
#apres une/des modification(s) vous pouvez ajouter ces/cette modification et la documenter(message)
git add <fichier> => ajouter le fichier nouvellemnt cree ou modifie au prochain commit
git commit -m "message" => creer le commit avec les ajouts precedents accompagne d'un message
git push => pousser le commit en ligne
git push --set-upstream origin <remote-branch> => pour une branche nouvellement creee,il faut la 
