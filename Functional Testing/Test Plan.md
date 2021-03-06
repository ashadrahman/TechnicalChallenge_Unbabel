Test Plan 

Testing Objective: The testing objective is to execute the functional test scenarios of the Annotation Tool.

Features to be tested: The scope of functional testing is following - Login, Choose one task, Perform Annotation, Take a break, Resume Annotation, Finish Annotation

Test Scenarios of the features:

Login

1. Navigate to the link: https://staging.annotation.tools.unbabel.com/
2. Click on sign in button
3. Enter correct Username and Password on the login page.
4. Login should have been successful.
5. Upon incorrect login details entered,  it should display incorrect login details warning.


Choose one task

1. After successful login done, the main page of the tool is accessible.
2. After logging into the annotation tool, the first thing to be noticed is a list of batches. Each line represents a batch that contains a certain amount of translation tasks to be annotated.
3. In each line there is title of the batch, the date it was created and a progress bar. The progress bar represents the amount of tasks needed to annotate to finish the batch. If the batch is finished, then the word Done will appear instead of the progress bar.
4. By clicking on the language pair of the batch the annotation page is accessible.


Perform annotation
1. Select the errors that is found in the target text with the mouse, like selecting a bit of text in a document. The selection will appear in the Current selections field inside the annotation area. (Note: If the selection is not correct, click on the icon with a bin to remove it and select the error again.)
2. Click on Type of Error, choose the type of error to which the selection belongs from the list, select the severity and click on Add Annotation to complete the annotation. (Note: One error is required for each annotation)
3. Important points to note:
(a) The first thing is that the minimum unit of selection is the word. That means that if there is a word in which, for example, there is a letter wrongly capitalized, select the whole word instead of just the incorrectly capitalized letter. On the other hand, the maximum unit for the selection will be the entire expression that is wrong. So if there is an expression that was translated too literally, select the whole expression; if the problem is in the structure of the sentence, then the sentence affected has to be selected.

(b) There are, however, a few exceptions in which it is possible to select less than one word. Those cases are:
• When there is an extra space. In this select only the extra space.
• When the error has to do with a punctuation mark. Then just select the punctuation mark.
• When there is a missing word (like a preposition, an omission, etc.). In that case select the space in which the word should appear.


Take a Break
1. For taking break, click on Finsh button and then click on Back button. The auto timer will stop counting.


Resume Annotation
1. For resuming, click the language pair of the batch on the annotation page
2. Select the circle on the top which denotes the task being performed earlier, and continue the annotation work again.


Finish Annotation
1. After completion of the task, click on Finish or Report -> Click on Finsh radio button under 'What do you want to do?'
2. Select the number of stars for Task Fluency and add some Task comment
3. Click on the Finish button to submit the annotations and fluency score for the text that is just annotated. This will save all the annotations done for that text and lead to the next task to be annotated.
