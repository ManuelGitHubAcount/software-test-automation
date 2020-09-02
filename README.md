# Automatic Functional Tests ->Focus Services 
_The focusservices program implements an application that runs functional tests automatically,
Navigating through the different components of the web page, allows you to view each component found
and the action executed in it, additionally the program validates internally if the component was located successfully, 
if it exists or does not exist. For any 'success' or 'failure' result, the program prints the results for each test case
to the console_

### Starting 🚀
_These instructions will allow you to get a copy of the project running on your local machine for testing purposes._

### Pre-requisites 📋
* _Focus Services Project Version: 1.0 (https://github.com/ManuelGitHubAcount/software-test-automation/)_.
* _Eclipse IDE Version: 2020-06 (https://www.eclipse.org/downloads/)_.
* _JDK Version: 1.8.0 (https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)_.
* _Junit Version: 4.13 (https://search.maven.org/artifact/junit/junit/4.13/jar)_.
* _Selenium Server Version: 3.141.59 (https://www.selenium.dev/downloads/)_.
* _ChromeDriver Version: 85.0.4183.87 (https://chromedriver.chromium.org/downloads)_.
* _Google Chrome Version 85.0.4183.83 (https://www.google.com.mx/chrome/)_.

### Installation 🔧
_To begin the installation process, first download the list of tools described in the prerequisites part. Then follow each of the following steps._
* **Step 1: Install JDK**. _And create JAVA_HOME environment variable and add the file PATH._
```
JAVA_HOME: C:\Program Files\Java\jdk1.8.0_151.
PATH: C:\Program Files\Java\jdk1.8.0_151\bin.
```
* **Step 2: Install Eclipse IDE for Java Developers**.
_When the installation is complete, access the Eclipse IDE Environment and open the Focus Services Project_
```
File -> Open projects from File System or Archive -> Import Source -> Directory -> Select focusservices project -> Finish.
Go to Projects -> Clean, then select the Build Project option.

To finish the process, if your project has errors, please go to...
Click on Project -> Maven -> Update Projects, this will allow you to build the project successfully.
```
* **Step 3: Install Google Chrome**.
_It is extremely necessary to install the indicated version or a higher version, otherwise the google chrome driver will not run successfully_.

* **Step 4: Install Junit, Selenium Server and ChromeDriver**.
_For these Junit, Selenium Server and ChromeDriver tools, it is not necessary to install or configure them, because they are already attached to the project_.

### Running the tests ⚙️
_To run the project and validate the test cases, do the following._
```
Go to Eclipse IDE and,
In the project, browse the project folders until you find FocusRunTestMethodsClass.class.
Path: focusservices -> src/test/java -> focusservices -> FocusRunTestMethodsClass.class.

Then, just Right click on the class 'FocusRunTestMethodsClass.class' -> Run As -> Junit Test.

The application will start to execute each of the test cases. Regardless of the results, you will get a message on the console.
```

### Built with 🛠️
_Working on it..._

### Authors ✒️
* **Manuel Reyes**

### License 📄
_Working on it..._
....

_Sincerely, Manuel Reyes_.
_Good luck_.
