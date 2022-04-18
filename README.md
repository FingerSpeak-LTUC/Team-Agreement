## Presentation Deck

Presentation Deck Template that all the team will be working on.

[Presentation Deck Template](https://docs.google.com/presentation/d/13hRAzckmsbfKL-CecybioWJFw-xEhrFDHBSrgQ64hXI/edit?usp=sharing)

## Schedule practice session

**Practice run of the presentation:**

    Date:
    Time:
    The place/Tool: Zoom Meetings

**Actual presentation:**

    Date:
    Time:
    The place/Tool: Zoom Meetings 

## Git Process

**Components of the project that lives on GitHub:**

- Building the code
- Tracking the changes
- Innovate solutions to problems that might arise during the project

**Share the Project Repository:**

- Ask for the username of the team memeber that you're inviting as a collaborator.
- On GitHub.com, navigate to the main page of the repository.
- Under your repository name, click  Settings.
- In the "Access" section of the sidebar, click  Collaborators & teams.
- Click Invite a collaborator.
- In the search field, start typing the name of the team member you want to invite, then click a name in the list of matches.
- Click Add NAME to REPOSITORY.
- The user will receive an email inviting them to the repository. Once they accept your invitation, they will have collaborator access to your repository.

**Accomplishing the features of the project will be done using Feature Branch Workflow:**

- The main branch stores the official release history, and the develop branch serves as an integration branch for features.
- Develop branch will contain the complete history of the project, whereas main will contain an abridged version.

**Command:**

    git branch develop
    git push -u origin develop

- Each new feature should reside in its own branch
- Feature branches use develop as their parent branch
- When a feature is complete, it gets merged back into develop. Features should never interact directly with main.

**Creating a feature branch:**

    git checkout develop
    git checkout -b feature_branch

**Merge the feature_branch into develop:**

    git checkout develop
    git merge feature_branch

**During the project Pull Request review workflow will be used:**

*Reviewing*

- All team members should oversee others work by hosting a meeting that will be planned as a review for all the pull requests.

*Merging*

- The team leader will be responsible for the merging of the PRs the process will be done during the meeting.
- All the distributed tasks (Project Features) should be merged after checking the work with the team members during the meeting.
- All the distributed tasks (Project Features) will be merged at the end of each working day.
