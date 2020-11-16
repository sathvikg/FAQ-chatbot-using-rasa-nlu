## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy
  
## course path
* courses
  - utter_courses
* affirm
  - utter_which_course
* deny
  - utter_goodbye
## contact path
* contact
  - utter_contact
## prereq
* prerequisites
  - utter_prerequisites
  
## timings
 * course_time
   - utter_time

## requirements
* requirements
  - utter_requirements
  
## class
* class
  - utter_class
  
## login problem
* login
  - utter_login
## Mlearn
* Mlearn
  - utter_machine_learning
  - utter_join_course
* affirm
  - utter_contact_enrol
* deny
  - utter_goodbye
  
## chatbot
* AI_chatbot_dev
  - utter_AI
  - utter_join_course
* affirm
  - utter_contact_enrol
* deny
  - utter_sorry
  
## django
* django
  - utter_django
  - utter_join_course
* affirm
  - utter_contact_enrol
* deny
  - utter_sorry 
  
## tutors
* tutor
  - utter_tutor



## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
