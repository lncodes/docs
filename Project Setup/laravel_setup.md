# Laravel Project Setup
1. Open project through terminal.
``` bash
cd <project-directory>
```
2. Install composer dependency
``` bash
composer install
```
3. Generate ***.env*** file.
``` 
cp .env.example .env
```
4. Change database configuration ( ***.env*** )
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_db_name
DB_USERNAME=your_db_username
DB_PASSWORD=your_db_password
```
5. Generate app encryption key.
``` 
php artisan key:generate
```
6. Migrate and seeding database ( ***If Needed*** )
``` 
php aritsan db:migration --seed
```
7. Run the project.
``` 
php artisan serve
```