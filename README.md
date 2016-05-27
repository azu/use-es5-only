# use-es5-only

Check using ES6 with ESLint.

## Install

Install with [npm](https://www.npmjs.com/):

    npm install

## Usage

### OK: ES5 codes

    npm run test:es5

### NG: ES6 codes

    npm run test:es6
    /use-es5-only/es6/es6.js
      2:1  error  Parsing error: The keyword 'const' is reserved
    
    ✖ 1 problem (1 error, 0 warnings)


## Contributing

Pull requests and stars are always welcome.
For bugs and feature requests, [please create an issue](https://github.com/azu/use-es5-only/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](http://twitter.com/azu_re)

## License

MIT © azu
