*** = STRETCH GOAL

# Project 4 - Pitch:
This is a musician lesson app where the user can login, and connect live with a musician that is offering lessons.  Both the student and the teacher will have their own profiles.  The student will be able to scroll through a list of teachers and find the one that is experienced with the instrument that they would like to learn.  The student can then book an appointment with the teacher on our platform, and will be provided with a link to a zoom room to meet.


## STRETCH GOALS
- Chat feature between students and teachers
- Teacher will have a calendar to schedule time for lessons


## Working Title: Music Platform


## Nick Hvattum, Zack Barovsky, & Salman Malik (The new and improved "Zack and da the Boizz")


## Technologies Used:
- Frontend: TypeScript/JS/React
- Backend: Mongo
- Websocket (for chat feature between user and teacher)

### Backend
- Mongo React Auth
- Will try to use GraphiQl

Table user {
  id int [pk]
  name string
  email string [unique]
  password string
  isTeacher boolean
  bio text[500]
  profile pic
  instrumentsPlayed text[100]
  qr code? (image for payment)
}


## Frontend
- Searchbar for teacher to search for student with add student button
- Upon payment, Zoom link will be distributed
- Will use Stripe to pay for lessons with teacher


## Questions
- How do you plan on learning/implementing this new technology?
    We plan on learning TypeScript as it pertains to Frontend React and implementing APIs and Stripe payment techonology, along with our Mongo backend.
- What is your goal with this project?
    To create a platform that allows for connectivity between users and musicians who want to offer their teachings and create revenue through short training sessions
- Who is the user for your app?
    The User is a aspiring musician, a student of the arts, a person looking to start a new hobby - along with the musicians that would like to offer their teaching services (especially at a time like this where there are no live shows)
- Any potential roadblocks you think you might run into?
    Learning new languages, Backend woes, time, linking the User and 



## Day-to-Day Breakdown

Daily Schedule is on our team trello board 😃:
https://trello.com/b/zTEYHQvx/p3-worktime


## Wireframes
https://wireframe.cc/z0jtzC
https://wireframe.cc/jdfDUk
https://wireframe.cc/o0D9FX
https://wireframe.cc/jLMzOW
https://wireframe.cc/z0jtzC
https://wireframe.cc/8mCrbz


## UserFlow for App

### TEACHER
- Register  =>  Create a profile  =>  Select teaching proposal  =>  Make teacher page  =>  Link to soundcloud, facebook, description, rates, youTube

### STUDENT
- Register  =>  Create a profile (put info about what they are looking for out of the app)  =>  View potential teacher pages to make a connection
