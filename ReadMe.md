Example Image:<br>
![Alt text](Screenshot.png?raw=true "Example Hello World Application")

Compiling:
```ps1
javac --module-path "C:\Program Files\javafx-sdk-18.0.1\lib" --add-modules javafx.controls HelloWorldApplication.java
```

Running:
```ps1
java --module-path "C:\Program Files\javafx-sdk-18.0.1\lib" --add-modules javafx.controls HelloWorldApplication
```

Other important ```--add-modules```:
- ```javafx.fxml```
- Example: 
```ps1
javac --module-path "C:\Program Files\javafx-sdk-18.0.1\lib" --add-modules javafx.controls,javafx.fxml FXML_Project.java
```

Compile whole folders... With:
```ps1
javac folder_name/*.java
```
