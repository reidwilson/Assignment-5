# Assignment-5

  The system I am proposing would be a text application that would allow students to answer a
  multiple choice question using their cell phones. If the professor desired it, their responses
  could be used in order to take attendance or grade the students on participation.

# Questions
  1. What kind of software do you want to see used in class?
  2. What could be done better right now with class questions?
  3. What kind of software would do you currently use in class?
  4. How much experience do you have with similar systems?
  5. Would you actually use this kind of system?
  6. Would you use this system if your answers were graded on correctness?
  7. Would you use this system if your answers were graded only on participation?
  8. How often should this system be used in class?
  9. Would you feel more engaged if you used this system
  10. What issues do you see with this system

# Answers

## Question 1
  1. I can't think of anything off the top of my head
  2. I would like to see brightspace work better
  3. I can't think of anything

## Question 2
  1. Most of the time professors don't use the answers
  2. I've never had a system like this
  3. We could use some sort of software

## Question 3
  1. None of my classes have anything like this
  2. I've never seen a system like this
  3. We use Piazza

## Question 4
  1. I used something similar for Economics
  2. I've never used anything like this
  3. I have used Piazza

## Question 5
  1. I believe so, if the system was simple it could potentially be really useful.
  2. I don't think it would really change my experience
  3. Sure, I would

## Question 6
  1. I would use it but I think that would be a terrible idea
  2. Yes, if it was graded.
  3. I would be forced to

## Question 7
  1. Yes
  2. Yes, but I would probably not pay as much attention to the question
  3. Yes

## Question 8
  1. I would say about every month or every two weeks
  2. Ideally not often
  3. Every week

## Question 9
  1. Yes
  2. Not really
  3. Yes

## Question 10
  1. I would say group participation could be an issue
  2. I feel like a lot of people wouldn't use the app
  3. I don't see any issues

# Requirements
  For this project to be successful, the app will need to be able to recieve and process texts quickly.
  It will need to be be able to register a professor who will be the only one able to create and edit questions.
  It will need to be able to handle multiple responses at the same time.
  It will need to be able to track students answers over time.
  It will need to be able to 

# Development Approach
  For this project, I will try to follow a Test Driven Development paradigm for general coding.
  To configure the app for the class, a professor will only have to send a special command that registers his phone number as a professor for the class.
  Once this is acomplished, the app will then send him a unique room key that he can give the class to text to the app in order to register each of them as students.
  For the application itself, I plan on storing the number of answers each student has submitted in a map that will keep track of their attendance.
  Additionally, I will have a map structure that will contain data about the "current" question such as what the question actually is and other metadata
  When the students are ready, they can either text the number the answer or text a keyword that will cause a reply text of what the current question is.
  This design will be able to avoid issues by mirroring existing functionality as much as possible which currently avoids state conflict. 
  In order to stay on track with goals, I have left certain implementations deliberatly vague in order to compensate for misfunctionality and future changes.
  As previously stated, certain elements are abstracted such that changes to one component will not affect existing code.
