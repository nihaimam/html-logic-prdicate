# swe432-assignment-3

If you work with partners, submit the same assignment and include all names.

Create a web form to accept logic predicates, similar to 'if' statements in programs. A logic predicate should have boolean variables connected with logical operators. Examples include: “A OR B,” “x && y,” “M and N or Q,” and “today | tomorrow.” Note that the examples use different symbols for logical operators. You need to design the syntax and format, including the syntax allowed for the logical operators, the syntax of variable names, and other decisions. For example, is there a limit on the number of boolean variables?

Your screen must include instructions that specify the format and syntax, a title with the course number (SWE 432) and names of all collaborators, and if a 1-paragraph collaborative summary if you work work with partners. You will be graded on usability aspects of the instructions such as layout and clarity.

Your form must also include a button to submit the logic predicate. Do not implement a backend for now, we are only building UI mockup screen.

Your screen must include at least two JavaScript functions that manipulate the BOM-DOM. You decide what your JS should do.

For now, you can check your form data using this simple general form handler servlet. Your HTML will send the user’s form data to this program, and it echoes the inputs to the user. Your HTML must include the HTML form tag:
<form method="post" action="https://cs.gmu.edu:8443/offutt/servlet/formHandler">
Copy this verbatim into your HTML. When the user presses a submit button, all data submitted will be echoed to the user’s screen.

We will be adding more functionality (including back-end code) to your front-end in future assignments.

