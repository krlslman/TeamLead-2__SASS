# TeamLead-2__SASS
Questions (here on .md) and notes (on html) for teamlead about Sass on 3rd June.

ASK QUESTIONS 

1. Who is the inventor of SASS?
A. James Gosling
B. Guido van Rossum
C. Misko Hevery
D. Hampton Catlin
Answer: D

2. What are the key features for Sass include?
A. Full CSS3-compatible
B. Language extensions such as nesting, variables, and mixins
C. Many useful functions for manipulating colors and other values
D. All of the above
Answer: D

3. What is the correct way to define a variable in Sass?
A. $primary-color: #888
B. @primary-color: #888
C. %primary-color: #888
D. #primary-color: #888
Answer: A

4. How do you find the minimum of x and y using JavaScript?
A. min(x,y)
B. Math.min(x,y)
C. Math.min(xy)
D. min(xy)
Answer: B

5. Consider the following arrays. What gets logged in various sorting conditions?
const arr1 = ['a', 'b', 'c'];
const arr2 = ['b', 'c', 'a'];
console.log(
 arr1.sort() === arr1,
 arr2.sort() == arr2,
 arr1.sort() === arr2.sort()
);
A. true, false, false
B. true, true, true
C. true, true, false
D. false, false, false
Answer: C

6. Let’s display some notifications to our user! What gets logged in the following snippet?
const notifications = 1;
console.log(
 `You have ${notifications} notification${notifications !== 1 && 's'}`
);
A. You have 1 notifications
B. You have 1 notificationtrue
C. You have 1 notificationfalse
D. None of them above
Answer: C

7. Which of the following class styles a table as a nice basic table with just some light padding and
horizontal dividers?
A. .table
B. .table-striped
C. .table-bordered
D. .table-hover
Answer: A

8. Which of the following class is used to create a button as a link in bootstrap?
A. .btn-hyperlink
B. .btn-link
C. .btn-anchor
D. None of these
Answer: B

9. Which Class Indicates A Dropdown Menu?
A. .dropdown
B. .select
C. .dropdown-list
D. .dropup-list
Answer: A

10. Which statement references the DOM node created by the code shown?
<p class="pull">lorem ipsum</p>
A. document.querySelector('class.pull')
B. document.querySelector('.pull');
C. document.querySelector('pull')
D. document.querySelector('#pull')
Answer: B

11. What is the output that is printed when the div containing the text "Click Here" is clicked?
<div id="A">
 <div id="B">
 <div id="C">Click Here</div>
 </div>
</div>
//JavaScript
document.querySelectorAll('div').forEach((e) => {
 e.onclick = (e) => console.log(e.currentTarget.id);
});
A. A
B. C
C. CBA
D. ABC
Answer: C

12. Which statement can be used to select the element from the DOM containing the text "Clarusway
Way to Reinvent Yourself" from this markup?
<h1 class="content">Clarusway</h1>
<div class="content">
 <span class="content">Clarusway Way to Reinvent Yourself</span>
</div>
A.document.querySelector("div.content")
B.document.querySelector("span.content")
C.document.querySelector(".content")
D.document.querySelector("div.span")
Answer: B

13. Which property references the DOM object that dispatched an event?
A. self
B. object
C. target
D. source
Answer: C

14. Which event is fired on a text field within a form when a user tabs to it, or clicks or touches it?
A. focus
B. blur
C. hover
D. enter
Answer: A


INTERVIEW QUESTIONS 

1. What are all the looping structures in JavaScript?
Answer: Following are looping structures in Javascript:
For, While, do-while loops

2. Explain the difference between "==" and "==="?
Answer: "==" checks only for equality in value whereas "===" is a stricter equality test and returns false if either the value or the type of the two variables are different.

3. What is the difference between an alert box and a confirmation box?
Answer: An alert box displays only one button which is the OK button.
But a Confirmation box displays two buttons namely OK and cancel.

4. What is SASS and what are its uses?
Answer: The SASS is useful in reducing the usage of CSS which will reduce the time and saves the code that in turn increases code reusability and reduces code redundancy. It provides own syntax for the CSS provides in developing more efficient code. SASS is a superset of CSS which is easier to use and it contains all the features of CSS.

5. How SASS is different from CSS?
Answer: This is the common SASS Interview Questions asked in an interview.
CSS is Cascading Style Sheets whereas SASS is Syntactically Awesome Style Sheets and SASS is a superset of CSS and it contains all the features of CSS. SASS is a CSS pre-processor that will allow using the different operations and using variables, mixins, functions, imports and different kinds of loops. Any types of variables can be declared, defined and used. It will use nested syntax.

6. What Bootstrap Package Includes?
Answer:  Scaffolding − Bootstrap provides a basic structure with Grid System, link styles, and background. This is is covered in detail in the section Bootstrap Basic Structure CSS − Bootstrap comes with the feature of global CSS settings, fundamental HTML elements styled and enhanced with extensible classes, and an advanced grid system. This is covered in detail in the section Bootstrap with CSS. Components − Bootstrap contains over a dozen reusable components built to provide iconography, dropdowns, navigation, alerts, pop-overs, and much more. This is covered in detail in the section Layout Components. JavaScript Plugins − Bootstrap contains over a dozen custom jQuery plugins. You can easily include them all, or one by one. This is covered in details in the section Bootstrap Plugins. Customize − You can customize Bootstrap's components, LESS variables, and jQuery plugins to get your very own version.

7. What is Twitter Bootstrap? 
Answer: Bootstrap is a sleek, intuitive, and powerful, mobile first front-end framework for faster and easier web development. It uses HTML, CSS and Javascript. Bootstrap was developed by Mark Otto and Jacob Thornton at Twitter. It was released as an open source product in August 2011 on GitHub.

