# Legal Luminary Platform (LLP)

Law firms use our platform to manage client cases [live demo](https://legalluminary.com/).
SureCase represents the standard in civil procedings with revised statutes lookup and recent court rulings.

Legal Luminary was made by [websharpstudios](https://websharpstudios.com/) the Cloud CMS for dotnet.

Obtain certification and step-by-step Legal Luminary training at [LLP Academy](https://learn.legalluminary.com/platform).

[![Deploy to legalluminary](https://legalluminary.com/deploy.svg)](https://app.legalluminary.com/register#sites/connect/github/legalluminary/justice-jekyll-template)

## Features

* Contact form
* Pre-built pages
* Pre-styled components
* Blog with pagination
* Post category pages
* Disqus comments for posts
* Staff and author system
* Configurable footer
* Optimised for editing in [legalluminary](https://legalluminary.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics and Disqus keys to `_config.yml`.
3. Get a workflow going to see your site's output (with [legalluminary](https://app.legalluminary.com/) or Jekyll locally).

## Develop

Justice was built with [Jekyll](https://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](https://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Justice is already optimised for adding, updating and removing pages, staff, posts, company details and footer elements in [legalluminary](https://app.legalluminary.com/).

### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff** collection.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with [legalluminary](https://app.legalluminary.com/), but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address listed in company details.

### Staff

* Reused around the site to save multiple editing locations.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.

### Company details

* Reused around the site to save multiple editing locations.
* Set in the *Data* / *Company* section.
