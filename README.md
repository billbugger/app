# BillBugger Application

[![Build Status](https://img.shields.io/travis/billbugger/app/master.svg?style=flat-square)](https://travis-ci.org/billbugger/app)
[![License](https://img.shields.io/packagist/l/billbugger/app.svg?style=flat-square)](https://packagist.org/packages/billbugger/app)


## Installation

1. Download [Composer](https://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project --prefer-dist billbugger/app [app_name]`.

If Composer is installed globally, run

```bash
composer create-project --prefer-dist billbugger/app
```

In case you want to use a custom app dir name (e.g. `/myapp/`):

```bash
composer create-project --prefer-dist billbugger/app myapp
```

You can now either use your machine's webserver to view the default home page, or start
up the built-in webserver with:

```bash
bin/cake server -p 8765
```

Then visit `http://localhost:8765` to see the welcome page.


## Configuration

Read and edit `config/app.php` and setup the `'Datasources'` and any other
configuration relevant for your application.

Or copy over the `config/.env.sample` to `.env` and edit the settings

## Layout

Billbugger uses the AdminLTE bootstrap theme. Specifically it uses the plugin `maiconpinto/cakephp-adminlte-theme` located here: [https://github.com/maiconpinto/cakephp-adminlte-theme](https://github.com/maiconpinto/cakephp-adminlte-theme)
