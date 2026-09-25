# wonder

Application web construite avec **Symfony 7**. Projet d'apprentissage du
framework (Doctrine ORM, AssetMapper, Twig, Security).

> **Work in progress** — le squelette applicatif Symfony est en place
> (configuration, sécurité, migrations Doctrine). Les entités, contrôleurs et
> vues sont en cours de développement.

## Stack technique

- **PHP 8.2+**
- **Symfony 7.1** (Console, AssetMapper, Twig, Security, Messenger)
- **Doctrine ORM 3** + migrations
- **Docker Compose** pour l'environnement de développement

## Mise en route

Prérequis : PHP 8.2+, Composer et Docker.

```bash
composer install
docker compose up -d        # base de données
symfony server:start        # ou : php -S localhost:8000 -t public
```

Copier `.env` vers `.env.local` et y renseigner vos propres identifiants avant
de lancer l'application. **Ne pas committer de secrets.**

## Licence

Distribué sous licence MIT. Voir [LICENSE](LICENSE).
