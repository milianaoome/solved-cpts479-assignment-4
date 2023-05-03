Download Link: https://assignmentchef.com/product/solved-cpts479-assignment-4
<br>
For this homework you will extend the QuizApp functionality from HW2 (not HW3) so that you can add new quiz questions. I have posted my solution to HW2 on Blackboard Learn. You can work from this version, or your own. See screenshots below. Specifically,

<ol>

 <li>Embed the main view into a Navigation Controller.</li>

 <li>Remove the “Quiz App” label and use the Prompt property of the Navigation Item to display “Quiz App”. The Title should just be “Quiz”.</li>

 <li>Add a Bar Button Item to the right side of the Navigation Item and change its System Item property to “Add” (you should see the “+” sign for the button).</li>

 <li>Add a new view controller and class called “AddQuestionViewController”. Add a segue from the “+” button to this view. In the Navigation Item of this new view, change the Prompt to “Quiz App”. The Title in the Navigation Item should display “Add Question <em>N</em>”, where <em>N</em> is the number of the new question (one more than the number of existing questions).</li>

 <li>The Add Question view should display six text fields for entering the question prompt and 2-5 answers. Below these, should be a segmented control for selecting the correct answer, appropriately labeled. The onscreen keyboard should dismiss when the user taps Return while editing the text fields. For now, we will assume the data for the new quiz question is entered correctly. Any answers left blank should not appear in the quiz question.</li>

 <li>In the Add Question view, add a “Cancel” button in the upper left and a “Save” button in the upper right. These will need to be added programmatically. Tapping “Cancel” should return to the Quiz where it left off without adding a new question.</li>

 <li>When the “Save” button is tapped, the app returns to the Quiz where it left off and adds the new quiz question to the end of the existing quiz questions. This new question should eventually appear as you cycle through the questions using the “Next” button. The user should be able to add multiple new questions.</li>

 <li>Be sure that auto layout constraints are set so that the view elements are appropriately displayed with no overlap regardless of device orientation.</li>

 <li>Other than the changes described above, your app should also meet all of the HW2 requirements (and <strong>not</strong> contain any of the additional HW3 functionality).</li>

</ol>

1 StoryBoard:







Simulator:





