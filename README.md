# Task List API: Buggy Edition!

## Learning Goals
There are 3 big opportunities this project offers:
- To practice understanding code someone else wrote 
- To practice finding and understanding bugs in code that you may not have encountered before
- To practice the setup workflow for getting a flask project that's already been written working on your computer.

## Bug Lowdown

There is 1 bug in this code, which causes 3 tests to fail.

The objective is to use your debugging skills to _understand_ **what** the program is doing wrong and **why**. At the end of the day, the easiest (and quite possibly best) way to fix the bug would be to just copy/paste your to the buggy functions to replace this solution, so the emphasis here is **less on fixing** the bug and **more on understanding**.

Have fun!

---------------------------------------------------------------------------------------------------------------------------------------


## Setup

### Environment Setup

Don't forget to add a `.env` file to define the environment variables this project expects. You can copy/paste your `.env` file from your version of the project and it should work, assuming the names of the environment variables are the same. 

Hint: You can do a search in the project for `os.environ.get` if you want to remember what environment variables this project requires.

### Virtual Environment Setup

We recommend creating a new virtual environment for working with this repo and reinstalling the dependencies into this venv.

### Database Setup

The databases you used for this project previously were probably `hello_books_development` and `task_list_api_test`. We suggest updating the environment variables for this repo to use different databases. To do that, you'll need to first create that new databases, then update the environment variables with those new database names. 

Because this project already has migrations, there's no need to run `flask db init` or `flask db migrate` but you should make sure to run `flask db upgrade`. This ensures the migrations are run to update your database appropriately. 