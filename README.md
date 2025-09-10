# Roblog (Ruby on Rails)

A simple blog application built with Ruby on Rails.  
This app allows users to create, read, update, and delete blog posts with titles and content.

## Features
- CRUD:
- Fields:
- Validations:

## Ruby version
- Ruby 3.2.5  
- Rails 8.0.2

> It is recommended to use [rbenv](https://github.com/rbenv/rbenv) or [rvm](https://rvm.io/) to manage Ruby versions.

## System dependencies
- **Database**: SQLite3 (default for development & test) / PostgreSQL (optional for production)  
- **Tailwindcss**: styling modern UI
- **Bundler**: manages gem dependencies  

## Configuration

1. Clone the repository:
   ```bash
   git clone https://github.com/isujun/roblog.git
   cd roblog

2. Install ruby dependencies
    ```bash
    bundle install
    ```
## Database creation

1. Create a new database:
    ```bash
    rails db:create
    ```

## Database initialization

1. Run database migrations:
    ```bash
    rails db:migrate
    ```

## How to run the test suite

Rails comes with Minitest by default.
1. To run all tests:
    ```bash
    rails test
    ```

## Service
- Job queues: ActiveJob (default adapter: Async)
- Cache: FileStore (default), can be switched to Redis for production
- Action Mailer: not configured yet (can be added for email notifications)


## Deployment instructions

1. Configure environment variables for production (SECRET_KEY_BASE, DATABASE_URL, etc).
2. Run database migrations on the server:
    ```bash
    rails db:migrate RAILS_ENV=production
    ```
3. Start the rails server in production mode:
    ```bash
    rails s -e production
    ```
4. Deployment platforms:
    - netlify
    - fly.io
    - Digital Ocean


## Project structure
- Model:
- Controller:
- Views:
- Routes:


## Screenshot
- Page1
- Page2
- Page3
