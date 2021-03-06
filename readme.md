![Flarum](https://flarum.org/img/logo.png)

**[Flarum](https://flarum.org/) is free, open-source forum software** built with PHP and [Mithril.js](https://mithril.js.org/). It is:

* **Simple**, with a responsive UI that is optimized for touch devices
* **Fast**, with a total JS payload size of ~130 KB gzipped
* **Extensible**, so you can tailor it to your use-case

![screenshot](https://flarum.org/img/screenshot.png)

## Installation

> **Flarum is currently in beta and should not be used in production.** It is being developed openly on GitHub. Check out the [Roadmap](https://flarum.org/roadmap/) to follow along with our progress.

You must have SSH access to a server with **PHP 5.5+** and **MySQL 5.5+**, and install [Composer](https://getcomposer.org/).

```
composer create-project flarum/flarum . --stability=beta
```

Read the [Installation Guide](https://flarum.org/docs/installation/) for more information.

## Development

This repository holds the Flarum skeleton application.
Its dependencies, such as [flarum/core](https://github.com/flarum/core) (where most development happens), have to be installed using [Composer](https://getcomposer.org/).

## Support

Refer to the [FAQ](https://flarum.org/docs/faq/), [Documentation](https://flarum.org/docs/), and ask questions on the [Community Forum](https://discuss.flarum.org/) or [Discord Chat](https://flarum.org/discord/).

## Contributing

Flarum is open-source and we would love your help building it! Please read the [Contributing Guide](https://github.com/flarum/flarum/blob/master/CONTRIBUTING.md) to learn how you can help.

## License

Copyright (c) 2015 Toby Zerner. Code released under the [MIT License](https://github.com/flarum/flarum/blob/master/LICENSE).
