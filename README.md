# karma-jasmine-seed

To use the seed:

1. Clone the project using `git clone https://github.com/bmbarker90/karma-jasmine-seed {folder}`, replacing folder with the folder name
    you would like to give it
2. Set the remote to your own repo url `git remote set-url origin https://github.com/USERNAME/REPOSITORY.git`
3. Run `npm install`
4. We have provided 3 files for you:
  - src/index.html for all of your HTML code
  - src/index.js to start your JS code
  - tests/test.spec.js to write your tests
  - You are welcome to add more JS files in `/src` and more test files in `/test`
5. To run tests, run `npm test`.


## Best practices
1. Write a `describe` for each function that you would like to test
2. Pure functions are the easiest to test. Pure functions are functions that, given the same inputs, will always produce the same output
3. Karma will watch changes to your files. This means that if you keep your terminal window open, it will re-run your tests any time you change your files!