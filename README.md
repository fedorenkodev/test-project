# Wordpress Starter

**Wordpress Starter** is a custom theme created for Secret Stache Media built on top of [Sage](https://roots.io/sage/). It contains both *functional* and *presentable* layers, *implements* custom admin and public experience, *builds* assets and views, *uses* [Blade templating engine](https://laravel.com/docs/5.7/blade) to render front-end and *provides* an ability to do more.

## Main Concepts

- Built on top of [Sage](https://roots.io/sage/)
- Uses [SSM Core](https://github.com/secretstache/ssm-core) and [SSM Theme Boilerplate](https://github.com/secretstache/ssm-theme-boilerplate) packages
- Contains both *functional* and *presentable* layers of the project
- Gets ACF fields data from **View Composers** and controllers and uses it to render frontend UI
- Uses [Blade templating engine](https://laravel.com/docs/5.7/blade) to render views
- Uses [Composer](https://getcomposer.org/) to manage dependencies
- Uses [Yarn](https://yarnpkg.com/en/) to compile assets, optimize images, concatenation / minification
- Uses [SASS](https://sass-lang.com/) as CSS-preprocessor

## Installation

1. **Clone** the repository to */wp-content/themes/*
- git clone https://github.com/fedorenkodev/test-project
2. **cd** to theme’s folder
3. **Run** *composer install - ignore warnings*
4. **Run** *yarn install*
6. **Run** *yarn build*
7. **Activate** the theme
8. **Install** required plugins


## Folders Walkthrough

**app/**

- responsible for the basic theme setup

  `Examples:` *admin.php, filters.php, helpers.php*

**config/**

- responsible for the theme configuration

  `Examples:` *assets.php, app.php, view.php*

**resources/**

- contains assets and presentable UI elements

  `Examples:` *blocks/, modules/, assets/*
