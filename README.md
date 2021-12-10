# CTAs

[![npm version](http://img.shields.io/npm/v/elr-scss-ctas.svg)](https://www.npmjs.org/package/elr-scss-ctas)
[![CI](https://github.com/Beth3346/elr-scss-ctas/actions/workflows/node.js.yml/badge.svg)](https://github.com/Beth3346/elr-scss-ctas/actions/workflows/node.js.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-ctas.svg?style=flat)](https://npmjs.com/package/elr-scss-ctas)
[![last commit](https://img.shields.io/github/last-commit/Beth3346/elr-scss-ctas.svg)](https://github.com/Beth3346/elr-scss-ctas)

a scss mixin for ctas

<!-- [View Demo](https://elr-ctas.netlify.app/) -->

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-ctas --save
```

or

```sh
yarn add elr-scss-ctas
```

## Implementation

This package is meant to be used with `elr-scss-ctas` for default button styles. If you want to use custom button styles don't use the `elr-button` classes.

### Scss

```scss
@import "elr-scss-ctas/src/main";
@import "elr-scss-cta/src/main";

@include elr-button-classes;

.cta {
  @include elr-cta;
}
```

---

### HTML

Optional classes `.cta-dark` `.cta-center`

```html
<section class="cta">
  <h2 class="cta-heading">Get Started Now</h2>
  <div class="cta-content">
    <p>
      Sign up now to get a really awesome and life changing free offer. More
      marketing speak goes here. Have fun with it! Lorem ipsum, dolor sit amet
      consectetur adipisicing elit. Amet debitis odio dolor, iusto impedit
      harum! Perspiciatis exercitationem modi eligendi recusandae.
    </p>
  </div>
  <div class="cta-button-holder">
    <a href="#" class="elr-button">Sign Up</a>
    <a href="#" class="elr-button elr-button-ghost">Learn More</a>
  </div>
</section>
```

## License

SEE LICENSE IN LICENSE.md
