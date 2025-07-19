Multiple Choice Quiz App

This is a simple console-based multiple-choice quiz application written in Java. It loads questions from a formatted text file and interacts with the user through the command line to test their knowledge about Pokémon. The quiz supports both regular questions with a single correct answer and bonus questions with multiple correct answers.

Features

    Loads questions from an external text file (ex: RandomQuiz.txt)
    Supports multiple answer options (A-D)
    Handles bonus questions with multiple correct answers
    Provides immediate feedback and a final score

How it Works

    Question Loading: The app reads questions from PokemonTrivia.txt, parsing question text, options, answers, and whether the question is a bonus.

    Quiz Interaction: Presents each question and options to the user, prompts for input, and checks correctness.

    Scoring: Keeps track of the number of correct answers and displays the total score at the end.

File Format for Questions

The questions file (RandomQuiz.txt) should follow this format:

          

    Q: What is the capital city of France?
    A: Madrid
    B: Paris
    C: Rome
    D: Berlin
    Answer: B
    
    Q: What is the largest planet in our Solar System?
    A: Earth
    B: Neptune
    C: Saturn
    D: Jupiter
    Answer: D

      

Note:

    Each question block is separated by a blank line.
    The Answer: line can contain one or multiple answers separated by spaces.
    The Bonus: line indicates if the question has multiple correct answers.

Usage

    Prepare your questions file: Create a text file named PokemonTrivia.txt in the same directory as your Java program, following the specified format.

    Compile the program:

          

javac Main.java

      

    Run the application:

          

java Main

      

Follow the prompts to answer each question.
Improvements & Customization

    You can modify the questions file to add more questions or change existing ones.
    Enhance the program to provide immediate feedback after each question.
    Add a timer or difficulty levels for more advanced features.

License

This project is for educational purposes. Feel free to modify and extend it!

Note: Ensure your quiz text file is correctly formatted and located in the same directory (src) as your compiled Java class.
