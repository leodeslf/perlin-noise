# Perlin Noise

```txt

             _.~^~.__.~^~._
           /~^~.______.~^~/\
          /^~.________.~^/ /
         /~^~.______.~^~/ /
        /_.~^~.__.~^~._/ /
       /_ /\___________\/
      /._/ /
     /~./ /
    /^~/ /
    \__\/

```

## About

A Perlin Noise library for JavaScript.

## Features

- `perlin1D`
- `perlin2D`
- `perlin3D`
- `perlin4D`

## Install

```bash
npm i @leodeslf/perlin-noise
```

## Usage

```javascript
import { perlin1D } from '@leodeslf/perlin-noise';

console.debug(perlin1D(0.125)); // -0.10894775390625
console.debug(perlin1D(0.120)); // -0.1056811008
console.debug(perlin1D(0.115)); // -0.10229407794375
```

[Live demo here](https://leodeslf.github.io/perlin-noise/ "GitHub Pages") (1D, 2D, 3D, and 4D).

## Author

[Leonardo de S.L.F](https://github.com/leodeslf "GitHub profile").

## License

MIT License.
