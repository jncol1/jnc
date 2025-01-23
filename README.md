# ceci est un test
Gestion des branches dans GitHub Desktop
Vous pouvez utiliser GitHub Desktop pour créer une branche à partir d’une branche existante dans votre dépôt afin de pouvoir tester les modifications en toute sécurité.

Platform navigation
Mac
Windows
Dans cet article
À propos de la gestion des branches
Création d'une branche
Création d’une branche à partir d’un commit précédent
Publication d’une branche
Basculement entre les branches
Suppression d’une branche
Pour aller plus loin
À propos de la gestion des branches
Vous pouvez utiliser les branches pour tester sans risques les changements apportés à votre projet. Les branches isolent votre travail de développement des autres branches du dépôt. Par exemple, vous pouvez utiliser une branche pour développer une nouvelle fonctionnalité ou résoudre un bogue.

Vous créez toujours une branche à partir d’une branche existante. En règle générale, vous pouvez créer une branche à partir de la branche par défaut de votre dépôt. Vous pouvez ensuite travailler sur cette nouvelle branche indépendamment des changements apportés au dépôt par d’autres personnes.

Vous pouvez également créer une branche à partir d’un commit précédent dans l’historique d’une branche. Cela peut être utile si vous devez retourner à une vue antérieure du dépôt pour investiguer un bogue ou pour créer un correctif logiciel ciblant votre dernière mise en production.

Une fois que vous êtes satisfait de votre travail, vous pouvez créer une demande de tirage (pull request) pour fusionner les changements que vous avez apportés dans la branche actuelle avec une autre branche. Pour plus d’informations, consultez « Création d’un problème ou d’une demande de tirage (pull request) à partir de GitHub Desktop » et « À propos des demandes de tirage (pull requests) ».

Vous pouvez toujours créer une branche dans GitHub Desktop si vous disposez d’un accès en lecture à un dépôt, mais vous pouvez uniquement pousser la branche vers GitHub si vous disposez d’un accès en écriture au dépôt.

Les administrateurs de dépôt peuvent activer des protections sur une branche. Si vous travaillez sur une branche protégée, vous ne pouvez pas supprimer une branche ni forcer une poussée (push) vers la branche. Les administrateurs de référentiel peuvent également activer d’autres paramètres de branche protégée pour appliquer des workflows spécifiques avant qu’une branche ne puisse être fusionnée. Pour plus d’informations, consultez « À propos des branches protégées ».

Les administrateurs de référentiel peuvent également activer des ensembles de règles. Les ensembles de règles peuvent être utilisés pour exiger des noms de branche spécifiques pendant la création d’une nouvelle branche ou pour autoriser uniquement les utilisateurs disposant d’autorisations de contournement à publier une nouvelle branche dans le référentiel à distance. GitHub Desktop affiche un avertissement et empêche la création de la branche si celle-ci ne respecte pas les ensembles de règles. Pour plus d’informations, consultez « À propos des ensembles de règles ».
