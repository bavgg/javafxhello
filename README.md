### Prerequisites

- Java SDK
- JavaFX SDK
- JavaFX JMODS
- Java

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/bavgg/javafxhello.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd javafxhello
   ```

3. **Compile:**

   ```bash
   javac --module-path %PATH_TO_FX_JAR% --add-modules javafx.controls,javafx.fxml -d out .\src\hellofx\*.java
   ```

4. **Create JAR file:**

   ```bash
   jar --create --file hellofx.jar --main-class=hellofx.Main -C out . -C src hellofx/hellofx.fxml
   ```

5. **Run the project:**

   ```bash
   java --module-path %PATH_TO_FX_JAR% --add-modules javafx.controls,javafx.fxml -jar .\hellofx.jar
   ```


## Contact

- Email: gestopajonas@gmail.com
- GitHub: [bavgg](https://github.com/bavgg)
