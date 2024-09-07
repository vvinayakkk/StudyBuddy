
Backend: https://github.com/vvinayakkk/StuddyBuddy-Backend

Frontend: https://github.com/AnushkaShendge/study-buddy-frontend

# 📚 StudyBuddy - Your Ultimate Study Companion

Welcome to **StudyBuddy**, a powerful platform built to enhance the learning experience for students through intelligent, interactive, and collaborative tools. Whether you're prepping for an exam or looking to share notes with friends, StudyBuddy has you covered!

---

## 🚀 Features Overview

### 1. **Custom Test Series Generator**
   - **Tailored Tests**: Create custom test series for Physics, Chemistry, and Maths. Select specific chapters, difficulty levels, and a time limit to generate a personalized test.
   - **Flexible Subject Selection**: Choose one, two, or all three subjects.
   - **Smart Scoring & Analysis**: Each test is scored based on question difficulty, and detailed analysis is provided to help students improve.

### 2. **AI-Powered Chatbot (Langchain RAG)**
   - **24/7 Query Assistance**: Powered by Langchain, our AI chatbot answers any questions related to your study material.
   - **Interact with PDFs**: Chat with multiple PDFs at once to find answers, summarize topics, or clarify doubts in real-time.

### 3. **Collaborative Notes Editor**
   - **Real-time Collaboration**: Share notes with friends and collaborate in real-time. Create documents with text, PDFs, and images seamlessly.
   - **Rich Editor**: Add PDFs, images, and other media to your notes for a comprehensive study resource.

### 4. **Friend Requests & Messaging**
   - **Social Integration**: Send friend requests and exchange messages with peers for seamless communication and collaboration.
   - **Stay Connected**: Share ideas, notes, and doubts easily.

### 5. **Resources Page**
   - **Comprehensive Study Materials**: Access resources curated by subject and chapter to review and practice.
   - **Integrated with Test Series**: After reviewing resources, jump into the test series to practice what you've learned.

### 6. **Community & Group Discussions**
   - **Collaborative Groups**: Join or create study groups where you can discuss doubts, collaborate on projects, or just exchange ideas.
   - **Community-driven Learning**: Engage with the student community to boost your learning experience.

### 7. **JWT-based Authentication**
   - **Secure Access**: Authentication powered by JWT ensures that your data remains safe and your sessions are secure.

---

## 🛠️ Tech Stack

### Frontend
- **React**: Dynamic and responsive UI
- **JWT Authentication**: Secure login and session management

### Backend
- **Django**: REST API for handling server-side logic
- **Node.js**: Additional microservices for real-time chat and notifications

### Database
- **PostgreSQL**: Robust relational database for storing test results, notes, and resources

### AI Integration
- **Langchain**: AI-powered chatbot and document querying system
- **RAG (Retrieval-Augmented Generation)**: Ensures accurate and context-aware query responses

---

## 📈 How it Works

1. **Create Your Test**: Select chapters, set difficulty and time, then start your custom test.
2. **Receive AI Assistance**: Use the Langchain chatbot to clarify doubts, summarize chapters, or ask for hints.
3. **Collaborate with Peers**: Share notes, create study groups, and message friends—all from one platform.
4. **Track Progress**: Get detailed analysis of your performance and revisit challenging topics through the resources page.

---

## 🖥️ Installation and Setup

### Prerequisites
- **Node.js**: Ensure you have Node.js installed for frontend setup.
- **Python 3.x**: Required for running the Django backend.
- **PostgreSQL**: Set up a PostgreSQL database locally or on the cloud.

### Backend (Django)

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/studybuddy.git
    cd studybuddy/backend
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run migrations:
    ```bash
    python manage.py migrate
    ```

4. Start the server:
    ```bash
    python manage.py runserver
    ```

### Frontend (React)

1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the React app:
    ```bash
    npm start
    ```

---

## 🛠️ Development & Contribution

Contributions are welcome! Here's how you can get started:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## 🎯 Future Enhancements
- **Gamified Learning**: Introduce a reward system for students based on their performance.
- **Leaderboards**: Track progress against other students and improve through competition.
- **More Subjects**: Expand the subjects offered to cover additional topics and courses.

---

Feel free to fork and contribute to make **StudyBuddy** even better!


