# Biblioth-que

Projet bibliothèque fait par Carla JULLIEN et Martin POINTEAU élèves de pré ing 1 groupe 5

Nous n'avons pas réussis a créer un makefile nous avons donc regrouper tout le code dans le même fichier et il faudra effectuer la commande gcc -o dans le terminal.
le code a été réalisé et tester intégralement sur les ordinateurs de l'école il ne présentait aucune erreur durant les tests.
ce que notre programme fait : 
- nouvel utilisateur avec un rôle (prof / étudiant) / connexion 

- propose un choix entre emprunter un livre / rendre un livre / voir nos livres disponible / se déconnecter / créer un nouveau livre (disponible seulement pour les profs)
- choix emprunter : on peut rechercher un livre par titre / auteur / catégorie (les livres seront toujours afficher par ordre alphabétique) puis emprunter un livre ou afficher directement toute la liste de livre disponible puis emprunter un livre, les livres emprunter par d'autres utilisateurs ne sont pas disponible, 3 livres max et 120 secondes chacun pour les élèves, 5 max et 180 secondes chacun pour les profs, si un livre n'est pas rendu a l'heure l'utilisateurs ne peut plus empruntés tant qu'il n'a pas rendu tout ses livres ou il est en retard

- choix rendre un livre : on affiche les livres déjà emprunter et le nombre de secondes avant que l'utilisateur sois en retard sur chaque livre,  puis rendre le livre de notre choix, ce qui les rendra disponibles a rempruntés pour tout le monde

- choix afficher les livres empruntés : affiche les livres empruntés par l'utilisateurs et le nombre de secondes qu'il lui reste pour chaque livre 

- choix se déconnecter : affiche un message d'au revoir et se quitte le programme

- choix créer un livre : les profs peuvent ajouter un livre dans la liste en inscrivant le titre l'auteur et la catégorie, le programme associe tout seul le numéro du livre.

chaque action concernant les livres s'effectue avec leur numéro d'identification, les commentaires sont en anglais, pour associer les livres aux utilisateurs le programme inscrit le numéro des livres sur le fichier iden et inscrit 00 une fois qu'ils les rendent, le programme modifie le 1 en 0 dans le fichier listlivre lorsque un livre est empruntés et remet un 1 lorsque il est rendu, le programme inscrit l'heure limite de rendu des livres empruntés dans le fichier heure pour chaque utilisateur et pour chaque livre puis réinscrit le nombre 2111111111 lorsqu'il est rendu.
