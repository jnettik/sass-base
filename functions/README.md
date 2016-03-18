# Sass Functions

This folder should contain project wide utility functions to be used with styles. Each partial should be named after it's function name. For example, a function called `em()` would be found in the `_em.scss` partial. This is to help ease finding function definitions.

Since functions should be self contained pieces of logic, order of inclusion shouldn't matter. Therefore this folder can be globbed. However, functions could depend on settings, and should be included after them. The partials in this directory shouldn't output any styles directly.
