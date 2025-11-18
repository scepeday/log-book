## Quick start & Development environment ready

Before you begin, make sure you have [`Laravel`](https://laravel.com) installed on your computer. You’ll need them to run the commands that set up the application database.

First run the migrations
```sh
php artisan migrate
```

Then, seed the database with the initial data:
```sh
php artisan db: seed
```

After those two steps, start the default Laravel development server:
```sh
php artisan serve
```

Once the server is running, you can log in using the credentials created by the database seeder:
E-mail: tales@que.pato
Password: pass

And that’s it — the project is ready to explore.
This is my first web development project using PHP with the Laravel framework, so please be kind! 😊

The application is a simple blog-style system where users (for example, students) can be registered. You can create and manage “concepts” such as notifications for late arrivals or absences, and then generate reports based on those concepts per student.
