# Claiming This Space: A First Post

Test Test

## What to Expect Here

This site will serve as a living document for a variety of topics. I've broken it down into a few main categories:

* **Guides & Projects:** Detailed walkthroughs for software, personal coding projects, and hands-on technical endeavors.
* **Resources:** Curated lists of the tools, websites, and media that I find genuinely useful or interesting.
* **Blog:** Personal thoughts, updates, and explorations that don't fit neatly into a guide or a list.

## The Technical Foundation

For those interested in the setup, this entire site is built using a simple, powerful stack:

1.  **Content:** Written in plain Markdown.
2.  **Generator:** Built with [MkDocs](https://www.mkdocs.org/), a static site generator.
3.  **Hosting:** Served via GitHub Pages.
4.  **Deployment:** Automated with GitHub Actions.

Here's an example of what the site's navigation configuration looks like in the `mkdocs.yml` file:

```yaml
nav:
  - Home: index.md
  - Guides & Projects: ...
  - Resources: ...
  - Blog: blog/index.md