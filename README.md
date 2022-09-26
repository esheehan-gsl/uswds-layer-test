# USWDS Layer Test

Example for configuring USWDS inside a cascade layer.

The project demonstrates a problem forwarding `uswds-typography` from one module and using `uswds-core` to access tokens in another module when both modules are loaded using the `load-css`function from `sass:meta`.

If you comment out either `src/_uswds.scss` line 4 or `src/style.scss` line 10, the build will work. If both lines are left in, Sass throws an error saying the target selector `%usa-prose-p` is not found.
