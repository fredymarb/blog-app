# Blog App - Ruby on Rails

This is a simple blog application built with **Ruby on Rails**, following the curriculum of [The Odin Project](https://www.theodinproject.com/lessons/ruby-on-rails-blog-app).

Users can create, view, and manage articles. Each article can have multiple comments.

## Features

- Create, edit, and delete blog posts
- Add comments to blog posts
- Basic routing using Rails conventions
- Full MVC structure (Models, Views, Controllers)

## Getting Started


Follow the steps below to run the project locally.

### Prerequisites

Ensure you have the following installed:

- Ruby (version `3.0.0` or above recommended)
- Rails (version `7.0+`)
- SQLite3
- Node.js & Yarn (for Rails asset pipeline)

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/rails-blog-app.git
   cd rails-blog-app

2. **Install dependencies**
   ```bash
   bundle install
   yarn install

3. **Set up the database**
   ```bash
   bin/rails db:create
   bin/rails db:migrate

4. **Start the Rails server**
   ```bash
   bin/rails server

