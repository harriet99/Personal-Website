<p align="center">
    <h2 align="center">Harriet's Personal Website - <a href="https://harrietkim.com">harrietkim.com</a></h2>
</p>

<p align="center">Personal website for posting projects and updates, built with Jekyll.</p>

## Stack

- [Jekyll](https://jekyllrb.com/) + Sass, based on the [Indigo](https://github.com/sergiokopplin/indigo) theme
- Hosted on [Netlify](https://www.netlify.com/), with the custom domain (`harrietkim.com`, registered via Namecheap) pointed at it

## Local development

1. Install [Jekyll](https://jekyllrb.com) and [Bundler](https://bundler.io/)
2. Clone this repo and install dependencies:
   ```sh
   bundle install
   ```
3. Run the dev server:
   ```sh
   bundle exec jekyll serve --config _config.yml,_config_dev.yml
   ```
4. Open [http://localhost:4000](http://localhost:4000)

Alternatively, `docker-compose up` runs the same dev server in a container without a local Ruby install.

## License

[MIT](https://kopplin.mit-license.org/) License © Sérgio Kopplin (original Indigo theme)
