# Contributing Guidelines

### Learn how to Setup Coding Environment, Fork a repo, makes changes, and ask the maintainers to review and merge it

## Setup Coding Environment

> Follow the below tutorial for your preferred language to set up the coding environment

| language |                                                                  C++                                                                  |                                                                 Java                                                                  |                                                              JavaScript                                                               |                                                                Python                                                                 |
| :------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
| Tutorial | [<img src="https://img.icons8.com/cute-clipart/2x/link.png" width="30px" height="30px">](https://www.youtube.com/watch?v=jvg4VtYEhKU) | [<img src="https://img.icons8.com/cute-clipart/2x/link.png" width="30px" height="30px">](https://www.youtube.com/watch?v=KwnavHTOBiA) | [<img src="https://img.icons8.com/cute-clipart/2x/link.png" width="30px" height="30px">](https://www.youtube.com/watch?v=2fwOthpmj4M) | [<img src="https://img.icons8.com/cute-clipart/2x/link.png" width="30px" height="30px">](https://www.youtube.com/watch?v=AKVRkB0fot0) |

## Creating Pull Request

You have a GitHub repo and can push to it. All is well. But how the heck do you contribute to other people's GitHub projects? That is what I wanted to know after I learned git and GitHub. I will explain how to fork a git repo, make changes, and submit a pull request.

> - When you want to work on another's GitHub project, the first step is to fork a repo.<br> <img src="img/fork.png" width="750" /><br>

---

> - Once there click on the Fork button in the top-right corner. This creates a new copy of the repo under your Github user account.
> - Clone this Github repo. Open up the GitBash/Command Line and type in: <br> <img src="img/git-clone.png" width="750"/><br>
> - Don't forget to write your GitHub user name.

---

> - `cd` into the specific directory.
> - Now create a branch of the master by pushing the command:
>   - **git branch -b < FIRST_LETTER_OF_YOUR_FIRST_NAME_AND_FIRST_LATTER_OF_YOUR_LAST_NAME/CURRENTDATE >**.
>   - Example : `git checkout -b RP/01012021` <br> <img src="img/git-branch.png" width="750" /><br>

---

> - You can now check the branches by pushing in the command: `git branch`. You will see the Master Branch and another branch along with your branch.
>   > - Switch to Development Branch. Never develop on Master Branch. Push in the command: git checkout < NEWLY_CREATED_BRANCH >.<br>
>   > - **_:warning: Note:_** _Created branch should be pushed on that day only when it was created, So for eatch day you have to create new branch and push end of the day._<br> <img src="img/git-checkout.png" width="750"/><br>

---

> open project on vs code by command : `code .` in current diractory.
> <img src="img/vs-code.png" width="750"/><br>

---

> #### To create new file for your solution please follow below points
>
> - Your files should be uploaded directly into the corresponding folder
>   - (e.g. if you solve a problem from leetcode in january 2021 in cpp, it goes inside the `leetcode folder` within `2021 folder` within the `january folder` with in the `cpp folder` and so on)
> - Under no circumstances create new folders within the language folders to upload your code unless specifically told to do so.
> - Start Coding. Make apt commits with proper commit messages. Always use git status to see that you have not made changes on the file you were supposed not to.
> - If you check all working fine then
> - Add entry in `CHANGELOG.md` as per below in your section if not then create your section.
>   - `- <PLATFORM_NAME>: <PROBLEM_NAME> (#<PROBLEM_ID>)`
> - Open `util.cpp` then set all the values in the variables without space.
> - run by hitting play button on right hand corner.
>   <img src="img/util.png" width="750"/><br>
> - deleted all the compiled/interpreted file.

- Add all the changes with this command: (`git add *`). This will add the changes to your present workspace. <br>
  <img src="img/git-add.png" width="750"/><br>

- Make a commit. This will save a snapshot of your Project.<br>
  <img src="img/git-commit.png" width="750"/><br>

- Push the changes: git push <br>
  <img src="img/git-push.png" width="750"/><br>

- Once you push the changes to your repo, Go to your forked repository, the Compare & pull request button will appear in GitHub.<br>
  <img src="img/pull_request.png" width="750"/><br>

- Click it and you'll be taken to this screen.<br>
  <img src="img/pull_2.png" width="750"/><br>
  - Open a pull request by clicking the Create pull request button. This allows the repo's maintainers to reviews your work. From here, they can merge it if it is good, or they may ask you for some changes.<br>

## Creating issue

Issues can be used to keep track of bugs, enhancements, or other requests.

- On GitHub, navigate to the main page of the repository.
- Under your repository name, click on the Issues button.
  <img src="img/issue.png" /><br>

- Click New issue.
  <img src="img/new_issue.png" /><br>
- If there are multiple issue types, click Get started next to the type of issue you'd like to open.
  <img src="img/issue_template_get_started_button.png" /><br>
  - Type a title and description for your issue.
  - After creating the issue you have to wait until the project maintainer assigns the issue to you.
  - when you're finished, click Submit new issue.
    <br>

#### If Still, you have some problem then Do watch this tutorial

[Git & GitHub Tutorial](https://www.youtube.com/watch?v=RGOj5yH7evk) <br>

## Here are some 12 Rules

#### You should be following while doing Open-Source to make your Contributions shine during the whole process:

- Be Nice, Be Respectful (BNBR)
- Check if the Issue you created, exists or not.
- Make proper commit messages and document your PR well.
- Always add Comments in your Code and explain it at points.
- Dynamic Input is always preferred over static Driver Code.
- Squash your commits before you push them.
- Always create a Pull Request from a Branch; Never from the Master.
- Follow proper Code conventions. Using i, j in Loops show a poor understanding of Code Quality. Use proper Variable, Function Names.
- Issues would be served on "First Come, First Serve" basis.
- Issues would be tagged as Easy, Medium, Hard. Scores would be assigned on the difficulty of Issue you solve.
- Code would be reviewed by Mentors before they are merged. Every PR requires 3 Reviews.
- No person can take up more than 2 Issues at a single point of time.