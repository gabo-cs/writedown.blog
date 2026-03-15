# WriteDown.Blog

An open blogging platform where anyone can publish by submitting a Markdown post through a pull request.

No accounts, no ads, no algorithms. Just writing.

**[writedown.blog](https://writedown.blog)**

## Contributing

Posts are just Markdown files. If you have something worth sharing, submit it as a Pull Request.

### How to submit a post

1. Fork this repo
2. Create a new file in `src/content/posts/your-post-title.md`
3. Add the required frontmatter:

```markdown
---
title: "Your Post Title"
description: "A one-sentence summary."
date: 2026-03-15
author: "Your Name"
---

Your content here.
```

4. Optionally, add a cover image:
   - Place the image in `public/images/` (e.g. `public/images/my-post.jpg`)
   - Reference it in the frontmatter:
   ```markdown
   image: /images/my-post.jpg
   ```
   The image will appear at the top of the post and as a preview when the link is shared on WhatsApp, LinkedIn, Slack, etc. Recommended size: 1200x630px.

5. Write your post in Markdown below the frontmatter
6. Open a Pull Request

The filename becomes the URL slug — `my-post.md` becomes `/posts/my-post`.

### Other Contributions

- Report bugs by opening an issue
- Suggest new features or improvements
- Improve documentation
- Enhance UI/UX
- Help with internationalization

### Guidelines

- Write about whatever you care about
- Be specific — concrete examples beat vague claims
- Be thoughtful — this is a space for clarity, not noise
- Keep it as long as it needs to be, no longer

## Running locally

```sh
npm install
npm run dev
```

The dev server starts at `localhost:4321`.

```sh
npm run build    # build for production
npm run preview  # preview the build locally
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
