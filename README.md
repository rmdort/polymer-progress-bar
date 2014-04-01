# &lt;progress-bar&gt;

Progress bar with polymerJS

> Maintained by [Vinay](https://github.com/rmdort).

** Styling only works with Chrome canary **

## Demo

> [Check it live](http://rmdort.github.io/polymer-progress-bar).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/progress-bar.html">
    ```

3. Start using it!

    ```html
    <progress-bar value="40%"></progress-bar>
    ```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`border`   | *string*                  | `10px`              | Border radius
`value`    | *string*                  | `20%`               | Default value
`progressColor`   | *string*                     | `#eee`               | Default background color
`barColor`    | *string*                  | `#000`               | Color of the progress bar

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/element-boilerplate/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)