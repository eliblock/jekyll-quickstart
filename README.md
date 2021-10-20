# Jekyll Starter

## Getting Started

### Dependencies

-   Ruby (use [`chruby`](https://github.com/postmodern/chruby#install) or [`rvm`](https://rvm.io/rvm/install#basic-install))
-   Node (use [`nvm`](https://github.com/nvm-sh/nvm#installing-and-updating))

### Setup

1. Get the code:
    - Either... fork this repo then clone it
    - Or... clone this repo, rename the directory, then re-set git (`rm -r .git && git init`).
1. Run `npm install && bundle isntall`
    - Commit the `package-lock.json` and `Gemfile.lock` to your repo!
1. In `_config.yml`, update the `baseurl` value as needed. [Learn more here!](https://mademistakes.com/mastering-jekyll/site-url-baseurl/)

### Running

```sh
npm start
```

### Committing

Before committing changes, run the formatter!

```sh
npm run lint:fix
```

## What is this?

> This starter is based on [mloberg/jekyll-starter](https://github.com/mloberg/jekyll-starter) with additional configuration

### What's already set up?

-   [Jekyll](https://jekyllrb.com/)
    -   With the
        [Jekyll::Compose](https://github.com/jekyll/jekyll-compose) plugin
        `sh bundle exec jekyll page "My New Page" bundle exec jekyll post "My New Post" `
-   [Tailwind CSS](https://tailwindcss.com/)
-   [Alpine.js](https://github.com/alpinejs/alpine/)

### Deploying

Includes configuration for deploying to [Netlify](https://www.netlify.com/) and
[GitHub Pages](https://pages.github.com/) (via GitHub Actions). Either option will require further configuration.
