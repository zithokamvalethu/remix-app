# remix-app
This project packages Remix


Development
From my terminal:

npm run dev
This starts your app in development mode, rebuilding assets on file changes.

Deployment
First, build my app for production:

npm run build
Then run the app in production mode:

npm start
Now I will need to pick a host to deploy it to.


Steps to follow:
# create a new project, and pick a pre-configured host
npx create-remix@latest
cd my-new-remix-app
# remove the new project's app (not the old one!)
rm -rf app
# copy your app over
cp -R ../my-old-remix-app/app app
