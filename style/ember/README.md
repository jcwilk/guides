Ember
=====

* Don't put a space between the opening handlebars braces and the variable.
* Prefer components over partials.
* Prefer `ember-fetch` over `ic-ajax`. ([sample][ember-fetch-sample])
  [documentation][ember-fetch]

[ember-fetch]: https://github.com/stefanpenner/ember-fetch
[ember-fetch-sample]: sample.js#L20-L29

Ember-Data
----------

* Visually separate relationships from attributes with a newline.
  [Example][relationships]

[relationships]: sample.js#L1-L7

Testing
-------

* Prefer sequential calls to asynchronous helpers ([sample][helpers])
* Prefer nesting assertions within an `andThen` block instead of a chained
  `.then` block ([sample][assertions])

[helpers]: sample.js#L10-L11
[assertions]: sample.js#L13-L17
