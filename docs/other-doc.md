---
layout: default
title: How to Do a Thing
---

# How to Do a Thing

_Published on September 28, 2025_
{: .article-meta}

This is an example article written in Markdown! Much easier than HTML.

**Pro tip:** You can use kramdown syntax to add CSS classes to your Markdown elements!
{: .highlight-box}

## Step 1: Create the Markdown File

Simply create a `.md` file in your `/docs` folder. Add front matter at the top for metadata.

## Step 2: Write in Markdown

You can use all the standard Markdown features:

- **Bold text**
- _Italic text_
- [Links](/)
- `Code snippets`

### Code blocks work too:

```bash
git add .
git commit -m "Add new article"
git push
```

## Step 3: Add CSS Classes

Use kramdown syntax to add classes:

```markdown
{: .highlight-box}
This paragraph gets the highlight-box class

{: .text-center}

## This heading will be centered

[Button Link](/)
{: .button}
```

## Step 4: Jekyll Renders It

{: .text-center}

GitHub Pages will automatically convert your Markdown to HTML with your custom classes!

---

[← Back to Home](/)
{: .button}
