# MarkdownDocs
MarkdownDocs is a static site generator, for websites and content built using Markdown.

## Installing
The same as Jekyll building steps, here you go:

1. Install all prerequisites. [List](./docs/build-prerequisites.md)
2. Install the jekyll and bundler gems.
```
gem install jekyll bundler
```
3. Create a new Jekyll site at ./myblog.
```
jekyll new myblog
```
4. Change into your new directory.
```
cd myblog
```
5. Build the site and make it available on a local server.
```
bundle exec jekyll serve
```
6. Browse to http://localhost:4000

> **If you are using Ruby version 3.0.0 or higher, step 5 may fail. You may fix it by adding webrick to your dependencies: `bundle add webrick`**

*Sourced from https://jekyllrb.com/docs/#instructions*
