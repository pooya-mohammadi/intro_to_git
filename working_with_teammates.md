# Working with teammates 

Working with teammates on a project is one of the main features of git and remote service providers like GitHub. 
In this section, we shall focus on:
1. how to clone a project
2. how to pull changes made by other members
3. how to tackle errors and conflicts that may occur in this way.


## how to clone a project
Before covering all the parts, consider that you are working a group and a member of the group has created a project(probably project's team leader)
and has invited you to the project as a contributor. To make it easier, consider you have all the permissions to make changes and so on. 

Let's get back to our first project that we created in the [cloning_remote_project section](https://github.com/pooya-mohammadi/intro_to_git/blob/main/creating_git_project.md). 
To clone a project we have two options as depicted in the following image:</br>
![img.png](images/working_with_teammates/cloning_options.png)</br>
Options: HTTPS and SSH 

1. SSH:</br>
If you have [established ssh-connection with GitHub](https://github.com/pooya-mohammadi/intro_to_git/blob/main/creating_git_project.md#lets-assign-public-key-to-github), 
you can choose this option. Then simply copy the address appeared at the bar right below the SSH-button.

2. HTTPS: </br>
This is used when you don't have ssh-connection and simply want to authenticate each time you are making a change on the project.
Then, copy the address appeared at the bar right below the buttons.</br>

**Note:** If you want to clone a project which does not belong to you or your team members, and you simply want to check it without making any changes, you can use HTTPS or SSH.

For the sake of this tutorial, we shall clone the [git_01](https://github.com/pooya-mohammadi/git_01/) project
to a different directory to have two copies of it in two destinations in order to mimic team members. 
This way, each destination will act as a member of our contrive team.

Let's clone the project: 
```commandline
git clone <project-url>
# in this tutorial, we'll clone the git_01 project with the following git-command
git clone git@github.com:pooya-mohammadi/git_01.git 
```

**Note-1:** To follow with this tutorial, you have to use one of your own projects because you don't have proper permissions to make change on my repo.</br>
**Note-2:** because I have established ssh-connection I use the ssh-url for cloning.</br>



 
