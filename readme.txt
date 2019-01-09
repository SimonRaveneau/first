

Tout d'abord les commandes de base :

# 1 - Tu initialises ton d�p�t local
$ git init

# 2 - Tu ajoutes l'URL vers ton d�p�t distant (GitHub)
$ git remote add origin git@github.com:br1o/Basics.git

# 3 - Tu r�cup�re les modifications distantes
$ git pull origin master

# 4 - Tu ajoutes toutes tes modifications locales
$ git add .

# 5 - Tu commit le tout
$ git commit -m"Ajout des sources de Basics"

# 6 - Tu pousses tes commits vers le d�p�t distant (GitHub)
$ git push origin master

# A tout moment, tu peux utiliser cette commande pour voir l'�tat de ton d�p�t local :
$ git status


# A chaque fois que tu auras des modifications que tu souhaites commiter :
$ git add mon_fichier_1.php mon_fichier_2.php ...
$ git commit -m"Mon super message de commit"
$ git push origin master

