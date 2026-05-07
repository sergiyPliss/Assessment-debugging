## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

1. Fork or clone this repo.
2. Fill missing dependencies and author section in `pyproject.toml`, fix any other problems if exists.
3. Fix bugs prevent the app `main.py` from running, or cause any errors if the app is running.
4. Change port the app ruuning on to `10030`.
5. Update `README.md` with an instruction about how to run this app:
   1. Choose either Arch Linux or Fedora Linux, and don't mess with the system `python` environment.
   2. Use a modern python package manager that respects `pyproject.toml` and `.python-version`, rather than `pip`.
   3. Setup virtual environment, start the app, and access the app.
6. Commit and push all the changes, and provide a link to your own repo in your submission in the last.

## Instructions on Launching App

1. Clone the repository.
2. Install anaconda.
4. Create a virtual enviroment with anaconda.\
      ```conda create --name myenv```\
      ```conda activate myenv```
5. Install required packages.\
    ```conda install -c conda-forge dash```\
   ```conda install numpy```\
   ```conda install pandas```
6. Run the app.\
   ```run main.py```
