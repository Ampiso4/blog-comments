# blog-comments

Dépôt public, vide par conception. Il n'héberge pas de code : il sert uniquement de
support aux **Discussions GitHub** qui alimentent les commentaires de
[blog.ampisoa.men](https://blog.ampisoa.men) via [Giscus](https://giscus.app).

Un fil de discussion par billet, créé automatiquement au premier commentaire.

## Pourquoi un dépôt séparé

Le dépôt du blog est privé. Giscus exige un dépôt public et les Discussions
activées. Un dépôt dédié évite d'exposer l'historique du site et isole les
commentaires du code.

## Modération

Aucune. Écrire demande un compte GitHub, ce qui suffit à filtrer le spam.

## Configuration

Les identifiants (`repoId`, `categoryId`) sont renseignés dans
`src/lib/site.ts` du dépôt du blog. Tant qu'ils sont vides, aucun bloc de
commentaire n'est rendu.
