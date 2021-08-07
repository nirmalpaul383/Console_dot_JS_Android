# Console_dot_JS_Android
a small android application project to run/evaluate javascript code and to show the output on a custom console using a custom 'console.log()' method. With support of file read/write access using Tasker's JavaScript interface. Based on https://github.com/nirmalpaul383/Console_dot_JS

.................................................................................................................................................................................

Welcome to Console.JS(Android) by N Paul.This is a small project to run/evaluate javascript code and to show the output on a custom console using a custom 'console.log()' method.
You can enter JavaScript code here. You can use the "console.log()" method to output a JS code. It also supports Tasker's JavaScript interface. You can find more information
about Tasker's JavaScript interface at https://tasker.joaoapps.com/userguide/en/javascript.html

.................................................................................................................................................................................

Console.js(Android)(https://github.com/nirmalpaul383/Console_dot_JS_Android) is based on "Console.js"(https://github.com/nirmalpaul383/Console_dot_JS) project by me. This project
is very similar to my another project 'Tasker.js'(https://github.com/nirmalpaul383/Project_Tasker_dot_JS) which is based on "JavaScript_Console_Mini-inside-webpage"(https://github.com/nirmalpaul383/JavaScript_Console_Mini-inside-webpage) project by me.

But the main difference between these(Console.js(Android) & 'Console.js') and those('Tasker.js' & 'JavaScript_Console_Mini-inside-webpage') project are that, these never instantly
return the output of a code untill "console.log()" method is used but those always return an output(regardless of defined/undefinded value). Another difference is that when a code
is thrown into those('JavaScript_Console_Mini-inside-webpage' & 'Tasker.js'), they first read it, then evaluate it, then print its output and are ready to take the another code
again (not forgetting the old codes). But comparatively in these project, if codes are thrown into these, these first read the entire codes, then evaluate it, and if there is
"console.log()" method only then output it, and if we throw a new code, these forgets the previously executed code.

.................................................................................................................................................................................

Console.js (Android) supports two JavaScript code execution modes. The first one is Tasker's JavaScriptlet mode (based on Tasker's sences and JavaScriptlet) and the second is
WebView mode (based on HTML, CSS and JavaScript (and android's WebView)). Most JavaScript code will run almost equally in these two modes, and these two modes support Tasker's
JavaScript interface. However, in terms of execution speed, it can be said that the webview mode is relatively faster (However, depending on the JavaScript code, exceptions may
occur). In terms of features, Tasker JavaScriptlet mode currently has a few more features. For example it supports JavaScript scrict ("use strict") mode, it can read and execute
local or network javascript file through a graphical interface (although with the help of Tasker JavaScript interface we can read and execute local JavaScript file in webview
mode also. We can use fetch api or xmlhttprequest for network js file.). Here is a small example of how to execute local js files through Tasker JavaScript interface:
let fileDataHolder = readFile ("local file path"); and to execute it use the syntax: eval (fileDataHolder). You can find more information about Tasker JavaScript interface here
https://tasker.joaoapps.com/userguide/en/javascript.htm .

.................................................................................................................................................................................


If you like these project please give a star to these projects. https://github.com/nirmalpaul383/Console_dot_JS_Android , 
Main project: https://github.com/nirmalpaul383/Console_dot_JS

if you like to check out my previous similar projects you can visit 
https://github.com/nirmalpaul383/Project_Tasker_dot_JS ,
Main project: https://github.com/nirmalpaul383/JavaScript_Console_Mini-inside-webpage

This project is originally made by me(N Paul).
My github profile: https://github.com/nirmalpaul383/
My youtube page: https://www.youtube.com/channel/UCY6JY8bTlR7hZEvhy6Pldxg/

This is an open source program. You are welcomed to modify it...
If you want to support me please give a like to our facebook page: https://facebook.com/a.new.way.Technical/

.................................................................................................................................................................................
