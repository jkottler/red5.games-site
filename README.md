# Website

This website is built using [Docusaurus 3](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ npm install
```

### Local Development

```
$ npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

This site is hosted with [Cloudflare Pages](https://pages.cloudflare.com/). Just branch and make changes. Push branches to see the changes on live staging sites. Merge branches to main to deploy to the production site.

#### Skipping Deployment

If you want to not deploy a set of changes, perhaps because you have made an incidental change like updating the readme, then **before** pushing or merging the changes:

1. Go to the Cloudflare Workers and Pages dashboard and navigate to Settings...Builds and Deployments
2. Select "Configure Production Deployments" or "Configure Preview Deployments" as appropriate
3. Unselect the "Enable automatic deployments" checkbox
4. Push or merge the changes in question
5. Re-enable the checkbox after the git operations are complete and you want to re-enable automatic deployments
