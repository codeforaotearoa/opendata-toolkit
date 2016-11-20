### Open Data Toolkit

For the theme, and basic layout, we're using the [Docster](https://github.com/DigitalMindCH/docster-jekyll-theme) theme with the [Jekyll](https://jekyllrb.com/) framework.

### How do I access the toolkit?

Currently, you can see a live version hosted at https://codeforaotearoa.github.io

### How do I run the toolkit locally?

Assuming you have [Ruby](https://www.ruby-lang.org/) installed, you'll need to go ahead and install the Jekyll gem if you don't already have it, like so:

```ruby
gem install jekyll
```

Once that's done, you can serve the site:

```ruby
jekyll serve
```

which will run it on localhost:4000 by default.

### What about building the toolkit?

If you want to build the site, run

```ruby
jekyll build
```

which will output static files to a folder called `docs`. The output can be changed in `config.yml` and is only called docs because that's what Github Pages is serving from.

### How can I help add to it?

If you want to add some changes, you can obtain a copy of the repo using Github. If you're not someone who has used Git heavily, the option to download a `.zip` file exists under the Clone or download button.

You can see the layout by checking the markdown pages in the pages folder to see some examples of how heirarchy and text formatting works.

If you're unable to submit a pull request with your changes, feel free to email any altered markdown files to info@codeforaotearoa.org and we'll manually add them.

Otherwise, if you're familiar with Git, just submit a pull request and we'll have a look.
