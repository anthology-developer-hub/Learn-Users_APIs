# Learn-Placements_Apis

API collections for Learn Users - CRUD operation.

## Prerequisites
Postman - latest version

## Installation
To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API Enpoints

The `Api_Export.json` file contains the following APIs:

- `GET /learn/api/public/v1/users`: Returns a list of Users.
- `GET /learn/api/public/v1/users/{userId}`: Loads a User.
- `DELETE /learn/api/public/v1/users/{userId}`: Deletes a User.
- `POST /learn/api/public/v1/users`: Creates a User.
- `PATCH /learn/api/public/v1/users/{userId}`: Updates a User.

## Usage

After importing the `Api_Export.json` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the environment variables correctly:

- `$LEARN_DOMAIN`: Learn domain name
- `$APP_KEY`: Your application key here
- `$APP_SECRET`: Your application secret here
- `$ACCESS_TOKEN`: Obtain the access token from the API request '/learn/api/public/v1/oauth2/token' using the above values and replace the variable
- `$USER_ID`: Id of a User to be searched
