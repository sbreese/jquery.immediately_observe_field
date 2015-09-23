= jquery.immediately_observe_field

This is a JQuery plugin that implements a way to observe form fields on a given frequency,
instead of having to rely on blur (too cumberstone for the user) or keyup (does not account 
for pasting of values or programettically entered values).

The frequency has to be specified in seconds.

Each onkeyup event resets the counter, so a frequency of more than 1 second will result 
on a not very responsive interface.


== Installation

Make sure that jQuery is included before this plugin. Then 
include "jquery.immediately_observe_field.js" with the following code.

Assuming that you copied it on /js/:

    <script src="/js/jquery.jquery.immediately_observe_field.js"></script>

== Example

See example.html

== Kudos

This is an improvement on splendeo's jquery.observe_field plugin.

== License

jquery.jquery.immediately_observe_field is licensed under the MIT license: