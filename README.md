# countryCapitalQuiz
A quiz application where users can test their knowledge by guessing country's capital.

Features:

Score tracking and feedback at the end.

To launch the project in your browser,

1. Install postgreSQL

2. Set password as 12345678

3. Create database world

4. Run below query in Query tool to create capitals table:

        CREATE TABLE capitals(

            id SERIAL PRIMARY KEY,

            country VARCHAR(45),

            capital VARCHAR(45),

        );

5. Import capitals.csv with Header toggled on

6. Download Node.js

7. If you're running this locally in VS Code use the commands:

        npm i

// to install the node module

    node index.js