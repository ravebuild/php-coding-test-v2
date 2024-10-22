# Rave Build PHP Coding Test
Welcome to the Rave Build PHP Coding Test! 

## The brief
This code base is a basic project class which has a collection of tasks which it provides access to.

Your job is to bring it up to a modern standard and fix any bugs or potential issues you might find 
while also showcasing your PHP skills.

### Technical requirements:
- Modernise the code, showcasing your knowledge of the latest and greatest PHP features and patterns where applicable
- Use native types instead of docblock where possible
- Ensure the code is consistently formatted (using any format you prefer, as long as it is consistent)
- Ensure all public properties + methods prevent unwanted behavior in the Task + Project classes
- Ensure all tests pass and meet your standards of good testing (feel free to add/edit/remove tests as you see fit)
- Ensure any bugs you fix are covered in the tests to prevent them being re-introduced 

### Functional requirements:
- Must be able to create a new instance of the Project class with a name.
- Must be able to add tasks (with an id + name) to a project
- Must be able to set a Task ID when creating a task (no need for an ID generator)
- Must be able to remove a task from a project by the Task ID
- Must be able to find a task that has been added to a project by the Task ID

### Once complete:
1. Note down any choices or assumptions you made and why you made them in this README. For example, "I assumed Task names are unique"
2. Note down what you would do if you had more time in this README. For example, "I would have added more tests to cover xyz... as I found the existing tests didn't cover the scenario when xyz..."
3. Delete the `vendor` directory, then zip this directory and email it to us

### FAQs
- We expect this test should take 1-2 hours to complete.
- The test cases and the test data are part of this test, feel free to add/edit/delete them however you wish
- You may add/edit/delete any file as part of this test
- You may make any changes/improvements/assumptions you wish as long as the functional requirements are met
- You may add/update/remove any composer dependency if needed
- You are welcome to use another test library (like pest) if you do not like PHPUnit, but you will need to port any test cases over that you feel are relevant
- We read your README notes and review your code by hand, so you are free to rename/change/remove public methods/properties etc.

> Note: Please do not create a pull request. This is a public repository and GitHub pull requests cannot be deleted so other candidates will be able to see your answers.

## Installation
PHP installations are quite complicated, so we have Dockerised the 
dependencies for this test in an attempt to simplify getting it running.
You need to:

1. Clone this Git repository
2. Install [Make](https://www.gnu.org/software/make/). For Windows
   [follow one of these instructions](https://stackoverflow.com/a/32127632).
   For MacOS, install with homebrew like `brew install make`. For Linux, use 
   your package manager like `apt install make`.
3. Install Docker. For Windows and MacOS we recommend 
   [installing Docker Desktop](https://docs.docker.com/desktop/install/windows-install/). 
   For Linux distributions we recommend
   [installing the Docker Engine](https://docs.docker.com/engine/install/).
4. Check that Docker is working by running `docker run hello-world`.

## Running the tests
Run `make test` to run the PHPUnit tests in a Docker container.

## Running program.php
Run `make run` to execute `program.php`. It is not required, but we have provided 
it if you would like to just run PHP code to debug things.

## My notes
### Choices or assumptions I made and reasons why
* E.g. I used PHP v4.3 syntax as I've never used newer versions

### Things I would do if I had more time
* E.g. I would have rewritten it to use Rust because it's super fast and that's what Khan Academy did!
