# Installation

Installation is not smooth.
Why is Python version dependency so painful...

## Installation on mac

1. run `brew install python3` (if fail, run `brew doctor` and see how to fix it)
2. start a virtual environment: `python3 -m venv tutorial-env`
3. activate the virtual environment: `source tutorial-env/bin/activate`
4. run `pip install apache-airflow`
5. run `airflow initdb`
6. run `airflow webserver -p 8080`

Step 2 and 3 are from [python3 doc](https://docs.python.org/3/tutorial/venv.html)

Step 4, 5, 6 are from [airflow doc](https://airflow.apache.org/start.html)

Mac has python by default, but it's probably not a good idea to mess with it (some dependency could be broken). 
It's easier to use Homebrew.
