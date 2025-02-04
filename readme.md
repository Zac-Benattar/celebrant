<h1 align="center">Wedding Celebrant themed Hugo + Tailwind CSS + Decap CMS theme based on <a href="https://zeon.studio/hugoplate">Hugoplate</a> from <a href="https://zeon.studio/"> Zeon Studio</a></h1>

### See it working
[hugocelebrant.netlify.app](https://hugocelebrant.netlify.app)

### Features

- Netlify settings pre-configured
- Contact form
- Responsive
- Write and update content in Markdown
- Integration with Decap CMS to write on the go
- Disqus Comments
- Syntax Highlighting
- All configurable

### Dependencies

- [Hugo](https://gohugo.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [PostCSS](https://postcss.org/)
- [PurgeCSS](https://purgecss.com/)
- [AutoPrefixer](https://autoprefixer.github.io/)
- [Hugo Modules](https://gohugo.io/hugo-modules/) by [Gethugothemes](https://gethugothemes.com/hugo-modules)
- [Markdown](https://markdownguide.org/)
- [Prettier](https://prettier.io/)
- [Jshint](https://jshint.com/)
- [Netlify](https://www.netlify.com/)

---

## Installation

[Clone](https://github.com/Zac-Benattar/celebrant) the repo

Install prereqs

- [Hugo Extended v0.124+](https://gohugo.io/installation/)
- [Node v20+](https://nodejs.org/en/download/)
- [Go v1.22+](https://go.dev/doc/install)

### Setup

Use the following command to set up the project. It triggers the required hugo commands to setup the theme in your project.

```bash
npm run project-setup
```

Install all the dependencies.

```bash
npm install
```

Start the local development server.

```bash
npm run dev
```

---

## Customise your project

### Site Config

`hugo.toml`

Site title, base URL, language, theme, plugins, etc.

`config/_default/params.toml`

Logo, favicon, search, SEO metadata, etc.

`data/theme.json`

Theme colours and fonts.

`data/social.json`

Set social links

---

## Advanced Usage

We have added some custom scripts to make your life easier. You can use these scripts to help you with your development.

### Update Theme

If you want to update the theme, then you can use the following command. It will update the theme to the latest version.

```bash
npm run update-theme
```

> **Note:** This command will work after running `project-setup` script.

### Update Modules

We have added a lot of modules to this template. You can update all the modules using the following command.

```bash
npm run update-modules
```

### Remove Dark Mode

If you want to remove dark mode from your project, you can use the following command to remove dark mode from your project.

```bash
npm run remove-darkmode
```

> **Note:** This command will work before running `project-setup` script. If you already run the `project-setup` command, then you have to run `npm run theme-setup` first, and then you can run this command. afterward, you can run `npm run project-setup` again.

---

## Build

To build your project locally, you can use the following command. It will purge all the unused CSS and minify all the files.

```bash
npm run build
```

## Deploy

A [Netlify](https://www.netlify.com/) configuration is packaged with this repo. Feel free to use other hosting providers but DecapCMS uses [Netlify Identity](https://docs.netlify.com/security/secure-access-to-sites/identity/), requiring Netlify hosting.

If you want to self host, simply build locally (instructions above), and serve the `public` folder to users.

> **Note:** You must change the `baseURL` in the `hugo.toml` file to your deploy URL or the site will not function.

---

## License

Copyright (c) 2025 - Present, Designed & Developed by [Zac Benattar](https://zcbn.dev/)

**Code License:** Released under the [MIT](https://github.com/Zac-Benattar/celebrant/blob/main/LICENSE) license. Original template by [zeon.studio](https://zeon.studio) under [MIT](https://github.com/zeon-studio/hugoplate/blob/main/LICENSE) license.

**Image license:** The images are only for demonstration purposes. They have their license, we don't have permission to share those images.