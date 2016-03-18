# Sass Mixins

This folder should contain project wide mixins, containing dynamic chunks of style. Ideally all mixins should accept some argument that alters the output of the styles. Partials should be named after the name of the mixin as well. For example, the mixin `square()` should be found in a partial named `_square.scss`. These partials should not output any styles directly.

Because mixins should be self contained pieces chunks of styles, the order of inclusion shouldn't matter. This directory can be globbed for inclusion.
