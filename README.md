# passport-github-auth-mern

# 🚀 Javascript full-stack 🚀

## MERN Stack

### Authenticate with passport js for Github

### React / Express / MongoDB / Node.js

https://github.com/coding-to-music/passport-github-auth-mern

http://localhost:3000/auth

https://passport-github-auth-mern.herokuapp.com

https://passport-github-auth-mern.onrender.com

by Joshua Evuetapha https://github.com/Joshuajee

https://github.com/Joshuajee/passport-github-auth

```java
      secret: process.env.JWT_SECRET,

mongoose_1.default.connect(`${process.env.MONGODB_URI

    clientID: process.env.GITHUB_CLIENT_ID,
    clientSecret: process.env.GITHUB_CLIENT_SECRET,
    callbackURL: process.env.GITHUB_CALLBACK_URL

JWT_SECRET
MONGODB_URI
GITHUB_CLIENT_ID
GITHUB_CLIENT_SECRET
GITHUB_CALLBACK_URL

```

## Deploying to Render

This plugin will extract info from Heroku and put it into a Docker file.

```java
heroku plugins:install @renderinc/heroku-import
```

Output:

```java
warning ../../../package.json: No license field
warning ../../../../../../package.json: No license field
warning "eslint-config-oclif > eslint-config-xo-space@0.27.0" has incorrect peer dependency "eslint@>=7.20.0".
warning "eslint-config-oclif > eslint-plugin-mocha@9.0.0" has incorrect peer dependency "eslint@>=7.0.0".
warning "eslint-config-oclif > eslint-plugin-unicorn@36.0.0" has incorrect peer dependency "eslint@>=7.32.0".
warning "eslint-config-oclif > eslint-config-xo-space > eslint-config-xo@0.35.0" has incorrect peer dependency "eslint@>=7.20.0".
warning "eslint-config-oclif > eslint-plugin-unicorn > eslint-template-visitor@2.3.2" has incorrect peer dependency "eslint@>=7.0.0".
warning "eslint-config-oclif > eslint-plugin-unicorn > eslint-template-visitor > @babel/eslint-parser@7.16.3" has incorrect peer dependency "eslint@^7.5.0 || ^8.0.0".
Installing plugin @renderinc/heroku-import... installed v1.1.0
```

```java
heroku render:import --app passport-github-auth-mern
```

Output:

```java

=== Gathering information about Heroku app
Verifying Heroku app exists and CLI is logged in... ✔️
Verifying app is using a single, official Heroku buildpack... ✔️
Getting stack image... heroku-20
Getting and translating plan... Heroku Free $0/mo --> Render Free $0/mo
Getting instance count... 1
Getting custom domains... 0 custom domain(s)
Getting environment variables... 2 environment variable(s)
Getting add-ons... 0 add-on(s)

? Select addons to import.

Create render.yaml file and Dockerfile.render? This will overwrite any existing files with the same name. (y/n): y
Generating render.yaml file... done
Generating Dockerfile.render... done

=== Environment variables excluded from render.yaml
The following environment variables were not included in the generated
  render.yaml file because they potentially contain secrets. You may need to
  manually add them to your service in the Render Dashboard.

- JWT_SECRET:

=== Follow these steps to complete import of service(s) and database(s) to Render
1. Add, commit, and push the generated render.yaml and Dockerfile.render to GitHub or GitLab.
2. Go to https://dashboard.render.com/select-repo?type=iac
3. Search for and select this repository.
4. Verify the plan showing the resources that Render will create, and
   then click 'Create New Resources'.
5. After the resources are deployed, you may need to manually add
   the above environment variables to your Web Service in the Render Dashboard.
   They were not included in the generated render.yaml because they potentially
   contain secrets.
```

### Configuration

First create a .env file on the root directory of the project the file should look like this

'''
DATABASE = your-mongo-db-uri

GITHUB_CLIENT_ID = your-github-app-client-id

GITHUB_CLIENT_SECRET = your-github-app-client-secret

GITHUB_CALLBACK_URL = your-github-app-callback-url

SESSION_SECRET = your-app-session-secret-it-can-be-any-string-of-your-choice

'''

replace these keys with the appropriate data.

### To run the app

run
`npm install`

and then

run `npm run dev`

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/passport-github-auth-mern.git
git push -u origin main
```

## Heroku

```java
heroku create passport-github-auth-mern

```

## Heroku MongoDB Environment Variables

```java
heroku config:set

heroku config:set JWT_SECRET="secret"

heroku config:set PUBLIC_URL="https://passport-github-auth-mern.herokuapp.com"
```

## Push to Heroku

```java
git push heroku

# or

npm run deploy
```
