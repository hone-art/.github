# Hone

Hone is an art journal web application. It allows artists to upload images of their art, keep track of their progress and if they choose, to share their art with others. The name “hone” comes from the idea of honing one's skill.  Unique functionalities include submissions of projects with various entries, a calendar to display projects, streaks to improve motivation, and a gallery of randomly selected entries for inspiration.

## Table of contents

* [Getting Started](#getting-started)
* [Technologies](#technologies)
* [Future Features](#future-features)
* [Authors](#authors)
* [License](#license)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for testing purposes.

### Front End Installation

1. ```$ git clone https://github.com/hone-art/hone_frontend.git```
2. ```$ cd hone```
3. ```$ npm install```
4. ```$ npm run dev```

You will also need a ```.env``` file with the following variables. Please ask an administrator for the email keys.
```
API_URL=http://localhost:8080
EMAIL_PUBLIC_KEY=<public_key>
EMAIL_SERVICE_ID=<service_id>
EMAIL_TEMPLATE_ID=<template_id>
```

### Back End Installation

1. ```$ git clone https://github.com/hone-art/hone_backend.git```
2.  Create a local PostgreSQL database called hone
3.  ```$ npm install```
4.  ```$ npx prisma migrate deploy```
6.  ```$ npm run dev```

You will also need a ```.env``` file with the following variables. Please ask an administrator for the JWT key.
```
DATABASE_URL="postgresql://<username>:<password>@localhost:5432/hone"
JWT_SECRET_KEY=<key>
```
  
## Technologies

* React version: 18.2.0
* TypeScript version: 5.3.3
* PostgreSQL version: 16.2
* Express version: 4.18.3
* Prisma version: 5.10.2
* Jest version: 29.7.0
* Cypress version: 13.7.1

## Future Features

* Support other file types (audio, video, etc)

## Authors

*  Yurika Hirata [(@yurikahirata)](https://github.com/yurikahirata)
*  Jiaxian Gu [(@JiaxanGu)](https://github.com/JiaxianGu)
*  Kiarosh Moeini [(@kiaroshmoeini)](https://github.com/kiaroshmoeini)

## License

This project is licensed under the MIT License.  See the [LICENSE.md](https://github.com/hone-art/.github/blob/main/LICENSE) file for details.
