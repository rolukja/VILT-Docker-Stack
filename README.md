# VILT Docker Stack


**VILT-Docker-Stack** is a modern web development stack that combines the power of:

- **[Vue.js](https://vuejs.org/):** For building reactive user interfaces.
- **[Inertia.js](https://inertiajs.com/):** To create server-driven single-page applications without building an API.
- **[Laravel](https://laravel.com/):** A robust PHP framework for the backend.
- **[Tailwind CSS](https://tailwindcss.com/):** For utility-first styling.

This project also comes with **Docker** integration for streamlined development and deployment.

### Features
- Full **Docker** setup with:
    - Nginx
    - PHP-FPM
    - MariaDB
    - phpMyAdmin
- Pre-configured **Laravel Breeze** authentication system.
- Example pages and CRUD operations to kickstart your project.
- Optimized for responsive design with **Tailwind CSS**.
- Multi-environment support for local and production deployments.

## Getting Started

### Prerequisites
To run this project, you need to have **Docker** and **Docker Compose** installed.

- [Install Docker](https://docs.docker.com/get-docker/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/rolukja/vilt-docker-stack.git
   cd vilt-docker-stack
   
2. Install Packagase
    ```bash
   composer install

3. Rename <b>.env.example</b> to <b>.env</b>

4. Start Docker
   ```bash
   ./vendor/bin/sail up -d

5. Install NPM
   ```bash
   ./vendor/bin/sail npm install

6. Start Vite
   ```bash
   ./vendor/bin/sail npm run dev