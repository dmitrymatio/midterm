# midterm
First Section

1. Cloning makes a copy of the entire repo.
    
    When I want to work on a repo from github I'd first have to create a clone of it on my machine.

2. Fetching updates the data in the local repo without merging into the working copy so essentially it's getting information about updates without updating the local copy. 

    When I want to update the list of remote branches to I'd would fetch. it's possible to loop fetch commands in the background to maintain relevant information about the remote repo locally.

3. Pulling is a short hand for fetching and merging, it will fetch first then apply the changes from the updates.

    When I want to update my lcoal copy of the repo I will pull the updates and changes. For example if someone updated the repo I might want to access the updates.

Second Section

| Asana                                                                                   | Trello                      |
|-----------------------------------------------------------------------------------------|-----------------------------|
| List, Board, Timeline, Calendar, Files, Progress, Portfolios, Workload, Inbox, My Tasks | Kanban Board Only           |
| Dependency Management                                                                   | N/A                         |
| More features come with a steeper learning curve                                        | Easier to Use               |
| Free is limited to 15 people                                                            | Free has no limit on people |


Third Section

1. The .git folder is the hidden folder that contains everything git needs to function as it does. The object database is found in the objects folder.

2. The git hash-object function computes the hash ID that will be used to store the file contents in the database. Git uses a SHA-1 hash. When passed the -w flag it will save the file contents to the database by creating a folder with the first two digits of the hash as the folder name and the rest of the hash as the file name.

3. Git doesn't store file names in the git hash object of our file instead it uses a tree object to reprent the directories of our project. The tree object stores links to other objects with their associated file/directory names.