                                                                                        Dimanche, 22 Decembre 2024
                                                                                        Bachelor 2 keyce Informatique & IA



//////// Description de notre projet //////////

Il s'agit la d'un projet de Gestion d'un parc informatique de maniere automatique Nommee SGPI.Auto pour : Systeme de Gestion d'un Parc Informatique

1** Ressources utilisees : 
                            a** Framework php Codeigniter 4.5.5
                            b** Editeur de texte : VS code
                            c** Serveur local: XAMPP SERVER
2** Guide d'installation : 
                            a** Installez XAMPP-SERVER
                            b** creer une base de donnee au nom gestion_parc_info puis importer celle associe au projet
                            c** placer le projet dans le repertoire : C:\Users\hp\Desktop\Projet_CI_Parc-Info\CI_Gestion_Parc_Info
                            ensuite ouvrer-le avec VScode puis ouvrir le terminal associe a VScode et lancer la commande "php spark serve", ouvrir une nouvel onglet dans votre navigateur et taper http://localhost:8080/.

3** Guide d'utilisation : a** Vous serez diriger vers une page d'authentification :
a ce stade vous avez 4 niveau de connexion : {Administrateur} :** Tous droits reserves **;
                                             {Gestionnaire} : Acces uniquement au stock;
                                             {Technicien} : Acces uniquement au poste pour voir les pannes;
                                             {Employe} : Acces uniquement pour signaler une panne;
                

                3.1** Administrateur :

                    Peut tout faire:
                    -Lire, Enregistrer, Modifier , Supprimer et meme Restaurer un utilisateur:
                        ***Dans le menu Utilisateur qui possede trois sous menu :
                                --Listes des utilisateurs: on a la possibilite de lister , modifier et supprimer un utilisateur;
                                --Ajouter utilisateur : 
                                    le formulaire d'ajout d'un utilisateur permetant d'enregistrer un utilisateur
                                --historique utilisateurs :
                                ou l'on retrouve les utilisateurs supprimes et l'on a la possibilite de les [suppimer definitivement] ou de les [restaurer]
                        ***Dans le menu stock:
                                --Fournisseur : l'on peut voir la listes des fournnisseurs, enregistrer un nouvau fournisseur, en editer un ou le supprimer.
                                --Magasin : 
                                    **equipement : CRUD des quipements 
                                    **logiciel :CRUD des logiciels mais avant il faudrait qu'il y est deja des licence_logiciels
                                    **licence-logiciel : CRUD des licences
                3.2** Gestionnaire : ne peut acceder qu'au stock
                                --Fournisseurs: CRUD des fournisseurs
                                --Magasin : CRUD des logiciel, licence_logiciel et equipements
                

4** Informations de connexion :
                                Administrateur : [
                                    'email':NjiyimFarel@gmail.com
                                    'mot de passe':NjiyimFarel@gmail.com2005
                                ];
                                Gestionnaire : [
                                    'email':DanAril@gmail.com
                                    'mot de passe':DanAril@gmail.com2005
                                ];
                                 Technicien : [
                                    'email':simochritian@gmail.com
                                    'mot de passe':simochritian@gmail.com2005
                                ];
                                 Employe : [
                                    'email':tcoupon@gmail.com
                                    'mot de passe':tcoupon@gmail.com2005
                                ];

/******************************************* NB: Il y a pa de controle de saisie sur les formulaires **********************/
