# Introduction to Microservices

### Date Time: 29-July-2023 at 09:00 AM IST

Event URL:

Youtube URL:

![Aishwarya|150x150](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/Aishwarya.png)

## Prerequisites:

N/A

## Software/Tools

> GitHub Desktop, Visual Studio Code


## What are we doing today?

> 1. Invite members into organization
> 2. Member Privileges - Base permissions
> 3. Create a new repository 
> 4. Add people from our organization
> 5. Set Branch protection rules
> 6. Create a new project using board in the organization
> 7. Add a new item in project
> 8. Move the item to "in progress"
> 9. Create a new branch in the new repository 
> 10. Clone the new repository using GitHub for desktop
> 11. Create a new feature branch and select current branch as new feature branch
> 12. Open the repository in VS Code and change the readme file
> 13. Commit the changes from GitHub for desktop
> 14. Create a Pull Request to merge the changes
> 15. Delete the branch after merging


## 1. Invite members into organization
Go to your organization &rarr People &rarr; Invite Member -> search user by entering their username, full name or email address -> Select Role in the organization as 'Member' -> Send invitation

![1_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/1_1.png)

![1_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/1_2.png)

## 2. Member Privileges - Base permissions
Go to your organization settings -> General - Member privileges -> Change the Base permissions to 'write'.
You can see your sent invitations under 'Invitations' and the invited person can join the organization using the link that they receive on thier respective emails.

![2_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/2_1.png)

![2_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/2_2.png)

![2_3| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/2_3.png)

![2_4| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/2_4.png)

## 3. Create a new repository
Go to 'Repositories' -> New Repository -> Give the name to your repo -> Select 'Public' -> Select 'Add a README file' -> Add .gitignore - '.gitignore template: VisualStudio' -> Choose License: MIT License -> Create Repository

![3_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/3_1.png)

![3_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/3_2.png)

![3_3| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/3_3.png)

## 4. Add people from our organization
Go to your repo's Settings -> Collaborators and Teams -> Add People -> Search for people from your organization and give write permissions to them -> Select 'Add user to this repository'

![4_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/4_1.png)

## 5. Set Branch protection rules
Generally we do not commit directly to the main or the master branch while working on projects. So we create a feature branch for that purpose. For example - dev, ut, Stage, main and prod for different stages of development life cycle. So for that purpose we add 'Branch Protection Rules' so that no one can directly commit to the main branch and changes are reviewed in a proper manner before merging it with the main branch and final production branch.

For creating a branch protection rule: Go to your repo -> Settings -> Branches -> Add Branch Protection rule -> give a name to your branch -> Check 'Require a pull request before merging' -> Set the number of required approvals -> Merge method as 'Squash and Merge' -> Check 'Do not allow bypassing the above settings' -> Create

![5_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/5_1.png)

![5_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/5_2.png)

![5_3| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/5_3.png)

## 6. Create a new project using board in the organization
We can create projects for tracking all the work done. We can choose from different available templates or start from scratch. There are 3 options available for creating new project: Table, Board, Roadmap.
Go to your organization -> Projects -> New Project -> Board -> Create

![6_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/6_1.png)

![6_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/6_2.png)

## 7. Add a new item in project
Click on the plus icon at the bottom to create a new task. The task is created as a draft.

![7_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/7_1.png)

## 8. Move the item to "in progress"
You can drag the task from To-Do to 'In-Progress' when you start working on a task. You can add description to your task and also add assignees to it.

![8_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/8_1.png)

## 9. Create a new branch in the new repository
For creating a new branch: Click on the branch option -> New Branch -> give a proper name to your branch such as <yourfirstname/date/task>

![9_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/9_1.png)

## 10. Clone the new repository using GitHub for desktop
Open GitHub Desktop -> Go to File -> Clone Repository -> Select your repo and the local path(Note: If your selected folder already contain some files, then first create an empty folder and then select the path for it) -> Click on Clone.


![10_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/10_1.png))

![10_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/10_2.png)

## 11. Create a new feature branch and select current branch as new feature branch
Click on current branch -> New branch -> Give name to your branch and select 'Create Branch' 

![11_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/11_1.png)

## 12. Open the repository in VS Code and change the readme file
Select your feature branch that you created -> Click on 'Open in Visual Studio Code' -> Make some changes to your README.md file -> Save the changes

![12_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/12_1.png)

![12_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/12_2.png)

## 13. Commit the changes from GitHub for desktop
Come back to Github Desktop -> Give a commit message and commit changes to the feature branch - Push origin

![13_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/13_1.png)

![13_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/12_2.png)

## 14. Create a Pull Request to merge the changes
- Click on Preview Pull Request -> If there are any changes, update them and then select 'Create Pull Request' 
- It will navigate you to GitHub Online where you can do a final review.
- Add a message -> Add assigness -> Create pull request
- The assignees will receive the request and they can review the changes, add comments or approve the request. They can even ask for changes if required.
- Once, the request is approved, you can merge the changes to the main branch.

![14_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/14_1.png)

![14_2| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/14_2.png)

![14_3| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/14_3.png)

![14_4| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/14_4.png)

![14_5| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/14_5.png)

## 15. Delete the branch after merging
Once your changes are mreged to the main branch and it is no longer required, delete the feature branch.
You can directly delete the branch after merging the changes or else you can also go to to Pull Requests -> Closed -> Select your branch -> Go to the section which says 'Pull Request successfully merged and closed' and click on 'Delete branch'.


![15_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/15_1.png)


![16_1| 100x100](https://github.com/Aishwarya-s-Tech-Skill-Academy/Practice/blob/main/Images/16_1.png)