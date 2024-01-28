Prerequisites
Install and set environment variable for java.
Windows - https://www.oracle.com/java/technologies/downloads/
Linux -  sudo apt-get install openjdk-8-jre 
MacOS - Java should already be present on Mac OS X by default. 2 Install and set environment varibale for Maven.
Windows - https://maven.apache.org/install.html
Linux/ MacOS - Homebrew (Easier)
install maven
Run your First Test
Clone the Java-Selenium-Test repository.
git clone https://github.com/Sameer7621/Automation_Selenium_TestNG_Java.git
Next get into Java-Selenium-Sample folder, and import Lamabdatest Credentials. You can get these from lambdatest automation dashboard.
For Linux/macOS::

export LT_USERNAME="YOUR_USERNAME"
export LT_ACCESS_KEY="YOUR ACCESS KEY"
For Windows:

set LT_USERNAME="YOUR_USERNAME"
set LT_ACCESS_KEY="YOUR ACCESS KEY"
Step 3. You may also want to run the command below to check for outdated dependencies. Please be sure to verify and review updates before editing your pom.xml file as they may not be compatible with your code.

 mvn versions:display-dependency-updates
Step 4. Run testsuite.

mvn clean compile test -D suite=testng.xml
