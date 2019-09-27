# Express Boilerplate!

This is a boilerplate project used for starting new projects!

## .env file
Create a .env file with the following contents...

NODE_ENV=development
PORT=8000
API_TOKEN="YOUR_API_TOKEN"

## Scripts

Start the application `npm start`

Start nodemon for the application `npm run dev`

Run the tests `npm test`

## Deploying

When your new project is ready for deployment, add a new Heroku application with `heroku create`. This will make a new git remote called "heroku" and you can then `npm run deploy` which will push to this remote's master branch.
