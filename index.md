---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Learn About Bitcoin 
{: .fs-9 }

Bitcoin Archive gathers the most important primary and secondary source material on the creation of Bitcoin in a highly searchable research database.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/pmarsceill/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

### Search

You can search any document in the archive by author, dates, and keywords. Try out terms like micropayment, VISA, Moore's Law, Mike Hearn, node, anonymous. Results will appear in real-time. 

### Sharing

Highlighting text will automatically update the permalink in browser so that you can link to any specific piece of text in any document. People who click the links you share will automatically jump to the highlighted text on the page. Headers also have anchor links.

### Copying this archive
1. Add Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```https://github.com/wakgill/bitcoin-archive.git
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Bitcoin Archive is &copy; 2020-{{ "now" | date: "%Y" }} by [Deryk Makgill](/).

### License

Bitcoin Archive is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

#### Thank you to the contributors of Bitcoin Archive

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.