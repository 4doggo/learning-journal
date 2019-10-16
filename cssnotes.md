# CSS
## What is CSS?
CSS stands for Cascading Style Sheets. It is used to make the ugly html pretty in a sense.  

CSS works by associating rules with HTML elements. 

CSS rule contains two parts: *selector* and *declaration* 

### **Selectors**
Selectors indicate which element the rule applies to. The same element can apply to more than one element if you separate the element names with **commas**

### **Declaration**
CSS declarations sit inside **curly brackets** and each is made up of **two** parts: a **property** and a **value** separated by a **colon**. You can specify several properties in one declaration, each separated by a **semi-colon**. 

#### *Memo*: 
You can also include CSS rules within HTML but its not good practice to do so is what I learned in 101. 

Therefore its important to place CSS rules in a separate style sheet. A benefit to doing so is is you want to make a change to how your site appears, you only need to edit the one CSS file and all of your pages will be updated. 

### *COLORS!!*
You can specify colors in 3 ways. RGB values, Hex codes or by color names (147 of them) that are already predefined. 

The rule for the body element sets the default color for all the text as well as background.

Example:

`body {
    background-color: black;
    color: white;}`

