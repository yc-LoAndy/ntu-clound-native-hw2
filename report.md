# NTU Cloud Native HW2
- Name: 羅元駿
- Student ID: r13922162

Github Repo is accessible [here](https://github.com/yc-LoAndy/ntu-clound-native-hw2).


## Explanation
### Repo 操作
The repository is created on the GitHub manually, and a local directory is created to connect this repository via `git remote add origin ...`.

Two branches, `hw1-p` and `hw1-f`, are created by `git checkout -b [branch name]`.

### Issue
An issue, "Example Issue", is created and in the open status. An issue template is also configured for others creating issues to apply.

### Pull Request
A pull request is created from two branches, `hw1-p` and `hw1-f`, to the `main` branch. Some code reviews are made on these pull requests.

### GitHub Action
A GitHub action is created in `.github/workflows/example_action.yml`. There is one job, `build`, in this action, which is consisted of 4 steps.

- Step1: Checkout to the branch.
- Step2: Extract branch name to $GITHUb_OUTPUT
- Step3: Print out the branch name from $GITHUB_OUTPUT.
- Step4: Check the branch name. If the branch where the PR is from is `hw1-f`, the fail this action by removing a non-existent file `nonExistentFile.txt`.
