# Interactive Quiz Application

This project is an interactive quiz application that allows users to upload or paste quiz data in JSON format and take quizzes with a timer option. The application supports both light and dark themes and provides feedback on quiz performance. Easily generate quizzes using language models and customize your learning experience.

## 🚀 Live Demo
**Try it now:** [https://joyontasaha.github.io/interactive-quiz-app/](https://joyontasaha.github.io/interactive-quiz-app/)

## Features
- Upload or paste quiz data in JSON format.
- Toggle between light and dark themes.
- Timer functionality with customizable durations.
- Review incorrect answers and retake the quiz.
- Visual feedback with animations and modals.

## Getting Started

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/JoyontaSaha/interactive-quiz-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd interactive-quiz-app
   ```
3. Open `index.html` in your web browser to start the application.

## Usage
1. Choose to upload a quiz JSON file or paste JSON data directly into the application.
2. Select the desired timer duration if needed.
3. Start the quiz and answer the questions.
4. Review your performance and retake the quiz if desired.

## JSON Format
The quiz JSON should follow this structure:
```json
{
  "title": "Quiz Title",
  "heading": "Quiz Heading",
  "questions": [
    {
      "question": "Question text",
      "options": [
        "A. Option 1",
        "B. Option 2",
        "C. Option 3",
        "D. Option 4"
      ],
      "correctAnswer": "A",
      "explanation": "Explanation for the correct answer."
    }
  ]
}
```

## Creating a Quiz with a Language Model

To create a quiz using a language model, you can prompt the model with a topic and request it to generate questions and answers in the specified JSON format. Here's a step-by-step guide:

1. **Choose a Topic**: Decide on the subject or topic for your quiz.

2. **Prompt the Language Model**: Use a language model (such as GPT) to generate quiz questions. You can use a prompt like:
   
   "Generate a quiz on [Your Topic] with 5 questions. Each question should have 4 options labeled A, B, C, and D, and include the correct answer and an explanation. Format the output as JSON."

3. **Format the Output**: Ensure the generated output matches the JSON structure required by the application:
   ```json
   {
     "title": "Your Quiz Title",
     "heading": "Your Quiz Heading",
     "questions": [
       {
         "question": "Question text",
         "options": [
           "A. Option 1",
           "B. Option 2",
           "C. Option 3",
           "D. Option 4"
         ],
         "correctAnswer": "A",
         "explanation": "Explanation for the correct answer."
       }
     ]
   }
   ```

4. **Load the Quiz**: Once you have the JSON formatted correctly, you can upload it to the application or paste it directly to start the quiz.

This approach allows you to quickly generate quizzes on various topics using the power of language models.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

Feel free to customize this README file to better fit your project's needs. 
