
# Reflection
Reflection is meant to act as an online journal for people who don't wish to keep their throughs 
and 'reflections' on their phone notes, google drive, or other applications. This application 
can also be utilized as a blog if a user wishes to be more public about their thoughts. This app
will provide a profile for a user to hold their posts as well as containing tags based on their
topics so other users could find public posts.


## Installation

Clone QR Stroage using Gitbash

```bash
  git clone https://github.com/TBlais10/Reflection
```

Go to the project directory

```bash
  cd Reflection
```
Run Springboot in of your IDE (Intelij Idea Recommended)

## Installation

Install my-project with npm

Clone the project

```bash
git clone https://github.com/TBlais10/Reflection-React
```

```bash
  npm install qr_storage
  cd qr_storage
```

To run the application

```bash
npm start
```
## API Reference

#### Create an account

```http
  POST /api/auth/signup
```

| Parameter  | Type     | Description                            |
| :--------- | :------- | :------------------------------------- |
| `username` | `string` | **Required**. Give us an email address |
| `password` | `string` | **Required**. Create a unique password |

#### Login to the system

```http
  POST /api/auth/signin
```

| Parameter  | Type     | Description                            |
| :--------- | :------- | :------------------------------------- |
| `username` | `string` | **Required**. Use your email address   |
| `password` | `string` | **Required**. Create a unique password |


#### Make an entry

```http
  POST /api/Entries/
```

| Parameter | Type         | Description                                |
| :-------- | :----------- | :----------------------------------------- |
| `title`   | `string`     | **Required** All posts must have a title   |
| `content` | `string`     | The conversation / subject matter of a post|

Returns the newly created Entry in a JSON Body


## Links to Project Repos

### Java Backend

https://github.com/TBlais10/Reflection

### React Frontend

https://github.com/TBlais10/Reflection-React
