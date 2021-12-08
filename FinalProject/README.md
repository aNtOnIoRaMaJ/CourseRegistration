1) Unzip Project.zip
2) Place the CourseRegistration.jar file in some directory 
3) Place the MySQLConnector.jar file in another directory
4) Run the command 

"java --module-path /$PATH_TO_JAVAFX_SDK/.jdks/javafx-sdk-17.0.1/lib --add-modules javafx.controls,javafx.fxml -jar /$PATH_TO_JAR/CourseRegistration.jar"

Note that this may not work due to MySQLConnector having a preconfigured location, if so, add MySQLConnector as an external library (point to path from 3).

Use the program by entering in a username/password and then adding/removing
courses, look at previous courses, et cetera. Below are some usernames/passwords
you can use, a student's login.

User:
arete39

Pass:
iamarete
