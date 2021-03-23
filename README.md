# window-protector
Protect your page.

## General Usage
<b>Ensure the file is properly loaded as a script on your page</b>
<br><br>
Create a new Protector object.<br>
`var Protector = new Protector(function(json){
  /*Your Callback*/
 })`
<br><br>
Start listening for window exits.<br>
`Protector.start();`
<br><br>
After calling the start function, anytime your user changes tabs, selects another window, and loses focus of the page,
it will fire the callback that you initialized it with. It will also feed your callback an argument with the amount 
of time it took between the Start() function and the unfocus event.
