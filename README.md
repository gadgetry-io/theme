# starterlog-theme

Welcome to the Starter Log Jekyll theme!

This minimalist theme for technical writing and ranting was handcrafted by the Practitioners at Gadgetry.io so that we could share our inner daemons :)  We've open sourced it so that others may also use if for personal and professional projects.

## License

The theme is available as open source under the terms of the [MPL-2.0 License](https://opensource.org/licenses/MPL-2.0).

### Dependencies

- Ruby Version = 2.3.0p0
- Bundler Version 1.12.5
- Jekyll Version = 3.2.1


### Getting Started

To demo and experiment with this code, simply install the dependencies and clone the project to your local workspace.  Run `bundle install` to pull in any gem dependencies and then run `jekyll serve` – this directory is setup just like a Jekyll site!


### Installation

To use this theme in your existing Jekyll project... Add this line to your Jekyll site's Gemfile:

```ruby
gem "starterlog-theme"
```

And add this line to your Jekyll site:

```yaml
theme: starterlog-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install starterlog-theme

## Usage

The Starter Log Theme is great for personal and professional projects.  It provides a custom boostrap theme and color scheme, layouts, includes, static pages, assets, and lunr search functionality that you can use to build out a fully functional jekyll project that compliments your technical writing...

Core components such as bootstrap, font-awesome, jquery, and lunr.js were used to develop the theme, and make it very simple to extend and build upon.

    /
      _includes             ## HEAD, HEADER AND FOOTER (e.g. Navbar)
        footer.html
        head.html
        header.html

      _layouts              ## LAYOUTS DIRECTORY
        default.html
        page.html
        post.html

      _pages                ## PAGES DIRECTORY FOR STATIC PAGES (html)

      assets                ## FONTS, IMAGES, SCRIPTS, STYLES
        fonts
        images
        modules
          reveal.js
        scripts
        styles


## HTML Presentations

Reveal.js is now included in the theme and allows you to create HTML presentations directly in your Jekyll site as a simple Post using HTML and Markdown syntax.

In the Front Matter of any Jekyll Post on your site, simply use the slide layout and specify the reveal.js theme you wish to use.

EXAMPLE:

    ---
    layout: slide
    title: Sample Presentation
    description: A presentation slide for how to use reveal.js in Jekyll
    theme: white
    transition: slide
    date:   2017-01-03 00:00:00 -0600
    categories: presentation
    ---

<hr>

### Reveal.js HTML Presentations

![Alt text](./docs/images/slide.png?raw=true "Presentations")



## Additional Screenshots

<hr>

### Home Page

![Alt text](./docs/images/home.png?raw=true "Home Page")

<hr>

### Palette

![Alt text](./docs/images/palette.png?raw=true "Palette")

<hr>

### Custom Bootstrap Theme

![Alt text](./docs/images/theme.png?raw=true "Custom Theme")

<hr>

### Lunr Search

![Alt text](./docs/images/search.png?raw=true "Lunr Search")

<hr>

### Search Results

![Alt text](./docs/images/search-results.png?raw=true "Search Results")

<hr>

### Static Page Templates

![Alt text](./docs/images/about.png?raw=true "About")



<br>
<br>
## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/gadgetry-io/theme. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

You theme is setup just like a normal Jekyll site!

To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to this theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.
