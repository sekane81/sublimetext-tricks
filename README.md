# Sublime Text 3 tricks
##Select

<b>Command + D</b><br> Select a word.
 
<b>Command + L</b><br> 
Select a line.
 
<b>Command + A </b><br>
Select the entire content within the document.
 
<b>Ctrl + Command + M</b><br> 
Select anything inside the bracket (which is useful when working with CSS or JavaScript)


##Plugins
<b>How to install a plugin</b><br>
First, install the <a href="https://sublime.wbond.net/installation">Package Control</a> by default is deactivated in Sublime Text.<br>
Copy:<br>
<code>import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by) </code><br><br>
Paste in View / Show Console.<br><br>
Know you can find a package in the repository to install , press CTRL + SHIFT + P and type Install Package.<br><br>

###BracketHighlighter<br>
Use CSS syntax to save time in creating HTML code<br>http://docs.emmet.io/cheat-sheet/<br><br>

###ColorPicker<br>
For designers, this package lets you open a panel color choice by pressing the key combination CTRL + SHIFT + C .<br><br>

###EMMET (Zen Coding)<br>
Use CSS syntax to save time in creating HTML code<br>http://docs.emmet.io/cheat-sheet/<br><br>

###CSS Snippets

###Sublimelinter

###Search Stack Overflow

 

