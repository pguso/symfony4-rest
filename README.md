## Installing

```
composer install
```

## Database

```
bin/console doctrine:database:create
bin/console doctrine:migrations:migrate
bin/console hautelook:fixtures:load

```

## Todo

- [ ] Fix resources scss
- [ ] Fix resources font-awesome
- [ ] Implement API
- [ ] Fix unit test for different environments (dev and test should differ)