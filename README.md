# Draft for ECMAScript Modules for Embedded Systems

A repository with the Draft for ECMAScript Modules for Embedded Systems.

Rendered version: https://ecmatc53.github.io/draft/

## Maintainance

1. Make your changes to `spec/index.emu` (ecmarkup uses HTML syntax, but is not HTML, so I strongly suggest not naming it ".html")
1. Any commit that makes meaningful changes to the spec, should run `npm run build` to verify the resulting output.
1. Whenever you update `ecmarkup`, run `npm run build` to check for any changes in the output.

### Watch

You can also use `npm run watch` to build files during development.
