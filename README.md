# window-protector
Protect your page.

## General Usage
<b>Ensure the file is properly loaded as a CDN on your page</b>
<br><br>
Create a new Protector object.<br>
`var Protector = new Protector(function(){
  /*Your Callback*/
 })`
<br><br>
Start listening for window exits.<br>
`Protector.start();`
