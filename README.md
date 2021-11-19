<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Locomotion

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Twenty-four views of a house cat.

<section class="intro">

[Image][muybridge:1887a] of Eadweard J. Muybridge's collotype of a house cat.

<!-- <image align="center" src="./data/image.jpg" alt="Twenty-four views of a house cat"> -->

<div class="image" align="center">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@36886e59df0d611b6d80cc6d58c8107d756c01c3/lib/node_modules/@stdlib/datasets/img-locomotion-house-cat/data/image.jpg" alt="Twenty-four views of a house cat">
    <br>
</div>

<!-- </image> -->

</section>

<!-- /.intro -->

<section class="installation">

## Installation

```bash
npm install @stdlib/datasets-img-locomotion-house-cat
```

</section>

<section class="usage">

## Usage

```javascript
var image = require( '@stdlib/datasets-img-locomotion-house-cat' );
```

#### image()

Returns a [buffer][@stdlib/buffer/ctor] containing image data.

```javascript
var img = image();
// returns <Buffer>
```

</section>

<!-- /.usage -->

<section class="examples">

<!-- TODO: more creative example. -->

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var image = require( '@stdlib/datasets-img-locomotion-house-cat' );

var img = image();
console.log( img );
```

</section>

<!-- /.examples -->

* * *

<section class="cli">

## CLI

<section class="installation">

## Installation

To use the module as a general utility, install the module globally

```bash
npm install -g @stdlib/datasets-img-locomotion-house-cat
```

</section>

<section class="usage">

### Usage

```text
Usage: img-locomotion-house-cat [options]

Options:

  -h,    --help                Print this message.
  -V,    --version             Print the package version.
```

</section>

<!-- /.usage -->

<section class="examples">

### Examples

```bash
$ img-locomotion-house-cat | <image_viewer>
```

</section>

<!-- /.examples -->

</section>

<!-- /.cli -->

<!-- <license> -->

## License

Digital image courtesy of the Getty's [Open Content Program][getty-open-content]. The data files (databases) are licensed under an [Open Data Commons Public Domain Dedication & License 1.0][pddl-1.0] and their contents are licensed under [Creative Commons Zero v1.0 Universal][cc0]. The software is licensed under [Apache License, Version 2.0][apache-license].

<!-- </license> -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/datasets/img-locomotion-nude-male`][@stdlib/datasets/img-locomotion-nude-male]</span><span class="delimiter">: </span><span class="description">forty-eight views of a nude male moving in place.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/datasets-img-locomotion-house-cat.svg
[npm-url]: https://npmjs.org/package/@stdlib/datasets-img-locomotion-house-cat

[test-image]: https://github.com/stdlib-js/datasets-img-locomotion-house-cat/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/datasets-img-locomotion-house-cat/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/datasets-img-locomotion-house-cat/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/datasets-img-locomotion-house-cat?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/datasets-img-locomotion-house-cat.svg
[dependencies-url]: https://david-dm.org/stdlib-js/datasets-img-locomotion-house-cat/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[getty-open-content]: http://www.getty.edu/about/opencontent.html

[pddl-1.0]: http://opendatacommons.org/licenses/pddl/1.0/

[cc0]: https://creativecommons.org/publicdomain/zero/1.0

[apache-license]: https://www.apache.org/licenses/LICENSE-2.0

[muybridge:1887a]: http://www.getty.edu/art/collection/objects/40918/eadweard-j-muybridge-animal-locomotion-american-1887/

[@stdlib/buffer/ctor]: https://github.com/stdlib-js/buffer-ctor

<!-- <related-links> -->

[@stdlib/datasets/img-locomotion-nude-male]: https://github.com/stdlib-js/datasets-img-locomotion-nude-male

<!-- </related-links> -->

</section>

<!-- /.links -->
