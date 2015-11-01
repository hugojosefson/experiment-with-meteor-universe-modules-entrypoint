Experiment to see how the meteor package `universe:modules-entrypoint` works.

Apparently only skips other `.js` files, if it can find `/main.js`.

If there is no `/main.js`, files are picked up by meteor as if `universe:modules-entrypoint` wasn't installed.
