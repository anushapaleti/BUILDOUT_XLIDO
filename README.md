XLIDO - Buildout Project (Crio.Do)

XLIDO is a Java-based backend assignment project

Tech Stack-

| Technology | Purpose |
|------------|---------|
| Java       | Core language |
| Gradle     | Build tool |
| JUnit      | Automated testing |
| Git        | Version control |
| GitHub     | Source code hosting |

Project Structure-


anushapaleti8-ME_BUILDOUT_XLIDO-master/
├── app/
│ ├── src/
│ │ ├── main/java/com/crio/xlido/ # Main Java source
│ │ └── test/java/com/crio/xlido/ # Unit tests
│ └── main/resources/ # Resource files
├── gradle/ # Gradle wrapper files
├── sample_input/ # Sample input files
├── gradlew # Gradle wrapper executable
├── run.sh # Run script used in Crio environment
├── settings.gradle # Gradle configuration
└── .gitignore

How to Run Locally-
-Install Required Software
-Java (JDK)
- Open Project Folder in VS Code

-Clone the Repository 
git clone https://github.com/anushapaleti/BUILDOUT_XLIDO.git
cd BUILDOUT_XLIDO

-Build the Project
.\gradlew build

-Run Test Cases
.\gradlew test

-View Test Report
app\build\reports\tests\test\index.html
