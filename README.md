# Content Repository for Alchemauss

Home to all content in mauss.dev.

## Writing

Contents inside `src` are structured exactly as the URL in the site.

Consider each individual file as each own post or article, inside it should

- Abide default `markdownlint` rules and [specified ones](.markdownlint.yaml)
- Have a front matter with at least a `title` property
- Have a body with only `h2`, `h3`, or `h4` tags

Use your own metadata by adding this template to the front matter when you're writing your own post.

```yaml
---
author:name: Kimi no Na wa
author:img: /assets/profile/USERNAME.(jpg|png)
author:link: https://social.media/USERNAME
---
```

Replace the value of `author:name` with your own name (or the post's author if you're opening a PR for someone else). If it's your first time writing, you can add your own avatar image into [`assets/profile`](assets/profile) folder, and reference it in `author:img`. Otherwise, just reference the avatar image file again. Lastly, replace the link in `author:link` with any link you want to point readers when clicking your avatar image.

***

<h3 align="center"><pre>Alchemauss Content</pre></h3>
