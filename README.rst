.. highlight:: ini

=========================
 Color Themes for Spyder
=========================
 Instructionr for Spyder
=========================

Color Themes for `Spyder <https://code.google.com/p/spyderlib>`_.

Theme List
==========

* Github
* Tomorrow

HowTo
=====

#. With Spyder closed, open ``~/.spyder2/spyder.ini``.
#. Add ``u'ColorSchemeName'`` to the end of the names list. For example::

   [color_schemes]
   names = [u'Custom', u'Emacs', u'IDLE', u'Pydev', u'Scintilla', u'Spyder', u'Spyder/Dark', u'Tomorrow']

#. Append the color scheme settings to the end of ``[color_schemes]`` section. For example::

   custom/background = #ffffff
   custom/currentline = #f7ecf8
   custom/currentcell = #fdfdde
   custom/occurence = #ffff99
   custom/ctrlclick = #0000ff
   custom/sideareas = #efefef
   custom/matched_p = #99ff99
   custom/unmatched_p = #ff9999
   custom/normal = (u'#000000', False, False)
   custom/keyword = (u'#0000ff', False, False)
   custom/builtin = (u'#900090', False, False)
   custom/definition = (u'#000000', True, False)
   custom/comment = (u'#adadad', False, True)
   custom/string = (u'#00aa00', False, False)
   custom/number = (u'#800000', False, False)
   custom/instance = (u'#924900', False, True)
   tomorrow/background = #ffffff
   tomorrow/currentline = #efefef
   tomorrow/occurence = #d6d6d6
   tomorrow/ctrlclick = #4271ae
   tomorrow/sideareas = #efefef
   tomorrow/matched_p = #d6d6d6
   tomorrow/unmatched_p = #ff9999
   tomorrow/normal = (u'#4d4d4c', False, False)
   tomorrow/keyword = (u'#8959a8', False, False)
   tomorrow/builtin = (u'#c82829', False, False)
   tomorrow/definition = (u'#4d4d4c ', True, False)
   tomorrow/comment = (u'#8e908c', False, True)
   tomorrow/string = (u'#718c00', False, False)
   tomorrow/number = (u'#f5871f', False, False)
   tomorrow/instance = (u'#3e999f', False, True)

#. The new color scheme will be available in the ``Tools`` -> ``Preferneces``
   -> ``Editor`` -> ``Syntax color scheme``. 


