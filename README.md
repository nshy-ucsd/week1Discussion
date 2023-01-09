**Running the tester on UNIX based systems (including a mac):**
Compile: javac -cp libs/junit-4.12.jar:libs/hamcrest-core-1.3.jar:. DemoArrayImplTester.java
Execute: java -cp libs/junit-4.12.jar:libs/hamcrest-core-1.3.jar:. org.junit.runner.JUnitCore DemoArrayImplTester

**Running the tester on Windows systems:**
Compile: javac -cp ".;libs\junit-4.12.jar;libs\hamcrest-2.2.jar" DemoArrayImplTester.java
Execute: java -cp ".;libs\junit-4.12.jar;libs\hamcrest-2.2.jar" org.junit.runner.JUnitCore DemoArrayImplTester