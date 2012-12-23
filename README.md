zencoding_bbedit
================

Modification of [Kendall Conrad's Zen-Coding plugin for BBEdit](http://www.angelwatt.com/coding/zen-coding_bbedit.php), uses [BBEdit's new "package" format (available since version 10)](http://www.barebones.com/support/bbedit/arch_bbedit10.html)

To install, simply look for a directory "Packages" inside your <code>~/Library/Application Support/BBedit/</code> directory, and copy the directory "zencoding_(version).bbpackage" there. If no "Packages" directory exists, create it first, then copy.

You can modify the <code>zen_settings.py</code> file as described on Kendall Conrad's site, only it's location has changed to <code>~/Library/Application Support/BBedit/Packages/zencoding_(version)/Contents/zencoding/</code> and in order to get to it you have to right-click the .bbpackage directory and use the "show contents" option, if you're in the finder.