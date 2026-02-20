# Gitpod Laravel Starter

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Gitpod](https://img.shields.io/badge/Gitpod-FFAE33?style=flat-square&logo=gitpod&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

> **Note:** This repository is a **fork** of [apolopena/gitpod-laravel-starter](https://github.com/apolopena/gitpod-laravel-starter).

A fully configurable LAMP/LEMP stack starter project powered by Laravel and Gitpod, supporting Laravel 6, 7, and 8 with out-of-the-box frontend presets for React, Vue, and Bootstrap, including optional authentication scaffolding.

## Overview

This project generates a complete cloud-based Laravel development environment on Gitpod. It provides a customizable LAMP or LEMP stack with multiple web server options, PHP debugging via Xdebug, optional phpMyAdmin, and configurable frontend scaffolding. Everything is controlled through a single `starter.ini` configuration file, enabling one-click deployment of complex development environments.

## Features

- **Laravel 6, 7, and 8 Support** -- Choose your Laravel major version via configuration
- **Multiple Web Servers** -- Switch between Apache, Nginx with PHP-FPM, or the PHP development server
- **Frontend Presets** -- Out-of-the-box support for React, Vue.js, and Bootstrap frontends
- **Auth Scaffolding** -- Optional Laravel UI authentication scaffolding with any frontend preset
- **PHP Debugging** -- Full Xdebug integration with VS Code and Theia launch configurations
- **Optional phpMyAdmin** -- Database administration interface installable via configuration
- **Hot Reloading** -- Browser-sync support for real-time code change previews
- **TypeScript Support** -- Easily add TypeScript to your project
- **Configurable Stack** -- Control all options through `starter.ini` without touching Dockerfiles
- **Preset Examples** -- Pre-configured example projects for React and Vue to learn from or use as starting points

## Prerequisites

- A [Gitpod](https://gitpod.io) account (free tier available)
- A [GitHub](https://github.com) account
- A modern web browser

## Getting Started

### Installation

No local installation required. Open this project directly in Gitpod.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/danielcregg/gitpod-laravel-starter)

### Usage

1. Click the **Open in Gitpod** button above to launch the workspace
2. Wait for initialization to complete (2-5 minutes on first launch)
3. The preview browser opens automatically with the Laravel start page
4. Configure the environment by editing `starter.ini` before creating a new workspace:
   - Set `default_server` to `apache`, `nginx`, or `php`
   - Enable React, Vue, or Bootstrap frontend presets
   - Toggle phpMyAdmin and auth scaffolding
   - Choose your Laravel version (`6.*`, `7.*`, or `8.*`)

Server management commands:
- `start_apache` / `stop_apache`
- `start_nginx` / `stop_nginx`
- `start_php_dev` / `stop_php_dev`
- `debug_on` / `debug_off` for Xdebug sessions
- `op` to open or refresh the preview browser

## Tech Stack

| Technology | Purpose |
|---|---|
| Laravel | PHP web application framework |
| PHP 7.4 | Server-side scripting language |
| MySQL | Relational database management |
| Apache | HTTP web server |
| Nginx + PHP-FPM | Alternative high-performance web server |
| Xdebug | PHP debugging and profiling |
| React / Vue / Bootstrap | Optional frontend framework presets |
| Docker | Custom Gitpod workspace image |
| Gitpod | Cloud development environment |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
