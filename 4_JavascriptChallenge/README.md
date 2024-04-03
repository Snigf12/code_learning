# Adding Javascript to previous challenge

This challenge is to make the last page you created functional (somewhat).  The challenge is to:
* If the user left a field blank, JavaScript should "alert" the user and will not write anything to the Table.
* If JavaScript verifies that the fields contain data, then write the information to the table.  Just to avoid confusion, in this challenge, you don't add the data as a new line of the table, just overwrite the data that is currently there...
* You should write a JavaScript Function that will perform this task(s), you may even want to separate the field validation and table writing into separate Functions.
Demo your working code to your instructor

NOTE:
If, when you write to the table, you see your update load but then revert back quickly, it's because your page is refreshing after completing the function(s).  Under the "onsubmit" call, add "return false" to prevent the reload... for example:
```html
<form onsubmit="validate();return false">
```
<!-- just ending html in case I want to add more text later -->