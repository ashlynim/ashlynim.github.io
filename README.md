# ashlynim.github.io

Personal website built with [Hugo](https://gohugo.io/) and the [LoveIt](https://github.com/dillonzq/LoveIt) theme, deployed via GitHub Pages.

🔗 **https://ashlynim.github.io/**

## Local Development

```bash
git clone --recurse-submodules https://github.com/ashlynim/ashlynim.github.io.git
cd ashlynim.github.io
hugo server -D
```

## Adding a New Post

```bash
hugo new posts/my-new-post.md
```

## Deployment

Pushes to `main` trigger the GitHub Actions workflow which builds and deploys automatically.
