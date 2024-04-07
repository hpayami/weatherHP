iOS Developer Code Challenge: Weather App with Testing and CI/CD
Objective:
Develop a simple yet comprehensive iOS weather application showcasing current weather and a 5-day forecast for a given location. The application should enable users to search for cities and display the weather details in a user-friendly interface. This project should demonstrate proficiency in SwiftUI, Combine, RxSwift, UIKit, Interface Builder, and programmatically created UI, along with testing and CI/CD practices.
Requirements:
1. Project Setup:
    * Utilize Swift for the application development.
    * Implement the main user interface using SwiftUI.
    * Integrate UIKit components within the SwiftUI interface through UIViewControllerRepresentable.
    * Use Interface Builder for designing at least one screen or component, to demonstrate your skills with .xib files.
    * Create one or more UI components programmatically, showcasing your expertise in programmatic UI layout and constraints.
2. Architecture:
    * Employ the MVVM architectural pattern for clear separation of concerns.
    * Utilize Combine for data flow and event handling within SwiftUI components.
    * Implement RxSwift for managing state and events in UIKit-based components.
3. Functionality:
    * Develop a city search feature, employing either Combine or RxSwift for asynchronous networking and user input processing.
    * Display essential weather information such as temperature, weather condition, humidity, and wind speed, along with a 5-day temperature forecast. Fetch this data from any open weather API.
    * Implement robust error handling for network request failures or when search queries return no results.
4. UI/UX Design:
    * Design the application with at least two screens: one for searching and another for displaying weather details.
    * Ensure the application is responsive across various device sizes.
    * Incorporate at least one custom UIKit component within the SwiftUI views to demonstrate your ability to blend these UI frameworks.
5. Code Quality, Testing, and CI/CD:
    * Maintain high standards of code cleanliness, readability, and documentation.
    * Write unit tests for the business logic and UI tests to verify the application's user interface and interactions.
    * Bonus: Set up a Continuous Integration/Continuous Deployment (CI/CD) pipeline using a platform like GitHub Actions, Travis CI, or Bitrise to automate testing and deployment processes.
Submission Guidelines:
* Submit your project via a Git repository link, ensuring it includes the complete source code.
* Your repository should contain a README file with setup instructions, an architectural overview, and additional notes about your implementation choices.
* Highlight how you've implemented unit and UI tests, as well as any CI/CD pipelines, to underscore your commitment to quality and automation.
