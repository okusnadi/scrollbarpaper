This plugin is an alternative to <a href='http://jscrollpane.kelvinluck.com'>jScrollPane</a>
As Scrollbar Paper's approach is completely different, I have decided to write a new plugin.

<h3>Overview</h3>
Scrollbar Paper does not replace browser's default scrollbar.
Instead, it covers it with a custom scrollbar, like paper on a wall: that is why it is called Scrollbar Paper :-)
The benefit of this approach is that the way browser's default scrollbar behaves is not modified: mouse wheel support, text selection and scrolling performance are the same as usual.

Besides, Scrollbar Paper's HTML does not wrap itself around its content, and thus, does not eventually break it: for instance, when jScrollPane might reset/break Flash/SWF movies, Scrollbar Paper will not.

Finally, Scrollbar Paper is refreshed regularly, thus keeping adapted to its content.

<h3>Showcase</h3>
See Scrollbar Paper in action <a href='http://www.lelieududesign.com/en/why-le-lieu-du-design'>here</a>

<h3>Limitations</h3>
Scrollbar Paper has been tested successfully on IE7/8, Firefox 3.5 and Safari 3/4.
Due to a current bug of Safari 4 reporting wrong <em>outerWidth</em>, <em>margin</em> CSS property should not be set on scrolled content.

<h3>Todo</h3>
Scrollbar Paper will stay <em>beta</em> until these things are done:
- there are still trivial cases where scrollbar's position is not correct: fix them!
- handle mouse wheel events on scrollbar itself
- handle clicks on scrollbar's track
- add arrows on scrollbar

<h3>Contact</h3>
This module is sponsored by <a href='http://www.absyx.fr'>Absyx</a>