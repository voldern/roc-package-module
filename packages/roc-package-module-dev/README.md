# roc-package-module-dev
Package providing module support.

Will build code using Babel for either ES5 or ES6.

## Exposes
In general; for a package to be considered valid it must export a `roc` object that will export the name of the package and an additional thing, [see documentation here](https://github.com/rocjs/roc/blob/master/docs/Extensions.md#general-structure).

It may or may not provide additional exports.

## Documentation
- [Action](/packages/roc-package-module-dev/docs/Actions.md)
- [Commands](/packages/roc-package-module-dev/docs/Commands.md)
- [Hooks](/packages/roc-package-module-dev/docs/Hooks.md)
- [Settings](/packages/roc-package-module-dev/docs/Settings.md)

## Runtime
Used with [roc-package-module](/packages/roc-package-module).