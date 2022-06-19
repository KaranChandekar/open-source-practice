## How to contribute (overall process)

1. Fork the project using the gray `Fork` button in the top right of this page.
2. Make any changes in your forked repository.
3. On this repo, click `Pull Requests` (which is the third option at the top of this page after the options `Code` and `Issues`) and raise a Pull Request by clicking the green `New Pull Request` button and selecting your fork from the right dropdown field.

You can ask questions by raising an [issue](https://github.com/Pradumnasaraf/open-source-practice/issues/new).

## How to clone the repository and make changes locally

- Click on the green `Code` button, then either the HTTPS or SSH option and, click the icon to copy the URL. Now you have a copy of the project. Thus, you can play around with it locally on your computer.

<p align="center"><img src="https://user-images.githubusercontent.com/51878265/149615132-10d4281f-a199-4112-b747-a3b8fa56299d.png"></p>

- Run the following commands into a terminal window (Command Prompt, Powershell, Terminal, Bash, ZSH). Do this to download the forked copy of this repository to your computer.

```bash
  git clone https://github.com/Pradumnasaraf/open-source-practice.git
```

- Switch to the cloned folder. You can paste this command into the same terminal window.

```bash
  cd open-source-practice
```

- Make a new branch. Your username would make a good branch because it's unique.

```bash
  git checkout -b <name-of-new-branch>
```

- Open the `README.md` file

- **Add your name to the  [list](https://github.com/Pradumnasaraf/open-source-practice#list) below.**
- For example
  ` - [Full Name](https://github.com/your-username) -> [Pradumna Saraf](https://github.com/Pradumnasaraf)`
  
- Stage your changes.

```bash
  git add README.md
```

or

```bash
  git add .
```

- Commit the changes.

```bash
  git commit -m "Add <your-github-username>"
```

- Check the status of your repository.

```bash
  git status
```

- The response should be like this:

```bash
On branch <name-of-your-branch>
nothing to commit, working tree clean
```

- Pushing your repository to GitHub.

```bash
  git push origin <name-of-your-branch>
```

or

```bash
  git branch -M main
  git push -u origin main
```

If you get an error message like the one below, you probably forgot to fork the repository before cloning it. It is best to start over and fork the project repository first.

```bash
ERROR: Permission to Pradumnasaraf/open-source-practice.git denied to <your-github-username>.
fatal: Could not read from remote repository.
Please make sure you have the correct access rights and the repository exists.
```

- On the GitHub website, navigate to your forked repo - on the top of the files section, you'll notice a new section containing a `Compare & Pull Request` button!

- Click on that button, this will load a new page, comparing the local branch in your forked repository against the main branch in the Pradumnasaraf open-source-practice. Accept the default values in the dropdown boxes and click the green `Create Pull Request` button. After creating the PR (Pull Request).

  Note: A pull request allows us to merge your changes with the original project repo.

- Your pull request will be reviewed and then eventually merged.

Hurray! You successfully have made your first contribution! 🎉

---

## list 

[Pradumna Saraf](https://github.com/Pradumnasaraf)

[Karan Chandekar](https://github.com/KaranChandekar)


### Don't forget to ⭐ this repo.
