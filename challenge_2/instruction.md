## Challenge 2

Create a simple CI/CD pipeline with GitHub Actions

### Instructions
1. Create your own project on github
2. Change remote origin to the repository that you have just created
3. Push all the change to the repo
4. Open file `.github/workflows/simple.yml` and add new steps with name 'Challenge 2', and set the working directory to `./challenge_1/example_directory`
```
name:
run:
working-directory: ./challenge_1/example_directory

```
5. Choose any command from completed task on challenge 1 to run with this step
6. Commit and push the code
7. Wait until the pipeline finish