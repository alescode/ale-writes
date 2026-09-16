# ale-writes

The source for [ale.macha.do](https://ale.macha.do), Alejandro Machado's personal writing site. It is a small Jekyll site hosted on GitHub Pages.

## Publish an essay

1. Add a Markdown file to `_my_posts/` with front matter for `layout`, `title`, `date`, and `description`.
2. Add an optional 1200x630 social image to `assets/og/` and set its filename as `ogimage`.
3. Preview locally with `bundle install` and `bundle exec jekyll serve`.
4. Push to the default branch. GitHub Pages deploys the site.

The homepage, Atom feed, and sitemap are generated from the `_my_posts` collection.
