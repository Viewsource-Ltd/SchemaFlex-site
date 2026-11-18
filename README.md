# SchemaFlex site

The website for SchemaFlex, published with GitHub Pages at <https://viewsource-ltd.github.io/SchemaFlex-site/>.

**Don't edit the files in this repository.** Every file except this README is replaced on each publish. The source is
in the private FlexTools repository, in `FlexTools.Local/SchemaFlex/site`. Its workflow,
`.github/workflows/schemaflex-site.yml`, builds the site (including an example diagram made by running SchemaFlex
itself) and commits the result here. It runs when the site or SchemaFlex's source changes on `main`, and when a
`schemaflex-v*` release is published.

Pages is set to serve the `main` branch from the root.
