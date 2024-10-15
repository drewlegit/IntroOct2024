# Day 1 Review

Please address your current understanding of the following topics we covered (or began to cover) in class today. Your thoughts about these can and should be revised throughout the training (and your career!) as your understanding grows.

I am *not* looking for super "technical" stuff here. Just your ability to express and convey in your way your understanding of these things.

## 1. Git

We created a git repository on our VMs and added some existing code and committed it. We then used the `gh` cli tool to push that code to Github. 

- Say a few words about why *we* are using source control in this class? 
    Git allows multiple developers (us) to work collaboratively and simultaneously on a single project, and affords us the ability to track code revisions (who did what, and when).
- Say a few words about how source control is used by teams of developers working on the same code base.
    My answer to the first question above is also applicable here. In addition to the collaborative benefits of using Git, working with source control allows safe experimentation (which can be discarded if necessary) and backup/recovery.
- What is meant when we say a copy of the repository is the "origin"? (That's our copy on github). 
    "Origin" is a reference to the main copy of the repository that your local version is connected to.
- Why do we create commits locally?
    It makes it easier to work at one's own pace, track changes easily, and test the code before pushing it.
- Why do we push those commits to Github?
    We push our commits so that multiple team members can all access the code and work collaboratively on the same project.



### Extra Credit

What were the steps, as detailed as you like, that we took to create our repository and push it to Github.

What are some other ways you might do the same thing?


## 2. Services

We began a project in Visual Studio to create a service. What is meant by the term "Service" in software development?
    Services provide something for people to use. A service is like a small job that is part of a bigger and inter-dependent system.
Our service exposes an *interface* that other applications can use to drive our service (make it do stuff). This is an
"Application Programming Interface". How does an API differ from a "User Interface" (UI)? How are they similiar?
    APIs are for software-to-software interaction, while UIs are for software-to-human interaction.
What are some benefits of exposing a service's interface using the HTTP Protocol?
    HTTP is simple, universal, and stateless.

We "tested" our API three different ways. 

1. Manually using SwaggerUI
2. Manually using the `.http` file functionality in Visual Studio
3. Automated using an xUnit test project.

Which is the *right* way to do it? Why give preference to automated tests? 
    The "right" way depends on the situation and the phase of development. However, automated testing is much more efficient for repetitious tasks, is reliably repeatable, and is able to be integrated into the build process.

### Extra Credit

Have you used any existing HTTP APIs in other projects?

Have you created any other HTTP APIs in your own work or studies?
