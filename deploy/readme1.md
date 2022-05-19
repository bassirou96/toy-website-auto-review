Votre équipe vous a indiqué qu’elle apprécie d’obtenir le feedback du linter Bicep sur les modifications de code avant de les envoyer à d’autres membres de l’équipe pour révision. Vous avez maintenant décidé de fournir à vos contributeurs et à vos réviseurs la possibilité de déployer et réviser leur code dans un environnement éphémère.

Dans cet exercice, vous allez mettre à jour votre workflow de demande de tirage pour déployer un environnement éphémère chaque fois qu’une demande de tirage est ouverte, puis le redéployer quand le code est envoyé à la branche de la demande de tirage. Vous allez aussi créer un autre workflow pour supprimer automatiquement l’environnement quand la demande de tirage est fermée. Vous allez tester vos modifications en créant une demande de tirage pour que votre site web utilise une image de conteneur Docker.

Pendant ce processus, vous allez :

Mettez à jour le workflow de demande de tirage pour déployer un environnement éphémère.
Créez un workflow de suppression de demande de tirage pour supprimer l’environnement éphémère.
Créez une demande de tirage et observez la création de l’environnement éphémère.
Approuvez la demande de tirage et observez la suppression de l’environnement éphémère.