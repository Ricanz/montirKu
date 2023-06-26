# montirKu
A system for helping the communication between mechanic and customer in any Workshop 

## Features

<!-- - Modal based Create+Edit, List with Pagination, Delete with Sweetalert -->
- Login, Register, Forget+Reset Password as default auth
- Profile, Update Profile, Change Password, Avatar
- Product Management 
- User Management
- Settings: Categories, Tags
- Frontend and Backend User ACL with Gate Policy (type: admin/user)
<!-- - Simple Static Dashboard
- Developer Options for OAuth Clients and Personal Access Token
- Build with Docker -->

## Installation

- `git clone https://github.com/Ricanz/montirKu`
- `cd laravel-vue-crud-starter/`
- `composer install`
- `cp .env.example .env`
- Update `.env` and set your database credentials
- `php artisan key:generate`
- `php artisan migrate`
- `php artisan db:seed`
- `php artisan passport:install`
- `npm install`
- `npm run dev`
- `php artisan serve`

## Unit Test

#### run PHPUnit

```bash
# run PHPUnit all test cases
vendor/bin/phpunit
# or Feature test only
vendor/bin/phpunit --testsuite Feature
```


## Credit
Special thanks to [Hujjat/laravStart](https://github.com/Hujjat/laravStart) and his georgeus Laravel-Vue Starter template.
It help me alot for building this system's template.

## License
[MIT license](https://opensource.org/licenses/MIT).

## Other
Follow me on LinkedIn to see my other "iseng" projects
https://www.linkedin.com/in/riyanti-maulya-887757128/



