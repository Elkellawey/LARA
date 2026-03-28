# LARA

## Run locally (PHP)

```bash
<<<<<<< HEAD
php -S 127.0.0.1:8000 router.php
=======
php -S 127.0.0.1:8000 -t .
>>>>>>> ed681df (added data/menu.json which contains all the items and categories details && added ConvertJsonToObject class which used to convert json to object to use in index file and replaced the old html by php and used the loop to show the data from the object we got from the previous class we added !)
```

Then open `http://127.0.0.1:8000/index.php`.

<<<<<<< HEAD
## Admin dashboard

1) Create your `.env` from `.env.example` and set `ADMIN_USERNAME` + (`ADMIN_PASSWORD_HASH` or `ADMIN_PASSWORD`).

2) Open `http://127.0.0.1:8000/admin/dashboard/` (it will redirect you to login if needed).

=======
>>>>>>> ed681df (added data/menu.json which contains all the items and categories details && added ConvertJsonToObject class which used to convert json to object to use in index file and replaced the old html by php and used the loop to show the data from the object we got from the previous class we added !)
## Edit the menu

- Menu data lives in `data/menu.json`.
- Rendering logic lives in `index.php` and `functions/ConvertJsonToObject.php`.
