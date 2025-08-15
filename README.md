# QuizBuzz

QuizBuzz is an interactive quiz app built with **Next.js** and **Tailwind CSS**. Users can select subjects, answer timed questions, and view detailed results. Quiz data is loaded dynamically from JSON files.

---

## Features

- **Subject Selection:** Pick a subject from the home page; questions load from JSON files.  
- **Timed Quiz:** Each question has a **10-second countdown**; unanswered questions are marked **unattempted**.  
- **Answer Validation:** Correct answers turn **green**, incorrect turn **red**, with immediate feedback.  
- **Scoring System:** Earn **4 points** per correct answer; score updates in real-time.  
- **Detailed Results:** View total points, correct/wrong/unattempted questions, percentage score, and time spent.  
- **Responsive Design:** Works on desktop, tablet, and mobile devices.  

---

## Technologies Used

- **Next.js**  
- **Tailwind CSS**  
- **React Icons**  
- **Confetti**  
- **JavaScript (ES6)**  

---

## Project Structure



public/data/: Contains JSON files for questions.
components/Results.jsx: Displays the quiz results.
components/QuestionTimer.jsx: Manages the countdown timer for questions.
components/SubjectCard.jsx: Displays the subjects available for selection.
pages/index.js: Home page listing available subjects.
pages/quiz/[subject].js: Quiz page for each subject.
public/images: Contains static assets like images.
context/PointsContext.js: Context for managing points state.
layout.js: Includes header and footer components.
