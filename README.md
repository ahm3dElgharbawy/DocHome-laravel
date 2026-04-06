## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/ahm3dElgharbawy/DocHome-laravel.git
```

2. Navigate to project:

```bash
cd DocHome-laravel
```

3. Install dependencies:

```bash
composer install
npm install
```

4. Setup environment:

```bash
cp .env.example .env
php artisan key:generate
```

5. Configure database in `.env`:

```
DB_DATABASE=blogy
DB_USERNAME=root
DB_PASSWORD=
```

6. Run migrations:

```bash
php artisan migrate
```

7. Start server:

```bash
php artisan serve
```

---
