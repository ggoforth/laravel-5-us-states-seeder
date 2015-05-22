#Laravel 5 State Seeder

**Usage**

```bash
$ php artisan make:model State
```

This will generate the model and migration for your database.  Then simply drop the `StatesSeeder.php` into your `seeds` folder.  Back at the command line run:

```bash
$ php artisan migrate
$ php artisan db:seed
```

You'll now have a functional States database suitable for populating drop downs or whatever else you crazy kids do with your states tables.
