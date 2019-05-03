## Garry's Mod Lua Syntax Highlighting for Notepad++ ##

Everything seems to compile fine, until getting to Linking in the GmodLua project.

Below are the current Linking Errors I'm running into.
- "Error" column: The Linking Error code returned.
- "Symbol Desired" column: Symbol name desired by the GmodLua project that cannot be found in any available library.
- "Symbol Available" column: Symbol name that appears in SciLexer.lib after SciLexer is compiled, which appears to be what GmodLua should be using.

__**If anybody has any insight on these errors, or can assist in bringing this project back to full functionality, please let me know.**__

Error | Symbol Desired | Symbol Available
----- | -------------- | ----------------
LNK2019 | ?InList@WordList@@QBE_NPBD@Z | ?InList@WordList@Scintilla@@QBE_NPBD@Z
LNK2019 | ??0LexerBase@@QAE@XZ | ??0LexerBase@Scintilla@@QAE@XZ
LNK2019 | ??1LexerBase@@UAE@XZ | ??1LexerBase@Scintilla@@UAE@XZ
LNK2001 | ?Release@LexerBase@@UAGXXZ | ?Release@LexerBase@Scintilla@@UAGXXZ
LNK2001 | ?Version@LexerBase@@UBGHXZ | ?Version@LexerBase@Scintilla@@UBGHXZ
LNK2001 | ?PropertyNames@LexerBase@@UAGPBDXZ | ?PropertyNames@LexerBase@Scintilla@@UAGPBDXZ
LNK2001 | ?PropertyType@LexerBase@@UAGHPBD@Z | ?PropertyType@LexerBase@Scintilla@@UAGHPBD@Z
LNK2001 | ?DescribeProperty@LexerBase@@UAGPBDPBD@Z | ?DescribeProperty@LexerBase@Scintilla@@UAGPBDPBD@Z
LNK2001 | ?PropertySet@LexerBase@@UAGHPBD0@Z | ?PropertySet@LexerBase@Scintilla@@UAGHPBD0@Z
LNK2001 | ?DescribeWordListSets@LexerBase@@UAGPBDXZ | ?DescribeWordListSets@LexerBase@Scintilla@@UAGPBDXZ
LNK2001 | ?WordListSet@LexerBase@@UAGHHPBD@Z | ?WordListSet@LexerBase@Scintilla@@UAGHHPBD@Z
LNK2001 | ?PrivateCall@LexerBase@@UAGPAXHPAX@Z | ?PrivateCall@LexerBase@Scintilla@@UAGPAXHPAX@Z
LNK2019 | ??0Accessor@@QAE@PAVIDocument@@PAVPropSetSimple@@@Z | ??0Accessor@Scintilla@@QAE@PAVIDocument@1@PAVPropSetSimple@1@@Z
LNK2019 | ?GetCurrent@StyleContext@@QAEXPADI@Z | ?GetCurrent@StyleContext@Scintilla@@QAEXPADI@Z
