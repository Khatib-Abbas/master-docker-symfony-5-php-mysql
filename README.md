VOIR DOCUMENTATION INSTALLATION DOCKER dans /documentation_installation
############ première instalation ################

#configurer git
Run
  git config --global user.email "abbas.khatib@ulb.be"
  git config --global user.name "khatib abbas"
symfony new --full my_project OU  symfony new my_project
############ première instalation ################

############ donner la permission de supprimer le cache ############
docker exec -ti www_1  bash
chmod 777 -R microservice/var
############ donner la permission de supprimer le cache ############


docker exec -ti www_1  bash
cd VOTRE_DOSSIER