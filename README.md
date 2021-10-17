# Distributed Execute

## Features

Distributed execution of data processing projects based on the number of data.

- Automatically import project to generate dockerfile.
- Start the plural container to process the divided data.

## Project Requirements

python 3.6.9

Ubuntu 18.04


## How to use
1. Copy project of data processing to this directory.
2. Create a bash script named "start" in the project to be processed and write the execution command.
3. Execute Docker_maker 
    ```bash
    bash Docker_maker your_other_project your_log_file
    ```
4. conatainer status monitoring (In development)
