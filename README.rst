=========================
 Instructionr for Spyder
=========================

open ``~/.spyder2/.spyder.ini``.

Add ``u'ColorSchemeName'`` to the end of the names list::

   [color_schemes]
   names = [u'Custom', u'Emacs', u'IDLE', u'Pydev', u'Scintilla', u'Spyder', u'Spyder/Dark', u'Tomorrow']

Add actual color scheme settings. For example::

   spyder/background = u'#ffffff'
   spyder/currentline = u'#feefff'
   spyder/occurence = u'#ffff99'
   spyder/ctrlclick = u'#0000ff'
   spyder/sideareas = u'#efefef'
   spyder/matched_p = u'#99ff99'
   spyder/unmatched_p = u'#ff9999'
   spyder/normal = (u'#000000', False, False)
   spyder/keyword = (u'#0000ff', False, False)
   spyder/builtin = (u'#900090', False, False)
   spyder/definition = (u'#000000', True, False)
   spyder/comment = (u'#adadad', False, True)
   spyder/string = (u'#00aa00', False, False)
   spyder/number = (u'#800000', False, False)
   spyder/instance = (u'#924900', False, True)
   tomorrow/background = u'#ffffff'
   tomorrow/currentline = u'#efefef'
   tomorrow/occurence = u'#d6d6d6'
   tomorrow/ctrlclick = u'#4271ae'
   tomorrow/sideareas = u'#efefef'
   tomorrow/matched_p = u'#d6d6d6'
   tomorrow/unmatched_p = u'#ff9999'
   tomorrow/normal = (u'#4d4d4c', False, False)
   tomorrow/keyword = (u'#8959a8', False, False)
   tomorrow/builtin = (u'#c82829', False, False)
   tomorrow/definition = (u'#4d4d4c ', True, False)
   tomorrow/comment = (u'#8e908c', False, True)
   tomorrow/string = (u'#718c00', False, False)
   tomorrow/number = (u'#f5871f', False, False)
   tomorrow/instance = (u'#3e999f', False, True)

