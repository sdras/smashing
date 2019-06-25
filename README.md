# Smashing Toronto 2019 Talk

I live coded a Vue/Nuxt portfolio app in 45 minutes with layout and animation at Smashing Conf, here's the repo, and it was deployed to: [https://smashingtoronto.netlify.com/](https://smashingtoronto.netlify.com/)

**I'll post the video here when it's up!**

## VS Code Extensions

I use my own [VS Code snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets) a ton in development to speed up my workflow/not have to type boilerplate.

I use my own [Night Owl VS Code Theme](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl&WT.mc_id=twitter-social-sdras)

Both are in my [Vue VS Code Extensionspack](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-extensionpack), which houses a lot of the extensions I use for development.

## CSS Grid Generator

I used my [CSS Grid Generator](https://cssgrid-generator.netlify.com/) to create the grids I used for the layout.

## Terminal Razzle Dazzle

I mentioned I'd share how I made my terminal fancy. For the colors:
`brew install lolcat`

Then in `.bash_profile`:

```
export CLICOLOR=1
export LSCOLORS=gx

alias l='ls | lolcat'
```

I used [Hub](https://hub.github.com/) to create a repo from the command line.
Also the sparks are from [Hyperpower](https://github.com/zeit/hyperpower).

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
