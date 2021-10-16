# Distributed Execute

## Features

Distributed execution based on starting multiple Docker

- Automatically import project to generate dockerfile 
- Distribute containers through operations

## Project Requirements

python 3.6.9

Ubuntu 18.04


## How to use
1. Copy the project that needs to be distributed to the directory 
2. Create start in the project to be processed and write the execution command
3. Execute Docker_maker 
    ```bash
    bash Docker_maker your_other_project
    ```
4. conatainer status monitoring (In development)


## File relationship

Docker_maker brings the project name into Dockerfile_template to build a Dockerfile.
