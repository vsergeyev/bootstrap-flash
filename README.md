bootstrap-flash
===============

Flash notification messages extension of Twitter Bootstrap.

It's adds to `window` a function `flash(msg, is_error)` to display twitter bootstrap
`alert` box. After 10 seconds it's fadeout.

Usage
=====

Green notification:

    flash("Success message!")


Red notification:

    flash("Error message!", true)