Steps to run the automation script:

1. Download the zip file 'TechnicalChallenge.zip' and unzip it.

2. Required softwares- Google Chrome webrowser, Eclipse IDE, Selenium jar file(selenium-server-standalone-3.12.0.jar) and java jdk 1.8 installed on the system.

3. Download 'chromedriver.exe' file from this link 'http://chromedriver.chromium.org/downloads' 

4. Place this chrome driver at any location (place it at 'C:\chromedriver.exe')

5. Open Eclipse IDE-> click on File -> Click on Import -> select General - Existing Projects into Workspace and click Next-> in Select root directory, click browse and select the unziped file 'TechnicalChallenge' and click on Finish Button.

6. The 'TechnicalChallenge' will open under Package explorer on the left side panel and expand it.

7. Right click on the 'TechnicalChallenge'-> select Build Path -> select Configure Build Path -> 'Properties for TechnicalChallenge' dialogue box will open up

8. Under the Java Build Path-> select Libraries Tab-> Click on add external JARS button-> add the selenium (selenium-server-standalone-3.12.0.jar) file

9. Under the same Libraries tab, select and remove the already mentioned 'selenium-server-standalone-3.13.0.jar - F:\Sanjay\Selenium\SeleniumFile (missing)'

10. Click Apply and OK on the 'Properties for TechnicalChallenge' dialogue box

11. Expand the 'TechnicalChallenge' project-> click and expand src folder-> click and expand Pack1->double click on AnnotationTest.java

12. The AnnotationTest.java file will open in the right window of eclipse.

13. Edit line 21 of the code by replacing "F:\\Sanjay\\Selenium\\SeleniumFile\\chromedriver.exe" with the location of your locally placed chromedriver ("C:\\chromedriver.exe")
    So, line 21 should now look like this:  System.setProperty("webdriver.chrome.driver","C:\\chromedriver.exe");

14. On the top tools bar, click on Run button(green button)->click Run As-> click TestNG Test -> Click OK on the Save and Launch dialogue box

15. The entire testing of the Annotation tool will start automatically on the chrome browser.

16. The test results can be seen in the console of the eclipse IDE.