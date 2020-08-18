# O-Educate
A open source project that building Online Education platform for student in the world. Technology that used : 
- Express
- Vue
- Nodejs
- Postgres
- Socket.io
- Knex.js
- Vuetify
- Mongodb

## Features
### Academy Management
- Student
    - Create a student (also create an account)
- Class
    - Insert student on class
    - Insert teacher on class
    - Recap scores
- Survey
    - Survey on end of semester about academy

### Academy features
- Meeting / Class
    - Upload text description like medium.com
    - Upload a document
    - Can insert youtube link
    - Meeting can be saved / publish
- Task
    - Create a task with deadline
    - Task can be a text or attachment
    - Management Task
    - Scoring Task

### Online Quiz
- Input time of Start and Finish quiz
- Quiz attached on each class

### Notification
- Notification can be on telegram and whatsapp
- List Notification : 
    - New Meeting / Class
    - New Task
        - Task Last 3 days
        - Task Last 1 days
        - Task last 12 hours
        - Task closed
    - A quiz notification
        - Quiz Created
        - Quiz 10 minutes before start
    - Custom notification

## Roles
- Principles
- Administration
- Teacher
- Student


## Todo : 
- [x] Create ERD (https://dbdiagram.io/d/5f3bdbd3cf48a141ff554d2c)
- [ ] Create Use Case
- [x] Initialization Vuejs
    - [x] Add Vuetify
    - [x] Add axios
    - [ ] Add tip-tap-vuetify
- [x] Initialization Express
    - [ ] Install knex postgres
    - [ ] Add JWT
- [ ] Create migration with knex.js
- [ ] Create authentication with JWT
- [ ] Create and Implement Login Page on Vue
- [ ] Create base dashboard layout on each role
- [ ] Coming soon….
