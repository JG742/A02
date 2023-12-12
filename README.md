# A02
**Why github**
Github is an online application that helps programmers keep track of their code and make it easy to present it to a community of like minded people to get feedback and collaboration.

**How to install git**
1.To use the online collaborative coding application known as github you got to first go to https://git-scm.com/ and download the latest version of git.
2. Download the installer made for your system/os and follow the installer steps.

**How to get started on github**
1. Now that we have git and gitbash downloaded which comes with git we have to make an account on github itself so we can use it. https://github.com/
2. After making an account we can make our first repository which we're going to be doing a lot in github.
3. Now we can link our local computer to our remote github by opening up gitbash and typing in ssh-keygen -t ed25519 -C "your_email@example.com" this will give us a SSH key which we can then use to link our remote and local systems. You will be prompted to enter your password after this by gitbash.
4. Use the SSH Key you just generated to go to your account settings to the SSH and GPG keys page where you can place your key.
5. Now that we're linked together go back to your github profile and press the (+) in the top right and slecet the option to make a new repository.
6. Name the repository whatever you like and note that you have the option to have your repository be empty or to be populated with a read.md file upon startup.

**How to install webstorm**
1.Webstorm is an ide used usually for Javascript it's quite similar to visual studio code or any other IDE you'd normally use.
2. Install webstorm here and go through all the installation wizard steps.
3.Then you're gonna want to link your github by going through File -Settings -Version Control -GitHub--"Add Account".

**Definitions** 

**Branch**-refers to a distinct path of progress that empowers developers to collaborate on new features or bug fixes without impacting the primary codebase. Each branch represents a self-contained snapshot of the project, facilitating concurrent development.
**Clone**-The act of duplicating a repository from the GitHub server to a personal computer is known as cloning. The commonly used command for cloning is 'git clone', followed by the repository's URL. Cloning enables developers to possess a local replica of the complete project, encompassing its files, commit history, and branches. This local duplicate can be altered, and any modifications can subsequently be pushed back to the GitHub repository.
**Commit**-A record of modifications made to files in a repository is referred to as a snapshot. When developers modify the code, they first stage these modifications and then commit them, thereby establishing a milestone in the project's timeline. Each commit is assigned a distinct identifier and is accompanied by a commit message that elucidates the intent behind the alterations.
**Fetch**-The git fetch command is utilized by developers to retrieve changes from a remote repository without automatically merging them into the local working branch. By executing this command, developers are able to fetch the most recent updates from the remote repository, enabling them to examine and evaluate the changes prior to making a decision on whether to merge them.
**GIT**- Git's source and control management system.
**Github**-Github is an online application that helps programmers keep track of their code and make it easy to present it to a community of like minded people to get feedback and collaboration.
**Merge**-Developers engage in the process of merging when they work on separate branches or features and desire to combine their modifications into the primary branch, commonly referred to as the "master" or "main" branch. Git's merge operation seamlessly integrates the alterations implemented in one branch with another.
**Merge Conflict**-A merge conflict arises when there are conflicting modifications in separate branches that cannot be automatically resolved by Git during a merge process. This conflict occurs when multiple contributors make changes to the same lines of code or file independently. GitHub highlights the conflicting sections in the affected files, and it is the developer's duty to manually resolve these conflicts by selecting which changes to retain. After resolving the conflicts, the modifications can be committed.
**Push**- The git push command is utilized to transmit your local modifications to a remote repository, usually on the GitHub platform. Once you have made alterations to your code locally and have committed them, you can employ the git push command to transfer these changes.
**Pull**- a command used to fetch and merge changes from a remote repository to your local repository.
**Remote**-a repository that is hosted on a server, usually on the GitHub platform, and is connected to a local repository on a developer's machine. Remotes enable developers to collaborate by uploading changes from their local repository to the remote or downloading changes from the remote to update their local copy.
**Repository**-A GitHub repository functions as a storage area for a project, encompassing files, directories, and a record of version changes. It acts as a centralized hub where developers collaborate on code, monitor modifications, and oversee project resources. Repositories are established on the GitHub platform and can be designated as either public or private.
