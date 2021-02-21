reStructuredText Improved
=========================

Overview
--------

This Package is for nice syntax highlighting of reStructuredText.  Best 
viewed with sunburst and twilight color schemes.

For have nice highlighting out of the box, it has many tweaks in scope 
names, that is instead of having right semantic names, it rather has names,
which are highlighted by most of color schemes.  Color schemes have to 
support ``markup.*`` scopes better...

Headings and terms (from definition lists) are available as symbols, so
you can use ``CTRL-R`` to jump to them.

.. note:: Creation of this syntax definition was the motivation for 
    writing SyntaxHighlightTools_.

For snippets check out `Restructured Text (RST) Snippets`_.

.. _SyntaxHighlightTools: https://bitbucket.org/klorenz/syntaxhighlighttools
.. _Restructured Text (RST) Snippets:
    https://sublime.wbond.net/packages/Restructured+Text+(RST)+Snippets


Changes
-------

2014-09-13
    - fix issue #6, only recognized preformatted code will be highlighted, other is skipped unhighlighted.

    - fix issue #7, domain names in directives

    - fix partly issue #5, doc and ref are highlighted in a special way

    - fix issue #4, render escapes in captions

2014-04-01
    - added some type-guessing for preformatted text for highlighted 
      preformatted text

2014-01-16
    - simplified list highlighting.  Only list-bullets or list-numbers are
      highlighted.  Such that issue #1 is fixed on all platforms.

    - made options to entity names and put them also into symbol list

2014-01-07
    - issue #1 was not fixed. list is not completely highlighted anymore in 
      ST3, but no hanging or crashes in ST2 anymore.

2014-01-03
    - fix issue #1: st2 hangs in list parsing

2013-12-31
    - improve list handling
    - add all list characters as list indicators

Author
------

Kay-Uwe (Kiwi) Lorenz <kiwi@franka.dyndns.org> (http://quelltexter.org)

Support my work on `Sublime Text Plugins`_: `Donate via Paypal`_

.. _Sublime Text Plugins:
    https://sublime.wbond.net/browse/authors/Kay-Uwe%20%28Kiwi%29%20Lorenz%20%28klorenz%29
    
.. _Donate via Paypal:
    https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WYGR49LEGL9C8
