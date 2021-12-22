This is a trivia game inspired by the popular game, 'Trivial Pursuit'. The trivia questions in this game are all about the 90s television show, 'Fresh Prince of Bel-Air'. There are 4 categories, with 5 questions each, that the user will have 20 seconds to answer. Each correct question will move your character to the next square on the board.

# Pseudocode

<!-- ! CSS Styling -->
## 4 screens
## HOME CONTAINER
  1a. home-container(desktop/ipad): masonry grid layout of the 9 characters plus game title card layered over the 9 character images and 2 color blocks(one will host enter button) 
    - 3 columns, auto-rows
  1b. home-container(mobile): solo centered grid layout of the game title card layered over the fresh prince will character image
    - 1 col, 2 rows, 2 layered centered divs and enter button on second row
  












  
## INTRO CONTAINER
  2a. intro-container(lg screens): 3 columns/ 4 rows
    -title-div: 1 row 3 cols
    -instructions-div: 1 row/ 3 cols
    -category-grid-container: 2 rows/ 3 cols for 4-6 category cards
    -start-btn
  2b. intro-container(mobile): 1 col / 8 rows

## QUIZ CONTAINER
  3a. quiz-container(lg screens): board game grid layout on desktop, landscape tablet sizing only, mobile sizing on portrait tablet size
  <!-- ! TO BE FILLED IN LATER -->
    - title-div
    <!-- - question-card-grid: 1 row 2 cols for timer icon, 1 row 2 col for question heading, 2 rows 2 cols for 4 choice btns -->
    - timer-div
    - question-card-grid
    - gif-div confirming answer choice
  3b. quiz-container(mobile): 4 rows, 1 col

## SCORING CONTAINER
  4a. scoring-container(lg screens):
  - 5 rows/ 3 cols:
    - title: 1 row/ span 3 col
    - total: 1 row/ span 3 col centered
    - category scoring grid: 2 rows/ span 3 col for 4-6 category scoring cards
    - return to home
  4b. scoring-container(mobile screens): 1 column 9 rows

  <!-- ! CLICK EVENTS -->
  * enter btn click event will send usr to next screen
  * start btn click event to start the game and go to next screen
  * choice btn click event activates gif div and scoring functionality
  * return to hom btn returns to home screen after scoring
  
  <!--? TRANSITIONS/TIMERS -->
  * question div and gif div will slide up transition back and forth as user answers questions
  * timer for every 15 seconds per question
  * 
  <!-- * FUNCTIONALITY -->
  ## 4-6 categories with 5 questions in each category, total 20-30 questions depending on level of difficulty; 5-7 minutes long quiz
  ## Timer/Scoring rules: each question you get 20 seconds to answer, and a score of 0 if u do not answer in that time, if you answer before 20 seconds, you either get 10 points for correct or 0 points for incorrect and itdoes slide up transition to next question.
  ## Local Storage for scoring??