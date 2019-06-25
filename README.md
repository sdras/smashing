# Smashing Toronto 2019 Talk

I live coded a Vue/Nuxt portfolio app in 45 minutes with layout and animation at Smashing Conf, here's the repo, and it was deployed to: [https://smashingtoronto.netlify.com/](https://smashingtoronto.netlify.com/)

**I'll post the video here when it's up!**

I mentioned I'd share how I made my terminal fancy. For the colors:
`brew install lolcat`

Then in `.bash_profile`:

```
export CLICOLOR=1
export LSCOLORS=gx

alias l='ls | lolcat'
```

Also the sparks are from [https://github.com/zeit/hyperpower](Hyperpower)

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
