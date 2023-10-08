# CSS Interview questions!

## What are different types of CSS selectors? 

The selectors that can be used include: <br> 
- ```universal selector`` : We can basically use this to select everything that falls in the HTML document. This is useful to reset the browser's default padding and margin to zero. <br>
- ```element selector``` : We can select the individual elements using this <br>
- ```class selector``` : We can select classes using this <br>
- ```id selector``` : We can select a specific id using this
- ```attribute selector``` : We can select only the elements of a particular type, having certain attributes using this. Here we have different types as well: 
    - ```[attribute = "value"]``` : matches with exact value of the attribute <br> 
    - ```[attribute ^= "value"]``` : matches with value that starts with attribute value <br>
    - ```[attribute$= "value]``` : matches with value that ends with the string. <br> 
    - ```[attribute*="value"]``` : matches where the value contains a specific substring <br>
    - ```[attribute~="value"]``` : matches where the value contains the whole word <br>
- ```pseudo classes or elements``` : We can select certain elements with pseduo classes that change, if the state of the element changes. Eg - hover. <br>
This can also involve pseudo elements which will select a certain part of an element, rather than the element itself. Eg - ::first-line will select the first line of the text inside an element. Basically how it would act if span was wrapped around that line <br>
- ```combinators``` : We can combine other selectors in order to target elements, within our documents. There are 4 types of combinators mainly: 
    - ```descendant combinator```: selects only the 
    - ```direct child combinator```: 
    - ```general sibling combinator```: 
    - ```adjacent sibling combinator```: 

