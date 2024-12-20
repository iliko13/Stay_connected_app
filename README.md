# 📱 Stay Connected App

Stay Connected is a versatile platform where users can ask questions, provide answers, and engage in meaningful discussions. The app allows users to:

Ask Questions: Add a title, multiple tags, and your question. Questions appear in both the General and Private sections, depending on the selected visibility.
Answer Questions: Respond to any question. If your answer is marked correct, you earn 10 points; otherwise, you score 0 points.
Validate Answers: Mark a submitted answer as correct or reject it and provide the correct answer instead. A green tick will appear beside questions with confirmed correct answers.
Search Functionality: Search for questions by their title, tags, or a combination of both for quick access to relevant discussions.
User Profiles: View your profile, including your photo, email, name, score, and the number of answered questions. You can tap on your answered questions to see only those you have interacted with.
Stay Connected offers a structured yet user-friendly environment to share knowledge, collaborate, and grow while keeping track of your progress through points and activity tracking.

# ⚙️ Features:

* Authorization ✅
* Scroll Feed 📲
* Ask Questions 💬
* Search via letters or tags or both 🔍
* See Searched Questions Details Page 📖
* See Searched Questions Answers 🕵️‍♂️
* Mark or Reject Questions' Answers ✅ 🚫
* Add Question ➕❓ 
* Add Answers ➕ ✔️
* Navigate to Profile( Score, Answered Question) 👤➡️

# 👨🏻‍💻 Tools & Technologies Used:
🚀 Xcode: Integrated development environment for building the app.
🚀 Language: Swift, for creating a robust and intuitive user experience.
🚀 Frameworks: UIKit and Foundation, for designing the UI and managing app functionality.
🚀 Version Control: GitHub, for collaborative development and code management.
🚀 Backend API: Swagger, for designing, documenting, and testing API endpoints efficiently.


# 🤝 Contribution:

Here's a refined version of your text:

The Stay_Connected app was developed using the UIKit framework, with contributions from Iliko Kukava and Sandro Maraneli. Together, we implemented various functionalities that enhance the user experience.

For authentication, we integrated token-based login, where the app communicates with the backend server to obtain tokens. These tokens are securely stored in the keychain, allowing users to seamlessly access the app without needing to log in again on subsequent launches.

We designed an intuitive and user-friendly interface for adding questions, which can be displayed as either private or general questions. We also implemented the ability for users to submit answers, with the app accurately tracking scores based on correct and rejected answers.

Our app utilizes a custom Network package and Keychain package to manage communication with the API. By calling various API endpoints, we fetch different types of information, such as tags, questions, and answers. We employ HTTP methods like GET, POST, and PATCH to interact with the server and ensure smooth data exchange.
