<h1 align="center">About Time Aviation Website Built with Hugo</h1>

This is a website built with hugo, using the hugoplate theme. This is the main presence for About Time Aviation out of Creswell, OR.

This is currently a work in progress/staging site for evaluation.

### 📦 Tech Stack

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
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

---

### 👉 Build Command

To build your project locally, you can use the following command. It will purge all the unused CSS and minify all the files.

```bash
npm run build
```

### 👉 Deploy Site

There are 5 different deploy platform configurations configured. Currently this site is being deployed to Github pages with a Github Actions script.

- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

And if you want to Host some other hosting platforms. then you can build your project, and you will get a `public` folder. that you can copy and paste on your hosting platform.

> **Note:** You must change the `baseURL` in the `hugo.toml` file. Otherwise, your site will not work properly.

