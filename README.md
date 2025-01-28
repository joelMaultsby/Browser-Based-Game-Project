# Browser-Based-Game-Project
Quiz Game Title: State Capitals

BEGIN Quiz

    SET score = 0

   Question 1
    DISPLAY "Question 1: What is the capital of Missouri?"
    GET  answer to question 1 which is answer1 from user
    IF answer1 == "Jefferson city"
        INCREMENT score by 1

   ELSE IF answer==null

        DISPLAY "Please provide a text answer. Empty response is not accepted."
    

    Question 2
    DISPLAY "Question 2: What is the capital Utah?"
    GET answer to question 2 which is answer2 from user
    IF answer2 == "Salt Lake city"
        INCREMENT score by 1


    ELSE IF answer==null

        DISPLAY "Please provide a text answer. Empty response is not accepted."

    Question 3
    DISPLAY "Question 3: What is the capital of Texas?"
    GET answer to question 3 which is answer3 from user
    IF answer3 == "Austin"
        INCREMENT score by 1

    ELSE IF answer==null

        DISPLAY "Please provide a text answer. Empty response is not accepted."

Question 4
    DISPLAY "Question 4: What is the capital of Florida?"
    GET answer to question 4 which is answer4 from user
    IF answer4 == "Tallahassee"
        INCREMENT score by 1
    

     ELSE IF answer==null

        DISPLAY "Please provide a text answer. Empty response is not accepted."

    Display final score to the score
    DISPLAY "Your final score is: " + score

END Quiz
