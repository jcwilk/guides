Ember
=====

* Don't put a space between the opening handlebars braces and the variable.
* Prefer components over partials.

Ember-Data
----------

* Visually separate relationships from attributes with a newline.
  [Example][relationships]

[relationships]: sample.js#L1-L7

Ember-CLI
----------

* Prefer `ember-fetch` over `ic-ajax`. 
  [ember-cli/rfcs#19][ember-fetch]

[ember-fetch]: https://github.com/ember-cli/rfcs/issues/19

Testing
-------

* Prefer sequential calls to asynchronous helpers ([sample][helpers])
* Prefer nesting assertions within an `andThen` block instead of a chained
  `.then` block ([sample][assertions])

[helpers]: sample.js#L10-L11
[assertions]: sample.js#L13-L17
