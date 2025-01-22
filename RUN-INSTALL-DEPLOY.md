

# run locally
```
npm install

npm run dev

```

# manage articles
```
# add new
./blog-astro-1/src/content/blog

```

# manage header
```
src/pages/index.astro

```

# deploy changes
```
# update git

```

# [How to send mail with Astrojs](https://hervy.se/blog/sending-mail-with-astrojs/)


- ## update deployment

  - ### refresh git to update deployment
  - ### [scrumming-it](https://app.netlify.com/sites/scrumming-it/deploys)

Repository

Your site is linked to a Git repository for continuous deployment.

Current repository: github.com/heidless-stillwater/blog-astro-1

## images
- ### [astro images](https://docs.astro.build/en/guides/images/)


## fonts
- ### [Using custom fonts](https://docs.astro.build/en/guides/fonts/)
- ### [astro font download](https://font.download/font/astro)
  - [fontsource](https://fontsource.org/)
    - ### [https://fontsource.org/fonts/press-start-2p](https://fontsource.org/fonts/press-start-2p)
```
npm install @fontsource/twinkle-star

# import font
src/layouts/BaseLayout.astro
---
import '@fontsource/twinkle-star';
---

```
