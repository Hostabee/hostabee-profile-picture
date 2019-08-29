# \<hostabee-profile-picture\>

[![Build Status](https://travis-ci.org/Hostabee/hostabee-profile-picture.svg?branch=master)](https://travis-ci.org/Hostabee/hostabee-profile-picture)
[![Sauce Test Status](https://saucelabs.com/buildstatus/mlouchart)](https://app.saucelabs.com/u/mlouchart)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Greenkeeper badge](https://badges.greenkeeper.io/Hostabee/hostabee-profile-picture.svg)](https://greenkeeper.io/)


A profile picture generator in a Web Component. Displays the image target by the given URL or generate one using a string (like username, email address, etc..).

```html
<hostabee-profile-picture></hostabee-profile-picture>
<hostabee-profile-picture src="John Doe"></hostabee-profile-picture>
<hostabee-profile-picture src="john.doe@example.org"></hostabee-profile-picture>
<hostabee-profile-picture id="hpp"></hostabee-profile-picture>
<script>
  document.querySelector('#hpp').src = {
    fullname: 'John Doe',
    profilePictureURL: 'https://image.flaticon.com/icons/svg/219/219988.svg',
  };
</script>
```

![Screenshot of hostabee-profile-picture](https://raw.githubusercontent.com/Hostabee/hostabee-profile-picture/master/screenshot.png)

## Installation

Install `<hostabee-profile-picture>`:

```shell
bower install Hostabee/hostabee-profile-picture --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/hostabee-profile-picture/hostabee-profile-picture.html">
```

## Running demos and tests in a browser

1. Fork the `hostabee-profile-picture` repository and clone it locally.

2. Make sure you have [npm](https://www.npmjs.com/) and [Bower](https://bower.io) installed.

3. When in the `hostabee-profile-picture` directory, run `npm install` and then `bower install` to install dependencies.

4. Run `npm start`, browser will automatically open the component API documentation.

5. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

- http://127.0.0.1:3000/components/hostabee-profile-picture/demo/basic.html
- http://127.0.0.1:3000/components/hostabee-profile-picture/test

## Running Tests

- When in the `hostabee-profile-picture` directory, run `polymer test`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git cz` **OR** [follow this commit guide](https://conventionalcommits.org/) to write the commit messages.

4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## License

Apache License 2.0

## Big Thanks

Cross-browser Testing Platform and Open Source ❤️Provided by:
<!-- Yes, I know. HTML inside mardown file... The only way to change the SVG size without open Inkscape. It could be your first good contribution to fix it! -->
[<img src="./images/sauce_labs_badge.svg" width="150">](https://saucelabs.com)

## Browsers compatibility matrix

[![Sauce Test Status](https://saucelabs.com/browser-matrix/mlouchart.svg)](https://saucelabs.com/u/mlouchart)
