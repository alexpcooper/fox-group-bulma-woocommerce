# Bulma Woocommerce

## Installation

`yarn add bulma-woocommerce`

or

`npm install bulma-woocommerce`

## Usage

To use please @import the /index.scss file of this package into your SCSS after you have imported Bulma.

You must disable the Woocommerce stylesheets by adding the following to your functions.php file:

```
add_filter( 'woocommerce_enqueue_styles', '__return_empty_array' );
```

## Develop

### Requirements

- Yarn

### Installation

To develop please run `yarn` to install required packages

### Stylelint

We are following a set of stylesheet formatting rules. Please run `yarn lint:styles` before pushing to the repo
