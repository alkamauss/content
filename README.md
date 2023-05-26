# Content Repository for Alchemauss

Home to all content in mauss.dev.

## Writing

Consider each folder its own route, and the `+article.md` file as the contents of the page. There's a couple of rules to follow when writing a post:

- Abide default `markdownlint` rules and [specified ones](.markdownlint.yaml)
- Have a front matter with at least a `title` property
- Have a body with only `h2`, `h3`, or `h4` tags

Use your own metadata by adding this template to the front matter when you're writing your own post.

```yaml
---
author:
  name: Kimi no Na wa
  img: /assets/profile/USERNAME.(jpg|png)
  link: https://social.media/USERNAME
---
```

Replace the value of `name:` with your own name (or the post's author if you're opening a PR for someone else). If it's your first time writing, you can add your own avatar image into [`assets/profile`](assets/profile) folder, and reference it in `img:`. Otherwise, just reference the avatar image file again. Finally, replace the link in `link:` with any link you want to point readers when clicking your avatar image.

***

<h3 align="center"><pre>Alchemauss Content</pre></h3>
