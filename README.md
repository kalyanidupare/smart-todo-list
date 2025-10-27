📝 smart-todo-list

A modern desktop To-Do List application built using JavaFX, Maven, and SQLite.
This project helps users organize, manage, and prioritize their daily tasks efficiently with a clean and elegant user interface.

🚀 Features

✅ Add, edit, and delete tasks with ease

📅 Mark tasks as completed or pending

💾 Tasks are stored locally using SQLite

🎨 Beautiful and responsive JavaFX UI

⚙️ Managed using Apache Maven for easy builds

🔍 Optional search or filter functionality for tasks

🕒 Auto data persistence — your tasks remain safe even after closing the app

🧩 Tech Stack
Component	Technology Used
Frontend	JavaFX
Backend	Core Java
Database	SQLite
Build Tool	Apache Maven
IDE Recommended	IntelliJ IDEA / Eclipse / VS Code (with Java Extension)
🛠️ Prerequisites

Before running this project, make sure you have the following installed:

✅ Java JDK 17+

✅ Apache Maven 3.9+

✅ A Java IDE such as IntelliJ IDEA, Eclipse, or VS Code

To confirm installations, run these commands in your terminal:

java -version
mvn -version

⚙️ Installation & Setup

Follow these steps to run the project locally 👇

Clone the Repository

git clone https://github.com/kalyanidupare/smart-todo-list.git


Navigate into the Project Folder

cd smart-todo-list


Build the Project using Maven

mvn clean install


Run the Application

mvn javafx:run

🧮 Project Structure
smart-todo-list/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/smarttodolist/
│   │   │       ├── Main.java
│   │   │       ├── Controller.java
│   │   │       └── DatabaseHandler.java
│   │   └── resources/
│   │       ├── ui/
│   │       │   └── main.fxml
│   │       └── css/
│   │           └── style.css
│   └── test/
│       └── ...
│
├── pom.xml
└── README.md

💡 Future Improvements

🔔 Task reminders and notifications

☁️ Cloud sync (Firebase / MongoDB Atlas integration)

📱 Mobile-friendly version using Gluon

🌗 Dark & Light theme toggle

📊 Dashboard analytics for completed vs. pending tasks

🤝 Contributing

Contributions are always welcome!
To contribute:

Fork the repo

Create a new branch (feature-branch-name)

Commit your changes

Push your branch and open a Pull Request

🧑‍💻 Author

Kalyani Dupare

🎓 Computer Science & Business Systems Student
💡 Passionate about building smart, user-friendly, and impactful software solutions

🪪 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

⭐ Support

If you like this project, please give it a ⭐ on GitHub → smart-todo-list

Your support helps others discover this project and motivates continued development! 💖
