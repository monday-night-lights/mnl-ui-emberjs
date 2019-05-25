# Monday Night Lights UI

A user interface for the [MNL Hockey League](https://www.mnlhl.com) built with
[Ember.js (Octane)](https://octane-guides-preview.emberjs.com/release/).

## Requirements for Local Development

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/) or
  [Mozilla Firefox](https://www.mozilla.org/firefox/)

## Installation

* `git clone <repository-url>` this repository
* `cd mnl-ui`
* `npm install`

## Running the App

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Addon Packages

`npm` packages built to specifically work with Ember.js are referred to as
[Ember addons](https://cli.emberjs.com/release/#whatareaddons). You can browse
quality addons at [Ember Observer](https://emberobserver.com/). Install or
uninstall addons with these commands:

    ember install <npm-package-name>
    npm uninstall <npm-package-name>

Using `ember install` will automatically include the package files in the
build, but you may need to restart the server to see the effects in the browser.

### Styling

The app is styled using [Tailwind CSS](https://v0.tailwindcss.com/docs), via the
[ember-cli-tailwind](https://github.com/embermap/ember-cli-tailwind#ember-cli-tailwind)
addon.

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

<!-- ### Deploying

Specify what it takes to deploy your app. -->

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [Ember Inspector for Chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [Ember Inspector for Firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
