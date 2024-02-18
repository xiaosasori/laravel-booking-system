# Laravel Booking System
## Init
- `php artisan migrate`
- `alias pest="./vendor/bin/pest"`
## Employees and services
- `php artisan make:model Employee -mf`
- `php artisan make:model Service -mf`
- `php artisan make:migration create_employee_service_table`
## Employee schedules and exclusion
- `php artisan make:model Schedule -mf`
- `php artisan make:model ScheduleExclusion -mf`
