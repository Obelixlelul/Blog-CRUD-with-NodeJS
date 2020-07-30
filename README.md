# NodeJS CRUD to a blog back-end

This is a project developed by me to study NodeJS. Here i aplied some concepts teached by [Bonieky Lacerda](https://www.linkedin.com/in/bonieky/) in his NodeJS course. To do this some frameworks like Express, Jimp, Mongoose, Multer, Mustache, Slug and UUID was used to build a CRUD to a blog. The database used is MongoDB.

## 1. Install

shure **MongoDB,Yarn and NPM** are installed in your PC.

## 2. The following database named `blog` exists.
| **Collection name** |    |      |       |        |      |     |                      |                    |
|------------|----|------|-------|--------|------|-----|----------------------|--------------------|
| ``posts``      | id | tags | body  | author | slug | __v | photo                |                    |
| ``user``       | id | name | email | salt   | hash | __v | resetPasswordExpires | resetPasswordToken |


## 2. START
Inside de project folder run:
```
$. service mongod start
```
```
yarn
```
```
npm start
```
## 3. ENTER
**Access:** http://localhost:7777  

_To change PORT 7777, go to file variables.env and change PORT to one as you like._

