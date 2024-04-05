# PSL Management System

The PSL Management System is a web application designed to manage various aspects of the Pakistan Super League (PSL), including team information, player profiles, match schedules, and results.

## Features

- View and manage information about PSL teams, including team members, coaches, and support staff.
- Access player profiles with detailed statistics and performance history.
- Stay updated on match schedules, venues.
- Reserve a ticket before the match.
- Chatbot using Gemini pro model by Google

## Technologies Used

- Frontend: HTML, CSS, JavaScript, EJS view engine
- Backend: Node.js, Express.js, SQL
- Database: Oracle (credentials required)

## Getting Started

1. Clone the repository: `git clone https://github.com/Ahmadraza1394/PSL-Management-System`
2. Navigate to the project directory: `cd psl-management-system`
3. Install dependencies: `npm install`
4. Set up Oracle database credentials:
   - Add your Oracle database credentials in dbConfig.js using the following format:
     ```javascript
     module.exports = {
       user: 'your_username',
       password: 'your_password',
       connectString: 'your_connection_string'
     };
     ```
5. Run the application: `npm start`


