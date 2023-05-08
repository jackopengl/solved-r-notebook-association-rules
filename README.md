Download Link: https://assignmentchef.com/product/solved-r-notebook-association-rules
<br>
For this portion of the assignment, we will be using data from Groceries, a dataset that can be found with the arules package. Each row in the file represents one buyer’s purchases. This link provides some helpful templated <a href="http://r-statistics.co/Association-Mining-With-R.html">examples for generating association rules: http://r-statistics.co/Association-Mining-With-R.html (http://rstatistics.co/Association-Mining-With-R.html)</a>

<ol>

 <li>Describe “Groceries” by answering following questions: What is the class of “Groceries”? How many rows and columns does Groceries contain?</li>

</ol>







<ol start="2">

 <li>Generate an item frequency barplot for the grocery items with support rate greater than 0.05. Include a screenshot of your results, along with the code you used to do this.</li>

</ol>







<ol start="3">

 <li>Now, create a subset of rules that contain your grocery item (you can find your item in the spreadsheet in Blackboard, in Class Discussions From Your Instructor). Select 4 different rules, (2 lhs and 2 rhs), and explain them in the way you would explain them to your roommate (I’m assuming your roommate is a smart person who is unfamiliar with data mining). Remember, every rule has three components: support, confidence, and lift. For each group of rules (grocery item on left-hand side, and grocery item on right-hand side), include a screenshot of your rules, along with the code you used to generate the rules. In a sentence or two, explain what meaning these rules might have for a supermarket retailer, such as Star Market. What could it do with this information?</li>

</ol>




<ol start="4">

 <li>Using the plot() function in the arulesViz package, generate a scatter plot of any three rules involving your grocery item. Include a screenshot of your plot, along with the code you used to generate the plot. Describe your results in a sentence or two.</li>

</ol>







<ol start="5">

 <li>Again using the plot() function in the arulesViz package, generate a plot for any three of your rules. This time, add two more arguments to the function: method=“graph”, engine=“htmlwidget”. What do you see now? Include a screenshot of your plot, along with the code you used to generate the plot. Describe your results in a sentence or two.</li>

</ol>