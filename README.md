<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/rolukja/vilt-docker-stack/actions"><img src="https://github.com/rolukja/vilt-docker-stack/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://hub.docker.com/r/rolukja/vilt-docker-stack"><img src="https://img.shields.io/docker/pulls/rolukja/vilt-docker-stack" alt="Docker Pulls"></a>
<a href="https://github.com/rolukja/vilt-docker-stack"><img src="https://img.shields.io/github/v/release/rolukja/vilt-docker-stack" alt="Latest Release"></a>
<a href="https://github.com/rolukja/vilt-docker-stack/blob/main/LICENSE"><img src="https://img.shields.io/github/license/rolukja/vilt-docker-stack" alt="License"></a>
</p>

## About VILT-Docker-Stack

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

2. Rename <b>.env.example</b> to <b>.env</b>

