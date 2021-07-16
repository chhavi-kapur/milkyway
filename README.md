# Milkyway: Online dessert ordering platform <br>

![milkyway](https://im4.ezgif.com/tmp/ezgif-4-5ec411e3a4bb.gif)

Milkyway, a website that lets customers browse a wide selection of Vancouver based bakeries while providing broad search categorization (search an item directly by name, by the shop’s name or by the categories- sweet or savoury or by the type of item- gluten-free, sugar-free, dairy-free or vegan.) It would allow the user to browse through multiple online stores available on the platform, look up various items offered at those stores and then order the desired items to their chosen customer address at their chosen time.

Using HTML5, CSS, Bootstrap, Java, Spring MVC Framework, Spring data JPA, Apache Maven, Thymeleaf, H2 database and Apache Tomcat.<br>

# How to import the project
## Importing project in Eclipse or Spring Tool Suite
### Adding toolbar shortcuts to your perspective.
* Create a new workspace or use your existing workspace.
* Go to Windows -> Perspective -> Customize Perspective.
* Go to Action Set Availability tab.
* Check Git, Git Navigation Action and Git Search.
* Go to Toolbar Visibility tab.
* Make Sure that Git is checked.
* Click Apply and close.

### Adding Git Staging and Git Repository view
* Go to Windows -> Show View -> Others
* Search Git and select Git Repositories and Git Staging (You can select multiple view by holding down Ctrl button and clicking the item).

### Cloning the Project
* In the Git Repositories View click on clone a repository.
* Paste "https://github.com/chhavikapur/milkyway.git" (without the quotes) in the URI value in the location section.
* In the Authentication section add your github username and password. 
* You can check "Store in Secure Store" if you don't want to enter your username and password everytime you push or pull.
* Click Next.
* In branch selection, select all branches and click Next.
* Choose the destination directory of your choice and click Finish.
* Now you should see the project in the Git Repositories View.
* Right click the milkyways[master] root project in the Git Repositories and select Import.
* Confirm that the folder is milkyways and import as value is maven.
* Click Finish and now you should see the project in the Package Explorer.

### Running the Project
* The project includes Tomcat dependencies by default so you can directly run the Project without Tomcat installation.
* In the Package Explorer go to src/main/java -> com.runtimeterror.milkyways and Open MilkywaysApplication.java
* Run the Program. If promted run the program as a Java Application. You should see maven building the project. 
* After maven finishes building you can open localhost:8080 in the browser to view the project. 

## Importing project in IntelliJ Idea
* Close previous project (if any).
* On the startup screen select Checkout from Version Control and select Git
* Add https://github.com/chhavikapur/milkyway.git in the URL section and Choose the directory of your choice to import the project in. 
* Click Test to check if the link is working correctly.
* Click on Clone.
* In the Checkout from Version Control dialog click Yes to open the project. 
* Wait for Maven to fetch the dependencies and Run the src/main/java -> com.runtimeterror.milkyways -> MilkyWaysApplication.java
* After maven finishes building you can open localhost:8080 in the browser to view the project.
