## Starting the project
<p>You can start the project by running these commands:</p>

1. Install compose by running: ```composer install```

2. Install npm-packages by running: ```npm install```

3. Copy env-example: ```cp .env.example .env```

4. Genereate application key: ```php artisan key:generate```

## Setting up the database
<p>Create a database for your project in your local database server (e.g., MySQL).</p>
<p>Update the .env file with the database credentials:</p>

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

Run the database migrations to set up the database structure:
```
php artisan migrate
```

## Run the Laravel Development Server
Start the Laravel back-end server:
```
php artisan serve
```

## Compile Front-End Assets
```
npm run dev
```

## Access the Application
Open your browser and navigate to ```http://127.0.0.1:8000``` (or the port where Laravel is running).
