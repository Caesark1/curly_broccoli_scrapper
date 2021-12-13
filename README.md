# Start project

1. After clonning this repo on your local machine. You need to create your own `.env` file like it was written in `.env_example` file
2. Than run command `export $(grep -v '^#' .env | xargs)`
3. Create virtual environment and activate it
4. `pip install -r requirements.txt`
5. After that run `python main.py` and wait till parsing of data will be ended
