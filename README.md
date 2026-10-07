# ROC · Ma licence FFN

Application du Royan Océan Club Natation pour remplir les formulaires FFN 2026–2027, signer à la souris ou au doigt et télécharger les PDF complétés. Les formulaires majeur et mineur sont disponibles sur téléphone, tablette et ordinateur.

## Accéder à l’application

- GitHub Pages : https://sylvain0507.github.io/roc-licences-ffn-2027/
- Version également disponible via Sites : https://roc-licences-ffn-2027.sylvainbeq.chatgpt.site/

## Confidentialité

Les coordonnées, les réponses de santé et la signature sont traitées dans le navigateur, en mémoire. Aucune donnée saisie n’est envoyée au serveur de l’application. La fermeture ou le rechargement de la page efface la saisie. Le PDF téléchargé contient les informations renseignées, y compris les réponses de santé. Il reste sous la responsabilité de l’utilisateur et doit ensuite être déposé manuellement dans Swim Community.

Ce dépôt contient le code, le logo et les PDF vierges, sans dossier complété d’adhérent.

## Fonctionnement

L’application propose un parcours en cinq étapes : coordonnées, licence, santé et autorisations, assurance et encadrement, signature et téléchargement. Chaque réponse Oui ou Non est inscrite dans le questionnaire de santé du PDF. L’attestation de réponses négatives n’est complétée que si toutes les réponses sont NON et que l’utilisateur la confirme.

## Hébergement GitHub Pages

Dans **Settings → Pages**, choisir **Deploy from a branch**, puis la branche **main** et le dossier **/(root)**. Le site est mis à jour lors des nouvelles publications sur cette branche.

Les fichiers HTML, CSS, JavaScript, images et PDF sont servis directement depuis la racine du dépôt. Aucune compilation ni base de données n’est nécessaire.

## Composants et documents

- Le logo appartient au Royan Océan Club Natation.
- Les formulaires FFN sont ceux fournis par le club ; leur mise en page est conservée.
- `pdf-lib` est utilisé sous licence MIT, reproduite dans `pdf-lib-LICENSE.md`.

Ce dépôt n’accorde pas de licence générale sur les documents FFN ou le logo du club.
