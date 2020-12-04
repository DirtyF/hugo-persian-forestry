# Hugo Persian Forestry Starter

[Hugo Persian Theme developed by Themefischer](https://github.com/themefisher/persian-hugo) for Forestry CMS.

![Persian Theme Preview](https://raw.githubusercontent.com/themefisher/persian-hugo/master/images/screenshot.png)

Import to Forestry in one single click!

[![Import to Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=DirtyF/hugo-persian-forestry&branch=forestry&engine=hugo&version=0.79.0)

## Prerequisites

- Hugo > 0.62.2 (tested with lastest Hugo version)

## Content Management

![Forestry user interface](https://raw.githubusercontent.com/forestryio/hugo-parsa-forestry/master/static/images/hugo-parsa-forestry.jpg)

This project has been pre-configured to work with [Forestry](https://forestry.io), just import your repository ✨.

Any changes you make will be commited back to the repo, and deployed if you're using Netlify.

## Customization

You can customize the theme through the [`config.yaml` file](https://github.com/DirtyF/hugo-persian-forestry/blob/master/yaml.toml). Those values are accessible from within Forestry.

## Deployment and hosting with Netlify

Import your site in [Netlify](https://netlify.com)

1. Create a new site in Netlify and import your repository.
2. Set the build command to: `hugo --gc --minify`
3. Set the publish directory to: `public`
4. Set `HUGO_VERSION` to `0.79.0` 

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

## Development

```bash
# clone your repository
# cd in the project directory
cd hugo-persian-forestry

# Start local dev server
hugo server
```

For more information, see [official Hugo documentation](https://gohugo.io/getting-started/).
