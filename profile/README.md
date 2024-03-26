# Hone

Hone is an art journal web application. It allows artists to upload images of their art, keep track of their progress and if they choose, to share their art with others. The name “hone” comes from the idea of honing one's skill.  Unique functionalities include submissions of projects with various entries, a calendar to display projects, streaks to improve motivation, and a gallery of randomly selected entries for inspiration.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for testing purposes.

### Front End Installation

1. ```$ git clone https://github.com/hone-art/hone_frontend.git```
2. ```$ cd hone```
3. ```$ npm install```
4. ```$ npm run dev```

### Back End Installation

1. ```$ git clone https://github.com/hone-art/hone_backend.git```
2.  Create a local PostgreSQL database called hone
3.  ```$ npm install```
4.  ```$ npx prisma migrate deploy```
6.  ```$ npm run dev```
  
## Technologies Used

* React version: 18.2.0
* TypeScript version: 5.3.3
* PostgreSQL version: 16.2
* Express version: 4.18.3
* Prisma version: 5.10.2
* Jest version: 29.7.0
* Cypress version: 13.7.1

## Usage

1. Log in
2. Create projects and entries
3. Adjust preferences for comments and public / private access.

## Authors

*  Yurika Hirata [(@yurikahirata)](https://github.com/yurikahirata)
*  Jiaxian Gu [(@JiaxanGu)](https://github.com/JiaxianGu)
*  Kiarosh Moeini [(@kiaroshmoeini)](https://github.com/kiaroshmoeini)

## License

This project is licensed under the MIT License.  See the [LICENSE.md](https://github.com/hone-art/.github/blob/main/LICENSE) file for details.
