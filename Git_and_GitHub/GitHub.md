## <img src="https://user-images.githubusercontent.com/66907264/168492868-473ad65c-dde0-4b2d-ac27-527fd082abe4.png" alt="drawing" width="40"/> GitHub 

While Git is a software application that runs on your local machine,
**GitHub** is a cloud storage service that allows you to store your
coding projects remotely.

(Git is the CLI, and GitHub is the website)

Thus, knowing Git will give you the chance to showcase your portfolio on
GitHub\! And Since most software development companies consider using
Git to be a critical skill for modern web developers, this is really
important. With a GitHub, You will be able to demonstrate your abilities
to future employers.

And here’s a picture that says it all. This is exactly what GitHub looks
like, it consists of repositories (boxes) and each repo contains one of
our projects.


<img width="400" alt="Screen Shot 2022-05-15 at 11 43 27 PM" src="https://user-images.githubusercontent.com/66907264/168492907-9b1fc3e9-79c6-431c-9f48-2d7451dcc9d2.jpg">

### Fork and Clone

**Forking** is an excellent tool for copying source code from someone's
repository to your repository and contributing to it.

For example, Alhasan has built an awful project, and Zahraa was shocked
at how terrible that project was, so she wants to add her magic touches
to improve it, but she can’t make changes to it directly because
firstly, she’s not the owner. Alhasan didn’t add her as a contributor so
she doesn’t have permission to manipulate it, so the only choice left is
to **Fork** it to have a copy of it on her own GitHub.

To **Fork** a repository: simply go to any repos in the GitHub =\> at
the top right corner, you will find the fork button, by pressing it, a
copy of that repository will be on your GitHub.

<img width="347" alt="Screen Shot 2022-05-15 at 11 43 27 PM" src="https://user-images.githubusercontent.com/66907264/168493031-5df3326c-d5be-47d6-b583-cb0f77a32bcc.png">

But now, one thing is left, Zahraa wants another copy of this repos on
her laptop (local machine) so she can add, edit, or delete some code
easily, to do that she’s gonna **clone** the forked repository to have a
copy of it.

Once it’s cloned, she can open it in any editor and start working on it.

To **clone** a repository: go to the repository page that you wanna
clone, at the top right you will see these three buttons, press the
green one
<br />
<img width="360" alt="Screen Shot 2022-05-15 at 11 44 07 PM" src="https://user-images.githubusercontent.com/66907264/168493042-1e92e3e8-a103-4868-9ce7-66196bac3401.png">

This window will appear to you, copy the provided link
<br />
<img width="414" alt="Screen Shot 2022-05-15 at 11 45 36 PM" src="https://user-images.githubusercontent.com/66907264/168493092-f0a67051-5c64-482a-96eb-5d9d6435bdc8.png">

Then in your terminal/Git Bash, write the following command  
`git clone \<paste the copied URL\>`

Pushing to Github

After making her changes, the project on GitHub now is not up to date
with her local project, plus Alhassan can't see her magic touches
because it's on her laptop only.

how do you think she can keep the remote repository up to date with the
local repository?

Do you remember the amazing tool that can interact with GitHub?

Shame on you, it's **Git**\! with git, she can set up a local repository
and add her changes to it, and once she finishes working she can push it
to GitHub by following these steps:

1. `git add .`
It tells Git that you want to include updates to a particular file in the stage area.

2. `git commit -m “YOUR MESSAGE”`
It is used to record the changes in the repository (fetch updates from the staging area to the repository).

3. `git push `
is used to upload local repository content to a remote repository (**GitHub**).

And Woohoo, now you can refresh the GitHub page and see the changes
that you made to the project.
