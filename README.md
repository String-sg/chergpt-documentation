# CherGPT Starter Kit Documentation
Deploy your own learning companion, with basic insights into how your students interact with a large language model
![image](https://github.com/String-sg/chergpt-documentation/assets/44336310/523007b2-ee6e-4380-a8cc-39e35c91c24c)

## Login Screen
<img width="1030" alt="image" src="https://github.com/String-sg/chergpt-documentation/assets/44336310/87c74e40-31ff-4e85-ae40-a667e1949416">

Note: typically you won't have to fork the repo unless you are keen on supporting documentation efforts:
### Installation

```
$ npm
```

### Local Development

```
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
