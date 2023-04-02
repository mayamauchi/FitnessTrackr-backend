
# Fitness Trackr - Backend
This is the backend component of Fitness Trackr, a web application for tracking workouts and exercises. 

It was developed as part of the Fullstack Academy curriculum. The backend is built using Node.js, Express, and PostgreSQL, and provides a RESTful API for the [frontend](https://github.com/mayamauchi/fitness-trackr-frontend) to communicate with.





## Authors

- [@mayamauchi](https://www.github.com/mayamauchi)
- [@krlars27](https://github.com/krlars27)


## Run Locally

Clone the project

```bash
git clone https://github.com/mayamauchi/FitnessTrackr-backend.git


```

Go to the project directory

```bash
cd FitnessTrackr-backend
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

Run seed

```bash
  npm run seed:dev
```

This will start the app on port 3000 by default. You can change the port by setting the PORT environment variable.





## Automated Tests
**NOTE:**  At first, there will be too many errors for the tests to even run.  Start by running the seed:dev script above, until it is working.

Once you get to running the tests, we recommend to start with just the DB test first, and move to API next.  This is because there will be so many errors in the beginning, it's hard to see what tests are passing or failing.

To run all the tests in watch mode (re-runs on code update), run

    npm run test:watch

### DB Methods


    npm run test:watch db

### API Routes (server must be running for these to pass)

    npm run test:watch api

