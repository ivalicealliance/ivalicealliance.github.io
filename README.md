# ivalicealliance.github.io

## Abstract
An open source website for [Ivalice Alliance](https://www.ivalicealliance.net) built using [Foundation](https://foundation.zurb.com/) and [Jekyll](https://jekyllrb.com/). This [starter pack](https://github.com/daigofuji/jekyll-foundation-6-starter) was used to setup the boilerplate.

## Editing
Edit any HTML or Markdown files. When your changes land on `master`, it will automatically build a new version of the site. The changes will normally be visible within a minute. 

You can also create new files.
- HTML files can go where it makes most sense (usually root folder)

## Building Locally
### Requirements
- Node Package Manager
- Ruby

### Installation
Run these commands once in your git folder.

```bash
> npm install
> bundle install
```

### Building
When you are ready to build the site, you should run these commands. 

```bash
> npm start
> bundle exec jekyll serve --watch
```

Any changes saved will make `npm` and `Jekyll` build the site locally. You can access it at your computer's [localhost:4000](http://localhost:4000).

## Contributing
1. Fork it (https://github.com/ivalicealliance/ivalicealliance.github.io/fork)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request