<!-- markdownlint-disable-next-line -->

**Note** **This repository is _not_ included in the Hacktoberfest event, as it is for practice only!**

We have other [repositories](https://github.com/orgs/EddieHubCommunity/repositories) in the organization that you can contribute to. If you would like to join our GitHub organisation, raise an [issue](https://github.com/EddieHubCommunity/support/issues/new?assignees=&labels=invite+me+to+the+organisation&template=invitation.yml&title=Please+invite+me+to+the+GitHub+Community+Organization) on this repo EddieHubCommunity-Support and you can also join the EddieHub [Discord](http://discord.eddiehub.org/) channel

---

## Hacktoberfest

What is it? Click on the poster below to watch the video for more details 📽

[![Watch The Video](https://user-images.githubusercontent.com/61582763/94226800-1d0d5d80-ff16-11ea-8097-689ec7b5af69.png)](https://youtu.be/tjH6txTiC6E)

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.1%20original-0927f5.svg)](CODE_OF_CONDUCT.md) [![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/EddieHubCommunity/hacktoberfest-practice)

## Hacktoberfest Practice Pull Requests

Repository for you to raise a Pull Request to **practice** open-source! 🎉

### Add your name to the alphabetical list and, optionally, a link to your GitHub account (in alphabetical order below your letter too)

### Option 1. Complete this process in GitHub (in your browser)

```mermaid
flowchart LR
    Fork[Fork the project]-->branch[Create a New Branch]
    branch-->Edit[Edit file]
    Edit-->commit[Commit the changes]
    commit -->|Finally|creatpr((Create a Pull Request))
```

**1. Fork the project:**

- Click the gray <kbd>Fork</kbd> button at the top right of this page. This creates your copy of the project and saves it as a new repository in your GitHub account.

**2. Create a New Branch:**

- On your new repository's page, click the gray main button in the upper left to reveal a dropdown menu.
- Enter the name of your new branch in the text box. (Branch names usually refer to what is being changed. Example: nameAdd).
  -Click on Create branch <new branch name>, which will automatically take you to your new branch. You can make edits on the main branch, but this may cause issues down the line. The best practice is to create a new branch for each separate issue you work on. That way your main branch remains in sync with Eddie's main branch.

**3. Edit:**

- On the top right of the Readme file, click on the pencil icon to edit the file by **adding your name and your GitHub profile link to the section that matches your Initial in [this list](https://github.com/EddieHubCommunity/hacktoberfest-practice#hacktoberfest-community). Make sure that your name is in alphabetical order.**
- After editing the Readme file, add a commit message and click on the green button saying "Commit Changes". Make sure you have selected the branch you have created.

**4. Raise a Pull Request:**

- Click `Pull Requests` option in your forked repository (which is the third option at the top of this page after the options `Code` and `Issues`).
- Click the green New Pull Request button. This will prep the new pull request for you by auto-filling the base repository: base with 'EddieGitHubCommunity: main' AND auto-filling your head repository: compare with your repository: main
- Click on your head repository's `compare` dropdown, and switch branches from your 'main' branch to `<new branch name>`.
- Finally, click the green `Create Pull Request` button. Great job! You did it!

You can ask questions by raising an [issue](https://github.com/EddieHubCommunity/hacktoberfest-practice/issues/new).

### Option 2. Complete this process on your computer (locally)

**1. Fork the project:**

- Click the gray Fork button at the top right of this page. This creates your copy of the project and saves it as a new repository in your GitHub account. ![fork](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/00b41de9-768c-4a01-a27e-f7aa75cd6a27)

**2. Clone this project on your computer:**

- Go to your profile. You will find forked repo named **_hacktoberfest-practice_**. go to the repo by clicking on it.
- Click on the green Code button, then either the HTTPS or SSH option, and, click the icon to copy the URL. Now you have a copy of the project. Thus, you can play around with it locally on your computer.

- Run the following commands into a terminal window (Command Prompt, Powershell, Terminal, Bash, ZSH). Do this to download the forked copy of this repository to your computer. ![git-clone](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/4d600e25-83b1-4e8f-9325-f1adc4f8ce3d)

```bash
  git clone https://github.com/YOUR_GITHUB_USERNAME/hacktoberfest-practice.git
```

- Switch to the cloned folder. You can paste this command into the same terminal window. ![opening-vscode](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/1a8b350d-0c96-461a-85f4-a59185aed6b6)

```bash
  cd hacktoberfest-practice
```

**3. Create a new branch:**

- Your username would make a good branch because it's unique. ![git-checkout](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/68ab0380-c731-4e67-bccc-b666da5dd174)

```bash
  git checkout -b <name-of-new-branch>
```

**4. Edit:**

- Open the `README.md` file

- **Add your name to the section that matches your Initial in [this list](https://github.com/EddieHubCommunity/hacktoberfest-practice#hacktoberfest-community), make sure that your name is in alphabetical order. Then save your changes.**

- For example
  `- [Full Name](https://github.com/your-username)`

**5. Stage your changes:**

```bash
  git add README.md
```

or

```bash
  git add .
```

**6. Commit the changes:**
![git-commit](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/9a6a58f3-ed0b-4bc2-b749-48baede77835)

```bash
  git commit -m "Add <your-github-username>"
```

- Check the status of your repository.

```bash
  git status
```

- The response should be like this:
  ![git-status](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/d3692bcd-02d9-47d7-9e6c-b386b0a6c72d)

```bash
On branch <name-of-your-branch>
nothing to commit, working tree clean
```

**7. Pushing your repository to GitHub:**

```bash
  git push origin <name-of-your-branch>
```

or

```bash
  git branch -M main
  git push -u origin main
```

![git-push](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/f1cec12f-ea26-4986-a820-7881bc69f764)

> **Warning**: If you get an error message like the one below, you probably forgot to fork the repository before cloning it. It is best to start over and fork the project repository first.

```bash
ERROR: Permission to EddieHubCommunity/hacktoberfest-practice.git denied to <your-github-username>.
fatal: Could not read from remote repository.
Please make sure you have the correct access rights and that the repository exists.
```

**8. Raise a Pull Request:**

- On the GitHub website, navigate to your forked repo - on the top of the files section, you'll notice a new section containing a `Compare & Pull Request` button! ![createpr](https://github.com/AmanxUpadhyay/hacktoberfest-practice/assets/76415079/0c971d35-5230-4f4a-923a-81a05c318887)

- Click on that button, this will load a new page, comparing the local branch in your forked repository against the main branch in the EddieHub Hacktoberfest repository. Do not make any changes in the selected values of the branches (do so only if needed), and click the green `Create Pull Request` button. After creating the PR (Pull Request), our GitHub Actions workflow will add a welcome message to your PR.
  Note: A pull request allows us to merge your changes with the original project repo.

- Your pull request will be reviewed and then eventually merged.

Hurray! You successfully made your first contribution! 🎉

---

## How can I fix a merge conflict?

A GitHub conflict is when people make changes to the same area or line in a file. This must be fixed before it is merged to prevent collision in the main branch.

- **To read more about this, go to [GitHub Docs - About Merge Conflicts](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)**

- **To find out about how to fix a Git Conflict, go to [GitHub Docs - Resolve Merge Conflict](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)**

- You can also ask for help in our [Discord server](http://discord.eddiehub.org) or submit an issue in the [Support repository](https://github.com/EddieHubCommunity/support).

---

## `Hacktoberfest Community`

### **Contents**

| [A](#a) | [B](#b) | [C](#c) | [D](#d) | [E](#e) | [F](#f) | [G](#g) | [H](#h) | [I](#i) | [J](#j) | [K](#k) | [L](#l) | [M](#m) | [N](#n) | [O](#o)
| [P](#p) | [Q](#q) | [R](#r) | [S](#s) | [T](#t) | [U](#u) | [V](#v) | [W](#w) | [X](#x) | [Y](#y) | [Z](#z) |

- ### **A**

  - [Aziz Prabowo](https://github.com/azizp128)

| [Back To Top](#contents) |

- ### **B**

  
  - [Burhanuddin Raja](https://github.com/BurhanRaja)

| [`Back To Top`](#contents) |

- ### **C**

  
  - [Cynthia Teeters](https://github.com/cynthiateeters)
  - [Dhruv Gupta](https://github.com/DhruvGupta6850)
| [`Back To Top`](#contents) |

- ### **D**

  
  - [Dywa VaraPrasad](https://github.com/dywa-varaprasad)

| [`Back To Top`](#contents) |

- ### **E**

 
  - [Ezinne Anne Emilia](https://github.com/ezinneanne)

| [Back To Top](#contents) |

- ### **F**

  
  - [Furqan Abid](https://github.com/heyyfurqan)

| [`Back To Top`](#contents) |

- ### **G**

  
  - [Gyau Boahen Elvis](https://github.com/gyauelvis)

| [`Back To Top`](#contents) |

- ### **H**

 
  - [Hussain Shariff](https://github.com/hussain-shariff)

| [`Back To Top`](#contents) |

- ### **I**

  
  - [Ivo Iliev](https://github.com/Iwi4a)

| [`Back To Top`](#contents) |

- ### **J**

  
  - [Jysan Aziz](https://github.com/jeexan2)

| [`Back To Top`](#contents) |

- ### **K**

  
  - [Kyrios Heylel](https://github.com/lucky-chap)

| [`Back To Top`](#contents) |

- ### **L**

  
  - [Lundbyit](https://github.com/Lundbyit)

| [`Back To Top`](#contents) |

- ### **M**
 
  - [Mwangi Gregory](https://github.com/MwangiGregory)

| [`Back To Top`](#contents) |

- ### **N**

  
  - [Nworie Chikwado Emmanuel](https://github.com/chikwado17)

| [`Back To Top`](#contents) |

- ### **O**

 
  - [Oyebolade Oladokun](https://github.com/Oyebolade)

| [`Back To Top`](#contents) |

- ### **P**
 
  - [Pushkaraj Kulkarni](https://github.com/pushkaraj2007)

| [`Back To Top`](#contents) |

- ### **Q**

| [`Back To Top`](#contents) |

- ### **R**

  
  - [Ryga](https://github.com/ryga9)

| [`Back To Top`](#contents) |

- ### **S**

  
  - [syedareehaquasar](https://github.com/syedareehaquasar)

| [`Back To Top`](#contents) |

- ### **T**

 
  - [Twinkle](https://github.com/twinkletrivaan)

| [`Back To Top`](#contents) |

- ### **U**

  
  - [Uttam Kumar](https://github.com/helper-uttam)

| [`Back To Top`](#contents) |

- ### **V**

  
  - [Vurugonda Kalyan](https://github.com/kalyan-vurugonda)

| [`Back To Top`](#contents) |

- ### **W**

  
  - [Willy Wonka](https://github.com/massablaise)

| [`Back To Top`](#contents) |

- ### **X**

| [`Back To Top`](#contents) |

- ### **Y**

  
  - [Yuvraj Singh Rana](https://github.com/yuviii99)

| [`Back To Top`](#contents) |

- ### **Z**

  
  - [Zamzam Hassan](https://github.com/MissZamzam)

| [`Back To Top`](#contents) |

## Our Pledge

We take participation in our community as a harassment-free experience for everyone and we pledge to act in ways to contribute to an open, welcoming, diverse and inclusive community.

If you have experienced or been made aware of unacceptable behaviour, please remember that you can report this. Read our [Code of Conduct](https://github.com/EddieHubCommunity/hacktoberfest-practice/blob/main/CODE_OF_CONDUCT.md).
