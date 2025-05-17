# Carten

This project is a small app made to lend audiovisual articles to students in an engineering school.

It's using Laravel for the back-end and Vue.js for the front-end.

Requirements to use the app :

Laravel 10+
Vue 3+

Enjoy !


---

## ⚙️ Installation Steps ⚙️

Follow these steps to get your project up and running:

### 1. Create Project Folder 📁

```bash
mkdir YourAppName
cd YourAppName
```

### 2. Clone Repository

Clone the boilerplate repository and then point the remote origin to your own GitHub repository (make sure you create it on GitHub first!).

```bash
# Clone the boilerplate
git clone https://github.com/RobinChappalley/Carten.git
```

### 3. Install Dependencies 📦

Install both the Node.js and PHP dependencies.

```bash
# Install Node.js dependencies and build assets
npm install
npm run build

# Install PHP dependencies
composer install
```

### 4. Configure Environment 📝

Copy the example environment file to create your own configuration.

```bash
cp .env.example .env
```

👉 **Important:** Edit the `.env` file if you need to configure database connections or other settings. By default, it uses SQLite.

### 5. Generate Key & Run Migrations 🔑

Generate the unique application key and set up the database schema.

```bash
# Generate application key
php artisan key:generate

# Run database migrations
php artisan migrate
```

### 6. Run the Application ▶️

Start the development server.

```bash
composer run dev
```

🎉 Your application should now be running! 🎉