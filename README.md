# [Sass](http://sass-lang.com/) + [Polymer](http://www.polymer-project.org/)

![Sass + Polymer](https://cloud.githubusercontent.com/assets/398893/3542332/c376eede-0855-11e4-88db-cf013ccc60c5.jpg)

> A demo of interoperability between [Sass](http://sass-lang.com/) and [Polymer](http://www.polymer-project.org/).

## Getting started

In order to run it locally you'll need to fetch some dependencies using [npm](https://www.npmjs.org/) and [RubyGems](https://rubygems.org/).

* Install [Bower](http://bower.io/):

    ```sh
    $ [sudo] npm install -g bower
    ```

* Install [Sass](http://sass-lang.com/):

    ```sh
    $ [sudo] gem install sass
    ```

* Install local dependencies:

    ```sh
    $ bower install
    ```

* Invoke the compiler to output the CSS file:

    ```sh
    $ sass --scss src/my-element.scss src/my-element.css
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/sass-interop/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) © WebComponents.org
