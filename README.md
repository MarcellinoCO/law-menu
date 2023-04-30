# Menu Catalog

🍱 Menu catalog service built with Nest.js, PostgreSQL, and Docker.

## Features

- Create, read, and update menus
- Read and update menus' availability
- Create, read, and update menu categories

## Requirements

- Docker
- Docker Compose

## Setup

1. Clone the repository:

```
git clone https://github.com/MarcellinoCO/law-menu
```

2. Change to the project directory:

```
cd law-menu
```

3. Build and start the Docker containers:

```
docker-compose up -d
```

The API should now be running on `http://localhost:3000`.

## API Documentation

API documentation is generated using Swagger and can be accessed at `http://localhost:3000/api`.

## Usage

### Create a Menu Item

```
POST /menu
```

### Get All Menu Items

```
GET /menu
```

### Get Menu Item by ID

```
GET /menu/:id
```

### Update a Menu Item

```
PUT /menu/:id
```

### Delete a Menu Item

```
DELETE /menu/:id
```

### Get All Unique Categories

```
GET /menu/categories
```

### Filter Menus by Category

```
GET /menu/filter?category=<category>
```
