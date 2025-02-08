# 📚 Java Swing Quiz Application

A dynamic and interactive quiz application built with Java Swing and MySQL, designed to provide an engaging learning experience! 🎯

## ✨ Features

- 🎨 User-friendly Graphical User Interface built with Java Swing
- 📊 Real-time score tracking and progress visualization
- 🎲 Random question selection from a comprehensive database
- 📥 Option to download quiz questions for offline usage
- 📝 Feedback submission system
- 📈 Performance history tracking
- 🎯 Multiple-choice question format with instant feedback

## 🛠️ Tech Stack

- **Language:** Java
- **GUI Framework:** Java Swing
- **Database:** MySQL
- **Development Tools:**
  - IntelliJ IDEA
  - MySQL Workbench
- **Dependencies:** JDBC for database connectivity

## 🗄️ Database Structure

The application uses three main tables:

1. **Questions Table**
   - Stores quiz questions and multiple-choice options
   - Tracks correct answers for automatic grading

2. **Results Table**
   - Records user scores and quiz attempts
   - Maintains timestamp for each attempt
   - Tracks number of questions attempted

3. **Feedback Table**
   - Collects user feedback
   - Stores submission timestamps
   - Links feedback to specific users

## 🚀 Getting Started

### Prerequisites

- Java JDK 8 or higher
- MySQL 8.0 or higher
- Maven (for dependency management)

### Installation

1. Clone the repository
```bash
git clone https://github.com/Shripad735/java-swing-quiz-app.git
```

2. Import the database schema
```bash
mysql -u your_username -p your_database < quizappjavaDB.sql
```

3. Configure database connection
- Update the database credentials in the configuration file
- Ensure MySQL service is running

4. Run the application
```bash
java -jar quiz-app.jar
```

## 💡 How to Use

1. Launch the application
2. Enter your username
3. Select the number of questions you want to attempt
4. Start answering the quiz questions
5. Submit your answers to see your results
6. Provide feedback about your experience (optional)
7. Download questions for offline practice if needed

## 🔜 Future Enhancements

- [ ] Additional question categories (Math, Science, etc.)
- [ ] Question timer functionality
- [ ] User authentication system
- [ ] Profile management
- [ ] Enhanced UI/UX with modern design elements
- [ ] Performance analytics dashboard

## 👨‍💻 Developer

**Shripad Khandare**
- 📧 Email: shripad.khandare@mitaoe.ac.in
- 📱 Contact: +91 8180094312

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to all contributors who helped in building this application
- Special thanks to MIT Academy of Engineering for the support
