 this assignment you will develop and test a Web application using HTML, CSS, and JavaScript that asks questions to determine if a person is your true love. More specifically your application should ask five questions in the form of statements and allow the user to respond to each statement with the numbers 1 through 5 with 1 indicating strongly disagree and 5 indicating strongly agree. You will then compare the person’s answers with your desired “true love” answers. The closer the answers are to your desired “true love” answers the better match the two of you are for each other.

For example, suppose you choose the statement “Broccoli is delicious.” and your desired answer was 1 (strongly disagree) because you really don’t like broccoli. If the application user entered 4 (agree), then the two of you would not be a very good match based on that question. In the broccoli example above you would want to calculate your question compatibility score for this question by taking the absolute value of the difference between their answer and your desired answer.

After all five questions are answered, you will need to add up the question compatibility scores for each of the questions and subtract the value from 100 to calculate a final compatibility score that has a maximum value of 100.

You will also need to set three threshold scores. One for “true love,” one for possible “friends,” and one for “run away.” You utilize your programming knowledge, creativity, and good taste to set and adjust the thresholds, phase the results, and share the results to the user. Be sure to review and test your ideas for the application with a friend or classmate to get some usability feedback.

If you are looking for some examples of what this application might look like if it was a command line application and Dr. Klump was creating it, you can see it here [link]. I’m sure you can improve on his design.

Requirement 1
Create an application that:

Is implemented in a single file name “index.html” or with separate CSS and JavaScript files
Is hosted as a public website using GitHub Pages or Microsoft Azure
Has a simple yet an aesthetically pleasing user interface
Includes user instructions that succinctly describes the application and how it works
Requirement 2
Be sure that the application also:

Asks five questions as described above
Calculates question compatibility scores for each question
Calculates the total compatibility scores across all questions
Requirement 3
Enhance the application so that it:

Displays a summary of each question’s compatibility score
Displays a summary of the overall compatibility score as a percentage
Displays an interesting closing remark based on the identified threshold scores
Validates user input, displays meaningful error messages as, and asks the question again as needed
Requirement 4
Finally test and refactor the application so that it:

Utilizes constants at the top of the file or in a separate file where possible
Utilizes a single function called “validate” to validate user input and displays and error message for all questions as needed
