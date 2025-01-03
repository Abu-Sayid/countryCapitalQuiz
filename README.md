# countryCapitalQuiz
A quiz application where users can test their knowledge by guessing country's capital.

Features:

Score tracking and feedback at the end.

To launch your react project in your browser,

Install postgreSQL

Set password as 12345678

Create database world

Run below query in Query tool to create capitals table:

CREATE TABLE capitals(

    id SERIAL PRIMARY KEY,

    country VARCHAR(45),

    capital VARCHAR(45),

)

Import capitals.csv with Header toggled on 

Download Node.js

If you're running this locally in VS Code use the commands:

npm i

node index.js