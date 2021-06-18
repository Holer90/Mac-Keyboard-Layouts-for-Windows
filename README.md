
Overwrite the default keyboard layout (tho edit)
================================

```
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout]
"IgnoreRemoteKeyboardLayout"=dword:00000001
```
save this as a `.REG` file and merge it.

Mac Keyboard Layouts for Windows
================================

Since the 1980s, Macintosh computers have included a keyboard layout that facilitates the typing of diacritics and other symbols through the use of the <kbd>Option</kbd> key. Windows supplies an [“International”](http://symbolcodes.tlt.psu.edu/accents/codeint.html) layout with a limited range of accents, but using this layout makes the quotation mark and apostrophe keys unusable.

These keyboard layouts fix this situation: one duplicates the standard U.S. layout used on the Mac (also identical to the “Canadian English” keyboard layout), and the other replicates the “U.S. Extended” keyboard layout introduced with Mac OS X. The U.S. Extended provides more accents and places some characters in more logical positions, but the standard Mac layout provides access to a few mathematical symbols that some might find useful. Unlike the Windows layout, these do not change the basic U.S. keyboard.

For their use, see [Penn State University](http://symbolcodes.tlt.psu.edu/accents/codemacext.html) or [Harvard](http://isites.harvard.edu/fs/docs/icb.topic537340.files/USExtended.pdf) for the U.S. Extended layout, or [Penn State’s page on the standard Mac layout](http://symbolcodes.tlt.psu.edu/accents/codemac.html), substituting the <kbd>AltGr</kbd> (right <kbd>Alt</kbd>) key for the <kbd>Option</kbd> key. The Windows On-Screen Keyboard also displays the available combinations.

To install, unzip the downloaded file, and run the “setup.exe” program corresponding to the desired layout; the installer will automatically add the layout to the input menu. Both layouts can be installed on a system simultaneously, and can be removed through the Control Panel.

The source files are in [Microsoft Keyboard Layout Creator](http://msdn.microsoft.com/en-us/goglobal/bb964665) format. Adobe has since created a [script for converting keyboard layouts from Mac to Windows format](http://blogs.adobe.com/typblography/2012/03/on-keyboard-layouts.html).
