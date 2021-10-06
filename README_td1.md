# TD noté 1 : Déploiement d'une application Web

Le code source d'une application vous est fourni par l'équipe de développement. Vous devez la déployer sur une infrastructure AWS. À la fin du déploiement, vous devrez fournir un rapport indiquant la méthode utilisée, ses avantages et ses inconvénients. Vous devrez détailler chaque étape et montrer ce que vous avez fait à l'aide de capture d'écran.

Liens des codes sources : 

* https://github.com/vportascarta/petite-caisse-frontend/tree/for-teaching

* https://github.com/vportascarta/petite-caisse-backend/tree/for-teaching

## Analyse du logiciel

Dans une première partie, vous effectuerez l'analyse du logiciel fourni, langage utilisé, fonctionnement, etc. Vous indiquerez les besoins fondamentaux de l'application (type de base de données, secrets, etc) et donc les services AWS qui peuvent répondre à vos besoins. Pour chaque besoin, indiquez un maximum de services différents possible.

## Choix de l'architecture AWS

Une fois les besoins identifiés, vous allez devoir définir une architecture pour votre infrastructure. Sélectionner parmi les services listés ceux dont vous aurez besoin. JUSTIFIER CHAQUE CHOIX (prix, sécurité, facilité de gestion, élasticité, etc.).

À l'aide de draw.io ou de l'éditeur de CloudFormation, faites le schéma de votre architecture. 

## Mise en place

Déployer votre architecture, avec la méthode de votre choix. Chaque étape devra être clairement indiquée et des captures d'écrans devront être faites. La totalité de votre méthode doit être reproductible par Mme Michu à l'aide de cette section. 

Une fois l'application fonctionnelle, envoyer le lien pour vérification. 

## Critiques

Vous avez choisi une architecture parmi plusieurs possibles. Définissez une nouvelle architecture utilisant des services différents, ayant des différences majeures avec la vôtre (le simple fait de passer de MariaDB à Postgres n'est pas considéré comme un changement majeur ! ). Expliquez les différences entre les deux architectures. Faites un tableau comparatif des points positifs et négatifs de chaque solution.
