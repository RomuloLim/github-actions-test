
# Github Actions Auto PR
This is a basic example to practice my knowledge of github actions.

## How it works?
The actions works when have a new accepted PR in **Main** branch. The action creates automaticaly a PR updating **Main** branch changes to **Homol** Branch, and if this PR is accepted, the action creates a PR updating **Homol** branch changes to **Dev** branch changes.

## Example
- First, make changes and create a PR to **Main** branch:

<img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/creating-pr.gif"
 width="600"
 height="400" />

- After, merge PR:

  <img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/accept-pr-main.gif"
 width="600"
 height="400" />
 
 - Now, the action will dispatch creating a PR to **Homol**:

<img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/accept-pr-homol.gif"
 width="600"
 height="400" />
 
 - When you merge PR, the action will dispatch creating a PR to **Dev**
 
 <img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/pr-dev.gif"
 width="600"
 height="400" />
 
 ## How to contribute
 
  Contributions make the open source community an amazing place to learn, inspire and create. all contributions
are **extremely appreciated**

1. Make a project fork
2. Make a new feature branch (`git checkout -b feature/awesomeFeat`)
3. Add Content (`git add -A`)
4. Commit changes (`git commit -m 'Adicionado conteudo brabo'`)
5. Make a push (`git push origin feature/awesomeFeat`)
6. Open pull request

> To test, you can make only fork 😉
 
 ## Notes
 - I'm learning english, but if you found an error in this readme, please contact me 😅
