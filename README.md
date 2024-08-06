ExamPlatform
====

A front-end page using Vue3 TS for simulating online exams

--------

## Features
- **Create a test paper**: You can create a test paper to accommodate all your questions of the same type.
- **Add questions**: You can fill in questions based on their type and add them to the test paper.
- **Custom question type**: You can customize the presentation style of questions by dragging and dropping the required question module through the custom type page provided by the platform.
- **Support Latex and Markdown**: The presentation of questions and options supports Latex and Markdown.
- **WYSIWYG**: (what you see is what you get)Support real-time display for Latex and Markdown when adding questions.
- **Support question disorder**: Support shuffling the display of question types and the order of question options during exams.
- **Score assessment**: At the end of the exam, the questions will be retrospectively reviewed.


## Usage
### Ordinary use
   > [!TIP]
   > If you don't like the style of the page, you can modify it yourself.
   
   > [!IMPORTANT]
   > Since this version does not provide binary executable files, you may need a Python interpreter (exe may coming soon)
    
   1. **Starting Flask Service with Python**
      ```Dos
      python app.py
      ```
   2. **Open the browser and enter the following URL**  
      `http://localhost:5000/`

   3. **Begin to operate**
      You can create a test paper, add questions, customize the question type, and start the exam.

### develop or debug
   <mark>If you want to develop or debug</mark>

   > [!IMPORTANT]
   > Please make sure you have **Node** and **npm**

   1. **Enter this folder**
      ```Dos
      cd \path\to\examPlatform
      ```
   2. **Obtain dependencies**
      ```Dos
      npm install
      ```
   3. **Start local server**
      ```Dos
      npm run dev
      ```
   4. **Make modifications**
      Finally, modify what you want to modify.