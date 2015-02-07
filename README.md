# [openthessaloniki.github.io](http://openindex.gr)

An Index for Open Data in Greece

## Contributors and Maintainers

If you know your way with Github, editing and updating the index is very simple, just [edit the `_data/openindex.yaml` file](https://github.com/OpenThessaloniki/openthessaloniki.github.io/blob/master/_data/) and send a Pull Request.

## Web Developers

If you want to contribute to the development of this site you first need to setup your environment based on the project's requirements.

### The Stack

 * [Node 0.10.x](http://nodejs.org/)
 * [Ruby](http://www.ruby-lang.org/en/downloads/) If you're on OS X or Linux you probably already have Ruby installed; test with `ruby -v` in your terminal.
 * [Grunt](http://gruntjs.com) `npm install -g grunt-cli`
 * [Bower](http://bower.io) `npm install -g bower`
 * [Jekyll](http://jekyllrb.com/) `gem install jekyll`

This project was built using [Jekyll](http://jekyllrb.com/) and is based on the [JekyllBootstrap template](http://jekyllbootstrap.com/), you don't need to be familiar with these tools to do most of the tasks.

### Installing the project

First [fork this repository](https://github.com/openthessaloniki/openthessaloniki.github.io/fork) and clone it to your local:

```shell
git clone git@github.com:YOUR_USERNAME/openthessaloniki.github.io.git
cd openthessaloniki.github.io
```

After cloning is finished you need to install the development dependencies:

```shell
npm install && bower install
```

### Working with the project

You can launch a webserver and a Jekyll watch alltogether simply by running grunt:

```shell
grunt
```

The default Grunt task will:

* Launch a jekyll watch and auto-build on every file change.
* Launch a local static webserver on port 9003.
* Open your browser on http://localhost:9003

### Assets and pages locations

* Edit styles from the `assets/css/main.css` file.
* Edit the layout from the `_includes/themes/twitter/` folder.
* The project's homepage is the file `index.html` in the root folder.
* Edit the markup for the *Meetups* and *Agenda* items in the `_includes/widgets/` folder.
* All the site's data are in the `_data/` folder.

## Colophon

* Uses [Bolt template](http://bootstrapzero.com/bootstrap-template/bolt)

## License

Copyright (c) 2014 SKGTech x OpenThessaloniki. Licensed under the [MIT](http://opensource.org/licenses/MIT) license.

