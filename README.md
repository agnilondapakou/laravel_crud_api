LARAVEL EMPLOYEES CRUD REST API

Command line :

- npm install
- php artisan serve

Endpoints :

1- index : /api/employees

2- store : /api/employees

    {
        "name": "John Doe",
        "email": "johndoe@gmail.com",
        "position": "Manager"
    }

3- show : /api/employees/id
    Ex : /api/employees/1

4- update : /api/employees/id
    Ex : /api/employees/1

    {
        "name": "John Doe",
        "email": "johndoe@gmail.com",
        "position": "Community Manager"
    }

5- destroy : /api/employees/id
    Ex : /api/employees/1