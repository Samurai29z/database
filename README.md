# database
1 requete pour ajouter un film :
                                 insert into 'cinema'.'information films' ('titre','date de sortie','duree') VALUES ('titre du film','date','duree');
2-requete pour modifier un film:
                                 UPDATE information films
                                 SET (ecrire la modification sans les parenthese),
                                 WHERE id = (identifiant de la ligne a modifier sans les parentheses)
3-requete pour supprimer un film:
                                 DELETE FROM 'information films'
                                 WHERE 'id' = (identifiant du film a supprimer sans les parentheses)
4-requete pour ajouter un client:
                                 insert into 'cinema'.'information clients' ('idclient','nom','prenom','email') VALUES ('id','le nom','le prenom','l'email);

5-requete pour modifier un client:
                                  UPDATE information client
                                 SET (ecrire la modification sans les parenthese),
                                 WHERE id = (identifiant de la ligne a modifier sans les parentheses)

6-requete pour supprimer un client:
                                   DELETE FROM 'information client'
                                 WHERE 'id' = (identifiant du film a supprimer sans les parentheses)

7-requete pour afficher les 03 derniers films ajouter:
                                         SELECT TOP 3 * FROM information films