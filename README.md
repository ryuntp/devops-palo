# DevOps Onboarding Part 2 - Challenges

Welcome to the DevOps Onboarding Part 2 repository. This repository contains hands-on exercises to help you get familiar with command line operations, bash scripting, and CI/CD pipelines.

## Structure
- `challenge_1`: Directory for challenge 1 on command line
    - `config/`: Config directory used in a practice.
    - `logs/`: Log directory used in a practice.
- `challenge_2`: Directory for challenge 2 on pipeline

## Challenges Overview

### Challenge 1
Navigate to challenge_1 directory

#### Easy Level
- **Task 1**: Listing Files
    - Objective: Use basic commands to list and navigate files.
    - Task: List all files in the current directory and navigate to a 'example_directory' directory.
- **Task 2**: Creating and Removing Files
    - Objective: Create a file, display its contents, and then remove it.
    - Task: Create a file named sample.txt, display its contents, and remove it.

#### Intermediate Level
- **Task 1**: Searching Text in Files.
    - Objective: Use grep to search for specific text in files.
    - Task: Search for the word "error" in all .log files in the logs directory.
- **Task 2**: Using Pipes
    - Objective: Use pipes to process command outputs
    - Task: Navigate to logs directory. List all files in a directory, count the number of lines containing the word "test" in each file, and save the result to results.txt.

#### Advanced Level
- **Task 1**: Combining Commands with Logical Operators
    - Objective: Use logical operators to chain commands based on their success or failure.
    - Task: Navigate to example_directory. Check if a directory named backup exists, if it does, list its contents; otherwise, create it and display a message.
- **Task 2**: Advanced `grep` Usage with Pipes
    - Objective: Use grep with pipes for advanced text processing.
    - Task: Find all .conf files, search for lines containing "server", sort the results, and save them to servers.txt.

### Challenge 2
Create a simple pipeline with GitHub Actions


Happy learning!