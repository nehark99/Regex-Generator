# Regex-Generator
A Regular Expression Generator
For generating all kinds of simple regular expression.

How to use:
1. Use the buttons to select your character and use the adjacent textbox to mention the range or exact quantity of the character (eg. 1,2 or 5 etc).
2. Then click on the "Add" button right beside the textbox.
3. You can choose to start a Look-behind (which lets you mention anchor words AFTER which the resultant substring exists) 
4. You can choose to start a Look-ahead (which lets you mention anchor words BEFORE which the resultant substring exists)
5. You can create groups to categorize and make your regex more understandable. 

Example: 
To make a regex for Date written as:
13-10-2019 or 2-5-2010

First start by clicking on the button "Any Digit" and giving it a range: 1,2
Then click on the Add button next to it.

Click on the button "Specific Character" and mention the Value (i.e. a hypen (-)) on the adjacent textbox. Click Add.

Again, use Any digit to give a range of 1,2 and add it.

Also, add a hypen in the same way.

Lastly click on the "Any Digit" button to give a range of 4. Click Add. 

You will get a regex that would satisfy the aforementioned strings containing dates. 

You can test it out by clicking the test button and entering your string that needs to be matched.
