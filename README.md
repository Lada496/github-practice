## How to start practice

1. Fork this repo
2. Clone the forked Repogitory
   `git clone https://github.com/Your-GitHub-Username/github-practice`
3. Keep your copy up to date with the original repogitory </br>
   3.1 `git remote add upstream https://github.com/Lada496/github-practice.git`
   3.2 `git fetch upstream`
4. Let local copy of master branch point to upstream
   `git branch --set-upstream-to=upstream/main main`
6. Create your feature branch
7. Open pull request to main branch

## Tips for avoiding merge conflict troubles
1. Freaquently check if there are any updates and fetch upstream if there are with
   `git pull origin main` or click "fetch and merge" if you manually update your repo. 

<img width="941" alt="Screen Shot 2022-02-07 at 5 23 50 PM" src="https://user-images.githubusercontent.com/67321065/152900544-87cd47a9-3f2a-4722-b7cd-5afeaf4b9f00.png">
2. check if your commit has been successfully done with `git status`<br />
3. Freaquently check what branch you modify with `git branch`
