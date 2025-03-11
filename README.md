# Jekyll Website Template

This repository contains a simple, customizable website template built with Jekyll that can be hosted for free using GitHub Pages. No coding experience required!

## Getting Started (For Beginners)

### 1. Create Your Website Repository

1. At the top of this page, click the green `"Use this template"` button
2. Select `"Create a new repository"`
3. Choose a name for your website (e.g., "my-blog" or "portfolio-site")
4. Click `"Create repository"`

You now have your own copy of this template to customize!

### 2. Personalize Your Site Settings

1. In your new repository, find and click on the `_config.yml` file
2. Click the pencil icon (Edit this file) to modify it
3. Update these important settings:
   - `title`: What you want to call your website
   - `description`: A brief description of your site (appears in the footer)
   - `name`: Your name or organization
   - `email`: Your contact email
4. Update other settings as desired
  - `max-width`: sets max width of site, change to `full` for full width or set a specific max size (in pixels)
6. Add a simple message like "Update site settings" and click `"Commit changes"`

The "About" and "Contact" pages are included in the site navigation (located at the top of the page) by default. You can disable either by removing their entry under the `nav_pages` section in the configuration file.

### 3. Activate Your Website (GitHub Pages)

1. Click on `"Settings"` in the top menu of your repository
2. On the left sidebar, click on `"Pages"`
3. Under "Branch", select `main` from the dropdown menu
4. Click `"Save"`

Your website is now live! GitHub will display a message with your site's URL, which will look like:
`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME`

Note that it may take a few minutes for your site to appear online as there is a build process that automatically occurs after activating the website for the first time and each time a commit (file addition, deletion or modification) is made to the repository.  The build generally takes about a minute.  The status of the build can be seen by clicking on the `Actions` link found at the top of the repository home page.

### 4. Edit Your Website Content

To edit the main pages of your site:

- `index.md`: Your homepage content
- `about.md`: Information about you or your site
- `contact.md`: How site visitors can contact you

To edit any file:
1. Click on the file name in your repository
2. Click the pencil icon to edit
3. Make your changes
4. Click `"Commit changes..."` when done

### 5. Adding Tags (Optional)

Tags help organize and categorize your blog posts. For each tag you want to use:

1. Create a new file in the `tag` folder named exactly like your tag with `.md` at the end (e.g., `programming.md` for a "programming" tag)
2. Add this content at the top of the file:

```yaml
---
layout: tagpage
title: Foo
tag: foo
robots: noindex
---
```

Replace "Foo" and "foo" with your actual tag name.

### 6. Writing Blog Posts

All blog posts live in the `_posts` folder and must follow a specific naming pattern: `YYYY-MM-DD-title-of-post.md`
To create a new post:

1. Navigate to the _posts folder
2. Click "Add file" → "Create new file"
3. Name your file following the pattern (e.g., 2025-03-09-welcome-to-my-blog.md)
4. Start your post with this information:

```yaml
---
layout: post
title: "Welcome to My Blog"
description: "A short introduction to my new blog."
date: 2025-03-09
author: Your Name
tags: welcome introduction
---
```

5. Write your post content below this section using Markdown formatting
6. Click `"Commit new file"` when finished

### To delete a post:

1. Go to the `_posts` folder
2. Click on the post you want to delete
3. Click the three-dot menu (⋯) in the upper right
4. Select `"Delete file"`
5. Commit the change

## Need Help?

- For more Jekyll customization: [Jekyll Documentation](https://jekyllrb.com/docs/)
- For Markdown help: [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- For GitHub Pages: [GitHub Pages Help](https://docs.github.com/en/pages)

## Advanced: Local Development
For technical users who prefer working locally:
After cloning the repository to your computer, you can start a local development server with:

> jekyll serve --disable-disk-cache -d /tmp

This requires having Jekyll installed on your computer (not necessary for most users who just want to edit through GitHub's website).