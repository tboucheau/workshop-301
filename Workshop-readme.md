#OVH projet cloud public
- code du projet : TGKD-TWHK

##Infrastructures As Code
###Workshop avancé (301)

L'Infrastructure As Code permet de gérer son infrastructure (servers, networks, cloud stuffs, storage, ...) avec du code.

Comme c'est du code, on va pouvoir le versionner, l'automatiser et le traiter avec des algorithmes.

###DEV
Flexible, manipulable à la main, faire évoluer simplement. CLI OpenStack avec CloudInit (post configuration lors du démarrage du serveur)

###TEST
Très proche de la prod, industrialiser à un haut niveau, lancer du test. Objectif, un bouton pour déployer (Terraform)

###PROD
Les tests sont OK (validé en phase de test). J'ai flaggué un code comme "production ready" que je veux utiliser en prod

##Déroulement
- SSH sur un bastion
- Navigateur pour avoir accès au repo GIT

##Préparation
Créer d'un projet CLOUD public "Workshop-301" avec le voucher
Ajouter le vrack "pn-41308" au projet cloud
créer un utilisateur openstack "wmWnaZSE6VjR" "2T6svJE9ahmsPfWhKusjMRrTBhEYc4MR"
créer un fichier credentials avec le fichier de confiruation de l'utilisateur

##DEV
création des fichiers de provisionning back, front et script-up
bien sourcer le fichier credential
execution "bash script-up"
récupération de l'IP public "openstack server list" : 54.37.23.158, 153, 148, 145 (front, back, front, back) car j'ai lancé le script deux fois
