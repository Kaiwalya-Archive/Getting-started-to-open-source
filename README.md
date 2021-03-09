<h1 align="center">
    ✨ All about Open Source ✨
</h1>

![issue badge](https://img.shields.io/github/issues/kaiwalyakoparkar/Git-For-Open-Source)
![stars badge](https://img.shields.io/github/stars/kaiwalyakoparkar/Git-For-Open-Source)
![Fork badge](https://img.shields.io/github/forks/kaiwalyakoparkar/Git-For-Open-Source)

## Learning skills :
This is very basic and foundational step. You will have to learn at least 30-40% of any technology. Technology can refer to any. Most popular are :
1. Full stack development
2. Front end development
3. Back end development
4. Machine learning
5. C++, Java, Python
etc.

## Finding Organisation :
Finding the organisation which matches your skillset is very important. You can refer google for this or 
1. Visit the websites of GSOC, GSSOC and such programs.
2. Go to there past year's organinsation lists
3. Filter the organisations according to your skillset
4. Go to the orginsation on the github and find the project that interests you.
5. And follow the steps below

## Code of conducts & Readme of Projects :
### Readme of Project :
Readme of a project is very essential for users/ first time contributors of the project. Readme files give brief overview of the project to the developers intersected to contribute to it. Every new contributor should read the readme files to understand the workflow. Readme files contains the following.
1. About the project
2. Tools used in the project
3. Step by step walk through to setup the project in local environment
4. Licence (In some cases)

If the projects are very big and contains many components then the developer should read the documentation associated with the component he wants to contribute to .

### Code of Conduct :
Code of conduct is basically a file which contains the behavorial instructions for everyone associated with the project. Every organisation today has a code of conduct. Every person in the community is bound to follow the code of conduct.

## Selecting or solving Issues & Bugs :
After you have successfully found out the organisation and project you want to contribute to and have read the readme's and code of conduct. So, now its time to do some work. In any organinsation/ project there are lots of issues open in the issues section. If you are first timer then you can filter the issues by `good-first-time-issues` which are specially created for anyone who is contributing first time.

### Confirming the issue and asking for help
This may sound weird but that's true. You have to go on the issue you want to solve. In the comments tell them like "Hey, I want to work on this issue, could you please tell me how can I solve this. " You can also ask this question on their newsletter platform on the general channel. You can get help of many people contributing to that organisation.

## Setting local environment :
The readme file about which we talked about contains all the steps you need to follow to setup that project locally on your computer.
1. Fork the project to make your own copy of the project (Very important do no ignore this)
2. Go to your forked project and clone it your computer using
```git
git clone https://github.com/<your-user-name>/<project-name>.git
```
3. Check the status
```git
git status
```
4. Set the upstream
    1. Check the linked origin
    ```git
    git remote -v
    ```
    2. add the upstream 
    ```git
    git remote add upstream <github-link-of-main-project-on-organisation>
    ```
5. Create a branch for the project
```git
git branch <any-branch-name>
```
6. Checkout (Enter in) the branch
```git
git checkout branch <branch-name-given-in-step-5>
```
7. Do the fixes: 
Do all the fixes you wanted to do in the project.

8. After fixing : Use following command to push to code to your copy of project (your fork).
```git
git push origin <branch-name>
```
9. Making pull request to organisation/project
    1. Go to github
    2. Open the forked project
    3. You will see the compare and pull request button click on it
    4. your `<your-username> -> <branch-name>` will be compared to `organisation -> main`
    5. Click on create pull request
    6. Describe your fixes and link the issue with it by adding `#<issue-number>` in the description
    7. Again click on pull request.
You now have made a pull request to your organisation/project. As soon as the pull request passes the integration tests and is merged in main code base the issue will be closed atomatically and you are now a contributor to the project

10. Now you can do anything of the branch created on your local machine. Either merge it or delete it.
11. Do not forget to run the following command before you start contributing to the next project.
```git
git pull upstream master
```
This will update the locale code with the lastest update main code. 
 
## Maintainers : 
[Kaiwalya Koparkar](https://kaiwalyakoparkar.github.io/)
