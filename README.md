# Laravel Log Kibana
Testing Laravel Log For Kibana Json Format

## Getting Started
```bash
cp .env.example .env
cp docker/.env.exmaple docker/.env 
make start
make bash
composer install
php artisan key:generate
php artisan tinker // Typing `Log:info('Hello, World!')` and Show localhost:5601
```
